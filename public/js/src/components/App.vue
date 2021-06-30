<template>



  <main role="main">
    <!-- Content -->
    <article>
      <header>
        <div class="carousel-default owl-carousel carousel-main carousel-nav-white background-dark text-center">
          <div class="item">
            <div class="s-12">
              <div >   <img src="img/bggg.jpg"></div>
              <div class="carousel-content">
                <div class="content-center-vertical line">
                  <div class="margin-top-bottom-80">
                    <!-- Title -->
                    <h1 class="text-white margin-bottom-30 text-size-60 text-m-size-30 text-line-height-1">Logiciel médical<br> Cabinets et Cliniques</h1>
                    <div class="s-12 m-10 l-8 center"><p class="text-white text-size-14 margin-bottom-40">GestiCab est désormais disponible sur votre smartphone, ayez toujours à porté de main vos dossiers médicaux, imageries, ... </p></div>
                    <div class="line">

                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </header>

      
  <div>
    <app-header />
    <div class='notes_wrapper'>
      <transition name='fade' >
        <router-view></router-view>
      </transition>
    </div>
  </div>
</template>

<script>
import Header from './others/header.vue'

export default {
  components: {
    'app-header': Header
  }
}
</script>
