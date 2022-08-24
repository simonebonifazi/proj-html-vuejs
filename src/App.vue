<template>
  <main>
    <!-- <BaseHeader /> -->
    <header class="container">
      <div class="d-flex justify-content-between align-items-center ">
        <figure>
          <img src="./assets/img/construction_logo.png" alt="logo">
        </figure>
        <nav class="d-flex align-items-center">
          <!-- aggiungere classe active con triangolino basso e color yellow
          poi cambiare in ul li e aggiungere a e cursor pointer -->
          <ul class="d-flex m-0">
            <!-- to fix class active -->
            <li class="px-3"> <a class="active" href="#"> HOME</a></li>
            <li class="px-3"> <a href="#"> ABOUT</a></li>
            <li class="px-3"> <a href="#"> SERVICES </a></li>
            <li class="px-3"> <a href="#"> WORK </a></li>
            <li class="px-3"> <a href="#"> ARTICLES </a></li>
          </ul>
          <!-- posso creare un componente, si ripete 4 volte
           ma con testo diverso che mi farò passare di volta in volta da props -->
          <button type=" button"> GET QUOTE</button>
        </nav>
      </div>
    </header>
    <!-- da mettere in seguito nel componente sopra -->
    <!-- jumbotron section -->
    <section id="jumbotron" class="d-flex justify-content-center  flex-column align-items-center ">
      <!-- add minicard on top 0 right 0 -->
      <h2> BUILDING INSPIRING SPACES</h2>
      <p class="py-3"> We Build Inspiring Residential & Commercial Spaces</p>
      <div class="d-flex">
        <button type="button" class="recent-work me-2"> EXPLORE RECENT WORK</button>
        <button type="button" class="quote"> GET A QUOTE TODAY</button>
      </div>
    </section>
  <!-- jumbo footer -->
      <section id="jumbo-footer">
        <p class="text-center py-4 m-0">
          Do You Have A Construction Project We Can Help With?
        </p>
        <!-- pos rel? spostare nel jumbo come footer? -->
      <button type="button" class="free-quote">
      <!-- position absolute? --> GET A FREE QUOTE
      </button>
      </section>
    <!-- our specialities section -->
    <section id="specialities">

      <div class="specialities-construction">
        <!-- nb la intro si ripete quasi sempre per ogni sezione -->
        <h4>Specialists In Modern Construction</h4>
        <span class="divisor">-</span>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim sed provident ex sapiente ut maxim?</p>
        <div class="mini-card text-center">
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
      <div class="values"><i></i> <span></span> <span></span>
        <p></p>
      </div>
      <div class="values"><i></i> <span></span> <span></span>
        <p></p>
      </div>
      <div class="values"><i></i> <span></span> <span></span>
        <p></p>
      </div>
      <div class="values"><i></i> <span></span> <span></span>
        <p></p>
      </div>
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
      <figure><img src="#" alt="#">
        <figcaption></figcaption>
      </figure>
      <figure><img src="#" alt="#">
        <figcaption></figcaption>
      </figure>
      <figure><img src="#" alt="#">
        <figcaption></figcaption>
      </figure>
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
    <!-- footer -->
    <footer>
      <section id="footer-top d-flex">
        <div class="us"></div>
        <div class="tweets"></div>
        <div class="contact-us"></div>
        <div class="find-us"></div>
      </section>

      <section id="footer-bottom">
        <div class="d-flex align-items-center justify-content-between">
          <span> copyright</span>
          <div>

          </div>
        </div>

      </section>
    </footer>
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

<style lang="scss" scoped>
@import "./assets/sass/style.scss";
@import "~bootstrap/scss/bootstrap";

//Layout
//   section{
//     min-height: 250px;
//     border: 2px dotted gold;

//     margin-bottom: 2rem;
//   }
// div{
//   height: 150px;
//   border: 1px dashed black;
  
//   margin-bottom: 1rem;
// }
//  span {
//   border: 1.5px solid green;
//  }

 //generics
 ul{
  li{
    list-style-type: none;

  }
 }

 a{
 text-decoration: none;
 color: black;
 }

 //Header
 header{
   div{
     
     background-color: $white;
     
     img{
        height: 45px;
      }

        //height: 100px;
        .active{
          color: $bright_sun;

        }
  }
    button{
      background-color: $bright_sun;

      padding: 0.5rem 1rem;     
      
      border: none;
        &:hover{
          background-color: $cod_gray;
          color: $white;
        }
    }
 }

 //jumbotron
 #jumbotron{
  background-image: url("./assets/img/home-slider-62528242.jpg");

  background-repeat: no-repeat;
  background-position: center;

  background-size: cover;
//temporanea
  min-height: 500px;
  h2{
    color: $white;
  }
  p{
    color: $bright_sun;
  }
  button{
    padding: 0.7rem 1.2rem;
    font-size:smaller;
  }
  .recent-work{
    background-color: $cod_gray;
    color: $white;
    border: none;
  }
  .quote{
    background-color: $bright_sun;
    border:none;
    
  }
 }

//jumbo footer
#jumbo-footer{
  background-color: $bright_sun;
  height: 80px;

}
//botton
.free-quote{
    border: 1px solid $white;
    background-color: $cod_gray;
    color: $white;
    font-size: small;

    padding: 0.7rem 1.2rem;

    position: relative;
    bottom: 0.5rem;
    left: 43%;

  }

  //specialities section
  #specialities{
    .mini-card{
      width:150px;
      height:150px;

      background-color: $pampas;
    }
  }

//collabs
#our-collabs{
  min-height: 400px;

  background-image: url("./assets/img/home-244125289.jpg");
  background-position: center;
  background-size: cover;

  
}
</style>
