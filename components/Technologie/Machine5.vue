<template>
    <section class="machine5">
        <div class="content-block">
            <div class="text-col">
                <h2 class="sub-title">MIKROSKOP ZUMAX</h2>
                <p class="intro-paragraph">
                    Mikroskop stomatologiczny ZUMAX OMS2350 jest używany przede wszystkim podczas leczenia kanałowego
                    oraz w protetyce, pozwalając na dostrzeżenie niewidocznych szczegółów anatomii uzębienia.
                </p>
                <p class="paragraph">
                    Wykorzystywany jest do odnajdywania ujść kanałów korzeniowych, usuwania obliteracji kanałów, czy do
                    precyzyjnego wykonywania wypełnień
                </p>
                <p class="paragraph">
                    Dzięki obrazowi HD umożliwia dostrzeżenie ubytków niewidocznych gołym okiem, pęknięć szkliwa,
                    drobnych zmian w przyzębiu oraz pozwala na wyjątkową precyzję podczas skomplikowanych zabiegów
                    stomatologicznych.
                </p>
            </div>

            <div class="image-col">
                <img src="/static/Machine5.jpg" alt="Tomograf CS 9600" />
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

.machine5 {
    padding-top: 160px;
}

.section-divider {
    padding-bottom: 96px;
    border: none;
    border-top: 1px solid #fff;
}

.content-block {
    display: flex;
    gap: 182px;
    padding: 0px 150px;
    align-items: center;
    flex-direction: row-reverse;
    justify-content: space-between;
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
    color: #15253F;
    margin: 0;
    text-transform: uppercase;
}

.paragraph {
    font-family: 'Figtree';
    font-size: 18px;
    line-height: 28px;
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
    border-bottom: #BC9667 1px solid;
}

.intro-paragraph {
    font-family: 'Gotu';
    font-size: 22px;
    line-height: 32px;
    font-weight: 400;
    color: #15253F;
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
    name: 'Machine5',
    components: {

    },
};
</script>