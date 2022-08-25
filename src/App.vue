<template>
  <main>
     <BaseHeader />
      <BaseMain/>
   
    <BaseFooter/>
  
  </main>
</template>

<script>
import BaseMain from './components/BaseMain.vue';
import BaseHeader from './components/BaseHeader.vue';
import BaseFooter from './components/BaseFooter.vue';

export default {
  name: 'ConstructionProject',
  components: {
    BaseMain,
    BaseHeader,
    BaseFooter
}
}
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap";
@import "./assets/sass/style.scss";

</style>
