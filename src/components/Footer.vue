<template>
  <div>

     <!-- footer alto -->
      <div class="footer-alto"></div>

     <!-- footer basso  -->
      <div class="footer-basso row d-flex justify-content-center bg-dark text-light">
        <div class="col m-3">
          <img src="@/assets/img/footer-logo.webp" alt="">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias, sit. Eum iure dolores dolore nam.</p>
          <a class="text-uppercase text-dark" href="#">learn more</a>
        </div>
        <div class="col m-3">
          <h5>latest tweets</h5>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae possimus quisquam ut. Perspiciatis, officia earum?</p>
        </div>
        <div class="col m-3">
          <h5>contact us now</h5>
          <ul>
            <li>a</li>
            <li>b</li>
            <li>c</li>
            <li>d</li>
          </ul>
        </div>
        <div class="col m-3">
          <h5>find us</h5>
        </div>
      </div>   

      <div class="barra-nera text-secondary d-flex align-items-center p-4">
        <p>©COPYRIGHT 2012 - 2021 | AVADA THEME BY THEMEFUSION | ALL RIGHTS RESERVED | POWERED BY WORDPRESS</p>
      </div>

  </div>
</template>

<script>
export default {
name : 'Footer',
}
</script>

<style lang='scss' scoped>
@import '@/style/footer.scss';
</style>