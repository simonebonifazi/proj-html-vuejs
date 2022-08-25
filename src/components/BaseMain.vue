<template>
    <div>
        <!-- jumbotron section -->
        <section id="jumbotron" class="d-flex justify-content-center  flex-column align-items-center mb-0">
            <!-- add minicard on top 0 right 0 -->
            <h2> BUILDING INSPIRING SPACES</h2>
            <span class="divisor"></span>
            <p class="py-3"> We Build Inspiring Residential & Commercial Spaces</p>
            <div class="d-flex">
                <button type="button" class="recent-work me-2"> EXPLORE RECENT WORK</button>
                <button type="button" class="quote"> GET A QUOTE TODAY</button>
            </div>
        </section>
        <!-- jumbo footer -->
        <section id="jumbo-footer" class="p-0">
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

            <div class="specialities-construction text-center d-flex flex-column align-items-center">
                <!-- nb la intro si ripete quasi sempre per ogni sezione -->
                <h4>Specialists In Modern Construction</h4>
                <span class="divisor"></span>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim sed provident ex sapiente ut maxim?</p>

                <div class="mini-deck d-flex">
                    <div v-for="(speciality,i) in specialities" :key="i" class="mini-card mx-2">
                        <!-- da ciclare con data -->
                        <i :class="speciality.icon" class="rounded-5"></i>
                        <h4> {{ speciality.title}}</h4>
                        <p>{{ speciality.description}}</p>
                    </div>
                </div>
            </div>
        </section>
        <section id="our-collabs" class="d-flex justify-content-center align-items-center">
            <!-- bg img, border top to round in some ways -->
            <div class="text-center">
                <div>3534</div>
                <div><i class="fa-solid fa-city"></i></div>
                <span>planning applications</span>
            </div>
            <div class="text-center px-3">
                <div>896</div>
                <div><i class="fa-solid fa-building"></i></div>
                <span> completed projects</span>
            </div>
            <div class="text-center pe-3">
                <div>172</div>
                <div><i class="fa-solid fa-users"></i></div>
                <span>trained professionals</span>
            </div>
            <div class="text-center">
                <div>19</div>
                <div><i class="fa-solid fa-globe"></i></div>
                <span>international offices</span>
            </div>
        </section>
        <!-- Explore section -->
        <section id="explore" class="d-flex align-items-center flex-column">
            <!-- intro -->
            <h4> Explore Recent Work</h4>
            <span class="divisor"></span>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim sed provident ex sapiente ut maxim?</p>

            <div class="d-flex">
                <img src="../assets/img/project1-featured-294276386-200x200.jpg" alt="proj-1">
                <img class="mx-3" src="../assets/img/project2-featured-15013609-600x600.jpg" alt="proj-2">
                <img src="../assets/img/project3-featured-189023420-200x200.jpg" alt="proj-3">
            </div>

            <div class="my-5"> VIEW ALL PROJECTS </div>

        </section>
        <!-- core values section -- cambia bg -->
        <section id="core-values" class="d-flex flex-column align-items-center justify-content-center">
            <!-- intro -->
            <h4>our core values</h4>
            <span class="divisor"></span>
            <p class="pb-5">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Possimus modi enim iure asperiores
                consectetur est
                delectus. Dicta delectus iusto, maxime nesciunt nobis libero voluptatibus</p>

            <!-- best services -->
            <div class="d-flex container text-center">

                <div v-for="(value, i) in values" :key="i" class="d-flex flex-column align-items-center px-2">
                    <i :class="value.icon"></i>
                    <span class="pt-3"> {{value.title}}</span>
                    <span class="pb-3">_</span>
                    <p> {{value.description}}</p>
                </div>
            </div>
        </section>
        <!-- review's secction -->
        <section id="reviews" class="text-center">
            <div class="container py-5">

                <!-- half intro -->
                <div class="d-flex flex-column align-items-center">

                    <h4>our home owners says</h4>
                    <div class="divisor text-center"></div>
                </div>
                <!-- review -->
                <img class="img-fluid" src="../assets/img/home-testimonial-113165296.jpg" alt="#">
                <p class="py-3"> "No man but feels more of a man in the world if he have but a bit of ground
                    that he can call his own.
                    However small it is on the surface, it is four thousand
                    miles deep: and that is a very handsome property."</p>
                <div class="reviewer fw-bold"> harry smith - new home owner</div>
                <!-- custom points -->
            </div>
        </section>
        <!-- latest news -->
        <section id="news" class="pt-5 d-flex flex-column align-items-center">
            <!-- intro -->
            <h4>latest news</h4>
            <div class="divisor"></div>
            <p> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aliquid vel perspiciatis unde blanditiis sunt
                veniam
                modi inventore commodi in hic</p>
            <!-- deck -->
            <div class="card-deck d-flex justify-content-center">

                <!-- cards -->
                <div v-for="(item, i) in news" :key="i" class="card">

                    <figure>
                        <img :src="item.src" :alt="item.title">
                        <figcaption class="p-2">
                            <h6>{{item.title}}</h6>
                            <span class="description pb-3">{{item.date}}</span>
                            <hr>

                            <p>{{item.description}}</p>
                        </figcaption>
                    </figure>
                </div>

                <div class="card mx-3">

                    <figure>
                        <img src="../assets/img/blog-post-92486644.jpg" alt="#">
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
                        <img src="../assets/img/blog-post-332773904.jpg" alt="#">
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
            <span class="py-5"> VIEW ALL ARTICLES</span>
        </section>
        <!-- parterns section -->
        <section id="partners" class=" container d-flex flex-column align-items-center">
            <!-- intro -->
            <h4> Trusted partners</h4>
            <span class="divisor"></span>
            <p class="pb-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis culpa suscipit assumenda,
                dolorum
                atque asperiores! Tempore nulla perferendis quaerat quidem consequuntur dolorum aliquam, eum iste! Illum
                explicabo ducimus fuga expedita?</p>
            <!-- partners -->
            <div class="d-flex justify-content-center align-items-center">

                <figure>
                    <img src="../assets/img/home-logo11-219096700-320x202.png" alt="#">
                </figure>
                <figure class="px-3">
                    <img src="../assets/img/home-logo10-219096700-320x202.png" alt="#">
                </figure>
                <figure class="px-3">
                    <img src="../assets/img/home-logo2-219096700-320x202.png" alt="#">
                </figure>
                <figure class="px-3">
                    <img src="../assets/img/home-logo1-219096700-320x202.png" alt="#">
                </figure>
                <figure>
                    <img src="../assets/img/home-logo9-219096700-320x202.png" alt="#">
                </figure>

            </div>
        </section>
        <!-- cta section -->
        <section id="cta-section" class="d-flex align-items-center justify-content-center mb-0">
            <!-- bg_img -->
            <div class="d-flex justify-content-center align-items-center">
                <div class="intro pe-5">
                    <!-- intro -->
                    <h4> building inspiring spaces</h4>
                    <span class="divisor"></span>
                    <p> Labore tempora aliquid voluptates illum esse provident adipisci quidem iure</p>
                </div>
                <div class="cta">
                    <button type="button"> get a free quote</button>
                    <div class="py-3"> only takes a few seconds</div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {
    name:"BaseMain",
    props: {
        specialities: Array,
        values: Array,
        news: Array,
    },

}
</script>

