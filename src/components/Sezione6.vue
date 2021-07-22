<template>
  <div>
       <div class=" div1">
          <h4 class="mb-4 text-uppercase">latest news</h4>
          <hr>
          <p class="mt-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero facere molestias ullam dignissimos aperiam iste, corrupti porro quis perspiciatis a.</p>
        </div>
        <div class="mt-5 div2 d-flex flex-row justify-content-center">
           <div class="col-3 text-start" v-for="(card,index) in cards" :key='index'>
             <img :src="card.immagine" alt="">
             <h4 class="mt-3">{{card.titolo}}</h4>
             <span>{{card.data}}</span>
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
      immagine:require('../assets/img/news/trattore.webp'),
      titolo:'Redeveloping Florida’s Remote Southern Coast',
      data:'December 7th, 2015',
      testo:'Technology is Here to Stay Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus purus nisl, elementum vitae consequat at, tristique ut enim. Sed ut dignissim leo. Nullam sed metus id sapien faucibus rhoncus sed',
    },
    {
      immagine:require('../assets/img/news/ponte.webp'),
      titolo:'How We Manage Large Construction Projects',
      data:'December 7th, 2015',
      testo:'Technology is Here to Stay Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus purus nisl, elementum vitae consequat at, tristique ut enim. Sed ut dignissim leo. Nullam sed metus id sapien faucibus rhoncus sed',
    },
    {
      immagine:require('../assets/img/news/torre.webp'),
      titolo:'Future proofing a modern home',
      data:'December 6th, 2015',
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