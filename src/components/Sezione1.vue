<template>
  <div>
      <div class="text-uppercase div1">
          <h4 class="mb-4">specialists in modern construction</h4>
          <hr>
          <p class="mt-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero facere molestias ullam dignissimos aperiam iste, corrupti porro quis perspiciatis a.</p>
        </div>
        <div class="mt-5 div2 d-flex flex-row justify-content-center" >
           <div class="col-2 colore" v-for='(card,index) in cards' :key='index'>

             <div class="show">
               <i :class="card.icona"></i>
               <h5>{{card.titolo}}</h5>
               <p>{{card.testo}}</p>
             </div>

             <div class="hide">
                <h5 class="text-capitalize">{{card.titoloHide}}</h5>
                <p>{{card.testo}}</p>
                <a class="text-uppercase" href="#">{{card.button}}</a>
             </div>
             
           </div>
             
           
        </div>
             
  </div>
</template>
             
<script>
export default {
name:'Sezione1',
data(){
return{
  cards:[
    {
      icona:'far fa-building',
      titolo:'Buldings',
      testo:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi, officiis.',
      titoloHide:'artfully crafted',
      button:'get a quote',
    },
    {
      icona:'fas fa-sync',
      titolo:'Renovate',
      testo:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi, officiis.',
       titoloHide:'freshly new',
      button:'get a quote',
    },
    {
      icona:'fas fa-home',
      titolo:'Construct',
      testo:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi, officiis.',
       titoloHide:'perfect lines',
      button:'get a quote',
    },
    {
      icona:'fas fa-truck',
      titolo:'Exclusive',
      testo:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi, officiis.',
       titoloHide:'planning',
      button:'get a quote',
    },
  ],


}
}
}
</script>

<style lang='scss' scoped>
@import '@/style/main.scss';
</style>
         
