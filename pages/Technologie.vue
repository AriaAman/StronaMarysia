<template>
  <section class="technologie-section">
    <div class="header-block">
      <div class="title-left">
        <h1 class="main-title">
          Wyróznia nas<br />
          <span>innowacyjne wyposażenie</span>
        </h1>
      </div>
      <div class="intro-right">
        <p>
          wyróżnia nas zaawansowane wyposażenie, które pozwala nam zapewnić najwyższy standard opieki, gwarantuje
          precyzyjność diagnostyki i skuteczność leczenia, a także zwiększa komfort naszych pacjentów. Nasza inwestycja
          w sprzęt przekłada się na doskonałe wyniki i satysfakcję każdego pacjenta.
        </p>
      </div>
    </div>
    <Machine1 />
    <Machine2 />
    <Machine3 />


  </section>
  <div class="technologie-section-bg-white">
    <Machine4 />
    <Machine5 />
    <Machine6 />
  </div>

  <div class="technologie-section">
    <Machine7 />
    <Machine8 />
    <Machine9 />
    <Machine10 />
  </div>


</template>

<style scoped>
.technologie-section-bg-white {
  background-color: #fff;
  padding: 0px 60px;

}

.technologie-section {
  background-color: #15253F;
  color: #fff;
  padding: 60px 60px;
  min-height: 100vh;
  font-family: 'Figtree', sans-serif;
}

/* En‑tête : "KOSZTY LECZENIA" et paragraphe explicatif */
.header-block {
  display: flex;
  gap: 335px;
  height: 454px;
  margin-bottom: 64px;
  justify-content: space-between;
}

.main-title {
  font-family: 'Aboreto';
  font-size: 112px;
  line-height: 130px;
  margin: 0;
  font-weight: 400;
  width: 885px;
  height: 390px;
  color: #BC9667;
}

.main-title span {
  display: block;
  color: #fff;
}

.intro-right {
  height: 342px;
  width: 576px;
  font-family: 'Gotu', sans-serif;
  font-weight: 400;
  font-size: 24px;
  line-height: 38px;
  color: #fff;
  margin: 0;
  text-transform: uppercase;
}
</style>


<script>
import Machine1 from '~/components/Technologie/Machine1.vue';
import Machine2 from '~/components/Technologie/Machine2.vue';
import Machine3 from '~/components/Technologie/Machine3.vue';
import Machine4 from '~/components/Technologie/Machine4.vue';
import Machine5 from '~/components/Technologie/Machine5.vue';
import Machine6 from '~/components/Technologie/Machine6.vue';
import Machine7 from '~/components/Technologie/Machine7.vue';
import Machine8 from '~/components/Technologie/Machine8.vue';
import Machine9 from '~/components/Technologie/Machine9.vue';
import Machine10 from '~/components/Technologie/Machine10.vue';

export default {
  name: 'TechnologiePage',
  components: {
    Machine1,
    Machine2,
    Machine3,
    Machine4,
    Machine5,
    Machine6,
    Machine7,
    Machine8,
    Machine9,
    Machine10,
  },
};
</script>