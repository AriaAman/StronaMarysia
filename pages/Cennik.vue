<template>
    <section class="pricing-section">
        <!-- En‑tête : "KOSZTY LECZENIA" à gauche, texte explicatif à droite -->
        <div class="header-block">
            <div class="title-left">
                <h1 class="main-title">
                    KOSZTY<br />
                    <span>LECZENIA</span>
                </h1>
            </div>
            <div class="intro-right">
                <p>
                    Zapraszamy do zapoznania się z naszym cennikiem leczenia,
                    który obejmuje szczegółowe informacje na temat kosztów poszczególnych zabiegów
                    stomatologicznych. Nasze ceny są transparentne i odzwierciedlają wysoką jakość
                    świadczonych usług oraz nowoczesne technologie, które wykorzystujemy.
                    Dzięki temu możesz mieć pewność, że inwestujesz w zdrowie i piękny uśmiech.
                </p>
            </div>
        </div>

        <div class="container-prix">
            <!-- Sous-titre -->
            <div class="subheader">
                <h2>TWOJA INWESTYCJA W ZDROWY UŚMIECH:</h2>
            </div>

            <!-- TABLEAU DES TARIFS -->
            <div class="pricing-table">
                <!-- KONSULTACJE -->
                <div class="pricing-block">
                    <h3>KONSULTACJE</h3>
                    <div class="pricing-row-name">
                        <div class="item-name">Konsultacja stomatologiczna</div>
                        <div class="item-name">
                            Konsultacja stomatologiczna ze zdjęciem pantomograficznym cyfrowym
                        </div>
                        <div class="item-name">Konsultacja implantologiczna z tomografem</div>
                    </div>
                    <div class="pricing-row-price">
                        <div class="item-price">200 zł</div>
                        <div class="item-price">150 zł</div>
                        <div class="item-price">400 zł</div>
                    </div>
                </div>

                <!-- DIAGNOSTYKA -->
                <div class="pricing-block">
                    <h3>DIAGNOSTYKA</h3>
                    <div class="pricing-row-name">
                        <div class="item-name">Zdjęcie punktowe</div>
                        <div class="item-name">Zdjęcie pantomograficzne</div>
                        <div class="item-name">Tomograf</div>
                    </div>
                    <div class="pricing-row-price">
                        <div class="item-price">50 zł</div>
                        <div class="item-price">100 zł</div>
                        <div class="item-price">250–350 zł</div>
                    </div>
                </div>

                <!-- PROFILAKTYKA -->
                <div class="pricing-block">
                    <h3>PROFILAKTYKA</h3>
                    <div class="pricing-row-name">
                        <div class="item-name">
                            Pakiet higienizacyjny (skaling, piaskowanie, fluoryzacja)
                        </div>
                        <div class="item-name">Fluoryzacja obu łuków zębowych</div>
                        <div class="item-name">Piaskowanie zębów</div>
                        <div class="item-name">Skaling ultradźwiękowy</div>
                    </div>
                    <div class="pricing-row-price">
                        <div class="item-price">350 zł</div>
                        <div class="item-price">150 zł</div>
                        <div class="item-price">200 zł</div>
                        <div class="item-price">200 zł</div>
                    </div>
                </div>

                <!-- IMPLANTOLOGIA -->
                <div class="pricing-block">
                    <h3>IMPLANTOLOGIA</h3>
                    <div class="pricing-row-name">
                        <div class="item-name">Wszczepienie implantu</div>
                        <div class="item-name">Odsłonięcie implantu i założenie śruby gojącej</div>
                        <div class="item-name">Korona porcelanowa na implancie</div>
                        <div class="item-name">
                            Prace implantologiczne złożone wyceniane są indywidualnie
                        </div>
                        <div class="item-name">Szablon implantologiczny</div>
                        <div class="item-name">
                            Podniesienie dna zatoki szczękowej (sinus lift)
                        </div>
                    </div>
                    <div class="pricing-row-price">
                        <div class="item-price">3000 zł</div>
                        <div class="item-price">300 zł</div>
                        <div class="item-price">od 3000 zł</div>
                        <div class="item-price">-</div>
                        <div class="item-price">1000 zł</div>
                        <div class="item-price">3000–4000 zł</div>
                    </div>
                </div>

                <!-- PROTETYKA -->
                <div class="pricing-block">
                    <h3>PROTETYKA</h3>
                    <div class="pricing-row-name">
                        <div class="item-name">Implantologia dentystyczna</div>
                        <div class="item-name">Implantologia dentystyczna</div>
                        <div class="item-name">Implantologia dentystyczna</div>
                    </div>
                    <div class="pricing-row-price">
                        <div class="item-price">Implantologia dentystyczna</div>
                        <div class="item-price">Implantologia dentystyczna</div>
                        <div class="item-price">Implantologia dentystyczna</div>
                    </div>
                </div>

                <!-- ENDODONCJA (MIKROSKOPOWA) -->
                <div class="pricing-block">
                    <h3>ENDODONCJA (MIKROSKOPOWA)</h3>
                    <div class="pricing-row-name">
                        <div class="item-name">Implantologia dentystyczna</div>
                        <div class="item-name">Implantologia dentystyczna</div>
                        <div class="item-name">Implantologia dentystyczna</div>
                    </div>
                    <div class="pricing-row-price">
                        <div class="item-price">Implantologia dentystyczna</div>
                        <div class="item-price">Implantologia dentystyczna</div>
                        <div class="item-price">Implantologia dentystyczna</div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
