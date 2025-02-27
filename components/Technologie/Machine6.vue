<template>
    <section class="machine6">
        <div class="content-block">
            <div class="text-col">
                <h2 class="sub-title">MORITA DENTAPORT</h2>
                <p class="intro-paragraph">
                    Endometr endodontyczny Morita Dentaport to urządzenie elektroniczne, dzięki któremu możliwe jest w
                    pełni precyzyjne oznaczenie długości kanałów korzeniowych.
                </p>
                <p class="paragraph">
                    W przeciwieństwie do tradycyjnych metod, z użyciem zdjęć rentgenowskich (zdjęcie z instrumentem),
                    pomiar wykonany przy pomocy endometru dokładnie wskazuje długość roboczą kanałów korzeniowych.
                    Urządzenie nie emituje promieni rentgenowskich, dzięki czemu jest w pełni bezpieczne dla Pacjenta.
                </p>
            </div>

            <div class="image-col">
                <img src="/static/Technologie/Machine6.jpg" alt="MORITA DENTAPORT" />
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

.machine6 {
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
    width: 732px;
    height: 732px;
    border-radius: 3px;
}
</style>

<script>

export default {
    name: 'Machine6',
    components: {

    },
};
</script>