<template>
  <section class="contact-section">
    <h1 class="section-title">
      SKONTAKTUJ SIĘ <br />
      <span>Z NAMI</span>
    </h1>

    <div class="contact-content">
      <div class="left-column">
        <img src="/static/PhotoCabinetDevant.jpg" alt="Clinique Pietruszczak" class="clinic-image" />
      </div>
      <div class="right-column">
        <img src="/static/PiotrLogoV2.svg" alt="Clinique Pietruszczak" class="clinic-image" />

        <div class="clinic-info">
          <p class="info-title">ADRES:</p>
          <p class="info-text">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="#BC9667" class="bi bi-geo-alt" viewBox="0 0 16 16">
              <path d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A32 32 0 0 1 8 14.58a32 32 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10"/>
              <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4m0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6"/>
            </svg>  
            Jaroty, ul. Stawigudzka 8e<br />
            10-687 Olsztyn
          </p>
        </div>

        <div class="clinic-contact">
          <p class="info-title">DANE KONTAKTOWE:</p>

          <!-- Téléphone -->
          <div class="contact-line">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="#BC9667" class="bi bi-telephone" viewBox="0 0 16 16">
              <path d="M3.654 1.328a.678.678 0 0 0-1.015-.063L1.605 2.3c-.483.484-.661 1.169-.45 1.77a17.6 17.6 0 0 0 4.168 6.608 17.6 17.6 0 0 0 6.608 4.168c.601.211 1.286.033 1.77-.45l1.034-1.034a.678.678 0 0 0-.063-1.015l-2.307-1.794a.68.68 0 0 0-.58-.122l-2.19.547a1.75 1.75 0 0 1-1.657-.459L5.482 8.062a1.75 1.75 0 0 1-.46-1.657l.548-2.19a.68.68 0 0 0-.122-.58zM1.884.511a1.745 1.745 0 0 1 2.612.163L6.29 2.98c.329.423.445.974.315 1.494l-.547 2.19a.68.68 0 0 0 .178.643l2.457 2.457a.68.68 0 0 0 .644.178l2.189-.547a1.75 1.75 0 0 1 1.494.315l2.306 1.794c.829.645.905 1.87.163 2.611l-1.034 1.034c-.74.74-1.846 1.065-2.877.702a18.6 18.6 0 0 1-7.01-4.42 18.6 18.6 0 0 1-4.42-7.009c-.362-1.03-.037-2.137.703-2.877z"/>
            </svg>
            <a href="tel:+48503529023">+48 503 529 023</a>
          </div>

          <!-- E-mail -->
          <div class="contact-line">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="#BC9667" class="bi bi-envelope" viewBox="0 0 16 16">
              <path d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0
               1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0
               1-2-2zm2-1a1 1 0 0 0-1
               1v.217l7 4.2 7-4.2V4a1
               1 0 0 0-1-1zm13
               2.383-4.708 2.825L15
               11.105zm-.034
               6.876-5.64-3.471L8
               9.583l-1.326-.795-5.64
               3.47A1 1 0 0 0 2
               13h12a1 1 0 0 0
               .966-.741M1
               11.105l4.708-2.897L1
               5.383z"/>
            </svg>
            <a href="mailto:kontakt@pietruszczak.pl">kontakt@pietruszczak.pl</a>
          </div>
        </div>
      </div>
    </div>

    <div class="route-section">
      <div class="route-section">
    <div class="route-left">
      <h2 class="route-title">DOJAZD DO GABINETU</h2>

      <p class="info-bus">DOJAZD KOMUNIKACJĄ MIEJSKĄ – AUTOBUSY:</p>
      <p class="info-chemin-text">
        Przystanek „Osiedle Zacisze” Linie: 136, 121
      </p>

      <p class="info-voiture">DOJAZD SAMOCHODEM:</p>
      <p class="info-chemin-text">
        Wjazd od ul. Bartąskiej (naprzeciw ul. Złotej)<br />
        Parkingi dla lokali usługowych – obok „Piekarni Tyrolskiej” oraz sklepu „Żabka”
      </p>

      <NuxtLink href="#" class="route-btn">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-map" viewBox="0 0 16 16">
          <path fill-rule="evenodd" d="M15.817.113A.5.5 0 0 1 16 .5v14a.5.5 0 0 1-.402.49l-5 1a.5.5 0 0 1-.196 0L5.5 15.01l-4.902.98A.5.5 0 0 1 0 15.5v-14a.5.5 0 0 1 .402-.49l5-1a.5.5 0 0 1 .196 0L10.5.99l4.902-.98a.5.5 0 0 1 .415.103M10 1.91l-4-.8v12.98l4 .8zm1 12.98 4-.8V1.11l-4 .8zm-6-.8V1.11l-4 .8v12.98z"/>
        </svg>
        Sprawdź jak do nas dojechać
      </NuxtLink>
    </div>

    <div class="route-map">
      <iframe
        class="map"
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2421.9319286438653!2d20.47464167664591!3d53.72895747177812!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x471e144d96b46a9b%3A0x545a03838388a3b1!2sPietruszczak%20Stomatologia!5e0!3m2!1sen!2spl!4v1708976543210"
        allowfullscreen="false"
        loading="lazy">
      </iframe>
    </div>
  </div>
    </div>
  </section>
