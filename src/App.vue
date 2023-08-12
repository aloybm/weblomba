<template>
  <div id="app" class="relative">
    <NavBar />
    <main>
      <div class="flex">
        <section
          id="section"
          class="relative mb-8 mt-20 ml-20  xl:left-[800px] xl:top-60 "
        >
          <h1
            class=" font-normal font-beranda w-auto xl:w-[410px] h-auto xl:h-[120px]  text-black text-5xl g:text-6xl  leading-[60px]"
          >
            Lorem Ipsum dolor Sit amet
          </h1>
          <p
            class="text-black text-lg md:text-xl mt-4 md:mt-6 text-justify w-auto xl:w-[477px] font-medium"
          >
            Lorem ipsum dolor sit amet consectetur adipiscing elit Ut et massa
            mi. Aliquam in hendrerit urna. Pellentesque sit amet sapien.
          </p>
          <button
            class="bg-[#EED4B5] hover:bg-orange-200 text-white py-2 px-4 rounded-full text-xl mt-12 xl:w-[254px] xl:h-[64px] xl:text-[36px]"
          >
            Daftar
          </button>
        </section>
      </div>
      <div class="flex">
      <section id="apa" class="relative mb-8  ml-5 xl:top-96">
        <div class="flex">
        <h1 class="vertical-text font-bold w-2 text-5xl xl:text-[108px] leading-[103px]">APA</h1>
        <h1 class="vertical-text font-bold w-2 text-5xl xl:text-[108px] leading-[103px] mt-40 ">ITU ?</h1>
          <div class="ml-32 mt-10 p-10">
          <h1
            class=" relativefont-normal font-beranda w-auto xl:w-[353px] h-auto xl:h-[168px]  text-black text-5xl g:text-6xl  leading-[60px]"
          >
            Lorem Ipsum dolor Sit amet
          </h1>
          <p
            class="text-black text-lg md:text-xl mt-4 md:mt-6 text-justify w-auto xl:w-[317px] xl:h-[229px] font-medium"
          >
            Lorem ipsum dolor sit amet consectetur adipiscing elit Ut et massa
            mi. Aliquam in hendrerit urna. Pellentesque sit amet sapien.
          </p>
          </div>
        </div>
        <div>
          
        </div>
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
.vertical-text {
           margin-left: 100px;
           text-align: center;
           width: 0px;
           word-break: break-all;
           white-space: pre-wrap;
           /* color: (248, 186, 113, 0.55) */
           color : #F8BA71
}
</style>
