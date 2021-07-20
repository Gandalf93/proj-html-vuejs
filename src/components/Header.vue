<template>
  <div class="text-center">
      <div class="navbar  p-3 d-flex row-flex align-items-center">
          <img class="mx-5 my-3" src="@/assets/img/logo.svg" alt="">
          <ul class="text-uppercase d-flex row-flex mx-5 my-3"> 
            <li>
              <a href="#">home</a> 
              </li>
            <li>
              <a href="#">about</a> 
              </li>
            <li>
              <a href="#">services</a> 
              </li>
            <li>
              <a href="#">work</a> 
              </li>
            <li>
              <a href="#">articles</a> 
              </li>
            <li>
              <a class="bg-warning px-4 py-2" href="#">get quote</a>
            </li>
          </ul>
      </div>

      <div class="jumbotron d-flex align-items-center justify-content-center flex-column text-light">
        <h1 class="text-uppercase">building inspiring spaces</h1>
        <p class="text-capitalize">we build inspiring residential &amp; commercial spaces</p>
        <div>
          <a href="#" class="mx-2 p-2 bg-dark text-light">explore recent work</a>
          <a href="#" class="mx-2 p-2 bg-warning text-dark">get a quote today</a>
        </div>
      </div>

      <div class="bg-warning linea-sotto">
        <p class="text-capitalize py-3">do you have a contruction project we can help with?</p>
        <a href="#" class=" p-2 bg-dark text-light text-uppercase">get a free quote</a>
      </div>
  </div>
</template>
      

<script>
export default {
name : 'Header',
}
</script>


<style lang='scss' scoped>
@import '@/style/header.scss';
</style>

    
    
    