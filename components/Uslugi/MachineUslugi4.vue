<template>
    <section class="machineUslugi9">
        <div class="content-block">
            <div class="text-col">
                <h2 class="sub-title">Stomatologia estetyczna</h2>
                <p class="paragraph">
                    Stomatologia estetyczna to dziedzina stomatologii, która skupia się na poprawie wyglądu zębów,
                    dziąseł i ogólnego uśmiechu pacjenta, łącząc aspekty zdrowotne z estetycznymi. Jej celem jest
                    osiągnięcie harmonii w uśmiechu poprzez zabiegi, które poprawiają kształt, kolor, ustawienie i
                    proporcje zębów, zapewniając naturalny i atrakcyjny wygląd.
                </p>
                <p class="paragraph">
                    W ramach stomatologii estetycznej stosuje się różnorodne techniki, takie jak wybielanie zębów,
                    licówki porcelanowe, korony pełnoceramiczne, a także konturowanie dziąseł, które pozwalają na
                    osiągnięcie idealnego uśmiechu. Nowoczesne materiały, takie jak kompozyty o wysokiej estetyce, oraz
                    zaawansowane technologie, jak cyfrowe projektowanie uśmiechu (DSD), umożliwiają precyzyjne
                    planowanie i realizację zabiegów, które spełniają najwyższe standardy estetyczne. Stomatologia
                    estetyczna nie tylko poprawia wygląd zębów, ale również wpływa na samopoczucie pacjenta, zwiększając
                    jego pewność siebie i satysfakcję z własnego wyglądu.
                </p>
            </div>

            <div class="image-col">
                <img src="/static/Uslugi/MachineUslugi9.jpg" alt="Stomatologia estetyczna" />
            </div>
        </div>
    </section>
</template>

<style scoped>
@media screen and (min-width: 2000px) {
    .content-block {
        justify-content: space-between;
    }
}

.machineUslugi9 {
    padding-top: 128px;
}

.section-divider {
    padding-bottom: 96px;
    border: none;
    border-top: 1px solid #fff;
}

.content-block {
    display: flex;
    gap: 182px;
    padding: 0px 50px 0px 50px;
    align-items: center;
    justify-content: space-around;
}

.text-col {
    display: flex;
    flex-direction: column;
    gap: 24px;
    width: 582px;
}

.paragraph {
    font-family: 'Figtree';
    font-size: 18px;
    line-height: 24px;
    font-weight: 400;
    color: #15253F;
    margin: 0;
}

.sub-title {
    font-family: 'Aboreto';
    font-size: 48px;
    line-height: 64px;
    font-weight: 400;
    color: #BC9667;
    margin: 0;
    border-bottom: #BC9667 solid 1px;
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
    width: 733px;
    height: 670px;
    border-radius: 3px;
}
</style>

<script>

export default {
    name: 'MachineUslugi9',
    components: {

    },
};
</script>