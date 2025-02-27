<template>
    <section class="machine3">
        <div class="content-block">
            <div class="text-col">
                <h2 class="sub-title">LASER BIOLASE EPIC X</h2>
                <p class="intro-paragraph">
                    Laser stomatologiczny Epic X amerykańskiej firmy Biolase to najnowocześniejszy laser diodowy w
                    swojej klasie na świecie.
                </p>
                <p class="paragraph">
                    Charakteryzuje go doskonała precyzja, minimalizuje krwawienie, redukuje bakterie, zmniejsza ból i
                    dyskomfort pozabiegowy pacjentów.
                </p>
                
                <p class="paragraph">
                    Znajduje zastosowanie w implantologii, chirurgii, protetyce i stomatologii estetycznej. Dzięki
                    specjalnej końcówce LASER SMILE jest doskonałym rozwiązaniem dla wybielania zębów.
                </p>
            </div>

            <div class="image-col">
                <img src="/static/Machine3.jpg" alt="LASER BIOLASE EPIC X" />
            </div>

           

        </div>  

        <div class="nouvelle-technologie">
             <label>Nowoczesne Technologie, Doskonałe Wyniki – Twoje Zdrowie Naszym Priorytetem!!</label>   
        </div>

    </section>
</template>

<style scoped>
@media screen and (min-width: 2000px) {
    .content-block {
        justify-content: space-between;
    }
}

.machine3 {
    padding-top: 96px;
}

.content-block {
    display: flex;
    gap: 335px;
    align-items: flex-start;
    padding: 96px 150px 0px 150px;
    align-items: center;
}

.text-col {
    height: 100%;
    display: flex;
    flex-direction: column;
    gap: 24px;
}

.sub-title {
    font-family: 'Aboreto';
    font-size: 48px;
    line-height: 64px;
    font-weight: 400;
    color: #BC9667;
    margin: 0;
    border-bottom: 1px solid #BC9667;
}

.intro-paragraph {
    font-family: 'Gotu';
    font-size: 22px;
    line-height: 32px;
    font-weight: 400;
    color: #fff;
    margin: 0;
    text-transform: uppercase;
}

.paragraph {
    font-family: 'Figtree';
    font-size: 18px;
    line-height: 28px;
    font-weight: 400;
    color: #fff;
    margin: 0;
}

.intro-paragraph {
    font-family: 'Gotu';
    font-size: 22px;
    line-height: 32px;
    font-weight: 400;
    color: #fff;
    margin: 0;
    text-transform: uppercase;
}

.image-col img {
    width: 580px;
    height: 580px;
    border-radius: 3px;
}
.nouvelle-technologie {
    display: flex;
    justify-content: center;
    font-weight: 400;
    font-family: 'Aboreto';
    font-size: 76px;
    line-height: 92px;
    padding: 96px 30px;
    margin: 0;
    color: #BC9667;
}

</style>

<script>

export default {
    name: 'Machine3',
    components: {

    },
};
</script>