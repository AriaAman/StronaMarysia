<template>
    <section class="machine4">
        <div class="content-block">
            <div class="text-col">
                <h2 class="sub-title">FIZJODYSPENSER IMPLANTMED W&H</h2>
                <p class="intro-paragraph">
                    Najnowszej generacji fizjodyspenser Implantmed, austriackiej firmy W&H. Synonim maksymalnej
                    precyzji, jakości i bezpieczeństwa w dziedzinie implantologii i chirurgii.
                </p>
                <p class="paragraph">
                    Dzięki niemu możliwe jest przeprowadzanie zaawansowanych procedur takie jak resekcje, usuwanie
                    zatrzymanych zębów mądrości czy modelowanie kości.
                </p>
                <p class="paragraph">
                    Posiada unikalną funkcję gwintowania maszynowego, która zapobiega kompresji kości, ułatwiając zabieg
                    implantacji. Znacznie poprawia dokładność i bezpieczeństwo zabiegów chirurgicznych.
                </p>
            </div>

            <div class="image-col">
                <img src="/static/Machine4.jpg" alt="Tomograf CS 9600" />
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


.machine4 {
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
    width: 733px;
    height: 670px;
    border-radius: 3px;
}
</style>

<script>

export default {
    name: 'Machine4',
    components: {

    },
};
</script>