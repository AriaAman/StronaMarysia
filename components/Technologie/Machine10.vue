<template>
    <section class="machine10">
        <div class="content-block">
            <div class="text-col">
                <h2 class="sub-title">RADIOWIZJOGRAFIA RVG Kodak 6100</h2>
                <p class="intro-paragraph">
                    Radiowizjograf RVG Kodak 6100 – niezbędny podczas każdego leczenia endodontycznego
                </p>
                <p class="paragraph">
                    Pozwala między innymi na precyzyjną ocenę długości kanału zęba, jak i sprawdzenie, czy został on
                    prawidłowo wypełniony w trakcie leczenia. Dzięki temu lekarz ma pewność, że przeprowadzone przez
                    niego leczenie jest skuteczne.
                </p>
                <p class="paragraph">
                    Radiowizjografia przypomina tradycyjne zdjęcie rentgenowskie, jednak jest jego unowocześnioną
                    wersją, dzięki której uzyskujemy zdjęcia w jakości cyfrowej.
                </p>
            </div>

            <div class="image-col">
                <img src="/static/Technologie/Machine10.jpg" alt="RADIOWIZJOGRAFIA RVG Kodak 6100" />
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

.machine10 {
    padding-top: 96px;
}

.content-block {
    display: flex;
    gap: 335px;
    padding: 96px 150px 96px 150px;
    align-items: center;

}

.text-col {
    max-width: 600px;
    display: flex;
    flex-direction: column;
    gap: 24px;
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

.sub-title {
    font-family: 'Aboreto';
    font-size: 48px;
    line-height: 64px;
    font-weight: 400;
    color: #BC9667;
    margin: 0;
    border-bottom: #BC9667 1px solid;
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
    name: 'Machine10',
    components: {

    },
};
</script>