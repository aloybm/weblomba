<template>
  <div class="relative">
    <img src="../src/assets/start2.svg" class="absolute z-0 w-full" alt="">
    <div id="app" class="relative z-10">
      <div class="">
        <NavBar />
        <main>
          <section id="beranda">
            <Beranda />
          </section>
          <section id="apa-itu">
            <Apaitu />
          </section>
          <section id="penilaian" class="pb-48">
            <Penilaian />
          </section>
          <img src="./assets/lebah.svg" class="absolute z-0 right-1/2" alt="">
          <section id="pendaftaran" class="pt-96">
            <Pendaftaran />
          </section>
          <section id="peraturan">
            <Peraturan />
          </section>
          <section id="kriteria">
            <Kriteria />
          </section>
          <section id="klasmen">
            <Klasmen />
          </section>
          <section id="footer">
            <Footer />
          </section>
        </main>
      </div>
    </div>
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import Pendaftaran from './components/Pendaftaran.vue';
import Peraturan from './components/Peraturan.vue'
import Klasmen from './components/Klasmen.vue'
import Apaitu from './components/Apaitu.vue'
import Beranda from './components/Beranda.vue'
import Footer from './components/Footer.vue'
import Penilaian from './components/penilaian.vue'
import Kriteria from "./components/kriteria.vue"


export default {
  components: {
    NavBar,
    Pendaftaran,
    Peraturan,
    Klasmen,
    Apaitu,
    Beranda,
    Footer,
    Penilaian,
    Kriteria
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
.horizontal-text{
    
    font-weight: bold;
    color: #F8BA71;
}
.font-b {
  font-family: 'Baloo';
}
.font-number {
  font-family: 'Titan One';
}
</style>