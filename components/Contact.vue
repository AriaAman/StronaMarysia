<template>
  <div class="container">
    <div class="top-bar">
      <div class="phone-number">
        <a href="tel:+48503529023">+48 503 529 023</a>
      </div>
      <div class="social-links">
        <a class="link" href="#" target="_blank">facebook</a>
        <a class="link" href="#" target="_blank">instagram</a>
        <a class="link" href="#" target="_blank">znanylekarz</a>
      </div>
    </div>

    <div class="content">
      <div class="top-content">
        <p class="heading">
          <span>NAPISZ</span><br />
          DO NAS
        </p>
        <div class="info-block">
          <p class="intro-text">
            CHCESZ SIĘ Z NAMI SKONTAKTOWAĆ? <br />
            MASZ PYTANIA? CHCESZ UMÓWIĆ WIZYTĘ?<br />
            WYPEŁNIJ PONIŻSZY FORMULARZ, A MY<br />
            SKONTAKTUJEMY SIĘ Z TOBĄ TAK SZYBKO,<br />
            JAK TO MOŻLIWE.
          </p>
          <div class="logo">
            <img src="/static/logoStomatologia.svg" alt="Logo" />
          </div>
        </div>
      </div>
      <div class="bottom-content">
          <form class="contact-form" @submit.prevent="submitForm">

            <input placeholder="Imię i Nazwisko" type="text" id="name" v-model="name" />

            <input placeholder="Email" type="email" id="email" v-model="email" />

            <input placeholder="Nr telefonu" type="text" id="phone" v-model="phone" />

            <textarea placeholder="Powód wizyty | Opisz problem" id="message" v-model="message" rows="4"></textarea>

            <div class="checkbox-container">
              <div class="checkbox-text">
                <input class="checkbox" type="checkbox" id="text-checkbox" v-model="acceptPolicy" />
                <label for="text-checkbox">
                  Wyrażam zgodę na przetwarzanie danych osobowych przez "Pietruszczak STOMATOLOGIA" 
                  w celu przesyłania treści marketingowych na mój adres e-mail podany powyżej w formularzu kontaktowym. 
                  W przeciwnym razie prosimy o kontakt telefoniczny
                </label>
              </div>
              <button type="submit" class="send-btn">Wyślij</button>
            </div>

            
          </form> 
      </div>
      
    </div>
  </div>
</template>

<script setup>
import { ref } from 'vue'

const name = ref('')
const email = ref('')
const phone = ref('')
const message = ref('')
const acceptPolicy = ref(false)

function submitForm() {
  alert(`Formulaire envoyé !\nName: ${name.value}`)
}
</script>

<style scoped>
.container{
  padding: 0 60px;
}
.social-links {
  gap: 32px;
  display: flex;
}

.top-bar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 74px;
  margin-top: 77px;
  margin-bottom: 99px;
}

.link {
  text-decoration: underline 2px;
  text-underline-offset: 8px;
  font-size: 28px;
  font-family: 'Inter', cursive;
  font-weight: 400;
  margin-left: 1rem;
  color: #15253F;
}

.phone-number a {
  color: #15253F;
  text-decoration: underline 2px;
  text-underline-offset: 8px;
  font-weight: 600;
  height: 62px;
  font-size: 52px;
  line-height: 62.4px;
  font-family: 'Figtree', cursive;
}

.content {
  width: 100%;
}

.top-content {
  display: flex;
  width: 100%;
  height: fit-content;
  justify-content: space-between;
  gap: 323px;
}

.bottom-content {
  display: flex;
  width: 100%;
  justify-content: flex-end;
}

.heading {
  color: #15253F;
  font-size: 112px;
  line-height: 130px;
  font-weight: 400;
  font-family: 'Aboreto', cursive;
  margin: 0;
}

.heading span {
  color: #BC9667;
}

.info-block {
  display: flex;
  gap: 113px;
}

.intro-text {
  color: #15253F;
  line-height: 32px;
  font-size: 20px;
  font-family: 'Gotu', cursive;
}

.logo img {
  height: 190px;
  width: 183px;
}

.contact-form {
  display: flex;
  flex-direction: column;
  gap: 40px;
  width: 733px;
}

.contact-form input {
  border: none;
  border-bottom: 1px solid #15253F;
  padding-bottom: 12px;
}

.contact-form input::placeholder {  
  color: #15253F;
  font-family: 'Figtree', cursive;
  font-size: 18px;
  line-height: 28px;
  font-weight: 400;
  margin-bottom: 12px;
}


.contact-form textarea {
  border: none;
  border-bottom: 1px solid #15253F;
  resize: none;
  height: 97px;
}

.contact-form textarea::placeholder {  
  color: #15253F;
  font-family: 'Figtree', cursive;
  font-size: 18px;
  line-height: 28px;
  font-weight: 400;
}

.checkbox-container {
  display: flex;
  width: 738px;
  gap: 20px;
  align-items: flex-start;
  padding-top: 40px;
  padding-left: 16px;
}

.checkbox-text {
  display: flex;
  font-family: 'Figtree', cursive;
  width: 419px;
  line-height: 20px;
  font-weight: 400;
  font-size: 14px;
  color: #15253F;
  align-items: flex-start;
}



.send-btn {
  display: flex;
  width: 283px;
  height: 72px;
  padding: 24px 105.5px;
  border-radius: 35px;
  border: 1px solid #0e1f35;
  background-color: transparent;
  cursor: pointer;
  justify-content: center;
  align-items: center;
  font-size: 23px;
  line-height: 24px;
  font-weight: 400;
}

.send-btn:hover {
  background-color: #0e1f35;
  color: #fff;
}
</style>
