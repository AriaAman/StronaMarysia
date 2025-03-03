<script setup>
import 'vue3-carousel/carousel.css'
import { Carousel, Slide, Pagination } from 'vue3-carousel'
import photo1 from '~/static/HomePage/photoHomePage4.jpg'
import photo2 from '~/static/HomePage/photoHomePage4.jpg'


const carouselConfig = {
    itemsToShow: 1,
    wrapAround: true,
    autoplay: 2000,
    transition: 500,
}
const carouselRef = ref();
const currentSlide = ref(1);

const next = () => {
    carouselRef.value.next();
    if (slides.length === currentSlide.value) {
        currentSlide.value = 1;
    } else {
        currentSlide.value++;
    }
}

const slides = [
    { id: 1, src: photo1 },
    { id: 2, src: photo2 },
]
</script>


<template>
    <section class="nasz-gabinet-section">
        <!-- Ligne horizontale (optionnelle) -->
        <hr class="top-divider" />

        <div class="content-wrapper">
            <!-- Colonne gauche : grande image + slider info -->
            <div class="left-side">
                <div class="image-container">
                    <!-- Image principale (par ex. wnętrze gabinetu) -->
                    <div class="carousel">
                        <Carousel ref="carouselRef" v-bind="carouselConfig">
                            <Slide v-for="slide in slides" :key="slide">
                                <img :src="slide.src" alt="slide" />
                            </Slide>
                        </Carousel>
                    </div>


                    <!-- Pagination style "01 / 07" + flèche circulaire -->
                    <div class="image-pagination">
                        <div class="number-pagination">
                            <span class="current">{{ currentSlide }}</span>
                            <span class="slash">/</span>
                            <span class="total">{{ slides.length }}</span>
                        </div>
                        <button @click="next" class="circle-arrow" >
                            <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="#BC9667"
                                class="bi bi-arrow-right-short" viewBox="0 0 16 16">
                                <path fill-rule="evenodd"
                                    d="M4 8a.5.5 0 0 1 .5-.5h5.793L8.146 5.354a.5.5 0 1 1 .708-.708l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L10.293 8.5H4.5A.5.5 0 0 1 4 8" />
                            </svg>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Colonne millieu : Titre / Sous-titre / Paragraphe -->
            <div class="middle-side">
                <div class="title-block">
                    <h1 class="main-title">
                        nasz
                        <span>gabinet</span>
                    </h1>
                    <h3 class="sub-title">KOMFORT I<br />NOWOCZESNE TECHNOLOGIE</h3>
                </div>
                <div class="bloc-description">
                    <p class="description">
                        Nasz gabinet stomatologiczny stworzony jest z myślą
                        o różnorodnych potrzebach pacjentów, łączy nowoczesne
                        wnętrza z dogodną lokalizacją na osiedlu Zacisze,
                        oferując łatwy dostęp do parkingów i wygodne połączenia komunikacyjne.
                    </p>
                    <p class="description">
                        Gabinet jest wyposażony w najnowocześniejszy sprzęt medyczny,
                        który umożliwia świadczenie usług na najwyższym poziomie.
                        Oferujemy innowacyjny system CAD/CAM CEREC, dzięki któremu
                        pacjenci mogą uzyskać precyzyjną, ceramiczną odbudowę zębów
                        już podczas jednej wizyty. Dysponujemy również zaawansowanym
                        aparatem RTG do zdjęć 3D, panoramicznych oraz cefalometrii,
                        co zapewnia szczegółową diagnostykę i kompleksowe leczenie stomatologiczne.
                    </p>
                </div>
            </div>

            <div class="right-side">
                <div class="image-container">
                    <img src="/static/HomePage/photoHomePage5.jpg" alt="Clinique Pietruszczak" class="clinic-image" />
                </div>
                <div class="logo-container">
                    <img src="/static/HomePage/LogoSitePiotrAvecDent.svg" alt="Clinique Pietruszczak"
                        class="clinic-image" />
                </div>
            </div>

        </div>
    </section>
</template>


<style scoped>
.right-side {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 114px;
}

.logo-container {
    height: 183px;
    width: 190px;
}

.nasz-gabinet-section {
    background-color: #15253F;
    color: #fff;
    padding: 60px 0px;
    font-family: 'Figtree', sans-serif;
}

.top-divider {
    border: none;
    border-top: 1px solid #fff;
    margin-bottom: 40px;
}

/* Disposition générale : 2 colonnes */
.content-wrapper {
    display: flex;
    gap: 40px;
    margin-top: 64px;
    justify-content: space-between;
}

/* Colonne gauche (grande image + pagination) */
.carousel {
    width: 587px;
}

.main-image {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

.image-pagination {
    margin-top: 64px;
    width: 587px;
    height: 104px;
    display: flex;
    align-items: flex-start;
    font-size: 18px;
    font-weight: bold;
    justify-content: space-between;
}

.image-pagination .current {
    color: #fff;
}

.image-pagination .slash {
    color: #BC9667;
}

.image-pagination .total {
    color: #BC9667;
}

/* Bouton circulaire (→) */
.circle-arrow {
    background: none;
    border: 2px solid #fff;
    width: 104px;
    height: 104px;
    border-radius: 50px;
    padding: 0;
    cursor: pointer;
    display: inline-flex;
    align-items: center;
    justify-content: center;
}

.circle-arrow:hover {
    background-color: #fff;
}

.number-pagination {
    display: flex;
    gap: 25px;
}

/* Colonne droite */
.middle-side {
    display: flex;
    flex-direction: column;
    position: relative;
    width: 587px;
}

/* Titre / Sous-titre */
.title-block {
    margin-bottom: 20px;
}

.main-title {
    font-family: 'Aboreto';
    font-size: 112px;
    line-height: 128px;
    margin: 0;
    font-weight: 400;
    color: #BC9667;
}

.main-title span {
    display: block;
    color: #fff;
}

.big-title br+span {
    color: #fff;
}

.sub-title {
    font-family: 'Aboreto', cursive;
    font-size: 40px;
    line-height: 56px;
    margin-top: 96px;
    margin-bottom: 40px;
    font-weight: 400;
    color: #fff;
}

/* Paragraphe(s) de description */
.bloc-description {
    width: 435px;
    height: 448px;
}

.description {
    font-family: 'Figtree';
    font-size: 18px;
    line-height: 28px;
    color: #fff;
}
</style>