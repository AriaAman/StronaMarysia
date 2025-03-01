<template>
    <section class="uslugi-section">
        <div class="header-block">
            <div class="title-left">
                <h1 class="main-title">
                    NASZA<br />
                    <span>OFERTA</span>
                </h1>
            </div>
            <div class="intro-right">
                <p>
                    Oferujemy szeroki zakres usług stomatologicznych, dostosowanych do indywidualnych potrzeb pacjentów.
                    Jesteśmy elastyczni w podejściu do leczenia i stale inwestujemy w rozwój oraz nowoczesne
                    technologie, aby zapewnić najwyższą jakość opieki i skuteczność naszych usług.
                </p>
            </div>
        </div>
        <MachineUslugi1 />
        <MachineUslugi2 />
        <MachineUslugi3 />
        <MachineUslugi5image />
        
        

    </section>
    <div class="uslugi-section-white">   
        <MachineUslugi4 />
        <MachineUslugi5 />
        <MachineUslugi6 />  
    </div>

    <div class="uslugi-section">
        <MachineUslugi12 />
        <MachineUslugi13 />
        <UlsugiChirurgie />

    </div>

</template>

<style scoped>
.uslugi-section {
    background-color: #15253F;
    color: #fff;
    padding: 60px 60px;
    min-height: 100vh;
    font-family: 'Figtree', sans-serif;
}

.uslugi-section-white {
    background-color: #fff;
    color: #15253F;
    padding: 60px 60px;
    min-height: 100vh;
    font-family: 'Figtree';
}

/* En‑tête : "KOSZTY LECZENIA" et paragraphe explicatif */
.header-block {
    display: flex;
    gap: 640px;
    height: 454px;
    margin-bottom: 64px;
    justify-content: space-between;
}

.main-title {
    font-family: 'Aboreto';
    font-size: 112px;
    line-height: 130px;
    margin: 0;
    font-weight: 400;
    height: 390px;
    color: #BC9667;
}

.main-title span {
    display: block;
    color: #fff;
}

.intro-right {
    height: 342px;
    font-family: 'Gotu', sans-serif;
    font-weight: 400;
    font-size: 24px;
    line-height: 38px;
    color: #fff;
    margin: 0;
    text-transform: uppercase;
}
</style>

<script>
import MachineUslugi1 from '~/components/Uslugi/MachineUslugi1.vue';
import MachineUslugi2 from '~/components/Uslugi/MachineUslugi2.vue';
import MachineUslugi3 from '~/components/Uslugi/MachineUslugi3.vue';
import MachineUslugi4 from '~/components/Uslugi/MachineUslugi4.vue';
import MachineUslugi5 from '~/components/Uslugi/MachineUslugi5.vue';
import MachineUslugi5image from '~/components/Uslugi/MachineUslugi5image.vue';
import MachineUslugi6 from '~/components/Uslugi/MachineUslugi6.vue';
import MachineUslugi12 from '~/components/Uslugi/MachineUslugi12.vue';
import MachineUslugi13 from '~/components/Uslugi/MachineUslugi13.vue';
import UlsugiChirurgie from '~/components/Uslugi/UlsugiChirurgie.vue';



export default {
  name: 'UslugiPage',
  components: {
    MachineUslugi1, 
    MachineUslugi2,
    MachineUslugi3,
    MachineUslugi5image,
    MachineUslugi4,
    MachineUslugi5,
    MachineUslugi6,
    MachineUslugi12,
    MachineUslugi13,
    UlsugiChirurgie
  },
};
</script>