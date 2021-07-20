<template>
  <div class="text-center">
      <!-- SEZIONE 1 -->
      <section class="sezione1 mt-5">
        <Sezione1/>
      </section>

      <!-- SEZIONE 2 CONTATORE -->
      <section class="sezione2 mt-5">
        <Sezione2/>
      </section>
          
      <!-- SEZIONE 3 -->
      <section class="sezione3 mt-5">
        <Sezione3/>
      </section>
        
      <!-- SEZIONE 4 -->
      <section class="sezione4">
        <Sezione4/>
      </section>

      <!-- SEZIONE 5 -->
      <section class="sezione5">
        <Sezione5/>
      </section>

      <!-- SEZIONE 6 -->
      <section class="sezione6">
       <Sezione6/>
      </section>
        
      <!-- SEZIONE 7 PARTNERS-->
      <section class="sezione7">
        <Sezione7/>
      </section>
  </div>
</template>

<script>

import Sezione1 from "./Sezione1.vue";
import Sezione2 from "./Sezione2.vue";
import Sezione3 from "./Sezione3.vue";
import Sezione4 from "./Sezione4.vue";
import Sezione5 from "./Sezione5.vue";
import Sezione6 from "./Sezione6.vue";
import Sezione7 from "./Sezione7.vue";

export default {
name : 'Main',
components : {

  Sezione1,
  Sezione2,
  Sezione3,
  Sezione4,
  Sezione5,
  Sezione6,
  Sezione7,
  },
};

</script>


<style lang='scss' scoped>
@import '@/style/main.scss';
</style>
           

           

          
          
          
