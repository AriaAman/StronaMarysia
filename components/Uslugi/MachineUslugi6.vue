<template>
    <section class="machineUslugi11">
        <div class="content-block">
            <div class="text-col">
                <h2 class="sub-title">Diagnostyka</h2>
                <p class="paragraph">
                    Diagnostyka w stomatologii to proces oceny stanu zdrowia jamy ustnej, który obejmuje wywiad z
                    pacjentem, badanie kliniczne oraz zaawansowane metody obrazowania, takie jak RTG i tomografia CBCT.
                </p>
                <p class="paragraph">
                    Dzięki tym narzędziom możliwe jest wykrycie próchnicy, chorób dziąseł, zmian w kościach, a także
                    niewidocznych gołym okiem schorzeń, takich jak torbiele czy nowotwory.
                </p>
                <p class="paragraph">
                    Można również stosować specjalistyczne badania, takie jak testy żywotności miazgi, diagnostykę
                    laserową czy cyfrowe skanowanie 3D, które pomagają precyzyjnie ocenić stan zębów i tkanek przyzębia.
                </p>
                <p class="paragraph">
                    Dzięki dokładnej diagnostyce możliwe jest nie tylko zapobieganie poważnym schorzeniom, ale także
                    precyzyjne planowanie leczenia, co znacząco poprawia skuteczność i efektywność interwencji
                    stomatologicznych. W efekcie, pacjenci mogą liczyć na szybsze, mniej inwazyjne leczenie, co
                    przekłada się na lepsze wyniki terapeutyczne i długoterminowe zdrowie jamy ustnej.
                </p>
            </div>

            <div class="image-col">
                <img src="/static/Uslugi/MachineUslugi11.jpg" alt="Diagnostyka" />
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

.machineUslugi11 {
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
    width: 732px;
    height: 732px;
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