<template>
  <div>
       <div class=" div1">
          <h4 class="mb-4 text-uppercase">latest news</h4>
          <hr>
          <p class="mt-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero facere molestias ullam dignissimos aperiam iste, corrupti porro quis perspiciatis a.</p>
        </div>
        <div class="mt-5 div2 d-flex flex-row justify-content-center">
           <div class="col-2" v-for="(card,index) in cards" :key='index'>
             <img :src="card.immagine" alt="">
             <h4>{{card.titolo}}</h4>
             <hr>
             <p>{{card.testo}}</p>
           </div>
           
        </div>
  </div>
</template>

<script>
export default {
name:'Sezione6',
data(){
  return{
    cards:[
    {
      immagine:'../assets/img/news/trattore.webp',
      titolo:'Redeveloping Florida’s Remote Southern Coast',
      testo:'Technology is Here to Stay Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus purus nisl, elementum vitae consequat at, tristique ut enim. Sed ut dignissim leo. Nullam sed metus id sapien faucibus rhoncus sed',
    },
    {
      icona:'fas fa-sync',
      titolo:'How We Manage Large Construction Projects',
      testo:'Technology is Here to Stay Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus purus nisl, elementum vitae consequat at, tristique ut enim. Sed ut dignissim leo. Nullam sed metus id sapien faucibus rhoncus sed',
    },
    {
      icona:'fas fa-users',
      titolo:'Future proofing a modern home',
      testo:'Technology is Here to Stay Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus purus nisl, elementum vitae consequat at, tristique ut enim. Sed ut dignissim leo. Nullam sed metus id sapien faucibus rhoncus sed',
    },
    
  ],

  }
}
}
</script>

<style lang='scss' scoped>
@import '@/style/main.scss';
</style>