<style lang="scss" scoped>




@import "../assets/sass/style.scss";
//jumbotron
#jumbotron{
    background-image: url("../assets/img/home-slider-62528242.jpg");

    background-repeat: no-repeat;
    background-position: center;

    background-size: cover;
    //temporanea
    min-height: 300px;

    h2 {
        color: $white;
    }

    p {
        color: $bright_sun;
    }

    button {
        padding: 0.7rem 1.2rem;
        font-size: smaller;
    }

    .recent-work {
        background-color: $cod_gray;
        color: $white;
        border: none;
    }

    .quote {
        background-color: $bright_sun;
        border: none;

    }
}

//jumbo footer
#jumbo-footer {
    background-color: $bright_sun;
    height: 80px;

}

//botton
.free-quote {
    border: 1px solid $white;
    background-color: $cod_gray;
    color: $white;
    font-size: small;

    padding: 0.7rem 1.2rem;

    position: relative;
    bottom: 0.95rem;
    left: 43%;

}

//specialities section
#specialities {
    .mini-card {
        width: 150px;
        padding: 0.5rem;
        background-color: $pampas;

        i{
            padding: 1rem;
            border: 1px solid $dove_gray;
            color:$dove_gray;

        }

        p{
            color:$dove_gray;
        }
    }
}

//collabs section
#our-collabs {
    min-height: 400px;

    background-image: url("../assets/img/home-244125289.jpg");
    background-position: center;
    background-size: cover;

    color: $bright_sun;
    font-size: xx-large;

    span {
        font-size: small;
        text-transform: uppercase;
    }

}

//explore center
#explore {
    img {
        width: 200px;
        height: 200px;
    }
}

//core values section
#core-values {
    background-color: $pampas;
    min-height: 450px;

    span,p{
        color: $silver;
    }

    i{
        font-size:2.5rem;
        color:$white;
        padding: 2rem;
        border-radius: 50%;
        background-color: $orange;

    }
}

//reviews section
#reviews {
    background-image: url("../assets/img/home-parallax-144609983.jpg");

    background-position: center;
    background-size: cover;

    color: $white;
    min-height: 450px;

    img {
        border-radius: 50%;
    }

    .reviewer {
        text-transform: uppercase;
    }
}

//news section
#news {

    background-color: $pampas;

    img {
        width: 150px;
        height: 80px;
    }

    .card {
        width: 150px;
        background-color: $white;

        border-radius: 0;

        h6 {
            text-transform: capitalize;
        }

        .description {
            font-size: xx-small;

        }

        hr {
            background-color: $pampas;
        }
    }
}

//partners section
#partners {
    img {
        width: 100px;
        height: 75px;
    }
}

//cta-section
#cta-section {
    background-image: url("../assets/img/about-call-to-action-57862405.jpg");
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    min-height: 450px;

    color: $white;

    button {
        color: black;
        padding: 0.7rem 1.2rem;
        font-size: small;
    }

    .cta>div {
        font-size: xx-small;
    }
}

</style>