<template>
  <div>
      <div class="text-uppercase div1">
          <h4 class="mb-4">our core values</h4>
          <hr>
          <p class="mt-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero facere molestias ullam dignissimos aperiam iste, corrupti porro quis perspiciatis a.</p>
        </div>
        <div class="mt-5 div2 d-flex flex-row justify-content-center">
            <div class="col-2 show" v-for='(card,index) in cards' :key='index'>
             <i :class="card.icona"></i>
             <h5>{{card.titolo}}</h5>
             <hr>
             <p>{{card.testo}}</p>
           </div>
           
        </div>
  </div>
</template>

<script>
export default {
name:'Sezione4',
data(){
  return{
    cards:[
    {
      icona:'fas fa-cog',
      titolo:'Great Services',
      testo:'Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia',
    },
    {
      icona:'fas fa-sync',
      titolo:'Highest Standards',
      testo:'Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia',
    },
    {
      icona:'fas fa-users',
      titolo:'Professional Team',
      testo:'Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia',
    },
    {
      icona:'far fa-lightbulb',
      titolo:'Creative Solutions',
      testo:'Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia',
    },
  ],

  }
}
}
</script>

<style lang='scss' scoped>
@import '@/style/main.scss';
</style>