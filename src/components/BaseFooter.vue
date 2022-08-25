<template>
    <!-- footer -->
    <footer>
        <section id="footer-top" class="d-flex justify-content-center py-5  mb-0 ">
            <div class="us">
                <figure>
                    <img src="../assets/img/footer-logo.png" alt="logo-footer">
                </figure>
                <figcaption class="py-3">
                    We are specialists in the construction of unique and exclusive properties. Our work inspires. We
                    pride
                    ourselves on delivering outstanding quality and design for leading clients across the world.
                </figcaption>
                <button type="button"> learn more</button>
            </div>
            <div class="tweets px-2">
                <h4 class="pb-3"> LATEST TWEETS</h4>
                <div class="d-flex justify-content-between">

                    <figure class="d-flex tweets-intro">
                        <img class="img-fluid" src="../assets/img/3a74ce3d0532b7773b174c45ca3bd05a_normal.png"
                            alt="theme-logo">
                        <figcaption>
                            <div class="fw-bold"> ThemeFusion</div>
                            <div>@Theme_Fusion</div>
                        </figcaption>
                    </figure>
                    <img class="miniature" src="../assets/img/image (1).svg" alt="twit-logo">
                </div>
                <div class="ms-5 pb-1">
                    Do you need sublime WordPress hosting for your next website?
                    Take advantage of exclusive partner offers that we have secured just for you,
                    & launch your site in seconds whith <span class="hashtag">#avada</span> on WP Engine hosting
                    & get 30% Off this Black Friday <a class="linkable"> bit.ly/3kjLLE2</a> <span
                        class="hashtag">#BlackFriday2020</span>

                    <figure class="py-3">
                        <img class="img-fluid" src="../assets/img/En2TRxLW4AEiWUN.jpeg" alt="wp-engine-discount">
                    </figure>
                    <figcaption class="d-flex justify-content-between align-items-center">
                        <div class="d-flex">
                            <figure>
                                <img class="miniature" src="../assets/img/image (2).svg" alt="heart-reg">
                            </figure>
                            <figure class="ps-4">

                                <img class="miniature" src="../assets/img/image (3).svg" alt="exit">
                            </figure>
                        </div>
                        <span> 22h</span>
                    </figcaption>
                </div>
            </div>
            <div class="contact-us px-2">
                <h4 class="pb-3">contact us today </h4>
                <ul>
                    <li class="d-flex pb-3">
                        <i class="fa-solid fa-globe"></i>
                        <div class="d-flex-flex-column">

                            <div class="ps-4">Corporate Location</div>
                            <div class="ps-4">1600 Amphitheatre Parkway</div>
                            <div class="ps-4">London WC11BA</div>
                        </div>
                    </li>
                    <li class="d-flex pb-3">
                        <i class="fa-solid fa-house"></i>
                        <div class="d-flex flex-column">

                            <div class="ps-4">Residential Location</div>
                            <div class="ps-4">9521 Broadsberry Avenue</div>
                            <div class="ps-4">Paddington RC7 9ZA</div>
                        </div>
                    </li>
                    <li class="d-flex pb-3">
                        <i class="fa-solid fa-phone-flip"></i>
                        <div class="ps-4"> 1.800.458.556 / 1.800.532.2112</div>
                    </li>
                    <li class="d-flex pb-3">
                        <i class="fa-regular fa-envelope"></i>
                        <div class="ps-4"> info@your-domain.com</div>
                    </li>
                    <li class="d-flex pb-3">
                        <i class="fa-regular fa-clock"></i>
                        <div class="ps-4">Monday - Friday: 9:00 AM - 6:00 PM</div>
                    </li>
                    <li class="d-flex pb-3">
                        <i class="fa-regular fa-clock"></i>
                        <div class="ps-4">Saturday - Sunday: 9:00 AM - 12:00 PM</div>
                    </li>
                </ul>
            </div>
            <div class="find-us">
                <h4>
                    find us
                </h4>
                <figure>
                    <img src="../assets/img/home-244125289.jpg" alt="location" class="img-fluid">
                </figure>
            </div>
        </section>

        <section id="footer-bottom" class="py-0 px-4">
            <div class="d-flex align-items-center justify-content-between py-4 px-5">
                <div> copyright 2012 - 2016 avada by <span class="fw-bold"> THEME FUSION</span> | all rights reserved |
                    powered by <span class="fw-bold"> wordpress</span>
                </div>

                <div class="icons">
                    <i class=" fa-brands fa-facebook-f"></i>
                    <i class="px-3 fa-brands fa-twitter"></i>
                    <i class="pe-3 fa-brands fa-youtube"></i>
                    <i class=" fa-brands fa-instagram"></i>
                </div>

            </div>

        </section>
    </footer>
</template>

<script>
export default {
name:"BaseFooter",
props:{

}
}
</script>

<style lang="scss" scoped>

@import "../assets/sass/style.scss";

//footer
footer {
    background-color: $tuatara ;
}

//footer top
#footer-top {

    .us,
    .tweets,
    .contact-us,
    .find-us {
        flex-basis: 22%;
        margin-bottom: 0;
    }

    .us {
        color: $dove_gray;
        line-height: 2rem;

        button{
            font-size:small;
            padding: 0.5rem;
        }
    }

    .tweets {
        color: $white;
        font-size: small;

        h4 {
            font-size: x-small;
        }

        .tweets-intro {

            img {
                border-radius: 50%;
                width: 48px;
                height: 48px;
            }
        }

        .miniature {
            width: 20px;
            height: 20px;
        }

        .hashtag,
        .linkable {
            color: $venice_blu;
        }

        a {
            cursor: pointer;
        }

        figcaption {
            color: $dove_gray;
        }
    }

    .contact-us {
        color: $dove_gray;
        font-size: smaller;

        h4 {
            color: $bright_sun;
            font-size: x-small;
            text-transform: uppercase;
        }
    }

    .find-us {
        h4 {
            color: $bright_sun;
            font-size: x-small;
            text-transform: uppercase;
        }
    }
}

//footer bottom
#footer-bottom {
    background-color: $cod_gray;
    color: $dove_gray;
    font-size: x-small;

    div,
    span {
        text-transform: uppercase;

    }

}
</style>