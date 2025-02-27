<template>
    <section class="machine9">
        <div class="content-block">
            <div class="text-col">
                <h2 class="sub-title">SMART DENTIN GRINDER</h2>
                <p class="intro-paragraph">
                    Smart Dentin Grinder to specjalny młynek, który pozwala usunięte zęby Pacjenta zamienić w wysokiej
                    jakości autologiczny biomateriał, który jest wykorzystywany do odbudowy kości m.in przy zabiegach
                    implantologicznych
                </p>
                <p class="paragraph">
                    Badania wykazały, że zębina wykazuje bardzo duże podobieństwo do kości. Preparat wyprodukowany z
                    poekstrakcyjnych zębów, umieszczony z w miejscu biorczym, ulega połączeniu i tworzy jakość kości
                    autogennej. Dzięki temu zostaje całkowicie wyeliminowany efekt „odrzucenia” biomateriału przez
                    Pacjenta, a czas gojenia się kości jest znacznie zredukowany.
                </p>
            </div>

            <div class="image-col">
                <img src="/static/Machine9.jpg" alt="SMART DENTIN GRINDER" />
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

.machine9 {
    padding-top: 96px;
}

.content-block {
    display: flex;
    gap: 182px;
    padding: 96px 150px 0px 150px;
    align-items: center;
    flex-direction: row-reverse;
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
    padding-top: 44px;
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
    width: 732px;
    height: 732px;
    border-radius: 3px;
}
</style>

<script>

export default {
    name: 'Machine9',
    components: {

    },
};
</script>