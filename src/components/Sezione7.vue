<template>
   <div>
        <div class="text-uppercase div1">
          <h4 class="mb-4">trusted partners</h4>
          <hr>
          <p class="mt-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero facere molestias ullam dignissimos aperiam iste, corrupti porro quis perspiciatis a.</p>
        </div>
        <div class="mt-5 div2 d-flex flex-row justify-content-center">
           <div class="col-2" >
             <!-- <img src="{{immagine}}" alt="" v-for="immagine in immagini" :key='immagine.id'> -->
           </div>
        </div>
  </div>
</template>

<script>
export default {
name: 'Sezione7',
data(){
 return{
   immagini:[
    './assets/img/img-partners/food.webp',
    //  './assets/img/img-partners/forest.webp',
    //  './assets/img/img-partners/home.webp',
    //  './assets/img/img-partners/market.webp',
    //  './assets/img/img-partners/realestate.webp',
     
   ]
  }
 }
 }

</script>

<style lang='scss' scoped>
@import '@/style/main.scss';
</style>