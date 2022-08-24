<template>
  <main>
    <!-- <BaseHeader /> -->
    <header class="container">
      <div class="d-flex justify-content-between align-items-center ">
        <figure>
          <img src="./assets/img/construction_logo.png" alt="logo">
        </figure>
        <nav>
          <!-- aggiungere classe active con triangolino basso e color yellow
          poi cambiare in ul li e aggiungere a e cursor pointer -->
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
    <!-- jumbotron section -->
    <section id="jumbotron">
      <h3></h3>
      <p></p>
      <button type="button"></button>
      <button type="button"></button>
    </section>
    <!-- our specialities section -->
    <section id="specialities">
      <div>
        <!-- pos rel? spostare nel jumbo come footer? -->
      </div>
      <button>
        <!-- position absolute? -->
      </button>

      <div class="specialities-construction">
        <!-- nb la intro si ripete quasi sempre per ogni sezione -->
        <h5></h5>
        <span></span>
        <p></p>
        <div class="mini-card">
          <!-- da ciclare con data -->
        </div>
      </div>
    </section>
    <section id="our-collabs" class="d-flex">
      <!-- bg img, border top to round in some ways -->
      <div><span></span><span></span><span></span></div>
      <div><span></span><span></span><span></span></div>
      <div><span></span><span></span><span></span></div>
      <div><span></span><span></span><span></span></div>
    </section>
    <!-- Explore section -->
    <section id="explore">
      <!-- intro -->
      <h5></h5>
      <span></span>
      <p></p>

      <img src="#" alt="#">
      <img src="#" alt="#">
      <img src="#" alt="#">

      <span></span>

    </section>
    <!-- core values section -- cambia bg -->
    <section id="core-values">
      <!-- intro -->
      <h5></h5>
      <span></span>
      <p></p>

      <!-- best services -->
      <div class="values"><i></i> <span></span> <span></span> <p></p></div>
      <div class="values"><i></i> <span></span> <span></span> <p></p></div>
      <div class="values"><i></i> <span></span> <span></span> <p></p></div>
      <div class="values"><i></i> <span></span> <span></span> <p></p></div>
    </section>
    <!-- review's secction -->
    <section id="reviews">
      <!-- half intro -->
      <h5></h5>
      <span></span>
      <!-- review -->
      <img src="#" alt="#">
      <p></p>
      <span></span>
      <!-- custom points -->
      </section>
      <!-- latest news -->
      <section id="news">
        <!-- intro -->
        <h5></h5>
        <span></span>
        <p></p>
        <!-- cards -->
        <figure><img src="#" alt="#"> <figcaption></figcaption></figure>
        <figure><img src="#" alt="#"> <figcaption></figcaption></figure>
        <figure><img src="#" alt="#"> <figcaption></figcaption></figure>
        <!-- SE SI RIPETE QUALCOSA; ... -->
        <span></span>
      </section>
      <!-- parterns section -->
      <section id="partners">
        <!-- intro -->
        <h5></h5>
        <span></span>
        <p></p>
        <!-- partners -->
        <img src="#" alt="#">
        <img src="#" alt="#">
        <img src="#" alt="#">
        <img src="#" alt="#">
        <img src="#" alt="#">

      </section>
      <!-- cta section -->
      <section id="cta-section">
        <!-- bg_img -->
        <div class="d-flex">
          <div class="intro">
            <!-- intro -->
            <h5></h5>
            <span></span>
            <p></p>
          </div>
           <div class="cta">
             <button type="button"></button>
             <span></span>
           </div>
          </div>
      </section>
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

    margin-bottom: 2rem;
  }
div{
  height: 150px;
  border: 1px dashed black;
  
  margin-bottom: 1rem;
}
 span {
  border: 1.5px solid green;
 }

</style>