p {
    margin: 0;
}
.container-prix {
    display: flex;
    width: 100%;
    flex-direction: column;
    margin: 0;
    padding-bottom: 96px;
}

/* Couleur de fond bleu sombre et texte clair */
.pricing-section {
    background-color: #15253F;
    color: #fff;
    padding: 60px 80px;
    min-height: 100vh;
    font-family: 'Figtree', sans-serif;
}

/* En‑tête : "KOSZTY LECZENIA" et paragraphe explicatif */
.header-block {
    display: flex;
    gap: 526px;
    height: 448px;
    margin-bottom: 40px;
}

.main-title {
    font-family: 'Aboreto';
    font-size: 112px;
    line-height: 130px;
    margin: 0;
    font-weight: 400;
    color: #BC9667;
}

.main-title span {
    display: block;
    color: #fff;
}

.intro-right {
    height: 304px;
    width: 732px;
    font-family: 'Gotu', cursive;
    font-weight: 400;
    font-size: 24px;
    line-height: 38px;
    color: #fff;
    margin: 0;
    text-transform: uppercase;
}

/* Sous‑titre + ligne */
.subheader {
    margin-top: 40px;
    margin-bottom: 40px;
}

.subheader h2 {
    font-family: 'Aboreto', cursive;
    font-size: 40px;
    line-height: 56px;
    color: #BC9667;
    margin: 0;
    font-weight: 400;
}

.subheader hr {
    border: none;
    border-top: 1px solid #BC9667;
    margin: 0;
}

/* Tableau principal */
.pricing-table {
    display: flex;
    flex-direction: column;
}

/* Chaque bloc (KONSULTACJE, DIAGNOSTYKA...) */
.pricing-block {
    border-top: 1px solid #FFFFFF;
    width: 1700px;
    gap: 182px;
    display: flex;
    padding: 32px 0px;
    align-items: center;
}

.pricing-block h3 {
    font-family: 'Aboreto', cursive;
    font-size: 40px;
    color: #fff;
    line-height: 56px;
    width: 30%;
    display: flex;
    font-weight: 400;
    text-transform: uppercase;
    align-items: center;
}

/* Chaque ligne : nom de l'acte à gauche + prix à droite */
.pricing-row-name {
    display: flex;
    gap: 32px;
    width: 428px;
    height: 100%;
    flex-direction: column;
}

.pricing-row-price {
    display: flex;
    position: relative;
    gap: 40px;
    flex-direction: column;
    justify-content: space-between;
    align-items: flex-start;
}

/* Nom de l'acte / du service */
.item-name {
    font-family: 'Figtree', cursive;
    font-size: 20px;
    line-height: 32px;
    color: #fff;
    max-width: 500px;
    font-weight: 400;
}

/* Prix */
.item-price {
    font-size: 20px;
    line-height: 32px;
    color: #BC9667;
    text-align: right;
    flex-shrink: 0;
    font-weight: 600;
    min-width: 50px;
}
</style>