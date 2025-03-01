<template>
    <section class="machineUslugi3">
        <div class="content-block">
            <div class="text-col">
                <h2 class="sub-title">Protetyka</h2>
                <p class="paragraph">
                    Protetyka to dziedzina stomatologii zajmująca się uzupełnianiem braków zębowych oraz poprawą wyglądu
                    zębów, mająca na celu przywrócenie pacjentowi funkcji żucia i poprawę jakości życia, zwłaszcza w
                    zakresie estetyki.
                </p>
                <p class="paragraph">
                    W naszym gabinecie oferujemy uzupełnienia kombinowane – połączenie uzupełnień ruchomych ze stałymi,
                    dostosowane do warunków i oczekiwań pacjenta. Każda praca protetyczna jest doprecyzowana i starannie
                    dobrana do indywidualnych potrzeb pacjenta, a współpraca z renomowanymi laboratoriami z Warszawy
                    gwarantuje najwyższą jakość koron, licówek, mostów i protez. Przy planowaniu leczenia szczegółowo
                    omawiamy wszystkie możliwe warianty, uwzględniając stan zdrowia pacjenta, rodzaj braków zębowych
                    oraz szacowany kosztorys.
                </p>
                <p class="paragraph">
                    Dzięki temu pacjent ma pełną świadomość dostępnych opcji i może podjąć świadomą decyzję dotyczącą
                    leczenia.
                </p>
            </div>

            <div class="image-col">
                <img src="/static/Uslugi/MachineUslugi3.jpg" alt="Protetyka" />
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

.machineUslugi3 {
    padding-top: 192px;
}

.content-block {
    display: flex;
    gap: 335px;
    padding: 0px 50px 112px 50px;
    align-items: center;

}

.text-col {
    display: flex;
    flex-direction: column;
    gap: 24px;
}

.paragraph {
    font-family: 'Figtree';
    font-size: 18px;
    line-height: 24px;
    font-weight: 400;
    color: #fff;
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
    width: 580px;
    height: 580px;
    border-radius: 3px;
}
</style>

<script>

export default {
    name: 'Machine3',
    components: {

    },
};
</script>