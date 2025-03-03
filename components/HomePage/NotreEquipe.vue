<script setup>
import 'vue3-carousel/carousel.css'
import { ref } from 'vue'
import { Carousel, Slide, Pagination } from 'vue3-carousel'
import photo1 from '~/static/HomePage/photoHomePage6.jpg'
import photo2 from '~/static/HomePage/photoHomePage6.jpg'


const carouselConfig = {
    itemsToShow: 1,
    wrapAround: true,
    autoplay: 2000,
    transition: 600,
}

const carouselRef2 = ref();
const currentSlide = ref(1);

const next = () => {
    carouselRef2.value.next();
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
    <section class="notre-equipe-section">
        <div class="content-wrapper">
            <!-- Colonne gauche : grande image + slider info -->
            <div class="left-side">
                <div class="image-container">
                    <!-- Image principale (par ex. wnętrze gabinetu) -->
                    <h1 class="main-title">
                        Poznaj
                        <span>nas</span>
                    </h1>
                </div>
            </div>

            <!-- Colonne millieu : Titre / Sous-titre / Paragraphe -->
            <div class="middle-side">
                <div class="title-block">
                    <h2 class="title">Piotr Pietruszczak</h2>
                    <h3 class="sub-title">Lekarz Stomatolog</h3>
                </div>
                <div class="bloc-description">
                    <p class="description">
                        Absolwent Lwowskiego Narodowego Uniwersytetu Medycznego, który ukończył z wyróżnieniem w 2005
                        roku. Przez kilka lat zdobywał doświadczenie w prywatnych klinikach w Polsce i za granicą. Od
                        dziewięciu lat jest właścicielem gabinetu PIETRUSZCZAK STOMATOLOGIA.
                    </p>
                    <br>
                    <p class="description">
                        W 2019 roku uzyskał tytuł „Expert in Oral Implantology” nadany przez Niemieckie Towarzystwo
                        Implantologii Stomatologicznej DGOI (Deutsche Gesellschaft für Orale Implantologie). Posiada
                        certyfikat PSI/ICOI/ICOI Europe. Członek Polskiego Stowarzyszenia Implantologicznego PSI. Stale
                        uczestniczy w licznych kursach, szkoleniach i konferencjach poszerzając swoją wiedzę na temat
                        nowych technologii i rozwiązań w leczeniu pacjentów.
                    </p>
                    <br>
                    <p class="description">
                        Prywatnie tata dwóch synów. Wielbiciel starego rocka i gry na perkusji.
                    </p>
                </div>

                <!-- Pagination style "01 / 07" + flèche circulaire -->
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

            <div class="right-side">
                <div class="image-container">
                    <p>
                        Jesteśmy zespołem wysoko wykwalifikowanych specjalistów, którzy z pasją i profesjonalizmem dbają
                        o każdego pacjenta, zapewniając najwyższy standard opieki stomatologicznej oraz indywidualne
                        podejście w każdej sytuacji.
                    </p>
                </div>
                <div class="logo-container">
                    <div class="carousel">
                        <Carousel ref="carouselRef2" v-bind="carouselConfig">
                            <Slide v-for="slide in slides" :key="slide" >
                                <img :src="slide.src" alt="slide" />
                            </Slide>
                        </Carousel>
                    </div>
                </div>
            </div>

        </div>
    </section>
</template>


<style scoped>
.title {
    font-family: 'Aboreto';
    font-size: 48px;
    line-height: 64px;
    margin: 0;
    font-weight: 400;
    color: #15253F;
    border-bottom: #15253F 2px solid;
}

.right-side {
    display: flex;
    flex-direction: column;
    gap: 114px;
}

.image-container {
    font-family: 'Gotu';
    font-size: 22px;
    line-height: 32px;
    margin: 0;
    font-weight: 400;
    color: #15253F;
    text-transform: uppercase;
}

.notre-equipe-section {
    background-color: #fff;
    padding: 60px 0px;
    height: fit-content;
    font-family: 'Figtree', sans-serif;
}

/* Disposition générale : 2 colonnes */
.content-wrapper {
    display: flex;
    gap: 171px;
}

/* Colonne gauche (grande image + pagination) */
.carousel {
    width: 587px;
    height: 812px;
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
    color: #15253F;
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

.number-pagination {
    display: flex;
    gap: 25px;
}

/* Colonne droite */
.middle-side {
    display: flex;
    flex-direction: column;
    position: relative;
    width: 435px;
    justify-content: flex-end;
}

/* Titre / Sous-titre */

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
    color: #15253F;
}

.sub-title {
    font-family: 'Gotu';
    font-size: 24px;
    line-height: 40px;
    margin-bottom: 20px;
    font-weight: 400;
    color: #BC9667;
}

/* Paragraphe(s) de description */
.bloc-description {
    width: 435px;
    height: 448px;
}

.description {
    font-family: 'Figtree';
    font-size: 16px;
    line-height: 24px;
    color: #15253F;
}
</style>