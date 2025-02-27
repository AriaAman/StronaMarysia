<template>
    <section class="machine8">
        <div class="content-block">
            <div class="text-col">
                <h2 class="sub-title">SPEKTROFOTOMETR SPECTRO SHADE</h2>
                <p class="intro-paragraph">
                    SpectroShade to zaawansowany technologicznie system, przeznaczony do błyskawicznej i wiarygodnej
                    analizy koloru zębów i prac protetycznych. 
                </p>
                <p class="paragraph">
                    Niewłaściwie dobrany kolor dyskwalifikuje nawet najlepiej wykonaną nową koronę, most czy protezę.
                    Spektrofotometr analizuje ilość światła pochłoniętego przez obiekt w całym zakresie pasma
                    widzialnego.
                </p>

                <p class="paragraph">
                    W ciągu kilku minut analizuje kolor, przezierność i wszelkie detale wpływające na naturalny wygląd
                    zęba. Jest pierwszym i jak na razie jedynym systemem, który wykonuje analizy w odniesieniu do tego,
                    co widzi ludzkie oko.
                </p>
            </div>

            <div class="image-col">
                <img src="/static/Machine8.jpg" alt="LASER BIOLASE EPIC X" />
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

.machine8 {
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
    name: 'Machine8',
    components: {

    },
};
</script>