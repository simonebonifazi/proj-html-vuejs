<template>
  <main>
    <BaseHeader />
    <BaseMain :specialities="specialities" />

    <BaseFooter />

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
},
data(){
  return{
    specialities: [
      {
        icon: "fa-solid fa-building",
        title: "Buildings",
        description: "Lorem ipsum dolor sit amet consectetur adipisicing elit."
      },
      {
        icon: "fa-solid fa-rotate",
        title: "Renovate",
        description: "Lorem ipsum dolor sit amet consectetur adipisicing elit."
      },
      {
        icon: "fa-solid fa - house-cimney",
        title: "Construct",
        description: "Lorem ipsum dolor sit amet consectetur adipisicing elit."
      },
      {
        icon: "fa-solid fa-truck",
        title: "Exclusive",
        description: "Lorem ipsum dolor sit amet consectetur adipisicing elit."
      },
    ]
  }
}
}
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap";
@import "./assets/sass/style.scss";

</style>
