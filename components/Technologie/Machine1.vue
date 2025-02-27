<template>
    <section class="machine1">
        <hr class="section-divider" />
        <div class="content-block">
            <div class="text-col">
                <h2 class="sub-title">TOMOGRAF CS 9600</h2>
                <p class="intro-paragraph">
                    to najbardziej zaawansowany aparat CBCT w swojej kategorii, oferujący najwyższą precyzję i
                    wszechstronność w diagnostyce stomatologicznej.
                </p>
                <p class="paragraph">
                    Innowacyjne urządzenie łączy w sobie zaawansowaną technologię
                    obrazowania 3D z prostotą użytkowania, umożliwiając uzyskanie
                    niezwykle szczegółowych i trójwymiarowych obrazów struktur
                    anatomicznych głowy i szyi.
                </p>
                <p class="paragraph">
                    Dzięki zastosowaniu stożkowej wiązki promieniowania rentgenowskiego
                    aparat pozwala na precyzyjne odwzorowanie nawet najdrobniejszych
                    detali budowy anatomicznej pacjenta, co jest kluczowe przy planowaniu
                    skomplikowanych zabiegów, takich jak implantologia, chirurgia
                    szczękowa, czy ortodoncja.
                </p>
                <p class="paragraph">
                    Został zaprojektowany z myślą o maksymalnym komforcie pacjenta –
                    zminimalizowana dawka promieniowania oraz skrócony czas badania
                    sprawiają, że procedura jest bezpieczniejsza i bardziej komfortowa.
                </p>
            </div>

            <div class="image-col">
                <img src="/static/Technologie/Machine1.jpg" alt="Tomograf CS 9600" />
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

.section-divider {
    padding-bottom: 96px;
    border: none;
    border-top: 1px solid #fff;
}

.content-block {
    display: flex;
    gap: 335px;
    padding: 0px 150px;
    align-items: center;
}

.text-col {
    max-width: 600px;
    display: flex;
    flex-direction: column;
    gap: 16px;
}

.intro-paragraph{
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

.sub-title {
    font-family: 'Aboreto';
    font-size: 48px;
    line-height: 64px;
    font-weight: 400;
    color: #BC9667;
    margin: 0;
    text-decoration: underline 1px;
    text-underline-offset: 9px;
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
    height: 579px;
    border-radius: 3px;
}
</style>

<script>

export default {
    name: 'Machine1',
    components: {

    },
};
</script>