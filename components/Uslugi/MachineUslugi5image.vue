<template>
    <section class="prosthetic-section">
        <!-- Gros titre -->
        <h2 class="section-title">
            PRACE PROTETYCZNE WYKONYWANE W NASZYM GABINECIE:
        </h2>
        <hr class="divider" />

        <!-- 1) KORONA -->
        <div class="block">
            <img src="/static/Uslugi/MachineUslugi4.jpg" alt="Korona" class="block-image" />
            <h3 class="block-title">KORONA</h3>
            <div class="block-text">
                <p>
                    Korona to stałe uzupełnienie protetyczne, które obejmuje
                    całą powierzchnię zęba, pozwalając na odtworzenie jego
                    kształtu, koloru oraz niewielką korektę ustawienia w łuku,
                    co przywraca estetyczny wygląd. Stosuje się ją, gdy
                    odbudowa naturalnej korony zęba przy użyciu kompozytu jest
                    niemożliwa.
                </p>
                <p>
                    Aby założyć koronę, konieczne jest zeszlifowanie zęba,
                    tworząc filar, na którym mocuje się koronę. Jeśli filar jest
                    zbyt słaby, stosuje się wzmacniający wkład koronowo-korzeniowy,
                    np. z włókna szklanego. W naszym gabinecie oferujemy korony
                    porcelanowe na podbudowie metalowej, pełnoceramiczne oraz
                    na podbudowie z tlenku cyrkonu.
                </p>
            </div>
        </div>

        <hr class="divider" />

        <!-- 2) LICÓWKI -->
        <div class="block">
            <img src="/static/Uslugi/MachineUslugi5.jpg" alt="Licówki" class="block-image" />
            <h3 class="block-title">LICÓWKI</h3>
            <div class="block-text">
                <p>
                    Licówki to uzupełnienie protetyczne w postaci cienkiej płytki
                    najczęściej wykonanej z porcelany, materiału ceramicznego lub
                    kompozytowego. Przy minimalnej preparacji szkliwa możliwe jest
                    osiągnięcie spektakularnego efektu.
                </p>
                <p>Poprzez zastosowanie licówek możemy:</p>
                <ul>
                    <li>wydłużyć i powiększyć zęby</li>
                    <li>zamknąć diastemy i tremy</li>
                    <li>poprawić nieprawidłowe ustawienie</li>
                    <li>wybielić i usunąć śnie przebarwienia</li>
                    <li>zatuszować uszkodzone szkliwo</li>
                    <li>odbudować rozległe ubytki przyszyjkowe</li>
                    <li>nadać wymarzony, zaprojektowany wcześniej kształt</li>
                </ul>
            </div>
        </div>

        <hr class="divider" />

        <!-- 3) MOST -->
        <div class="block">
            <img src="/static/Uslugi/MachineUslugi6.jpg" alt="Most" class="block-image" />
            <h3 class="block-title">MOST</h3>
            <div class="block-text">
                <p>
                    Most stosuje się w przypadku braku jednego lub kilku
                    sąsiadujących ze sobą zębów. By zamocować most w jamie
                    ustnej potrzebna jest do tego solidna podstawa w postaci
                    implantów lub zębów naturalnych, sąsiadujących z danym
                    brakiem zębowym. Podobnie jak w przypadku koron zęby
                    sąsiadujące wymagają opracowania filarów pod mosty.
                </p>
                <p>
                    Zgodnie z najnowszymi standardami w przypadkach gdy
                    obok luki znajdują się zęby zdrowe zaleca się uzupełnienie
                    brakujących zębów przy pomocy wszczepów
                    śródkostnych – implantów
                </p>
            </div>
        </div>

        <hr class="divider" />

        <!-- 4) INLAY, ONLAY I OVERLAY -->
        <div class="block">
            <img src="/static/Uslugi/MachineUslugi7.jpg" alt="Inlay, Onlay i Overlay" class="block-image" />
            <h3 class="block-title">
                INLAY, ONLAY <br /> I OVERLAY
            </h3>
            <div class="block-text">
                <p>
                    INLAY, ONLAY I OVERLAY to nowoczesna metoda wypełnienia
                    w koronie zęba, którą stosuje się w przypadku dużych ubytków.
                    Stanowi alternatywę dla wypełnienia w zębie wykonanego metodą
                    tradycyjną. Umożliwiają dokładną rekonstrukcję kształtu
                    anatomicznego zęba (guzków, bruzd i punktów stykowych
                    między zębami).
                </p>
                <p>
                    Kompozytowe lub porcelanowe, wykonywane na podstawie
                    wycisków w laboratorium protetycznym. Zabieg wymaga
                    zazwyczaj dwóch wizyt. Na pierwszym spotkaniu leczymy
                    ząb i przygotowujemy pod uzupełnienie, wykonujemy
                    wyciski i zakładamy wypełnienie tymczasowe. Już na
                    drugiej wizycie całkowicie bezboleśnie wklejamy gotowy
                    onlay, inlay, overlay.
                </p>
            </div>
        </div>

        <hr class="divider" />

        <!-- 5) PROTEZY RUCHOME -->
        <div class="block">
            <img src="/static/Uslugi/MachineUslugi8.jpg" alt="Protezy ruchome" class="block-image" />
            <h3 class="block-title">PROTEZY RUCHOME</h3>
            <div class="block-text">
                <p>
                    Proteza zębowa to uzupełnienie protetyczne mające
                    zastosowanie w przypadku licznych ubytków zębowych
                    lub całkowitego bezzębia. Przywraca utracone funkcje
                    jamy ustnej.
                </p>
                <p>Wyróżniamy:</p>
                <ul>
                    <li>
                        protezy ruchome oparte na zębach własnych pacjenta –
                        wyjmowane przez pacjenta (protezy akrylowe, protezy
                        szkieletowe (klamrowe i bezklamrowe), protezy
                        teleskopowe)
                    </li>
                    <li>
                        protezy ruchome całkowite (stosowane w przypadku
                        bezzębia)
                    </li>
                </ul>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'ProstheticWorks'
};
</script>

