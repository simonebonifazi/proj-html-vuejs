<template>
    <header class="container">
      <div class="d-flex justify-content-between align-items-center ">
        <figure>
          <img src="../assets/img/construction_logo.png" alt="logo">
        </figure>
        <nav class="d-flex align-items-center p-2">
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
</template>

<script>
export default {
  name: 'BaseHeader',
  props: {
    
  }
}
</script>

<style scoped lang="scss">
@import "../assets/sass/style.scss";
 //Header
 header {
   padding: 0.5rem;

   div {

     background-color: $white;

     img {
       height: 45px;
     }

     //height: 100px;
     .active {
       color: $bright_sun;

     }
   }

   button {
     background-color: $bright_sun;

     padding: 0.5rem 1rem;

     border: none;

     &:hover {
       background-color: $cod_gray;
       color: $white;
     }
   }
 }
</style>
