<template>
    <section class="machine2">
        <div class="content-block">
            <div class="text-col">
                <h2 class="sub-title">SKANER WEWNĄTRZUSTNY <br> CS 3600</h2>
                <p class="intro-paragraph">
                    Carestream CS 3600 to nowoczesne urządzenie, które pozwala na otrzymanie wirtualnego obrazu jamy
                    ustnej na ekranie komputera w ciągu kilku minut.
                </p>
                <p class="paragraph">
                    Dokładne działanie urządzenia opiera się na wykonywaniu tysięcy drobnych ujęć, które następnie
                    składają się na kompletny, precyzyjny obraz.
                </p>
                <p class="paragraph">
                    Dzięki temu, że urządzenie jest w stanie wychwycić najdrobniejsze detale anatomiczne, wszelkie
                    planowane prace, szczególnie te protetyczne, będą cechować się niezwykłym dopasowaniem do
                    indywidualnych warunków jamy ustnej pacjentów.Ponadto urządzenie pozwala wyeliminować dyskomfort u
                    pacjentów związany z silnym odruchem wymiotnym podczas używania mas wyciskowych.
                </p>
            </div>

            <div class="image-col">
                <img src="/static/Technologie/Machine2.jpg" alt="SKANER WEWNĄTRZUSTNY CS 3600" />
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

.machine2 {
    padding-top: 96px;
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
    name: 'Machine2',
    components: {

    },
};
</script>