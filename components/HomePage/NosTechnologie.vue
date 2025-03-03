<script setup>
import { ref } from 'vue'
import 'vue3-carousel/carousel.css'
import { Carousel, Slide, Pagination } from 'vue3-carousel'
import photo1 from '~/static/Technologie/Machine1.jpg'
import photo2 from '~/static/Technologie/Machine2.jpg'
import photo3 from '~/static/Technologie/Machine3.jpg'
import photo4 from '~/static/Technologie/Machine4.jpg'
import photo5 from '~/static/Technologie/Machine5.jpg'
import photo6 from '~/static/Technologie/Machine6.jpg'
import photo7 from '~/static/Technologie/Machine7.jpg'
import photo8 from '~/static/Technologie/Machine8.jpg'
import photo9 from '~/static/Technologie/Machine9.jpg'
import photo10 from '~/static/Technologie/Machine10.jpg'


const carouselConfig = {
    itemsToShow: 1,
    wrapAround: true,
    autoplay: 6000,
    transition: 500,
}
const carouselRef3 = ref();
const currentSlide = ref(1);

const next = () => {
    carouselRef3.value.next();
    if (slides.length === currentSlide.value) {
        currentSlide.value = 1;
    } else {
        currentSlide.value++;
    }
}

const slides = [
    { id: 1, src: photo1 },
    // { id: 2, src: photo2 },
    // { id: 3, src: photo3 },
    // { id: 4, src: photo4 },
    // { id: 5, src: photo5 },
    // { id: 6, src: photo6 },
    // { id: 7, src: photo7 },
    // { id: 8, src: photo8 },
    // { id: 9, src: photo9 },
    // { id: 10, src: photo10 },
]

const texts = ref ([
    {id: 1, title: 'TOMOGRAF CS 9600',text: 'Tomograf komputerowy Kodak Carestream CS 9600 to najbardziej zaawansowany aparat CBCT w swojej kategorii. Innowacyjne urządzenie o doskonałej precyzji obrazowania. Dzięki zastosowaniu stożkowej wiązki promieniowania rentgenowskiego pozwala na uzyskanie niezwykle szczegółowych obrazów, odzworowujących nawet najdrobniejsze detale anatomicznej budowy głowy pacjenta, przy jednoczesnym zminimalizowaniu dawki promieniowania oraz skróceniu czasu potrzebnego na badanie.'},

])

function onMoreTechnologie() {
    navigateTo('/uslugi')
}

</script>

<template>
    <section class="technologie-section">
        <hr class="top-divider" />
        <div class="header-text">
            <p class="left-intro">
                SPECJALIZUJEMY SIĘ W LECZENIU CHORÓB PRZYZĘBIA ZA POMOCĄ NOWOCZESNYCH URZĄDZEŃ,
                MIKROSKOPÓW CHIRURGICZNYCH, LASERÓW BIOSTYMULACYJNYCH I INNOWACYJNYCH NARZĘDZI DO
                DIAGNOZOWANIA I LECZENIA PROBLEMÓW STOMATOLOGICZNYCH.
            </p>
            <div class="title-block">
            <h2 class="big-title">NOWOCZESNE<br /><span>TECHNOLOGIE</span></h2>
        </div>
        </div>

       
        <div class="content-wrapper">
            <!-- Colonne gauche : Titre, description ... -->
            <div class="left-column">
                <div class="machine-info" v-for="text in texts" :key="text.id">
                    <h3 class="machine-title">{{ text.title }}</h3>

                    <div class="image-pagination">
                        <div class="number-pagination">
                            <span class="current">{{ currentSlide }}</span>
                            <span class="slash">/</span>
                            <span class="total">{{ slides.length }}</span>
                        </div>
                        <button @click="next" class="circle-arrow">
                            <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="#BC9667"
                                class="bi bi-arrow-right-short" viewBox="0 0 16 16">
                                <path fill-rule="evenodd"
                                    d="M4 8a.5.5 0 0 1 .5-.5h5.793L8.146 5.354a.5.5 0 1 1 .708-.708l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L10.293 8.5H4.5A.5.5 0 0 1 4 8" />
                            </svg>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Colonne centrale : Nom de la machine / pagination / flèche circulaire -->
            <div class="center-column">
                <div class="carousel">
                    <Carousel ref="carouselRef3" v-bind="carouselConfig">
                        <Slide v-for="slide in slides" :key="slide">
                            <img :src="slide.src" alt="slide" />
                        </Slide>
                    </Carousel>
                </div>
            </div>

            <!-- Colonne droite : Image + descriptif + bouton -->
            <div class="right-column" >
                <div class="text-info" v-for="text in texts" :key="text.id">
                    <p>
                        {{ text.text }}
                    </p>
                </div>

                <!-- Bouton "Więcej o technologii" -->
                <button class="more-services-btn" @click="onMoreTechnologie">
                    Więcej o usługach
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="#BC9667"
                        class="bi bi-arrow-right" viewBox="0 0 16 16">
                        <path fill-rule="evenodd"
                            d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8" />
                    </svg>
                </button>
            </div>
        </div>
    </section>
