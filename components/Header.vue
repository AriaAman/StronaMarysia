<template>
  <div class="header">
    <NuxtLink to="/" class="logo">
      <img src="/static/logoPiotr.svg" alt="Logo" />
    </NuxtLink>

    <nav class="nav-links">
      <NuxtLink to="/">Home</NuxtLink>
      <NuxtLink to="/uslugi">Usługi</NuxtLink>
      <NuxtLink to="/technologie">Technologie</NuxtLink>
      <NuxtLink to="/cennik">Cennik</NuxtLink>
      <NuxtLink to="/kontakt">Kontakt</NuxtLink>
    </nav>

    <div class="nav-phone">
      <a href="tel:+48503529023">+48 503 529 023</a>
    </div>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Aboreto&family=Inter:wght@100;300;400;600;700;900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Aboreto&family=Figtree:ital,wght@0,300..900;1,300..900&family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Aboreto&family=Figtree:ital,wght@0,300..900;1,300..900&family=Gotu&family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap');

.header {
  background-color: #15253F;
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 178px;
  padding: 0 60px;
  box-sizing: border-box;
}

.logo img {
  width: 266px;
  height: 38px;
}

.nav-links {
  display: flex;
}

.nav-links a {
  text-decoration: inherit;
  color: #fff;
  font-family: 'Figtree', cursive;
  font-size: 19px;
  line-height: 20px;
  font-weight: 400;
  padding: 25px;
  position: relative;
}

.nav-links a:hover {
  text-decoration: underline;
}

/* ----- Téléphone ----- */
.nav-phone a {
  color: #BC9667;
  text-decoration: underline;
  text-underline-offset: 5px;
  font-family: 'Inter', cursive;
  font-size: 19px;
  line-height: 20px;
  font-weight: 400;
}
</style>