<style scoped>
.prosthetic-section {
    background-color: #15253F;
    color: #fff;
    padding: 60px 80px;
    font-family: 'Figtree', sans-serif;
}

/* Titre principal de la section */
.section-title {
    font-family: 'Aboreto', cursive;
    font-size: 40px;
    /* Ajuste selon maquette */
    line-height: 52px;
    color: #BC9667;
    /* Doré */
    margin: 0 0 20px;
    font-weight: 400;
    text-transform: uppercase;
    /* Si besoin */
}

.divider {
    border: none;
    border-top: 1px solid #fff;
    margin: 20px 0;
}

/* Chaque bloc : image à gauche, titre au centre, texte à droite */
.block {
    display: grid;
    grid-template-columns: 300px 200px 1fr;
    /* Ajuste les largeurs */
    gap: 20px;
    align-items: start;
    margin-bottom: 40px;
}

/* Image */
.block-image {
    width: 427px;
    height: 427px;
    height: auto;
    border-radius: 6px;
    /* Si besoin */
}

/* Titre (ex: KORONA) */
.block-title {
    font-family: 'Aboreto', cursive;
    font-size: 28px;
    /* Ajuste */
    line-height: 36px;
    font-weight: 400;
    color: #fff;
    text-transform: uppercase;
    display: flex;
    align-items: center;
    margin: 0;
    /* Pour supprimer tout espace par défaut */
}

/* Texte descriptif */
.block-text {
    font-family: 'Gotu', sans-serif;
    font-size: 18px;
    line-height: 28px;
    color: #fff;
    display: flex;
    flex-direction: column;
    gap: 10px;
}

.block-text ul {
    margin: 0;
    padding-left: 20px;
    list-style: disc;
    /* Pour un bullet point normal */
}

.block-text li {
    margin-bottom: 5px;
}
</style>