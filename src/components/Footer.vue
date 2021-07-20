<template>
  <div>

     <!-- footer alto -->
      <div class="footer-alto"></div>

     <!-- footer basso  -->
      <div class="footer-basso row d-flex justify-content-center bg-dark text-light">
        <div class="col m-3">
          <img src="@/assets/img/footer-logo.webp" alt="">
          <p>We are specialists in the construction of unique and exclusive properties. Our work inspires. We pride ourselves on delivering outstanding quality and design for leading clients across the world.</p>
          <a class="text-uppercase text-dark" href="#">learn more</a>
        </div>
        <div class="col m-3">
          <h5>latest tweets</h5>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae possimus quisquam ut. Perspiciatis, officia earum?</p>
        </div>
        <div class="col m-3">
          <h5>contact us now</h5>
          <ul>
            <li>
              Corporate Location
              1600 Amphitheatre Parkway
              London WC1 1BA
            </li>
            <li>
              Residential Location
              9521 Broadsberry Avenue
              Paddington RC7 9ZA
            </li>
            <li>
              1.800.458.556 / 1.800.532.2112
            </li>
            <li>
              info@your-domain.com
            </li>
            <li>
              Monday – Friday: 9:00 AM – 6:00 PM
              </li>
            <li>
              Saturday – Sunday: 9:00 AM – 12:00 PM
            </li>
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