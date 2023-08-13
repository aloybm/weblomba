<template>
  <img src="../src/assets/start2.svg" class="absolute z-0 w-full" alt="">
  <div id="app" class="relative">
    <div class="z-10">
      <NavBar />
      <main>
        <section id="beranda">
          <Beranda />
        </section>
        <section id="apa-itu" class="">
          <Apaitu />
        </section>
        <section id="pendaftaran">
          <Pendaftaran />
        </section>
        <section id="peraturan">
          <Peraturan />
        </section>
        <section id="klasemn">
          <Klasmen />
        </section>
      </main>
    </div>
  </div>
  <img src="../src/assets/end.svg" class="w-full" alt="">
</template>

<script>
import NavBar from "./components/NavBar.vue";
import Pendaftaran from './components/pendaftaran.vue';
import Peraturan from './components/peraturan.vue'
import Klasmen from './components/klasmen.vue'
import Apaitu from './components/apaitu.vue'
import Beranda from './components/beranda.vue'

export default {
  components: {
    NavBar,
    Pendaftaran,
    Peraturan,
    Klasmen,
    Apaitu,
    Beranda
  },
};
</script>

<style>
body {
  font-family: 'Montserrat';
}
.font-beranda {
  font-family: 'Baloo Bhai';
}
.vertical-text {
    width: 50px;
    font-weight: bold;
    word-wrap: break-word;
    text-align: center;
    color: #F8BA71;
}
.font-b {
  font-family: 'Baloo';
}
.font-number {
  font-family: 'Titan One';
}
</style>