</template>

<style scoped>

.number-pagination{
    gap: 25px;
    display: flex;
    font-weight: bold;
}

.header-text{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 172px;
    align-items: center;
}

.image-pagination {
    display: flex;
    width: 435px;
    height: 104px;
    justify-content: space-between; 
}

.carousel {
   width: 500px;
   height: 468px;
}
.technologie-section {
    background-color: #fff;
    /* ou #F8F8F8, selon ta maquette */
    color: #15253F;
    padding: 60px 0px;
    font-family: 'Figtree', sans-serif;
}

/* Ligne horizontale en haut */
.top-divider {
    border: none;
    border-top: 2px solid #15253F;
    margin-bottom: 40px;
}

/* Wrapper à 3 colonnes */
.content-wrapper {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    margin-top: 96px;
    gap: 172px;
    align-items: start;
}

/* ------ Colonne gauche ------ */
.left-column {
    display: flex;
    flex-direction: column;
    gap: 20px;
}

.left-intro {
    font-family: 'Gotu';
    font-size: 22px;
    line-height: 32px;
    margin: 0;
    color: #15253F;
}

.big-title {
    font-family: 'Aboreto';
    font-size: 76px;
    line-height: 92px;
    margin: 0;
    font-weight: 400;
    color: #BC9667;
}

.big-title span {
    color: #15253F;
}

/* ------ Colonne centrale ------ */
.center-column {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
}

.machine-info {
    display: flex;
    flex-direction: column;
    height: 468px;
    border-top: #15253F 2px solid;
    padding-top: 34px;
    justify-content: space-between;
}

.machine-title {
    font-family: 'Aboreto';
    font-size: 48px;
    line-height: 56px;
    margin: 0;
    font-weight: 400;
    color: #15253F;
}

/* Pagination style "01 / 10" + flèche circulaire */
.pagination-block {
    display: flex;
    align-items: center;
    gap: 16px;
    font-family: 'Figtree', sans-serif;
    font-size: 18px;
    color: #15253F;
}

.current {
    color: #15253F;
}

.slash,
.total {
    color: #BC9667;
}

.circle-arrow {
    background: none;
    border: 2px solid #15253F;
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
    background-color: #15253F;
}

/* ------ Colonne droite ------ */
.right-column {
    display: flex;
    flex-direction: column;
    gap: 24px;
}

.machine-image {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

.text-info {
    font-family: 'Figtree';
    font-size: 16px;
    line-height: 24px;
    color: #15253F;
    display: flex;
    flex-direction: column;
    gap: 10px;
}

/* Bouton "Więcej o technologii" */
.more-services-btn {
    align-self: flex-end;
    margin-top: 64px;
    padding: 24px 64px;
    background-color: transparent;
    border: 1px solid #15253F;
    color: #15253F;
    font-family: 'Inter';
    font-weight: 400;
    font-size: 23px;
    line-height: 24px;
    display: inline-flex;
    gap: 8px;
    width: 435px;
    border-radius: 100px;
    cursor: pointer;
    gap: 24px;
    justify-content: center;
    align-items: center;
}

.more-services-btn:hover {
    background-color: #15253F;
    color: #fff;
}
</style>