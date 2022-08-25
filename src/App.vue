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
    <section id="jumbotron" class="d-flex justify-content-center  flex-column align-items-center mb-0">
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

      <div class="specialities-construction text-center">
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
    <section id="explore" class="text-center">
      <!-- intro -->
      <h4> Explore Recent Work</h4>
      <span class="divisor">-</span>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim sed provident ex sapiente ut maxim?</p>

      <img src="./assets/img/project1-featured-294276386-200x200.jpg" alt="proj-1">
      <img class="mx-3" src="./assets/img/project2-featured-15013609-600x600.jpg" alt="proj-2">
      <img src="./assets/img/project3-featured-189023420-200x200.jpg" alt="proj-3">

      <div class="my-5"> view all project </div>

    </section>
    <!-- core values section -- cambia bg -->
    <section id="core-values" class="text-center">
      <!-- intro -->
      <h4>our core values</h4>
      <span>-</span>
      <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Possimus modi enim iure asperiores consectetur est
        delectus. Dicta delectus iusto, maxime nesciunt nobis libero voluptatibus</p>

      <!-- best services -->
      <div class="values"><i></i> <span></span> <span></span>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat officiis cupiditate incidunt tenetur
          perspiciatis at! Repudiandae tenetur perspiciatis fugit excepturi accusantium ullam</p>
      </div>
      <div class="values"><i></i> <span></span> <span></span>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat officiis cupiditate incidunt tenetur
          perspiciatis at! Repudiandae tenetur perspiciatis fugit excepturi accusantium ullam</p>
      </div>
      <div class="values"><i></i> <span></span> <span></span>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat officiis cupiditate incidunt tenetur
          perspiciatis at! Repudiandae tenetur perspiciatis fugit excepturi accusantium ullam</p>
      </div>
      <div class="values"><i></i> <span></span> <span></span>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat officiis cupiditate incidunt tenetur
          perspiciatis at! Repudiandae tenetur perspiciatis fugit excepturi accusantium ullam</p>
      </div>
    </section>
    <!-- review's secction -->
    <section id="reviews" class="text-center">
      <div class="container">

        <!-- half intro -->
        <h4>our home owners says</h4>
        <div class="divisor">-</div>
        <!-- review -->
        <img class="img-fluid" src="./assets/img/home-testimonial-113165296.jpg" alt="#">
        <p> "No man but feels more of a man in the world if he have but a bit of ground
          that he can call his own.
          However small it is on the surface, it is four thousand
          miles deep: and that is a very handsome property."</p>
        <div> harry smith - new home owner</div>
        <!-- custom points -->
      </div>
    </section>
    <!-- latest news -->
    <section id="news" class="text-center">
      <!-- intro -->
      <h4>latest news</h4>
      <div class="divisor">-</div>
      <p> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aliquid vel perspiciatis unde blanditiis sunt veniam
        modi inventore commodi in hic</p>
      <!-- deck -->
      <div class="card-deck d-flex justify-content-center">

        <!-- cards -->
        <div class="card">

          <figure>
            <img src="./assets/img/blog-post-134132600.jpg" alt="#">
            <figcaption>
              <h6>redeveloping florida's remote southern coast</h6>
              <span class="description pb-3">december 7th, 2015</span>
              <hr>

              <p>Technology is Here to Stay Lorem ipsum dolor sit, amet consectetur adipisicing elit. Natus accusamus
                quibusdam eveniet maxime</p>
            </figcaption>
          </figure>
        </div>

        <div class="card mx-3">

          <figure>
            <img src="./assets/img/blog-post-92486644.jpg" alt="#">
            <figcaption>
              <h6></h6>
              <span></span>
              <hr>

              <p></p>
            </figcaption>
          </figure>
        </div>
        <div class="card">

          <figure>
            <img src="./assets/img/blog-post-332773904.jpg" alt="#">
            <figcaption>
              <h6></h6>
              <span></span>
              <hr>

              <p></p>
            </figcaption>
          </figure>
        </div>
      </div>
      <!-- SE SI RIPETE QUALCOSA; ... -->
      <span> view all articles</span>
    </section>
    <!-- parterns section -->
    <section id="partners" class="text-center">
      <!-- intro -->
      <h4> Trusted partners</h4>
      <span class="divisor">-</span>
      <p class="pb-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis culpa suscipit assumenda, dolorum
        atque asperiores! Tempore nulla perferendis quaerat quidem consequuntur dolorum aliquam, eum iste! Illum
        explicabo ducimus fuga expedita?</p>
      <!-- partners -->
      <div class="d-flex justify-content-center align-items-center">

        <figure>
          <img src="./assets/img/home-logo1-219096700-320x202.png" alt="#">
        </figure>
        <figure class="px-3">
          <img src="./assets/img/home-logo2-219096700-320x202.png" alt="#">
        </figure>
        <figure class="px-3">
          <img src="./assets/img/home-logo9-219096700-320x202.png" alt="#">
        </figure>
        <figure class="px-3">
          <img src="./assets/img/home-logo11-219096700-320x202.png" alt="#">
        </figure>
        <figure>
          <img src="./assets/img/home-logo10-219096700-320x202.png" alt="#">
        </figure>

      </div>
    </section>
    <!-- cta section -->
    <section id="cta-section" class="d-flex align-items-center justify-content-center mb-0">
      <!-- bg_img -->
      <div class="d-flex justify-content-center">
        <div class="intro ">
          <!-- intro -->
          <h4> building inspiring spaces</h4>
          <span class="divisor"> - </span>
          <p> Labore tempora aliquid voluptates illum esse provident adipisci quidem iure</p>
        </div>
        <div class="cta">
          <button type="button"> get a free quote</button>
          <div> only takes a few seconds</div>
        </div>
      </div>
    </section>
    <!-- footer -->
    <footer>
      <section id="footer-top" class="d-flex justify-content-center pt-3">
        <div class="us">
          <figure>
            <img src="./assets/img/footer-logo.png" alt="logo-footer">
          </figure>
          <figcaption class="py-3">
            We are specialists in the construction of unique and exclusive properties. Our work inspires. We pride
            ourselves on delivering outstanding quality and design for leading clients across the world.
          </figcaption>
          <button type="button"> learn more</button>
        </div>
        <div class="tweets">
          <h4 class="pb-3"> LATEST TWEETS</h4>
          <div class="d-flex justify-content-between">

            <figure class="d-flex tweets-intro">
              <img class="img-fluid" src="./assets/img/3a74ce3d0532b7773b174c45ca3bd05a_normal.png" alt="theme-logo">
              <figcaption>
                <div class="fw-bold"> ThemeFusion</div>
                <div>@Theme_Fusion</div>
              </figcaption>
            </figure>
            <img class="miniature" src="./assets/img/image (1).svg" alt="twit-logo">
          </div>
          <div class="ms-5 pb-1">
            Do you need sublime WordPress hosting for your next website?
            Take advantage of exclusive partner offers that we have secured just for you,
            & launch your site in seconds whith <span class="hashtag">#avada</span> on WP Engine hosting
            & get 30% Off this Black Friday <a class="linkable"> bit.ly/3kjLLE2</a> <span
              class="hashtag">#BlackFriday2020</span>

            <figure class="py-3">
              <img class="img-fluid" src="./assets/img/En2TRxLW4AEiWUN.jpeg" alt="wp-engine-discount">
            </figure>
            <figcaption class="d-flex justify-content-between align-items-center">
              <div class="d-flex">
                <figure>
                  <img class="miniature" src="./assets/img/image (2).svg" alt="heart-reg">
                </figure>
                <figure class="ps-4">

                  <img class="miniature" src="./assets/img/image (3).svg" alt="exit">
                </figure>
              </div>
              <span> 22h</span>
            </figcaption>
          </div>
        </div>
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

 .divisor{
  width: 75px;

  color: $bright_sun;
 }

 section{
  margin-bottom: 3rem;
 }

 figure{
  margin: 0;
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
      height:120px;

      background-color: $pampas;
    }
  }