</template>

<style scoped>
p {
  margin: 0;
}

.contact-section {
  background-color: #15253F;
  padding: 60px 80px;
  color: #fff;
}

.section-title {
  font-family: 'Aboreto', cursive;
  font-size: 112px;
  line-height: 130px;
  font-weight: 400;
  color: #BC9667;
  margin: 0;
}
.section-title span {
  color: #fff;
}

.contact-content {
  display: flex;
  margin-top: 96px;
  gap: 335px;
}

.left-column .clinic-image {
  width: 733px;
  height: 462px;
  border-radius: 4px;
}

.right-column {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

/* Titre, sous-titre, etc. */
.clinic-info {
  margin-top: 64px;
}

.info-title {
  font-family: 'Gotu', sans-serif;
  font-size: 24px;
  margin: 0;
  padding-bottom: 16px;
}
.info-text {
  font-family: 'Figtree', cursive;
  font-size: 24px;
  color: #BC9667;
  margin: 0;
  padding-bottom: 40px;
}

/* Icônes + Lien sur une même ligne */
.contact-line {
  display: flex;
  align-items: center; 
  text-decoration: underline;
  text-underline-offset: 6px;
  gap: 8px;           
  margin-bottom: 16px;
}

.contact-line a {
  font-family: 'Figtree', sans-serif;
  font-size: 24px;
  color: #BC9667;
  text-decoration: underline; /* Souligne uniquement le texte, pas l’icône */
}

/* Pour la carte et la suite... */
.route-section {
  margin-top: 60px;
  display: flex;
  gap: 50px;
}

/* Conteneur général de la section */
.route-section {
  display: flex;
  gap: 50px;
  margin-top: 60px;
}

/* Colonne texte (à gauche) */
.route-left {
  max-width: 600px;
  color: #fff; /* Supposons un fond sombre derrière */
}

/* Titre de la section */
.route-title {
  font-family: 'Aboreto', cursive;
  font-weight: 400;
  font-size: 40px;     
  line-height: 60px;   
  padding-bottom: 64px;
  color: #fff;         
}

/* Sous-titres comme "DOJAZD KOMUNIKACJĄ..." */
.info-voiture {
  font-family: 'Gotu', cursive;
  font-weight: 400;
  font-size: 24px;
  line-height: 32px;
  padding-bottom: 12px;
  color: #fff;
}

.info-bus {
  font-family: 'Gotu', cursive;
  font-weight: 400;
  font-size: 24px;
  line-height: 32px;
  padding-bottom: 12px;
  color: #fff;
}

.info-chemin-text{
  font-family: 'Gotu';
  font-weight: 400;
  font-size: 24px;
  line-height: 30px;
  color: #BC9667;
  padding-bottom: 40px;
}

/* Bouton "Sprawdź jak do nas dojechać" */
.route-btn {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  margin-top: 96px;
  text-decoration: underline;
  text-underline-offset: 10px;
  color: #fff;
  font-family: 'Figtree';
  font-size: 24px;
}

/* Colonne carte (à droite) */
.route-map {
  height: 620px;
  width: 1189px; 
  display: flex;
  align-items: center;
}

/* Iframe Google Maps */
.map {
  width: 100%;
  height: 100%;
  border: none;
  border-radius: 4px;
}
</style>
