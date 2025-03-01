<template>
    <section class="machineUslugi13">
        <div class="content-block">
            <div class="text-col">
                <h2 class="sub-title">Chirurgia stomatologiczna</h2>
                <p class="paragraph">
                    Implantologia dentystyczna to zaawansowana dziedzina stomatologii, zajmująca się odbudową braków w
                    uzębieniu poprzez wszczepianie tytanowych implantów, które zastępują korzenie utraconych zębów.
                    Implanty są biokompatybilne, co oznacza, że integrują się z kością, tworząc stabilną podstawę dla
                    sztucznych zębów, a także zapobiegają zanikowi kości, co często występuje po utracie zęba.
                </p>
                <p class="paragraph">
                    Implanty można dostosować do różnych sytuacji klinicznych – od pojedynczych braków zębowych po pełną
                    rekonstrukcję łuków zębowych. Proces leczenia obejmuje diagnostykę, zabieg chirurgiczny, gojenie
                    oraz zamocowanie korony, mostu lub protezy. Dzięki nowoczesnym technologiom, takim jak tomografia
                    CBCT, implanty można precyzyjnie zaplanować, co zwiększa skuteczność i bezpieczeństwo zabiegu.
                </p>
                <p class="paragraph">
                    Implanty oferują trwałe i estetyczne rozwiązanie, które przy odpowiedniej pielęgnacji może służyć
                    przez wiele lat. Stanowią one najbardziej naturalną alternatywę dla tradycyjnych protez,
                    przywracając pełną funkcję żucia, mówienia i estetyki, co znacząco poprawia jakość życia pacjentów.
                </p>
            </div>

            <div class="image-col">
                <img src="/static/Uslugi/MachineUslugi13.jpg" alt="Chirurgia stomatologiczna" />
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

.machineUslugi13 {
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
    width: 733px;
    height: 670px;
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