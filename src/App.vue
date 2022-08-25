<template>
  <main>
    <BaseHeader />
    <BaseMain :specialities="specialities" :values="values" />

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
        icon: "fa-solid fa-house",
        title: "Construct",
        description: "Lorem ipsum dolor sit amet consectetur adipisicing elit."
      },
      {
        icon: "fa-solid fa-truck",
        title: "Exclusive",
        description: "Lorem ipsum dolor sit amet consectetur adipisicing elit."
      },
    ],
  values:[
    {
      icon: "fa-solid fa-house-chimney rounded-6 bg-info",
      title:"Great Services",
      description:"Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat officiis cupiditate incidunt  tenetur perspiciatis at! Repudiandae tenetur perspiciatis fugit excepturi accusantium ullam",
    },
    {
      icon: "fa-solid fa-gear rounded-6 bg-primary ",
      title:"Highest Standards",
      description:"Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat officiis cupiditate incidunt  tenetur perspiciatis at! Repudiandae tenetur perspiciatis fugit excepturi accusantium ullam",
    },
    {
      icon: "fa-solid fa-users rounded-6",
      title:"Professional Teams",
      description:"Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat officiis cupiditate incidunt  tenetur perspiciatis at! Repudiandae tenetur perspiciatis fugit excepturi accusantium ullam",
    },
    {
      icon: "fa-solid fa-lightbulb rounded-6 bg-success",
      title:"Creative Solutions",
      description:"Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat officiis cupiditate incidunt  tenetur perspiciatis at! Repudiandae tenetur perspiciatis fugit excepturi accusantium ullam",
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
