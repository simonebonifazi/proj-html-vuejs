<template>
  <div>
    <BaseHeader />

    <!-- da mettere in seguito nel componente sopra -->
    <img src="./assets/img/construction_mobile_logo.png" alt="logo-avada">
  </div>
</template>

<script>
import BaseHeader from './components/BaseHeader.vue';

export default {
  name: 'ConstructionProject',
  components: {
    BaseHeader
}
}
</script>

<style lang="scss">
@import "./assets/sass/style.scss";
@import "~bootstrap/scss/bootstrap";


</style>
