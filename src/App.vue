<template>
  <div id="app" class="relative">
    <NavBar />
    <main>
    <div class="flex">
      <section id="section" class="relative mb-8 mt-20 ml-20  xl:left-[800px] xl:top-60 ">
        <h1 class=" font-normal font-beranda w-auto xl:w-[410px] h-auto xl:h-[120px]  text-black text-5xl g:text-6xl  leading-[60px]">
          Lorem Ipsum dolor Sit amet
        </h1>
        <p class="text-black text-lg md:text-xl mt-4 md:mt-6 text-justify w-auto xl:w-[477px] font-medium">
          Lorem ipsum dolor sit amet consectetur adipiscing elit Ut et massa mi. Aliquam in hendrerit urna. Pellentesque sit amet sapien.
        </p>
        <button class="bg-[#EED4B5] hover:bg-orange-200 text-white py-2 px-4 rounded-full text-xl mt-12 xl:w-[254px] xl:h-[64px] xl:text-[36px]">
          Daftar
        </button>
      </section>
    </div>
    </main>
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";

export default {
  components: {
    NavBar,
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

</style>
