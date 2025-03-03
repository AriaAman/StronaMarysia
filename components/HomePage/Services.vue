<template>
  <section class="services-section">
    <!-- Colonne de gauche : Titre / Sous-titre / Paragraphe(s) -->
    <div class="left-column">
      <h2 class="big-title">
        ZAKRES<br />
        <span>USŁUG</span>
      </h2>
      <h3 class="sub-title">KOMPLEKSOWA OPIEKA</h3>
      <p class="info-text">
        W naszym gabinecie stomatologicznym w Olsztynie zapewniamy kompleksową opiekę
        dostosowaną do różnych potrzeb pacjentów. Specjalizujemy się w nowoczesnej implantologii
        dentystycznej, oferując precyzyjne odbudowy zębów, które przywracają pełną funkcję i
        estetykę. Wykonany przez nas zabieg leczenia kanałowego skutecznie zapobiega ekstrakcji zębów,
        łagodząc ból i przywracając ich pełną funkcję.
      </p>
      <p class="info-text">
        Oferujemy również stomatologię estetyczną, która obejmuje wybielanie zębów oraz zakładanie licówek,
        aby poprawić ich wygląd i zapewnić piękny uśmiech. Nasze usługi protetyczne obejmują korony, mosty
        i protezy, które odbudowują braki zębowe i przywracają komfort życia. Dbamy również o profilaktykę
        i diagnostykę, korzystając z nowoczesnych technologii.
      </p>
    </div>

    <!-- Colonne de droite : liste de services -->
    <div class="right-column">
      <div class="services-list">
        <div class="service-row" v-for="(service, index) in services" :key="index">
          <div class="service-info">
            <h4 class="service-name">{{ service.name }}</h4>
            <p class="service-desc">{{ service.description }}</p>
            <div class="service-arrow">
              <!-- Icône de flèche → -->
              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="#BC9667" class="bi bi-arrow-right"
                viewBox="0 0 16 16">
                <path fill-rule="evenodd"
                  d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8" />
              </svg>
            </div>
          </div>
        </div>
      </div>

      <!-- Bouton "Więcej o usługach" -->
      <button class="more-services-btn" @click="onMoreServices">
        Więcej o usługach
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="#BC9667" class="bi bi-arrow-right"
          viewBox="0 0 16 16">
          <path fill-rule="evenodd"
            d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8" />
        </svg>
      </button>
    </div>
  </section>
</template>

<script setup>
import { ref } from 'vue'

const services = ref([
  {
    name: 'Implantologia dentystyczna',
    description: 'Metoda odbudowy braków zębowych za pomocą nowoczesnych implantów, które przywracają funkcję i estetykę uzębienia.'
  },
  {
    name: 'Leczenie kanałowe (endodoncja)',
    description: 'Polega na usunięciu zainfekowanej tkanki z wnętrza zęba, oczyszczeniu kanałów i ich wypełnieniu, co pozwala na uratowanie zęba przed ekstrakcją.'
  },
  {
    name: 'Protetyka',
    description: 'Zajmuje się odbudową braków zębowych przy użyciu koron, mostów i protez, przywracając pełną funkcję i estetykę uzębienia.'
  },
  {
    name: 'Stomatologia estetyczna',
    description: 'Poprawia wygląd zębów poprzez wybielanie, licówki i korektę uśmiechu.'
  },
  {
    name: 'Stomatologia zachowawcza',
    description: 'Koncentruje się na leczeniu próchnicy, wypełnieniach i odbudowie zębów, aby zachować ich zdrowie i funkcję.'
  },
  {
    name: 'Diagnostyka',
    description: 'Polegają na ocenie stanu zdrowia jamy ustnej za pomocą badań klinicznych i obrazowych, umożliwiając wczesne wykrywanie i planowanie leczenia problemów zębów i dziąseł.'
  },
  {
    name: 'Profilaktyka',
    description: 'Obejmuje regularne wizyty kontrolne, higienę jamy ustnej oraz zabiegi, takie jak fluoryzacja i usuwanie kamienia nazębnego, mające na celu zapobieganie chorobom zębów i dziąseł.'
  },
  {
    name: 'Chirurgia stomatologiczna',
    description: 'Polegają na ocenie stanu zdrowia jamy ustnej za pomocą badań klinicznych i obrazowych, umożliwiając wczesne wykrywanie i planowanie leczenia problemów zębów i dziąseł.'
  }
])

function onMoreServices() {
  navigateTo('/uslugi')
}
</script>

<style scoped>
.services-section {
  background-color: #15253F;
  color: #fff;
  padding: 60px 0px;
  font-family: 'Figtree';
  display: flex;
  gap: 475px;
  min-height: 100vh;
}

/* Colonne de gauche : grands titres & paragraphes */
.left-column {
  display: flex;
  flex-direction: column;
  gap: 24px;
  width: 435px;
  height: 976px;
}

.big-title {
  font-family: 'Aboreto';
  font-size: 112px;
  line-height: 132px;
  margin: 0;
  font-weight: 400;
  color: #BC9667;
}

.big-title span {
  color: #fff;
}

.sub-title {
  font-family: 'Aboreto';
  font-size: 40px;
  line-height: 56px;
  padding-bottom: 32px;
  margin: 0;
  font-weight: 400;
  color: #fff;
}

.info-text {
  font-family: 'Figtree';
  font-size: 18px;
  line-height: 28px;
  font-weight: 400;
  margin: 0;
}

.left-column p {
  font-family: 'Gotu', sans-serif;
  font-size: 18px;
  line-height: 28px;
  margin: 0;
}

/* Colonne de droite : liste de services & bouton */
.right-column {
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
}

/* La liste de services */
.services-list {
  display: flex;
  flex-direction: column;
  width: 890px;
}

.service-row {
  align-items: center;
  padding: 24px 0;
  border-top: 1px solid #fff;
}

.service-info {
  display: flex;
  flex-direction: row;
  padding-right: 20px;
  align-items: center;
  justify-content: space-between;
}

.service-name {
  font-family: 'Figtree';
  font-size: 20px;
  color: #fff;
  margin: 0;
  line-height: 24px;
  font-weight: 400;
  width: 283px;
}

.service-desc {
  font-family: 'Figtree';
  font-size: 16px;
  line-height: 24px;
  color: #fff;
  font-weight: 200;
  margin: 0;
  width: 435px;
}

/* Bouton "Więcej o usługach" */
.more-services-btn {
  align-self: flex-end;
  margin-top: 64px;
  padding: 24px 64px;
  background-color: transparent;
  border: 1px solid #fff;
  color: #fff;
  font-family: 'Inter';
  font-weight: 400;
  font-size: 23px;
  line-height: 24px;
  display: inline-flex;
  gap: 8px;
  width: 587px;
  border-radius: 100px;
  cursor: pointer;
  gap: 24px;
  justify-content: center;
  align-items: center;
}

.more-services-btn:hover {
  background-color: #fff;
  color: #15253F;
}
</style>