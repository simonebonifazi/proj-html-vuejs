<template>
  <main>
    <!-- <BaseHeader /> -->
    <header>
      <div class="d-flex justify-content-between align-items-center ">
        <figure>
          <img src="./assets/img/construction_logo.png" alt="logo">
        </figure>
        <nav>
          <span> blabla prova</span>
          <span> blabla prova</span>
          <span> blabla prova</span>
          <span> blabla prova</span>
          <span> blabla prova</span>
          <!-- posso creare un componente, si ripete 4 volte
           ma con testo diverso che mi farò passare di volta in volta da props -->
          <button type="button"> GET QUOTE</button> 
        </nav>
      </div>
    </header>
    <!-- da mettere in seguito nel componente sopra -->
  </main>
</template>

<script>
// import BaseHeader from './components/BaseHeader.vue';

export default {
  name: 'ConstructionProject',
  components: {
    // BaseHeader
}
}
</script>

<style lang="scss">
@import "./assets/sass/style.scss";
@import "~bootstrap/scss/bootstrap";

//Layout
  section{
    min-height: 250px;
    border: 2px dotted gold;
  }
div{
  height: 150px;
  border: 1px dashed black;
}
 span {
  border: 1.5px solid green;
 }

</style>
