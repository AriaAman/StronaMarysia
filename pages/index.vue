<script setup>
import 'vue3-carousel/carousel.css'
import { Carousel, Slide } from 'vue3-carousel'
import photo1 from '~/static/HomePage/photoHomePage1.jpg'
import photo2 from '~/static/HomePage/photoHomePage2.jpg'
import photo3 from '~/static/HomePage/photoHomePage3.jpg'
import Services from '~/components/HomePage/Services.vue'
import NotreCabinet from '~/components/HomePage/NotreCabinet.vue'
import NotreEquipe from '~/components/HomePage/NotreEquipe.vue'
import NosTechnologie from '~/components/HomePage/NosTechnologie.vue'

const carouselConfig = {
  itemsToShow: 1,
  wrapAround: true,
  autoplay: 2000,
  transition: 600,
}

const slides = [
  { id: 1, src: photo1 },
  { id: 2, src: photo2 },
  { id: 3, src: photo3 }
]
</script>

<template>
  <section class="home-section">
    <div class="header-block">
      <div class="title-left">
        <h1 class="main-title">
          Profesjonalizm
          <span>& doświadczenie</span>
        </h1>
      </div>
      <div class="intro-right">
        <p>
          Od 2012 roku łączymy profesjonalizm z troską o zdrowie Pacjentów, oferując kompleksową opiekę stomatologiczną
          opartą na nowoczesnych technologiach i indywidualnym podejściu.
        </p>
        <br>
        <p>Zapraszamy do zapoznania się z naszą ofertą i odwiedzenia naszego gabinetu – Twoje zadowolenie jest naszą
          największą satysfakcją.</p>
      </div>
    </div>
    <div class="breadcrumbs">
      <p>STOMATOLOGIA | IMPLANTOLOGIA | PROTETYKA | ENDODONCJA | TOMOGRAF | RTG</p>
    </div>
    <div class="carousel">
      <Carousel v-bind="carouselConfig">
        <Slide v-for="slide in slides" :key="slide">
          <img :src="slide.src" alt="slide"/>
        </Slide>
      </Carousel>
    </div>

    <div class="enBasCarousel">
      <div class="clinic-info">
          <p class="info-title">Gabinet stomatologiczny</p>
          <p class="info-text">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="#BC9667" class="bi bi-geo-alt" viewBox="0 0 16 16">
              <path d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A32 32 0 0 1 8 14.58a32 32 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10"/>
              <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4m0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6"/>
            </svg>  
            Jaroty, ul. Stawigudzka 8e<br />
            10-687 Olsztyn
          </p>
        </div>

      <NuxtLink href="#" class="route-btn">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-map" viewBox="0 0 16 16">
          <path fill-rule="evenodd" d="M15.817.113A.5.5 0 0 1 16 .5v14a.5.5 0 0 1-.402.49l-5 1a.5.5 0 0 1-.196 0L5.5 15.01l-4.902.98A.5.5 0 0 1 0 15.5v-14a.5.5 0 0 1 .402-.49l5-1a.5.5 0 0 1 .196 0L10.5.99l4.902-.98a.5.5 0 0 1 .415.103M10 1.91l-4-.8v12.98l4 .8zm1 12.98 4-.8V1.11l-4 .8zm-6-.8V1.11l-4 .8v12.98z"/>
        </svg>
        Sprawdź jak do nas dojechać
    </NuxtLink>
    </div>
    <Services />
    <NotreCabinet />
  </section>
  <div class="home-section-white">
      <NotreEquipe /> 
      <NosTechnologie />
    </div>
</template>

<style scoped>

.breadcrumbs {
  height: 144px;
  border-left: #fff 1px solid;
  text-align: center;
  font-family: 'Figtree';
  font-size: 20px;
  line-height: 24px;
  display: flex;
  padding-left: 17px;
  color: #BC9667;
  align-items: flex-end;
}

.carousel {
  margin: 24px 0px;
}

.enBasCarousel {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  height: 194px;
}

.info-title {
  font-family: 'Figtree';
  font-size: 24px;
  line-height: 30px;
  font-weight: 400;
  color: #fff;
  margin: 0; 
  padding-bottom: 16px;
}

.info-text {
  font-family: 'Figtree';
  font-size: 24px;
  line-height: 30px;
  font-weight: 400;
  color: #BC9667;
  margin: 0;
}

.route-btn {
  display: inline-flex;
  align-items: center;
  gap: 11px;
  text-decoration: underline;
  text-underline-offset: 10px;
  color: #fff;
  font-family: 'Figtree';
  font-size: 24px;
}

.home-section {
  background-color: #15253F;
  color: #fff;
  padding: 60px 60px;
  min-height: 100vh;
  font-family: 'Figtree';
}

.home-section-white {
  background-color: #fff;
  color: #15253F;
  padding: 60px 60px;
  min-height: 100vh;
  font-family: 'Figtree';
}

/* En‑tête : "KOSZTY LECZENIA" et paragraphe explicatif */
.header-block {
  display: flex;
  gap: 300px;
}

.main-title {
  width: 1033px;
  height: 256px;
  font-family: 'Aboreto';
  font-size: 107px;
  line-height: 128px;
  margin: 0;
  font-weight: 400;
  color: #BC9667;
}

.main-title span {
  display: block;
  color: #fff;
}

.intro-right {
  height: 208px;
  width: 435px;
  font-family: 'Figtree';
  font-weight: 400;
  font-size: 20px;
  gap: 16px;
  line-height: 24px;
  color: #fff;
  margin: 0;
}
</style>