//collabs section
#our-collabs{
  min-height: 400px;

  background-image: url("./assets/img/home-244125289.jpg");
  background-position: center;
  background-size: cover;

  //trovare modo per arrotondare i bordi
}

//explore center
#explore{
 img{
  width: 200px;
  height: 200px;
 }
}

//core values section
#core-values{
  background-color: $pampas;
  min-height:450px;

}

//reviews section
#reviews{
  background-image: url("./assets/img/home-parallax-144609983.jpg");

  background-position: center;
  background-size: cover;

  color: $white;
  min-height:450px;
  img{
    border-radius: 50%;
  }
}
//news section
#news{

  background-color: $pampas;
  img{
    width: 150px;
    height: 80px;
  }
  .card{
    width:150px;
    background-color: $white;

    border-radius:0;

    .description{
      font-size: xx-small;
    
    }
    hr{
      background-color: $pampas;
    }
  }
}
//partners section
#partners{
  img{
    width: 100px;
    height: 75px;
  }
}

//cta-section
#cta-section{
  background-image: url("./assets/img/about-call-to-action-57862405.jpg");
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  min-height:450px;

  color: $white;
  button{
    color: black;
    padding: 0.7rem 1.2rem;
  }
}

//footer
footer{
  background-color: $tuatara ;
  height: 450px;

}

#footer-top{
  .us,.tweets,.contact-us,.find-us{
    flex-basis: 22%;
  }
  .us{
    color: $dove_gray;
    line-height: 2rem;
  }
  .tweets{
    color:$white;
    font-size: small;
    h4{
      font-size:x-small;
    }
    .tweets-intro{

        img{
        border-radius: 50%;
        width: 48px;
        height: 48px;
        }
      }
    .miniature{
      width: 20px;
      height: 20px;
    }
    .hashtag,.linkable{
      color: $venice_blu;
    }
    a{
      cursor:pointer;
    }
    figcaption{
      color:$dove_gray;
    }
  }
}

</style>
