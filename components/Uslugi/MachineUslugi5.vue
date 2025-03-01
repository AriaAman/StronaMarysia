<template>
    <section class="machineUslugi10">
        <div class="content-block">
            <div class="text-col">
                <h2 class="sub-title">Stomatologia zachowawcza</h2>
                <p class="paragraph">
                    Stomatologia zachowawcza to dziedzina stomatologii koncentrująca się na zapobieganiu i leczeniu
                    chorób zębów, głównie próchnicy oraz niewielkich uszkodzeń tkanek twardych zębów. Jej celem jest
                    zachowanie naturalnych zębów pacjenta w jak najlepszym stanie poprzez usuwanie ubytków próchnicowych
                    i odbudowę uszkodzonych zębów za pomocą materiałów kompozytowych, które imitują naturalną strukturę
                    zęba.
                </p>
                <p class="paragraph">
                    W ramach stomatologii zachowawczej stosuje się różne techniki, takie jak remineralizacja szkliwa,
                    leczenie endodontyczne (kanałowe) oraz stosowanie nowoczesnych wypełnień, które zapewniają
                    estetyczny wygląd i długotrwałą ochronę zębów. Dzięki zaawansowanym narzędziom diagnostycznym, takim
                    jak cyfrowe RTG, możliwe jest wczesne wykrywanie zmian próchnicowych, co pozwala na ich szybkie i
                    mniej inwazyjne leczenie. Regularne wizyty kontrolne i profilaktyczne zabiegi, takie jak fluoryzacja
                    czy lakowanie bruzd, są kluczowe w zapobieganiu dalszym uszkodzeniom i utrzymaniu zdrowych zębów na
                    długie lata.
                </p>
            </div>

            <div class="image-col">
                <img src="/static/Uslugi/MachineUslugi10.jpg" alt="Stomatologia zachowawcza" />
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

.machineUslugi10 {
    padding-top: 128px;
}

.content-block {
    display: flex;
    gap: 182px;
    align-items: center;
    padding: 0px 50px 0px 50px;
    justify-content: space-around;
    flex-direction: row-reverse;
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
    width: 579px;
    height: 579px;
    border-radius: 3px;
}
</style>

<script>

export default {
    name: 'MachineUslugi10',
    components: {},
};
</script>