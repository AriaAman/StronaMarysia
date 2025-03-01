<template>
    <section class="machineUslugi12">
        <div class="content-block">
            <div class="text-col">
                <h2 class="sub-title">Profilaktyka</h2>
                <p class="paragraph">
                    Profilaktyka stomatologiczna to kluczowa dziedzina stomatologii, która koncentruje się na
                    zapobieganiu chorobom zębów i dziąseł oraz utrzymaniu zdrowia jamy ustnej na najwyższym poziomie.
                    Jej celem jest minimalizowanie ryzyka wystąpienia próchnicy, choroby przyzębia czy ubytki, poprzez
                    regularne wizyty kontrolne, odpowiednią higienę jamy ustnej i stosowanie specjalistycznych zabiegów
                    profilaktycznych.
                </p>
                <p class="paragraph">
                    W ramach profilaktyki stomatologicznej stosuje się różnorodne zabiegi, takie jak profesjonalne
                    czyszczenie zębów, fluoryzacja, lakowanie bruzd u dzieci, a także edukacja pacjentów w zakresie
                    właściwej techniki szczotkowania, nitkowania i wyboru odpowiednich produktów do higieny jamy ustnej.
                </p>
                <p class="paragraph">
                    Regularne przeglądy stomatologiczne pozwalają na wczesne wykrycie problemów, które mogą zostać
                    szybko i skutecznie rozwiązane, zanim przekształcą się w poważniejsze schorzenia.
                    Profilaktyka stomatologiczna odgrywa kluczową rolę w długotrwałym utrzymaniu zdrowych zębów i
                    dziąseł, co ma bezpośredni wpływ na ogólny stan zdrowia pacjenta.
                </p>
            </div>

            <div class="image-col">
                <img src="/static/Uslugi/MachineUslugi12.jpg" alt="Profilaktyka" />
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

.machineUslugi12 {
    padding-top: 120px;
}

.content-block {
    display: flex;
    gap: 182px;
    padding: 0px 50px;
    align-items: center;
    flex-direction: row-reverse;
    justify-content: space-evenly;
}

.text-col {
    display: flex;
    flex-direction: column;
    gap: 24px;
    width: 581px;
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
    name: 'Machine2',
    components: {

    },
};
</script>