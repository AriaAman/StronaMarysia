<template>
    <section class="machineUslugi2">
        <div class="content-block">
            <div class="text-col">
                <h2 class="sub-title">Leczenie kanałowe (endodoncja)</h2>
                <p class="paragraph">
                    Endodoncja to dział stomatologii zajmujący się leczeniem chorób miazgi zęba, głównie spowodowanych
                    przez bakterie wnikające do miazgi przez ubytki próchnicowe, powodując stan zapalny.
                    Miazga zęba może także ucierpieć wskutek urazów. Celem leczenia endodontycznego jest eliminacja
                    bakterii z kanałów korzeniowych, ich mechaniczne i chemiczne opracowanie oraz szczelne wypełnienie.
                </p>
                <p class="paragraph">
                    Mikroskop do leczenia kanałowego umożliwia precyzyjną ocenę liczby i lokalizacji kanałów, a także
                    identyfikację zwężeń, zarośnięć i perforacji kanałowych. Endometr endodontyczny służy do dokładnego
                    określenia długości kanałów, wykorzystując różnice w oporności elektrycznej tkanek. W trakcie
                    leczenia stosuje się radiowizjografię, czyli cyfrowe zdjęcia RTG, a w trudnych przypadkach -
                    tomografię CBCT.
                </p>
                <p class="paragraph">
                    Jest to przede wszystkim ratowanie własnych zębów pacjenta, co jest możliwe dzięki nowoczesnym
                    technikom. Przypadki o słabych rokowaniach mają teraz większą szansę na wyleczenie, leczenie
                    endodontyczne staje się coraz bardziej skuteczne i precyzyjne.
                </p>
            </div>

            <div class="image-col">
                <img src="/static/Uslugi/MachineUslugi2.jpg" alt="Implantologia dentystyczna" />
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

.machineUslugi2 {
    padding-top: 192px;
}   

.content-block {
    display: flex;
    gap: 182px;
    padding: 0px 50px;
    align-items: center;
    flex-direction: row-reverse;
}

.text-col {
    display: flex;
    flex-direction: column;
    gap: 24px;
}

.paragraph {
    font-family: 'Figtree';
    font-size: 16px;
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
    width: 732px;
    height: 732px;
    border-radius: 3px;
}
</style>

<script>

export default {
    name: 'Machine2',
    components: {

    },
};
</script>