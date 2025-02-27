<template>
    <section class="machine7">
        <div class="content-block">
            <div class="text-col">
                <h2 class="sub-title">ZNIECZULENIE DENTAPEN</h2>
                <p class="intro-paragraph">
                    Carestream CS 3600 to nowoczesne urządzenie, które pozwala na otrzymanie wirtualnego obrazu jamy
                    ustnej na ekranie komputera w ciągu kilku minut.
                </p>
                <p class="paragraph">
                    Dentapen to szwajcarski system do znieczuleń komputerowych, sterowany za pomocą miniprocesora.
                </p>
                <p class="paragraph">
                    Nowa technologia pozwala na kontrolowanie przepływu środka znieczulającego, dzięki czemu pacjent nie
                    odczuwa nieprzyjemnego rozpychania tkanek, tak jak to się dzieje w tradycyjnej metodzie
                    znieczulania.
                </p>
                <p class="paragraph">
                    Wyglądem przypomina długopis, co w przeciwieństwie do tradycyjnej strzykawki nie wywołuje
                    nieprzyjemnych skojarzeń.
                </p>
            </div>

            <div class="image-col">
                <img src="/static/Machine7.jpg" alt="SKANER WEWNĄTRZUSTNY CS 3600" />
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


.content-block {
    display: flex;
    gap: 182px;
    padding: 96px 150px 0px 150px;
    flex-direction: row-reverse;
    align-items: center;
}

.text-col {
    width: 587px;
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
    width: 732px;
    height: 732px;
    border-radius: 3px;
}
</style>

<script>

export default {
    name: 'Machine7',
    components: {

    },
};
</script>