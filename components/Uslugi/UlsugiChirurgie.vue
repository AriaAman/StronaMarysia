<template>
    <section class="chirurgie-section">
      <!-- Titre principal -->
      <h2 class="section-title">
        ZABIEGI CHIRURGICZNE WYKONYWANE<br />
        W NASZYM GABINECIE:
      </h2>
  
      <div class="procedure-list">
        <!-- EKSTRAKCJE -->
        <div class="procedure-row">
          <div class="procedure-name">EKSTRAKCJE</div>
          <div class="procedure-desc">
            • usunięcie zęboduł zębów, których nie daje się skutecznie leczyć zachowawczo;
          </div>
        </div>
  
        <!-- USUWANIE ZĘBÓW ZATRZYMANYCH -->
        <div class="procedure-row">
          <div class="procedure-name">USUWANIE ZĘBÓW ZATRZYMANYCH</div>
          <div class="procedure-desc">
            • tzw (ósemek), złamanych lub niewyrżniętych, których usunięcie jest konieczne
              ze względu na postępowanie ortodontyczne lub protetyczne;
          </div>
        </div>
  
        <!-- EKSTRAKCJĘ ZĘBÓW MĄDROŚCI -->
        <div class="procedure-row">
          <div class="procedure-name">EKSTRAKCJĘ ZĘBÓW MĄDROŚCI</div>
          <div class="procedure-desc">
            • zabieg chirurgiczny polegający na usunięciu trzecich trzonowców,
              znanych jako zęby mądrości; są to ostatnie zęby, które wyrzynają się
              w jamie ustnej, zazwyczaj między 17. a 25. rokiem życia;
          </div>
        </div>
  
        <!-- RESEKCJĘ WIERZCHOŁKA KORZENIA -->
        <div class="procedure-row">
          <div class="procedure-name">RESEKCJĘ WIERZCHOŁKA KORZENIA</div>
          <div class="procedure-desc">
            • polega na odcięciu wierzchołka korzenia wraz z otaczającą zmianą
              (zabieg ratujący ząb w przypadku występowania dużych ropni i torbieli);
          </div>
        </div>
  
        <!-- HEMISEKCJĘ -->
        <div class="procedure-row">
          <div class="procedure-name">HEMISEKCJĘ</div>
          <div class="procedure-desc">
            • zabieg przeprowadzany na zębach wielokorzeniowych, który polega
              na usunięciu jednego lub więcej korzeni, z zachowaniem pozostałych;
          </div>
        </div>
  
        <!-- LECZENIE POWIKŁANYCH ROPNI -->
        <div class="procedure-row">
          <div class="procedure-name">LECZENIE POWIKŁANYCH ROPNI</div>
          <div class="procedure-desc">
            • polega na zarządzaniu i leczeniu ropni, które powstają w wyniku zakażeń
              bakteryjnych, często w obrębie tkanek miękkich jamy ustnej,
              takich jak dziąsła, korzenie zębów czy kości szczęki;
          </div>
        </div>
  
        <!-- AUGMENTACJA KOŚCI -->
        <div class="procedure-row">
          <div class="procedure-name">AUGMENTACJA KOŚCI</div>
          <div class="procedure-desc">
            • (sterowana regeneracja kostna) – zabieg, którego celem jest odbudowanie tkanki
              kostnej, w sytuacji kiedy doszło do jej zaniku (więcej...).
              Stosujemy wówczas wysokiej jakości bio-materiał, który uzupełnia i odbudowuje
              niszczǫce kość;
          </div>
        </div>
      </div>
  
      
    </section>
    <div class="missing-service">
        JEŚLI NIE ZNALAZŁEŚ POSZUKIWANEJ USŁUGI, <br />
        ZAPYTAJ NAS – CHĘTNIE POMOŻEMY!
      </div>
  </template>
  
  <script>
  export default {
    name: 'ChirurgiePage'
  }
  </script>
  
  <style scoped>
  .chirurgie-section {
    background-color: #15253F;
    color: #fff;
    padding-left: 350px; /* Ajuste si besoin */
    padding-right: 80px; /* Pour respirer à droite également, si besoin */
    padding-top: 60px;
    padding-bottom: 60px;
    font-family: 'Figtree', sans-serif;
  }
  
  .section-title {
    font-family: 'Aboreto', cursive;
    font-size: 40px;
    line-height: 40px;
    color: #BC9667;
    margin-bottom: 64px;
    font-weight: 400;
    text-transform: uppercase;
  }
  
  /* Liste de procédures */
  .procedure-list {
    display: flex;
    flex-direction: column;
  }
  
  /* Chaque ligne : nom + description */
  .procedure-row {
    display: grid;
    grid-template-columns: 300px 1fr;
    align-items: center;
    gap: 182px;
    padding: 20px 0;
    border-top: 1px solid #fff;
  }
  .procedure-row:first-child {
    border-top: none; /* Enlève la ligne sur la 1ère */
  }
  
  .procedure-name {
    font-family: 'Aboreto', cursive;
    font-size: 40px;
    line-height: 60px;
    width: 425px;
    color: #fff;
    text-transform: uppercase;
    font-weight: 400;
  }
  
  .procedure-desc {
    font-family: 'Gotu', sans-serif;
    font-size: 17px;
    line-height: 24px;
    color: #fff;
  }
  
  /* BLOC "JEŚLI NIE ZNALAZŁEŚ USŁUGI..." */
  .missing-service {
    font-family: 'Aboreto', cursive; 
    font-weight: 400;
    font-size: 76px;    
    line-height: 92px;  
    letter-spacing: -2px; 
    color: #BC9667;
    margin: 90px 0px 90px 100px;  
    text-transform: uppercase; 
  }
  </style>
  