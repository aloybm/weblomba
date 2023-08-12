<template>
  <div id="app" class="relative">
    <NavBar />
    <main>
    <div class="flex">
      <section id="beranda" class="relative mb-8 mt-20 ml-20 xl:left-[800px] xl:top-60">
      <h1 class=" font-normal font-beranda w-auto xl:w-[410px] h-auto xl:h-[120px] text-black text-5xl g:text-6xl leading-[60px]">Lorem Ipsum dolor Sit amet</h1>
      <p class="text-black text-lg md:text-xl mt-4 md:mt-6 text-justify w-auto xl:w-[477px] font-medium">
        Lorem ipsum dolor sit amet consectetur adipiscing elit Ut et massa mi. Aliquam in hendrerit urna. Pellentesque sit amet sapien.
      </p>
      <button class="bg-[#EED4B5] hover:bg-orange-200 text-white py-2 px-4 rounded-full text-xl mt-12 xl:w-[254px] xl:h-[64px] xl:text-[36px]">Daftar</button>
      </section>
    </div>
    <div class="flex">
      <section id="pendaftaran" class="relative mb-8 ml-5 xl:top-96">
      <div class="flex">
        <div class="flex flex-row p-12 pl-5">
          <h1 class="vertical-text font-bold leading-[103px] ">APA</h1>
          <h1 class="vertical-text font-bold mt-28 leading-[103px] pl-20 ">ITU ?</h1>
        </div>
        <div class="ml-32 mt-10 p-10 pl-0">
          <h1 class=" relative font-normal font-b w-auto xl:w-[353px] h-auto xl:h-[168px] text-black text-5xl leading-[60px] g:text-6xl ">Lorem Ipsum dolor Sit amet</h1>
          <p class="text-black text-lg md:text-xl mt-4 md:mt-6 text-justify w-auto xl:w-[317px] xl:h-[229px] font-medium">
            Lorem ipsum dolor sit amet consectetur adipiscing elit Ut et massa mi. Aliquam in hendrerit urna. Pellentesque sit amet sapien.
          </p>
        </div>
        <div class="flex flex-col pl-7">
          <div class="flex">
            <p class="font-number font-normal text-6xl xl:ml-20 xl:mt-20 text-[#EED4B5]">1</p>
            <div class="flex container pl-14 mt-10 p-10 text-2xl leading-[36px] xl:w-[470px] xl:pr-0 mr-0 text-justify">
              <p>
                Lorem ipsum dolor sit amet consectetur adipiscing
              </p>
            </div>
          </div>
          <div class="flex">
            <p class="font-number font-normal text-6xl xl:ml-20 xl:mt-10 text-[#EED4B5]">2</p>
            <div class="flex container pl-12 p-10 text-2xl leading-[36px] xl:w-[470px] xl:pr-0 mr-0 text-justify">
              <p>
                Lorem ipsum dolor sit amet consectetur adipiscing
              </p>
            </div>
          </div>
          <div class="flex ">
            <p class="font-number font-normal text-6xl xl:ml-20 xl:mt-10 text-[#EED4B5]">3</p>
            <div class="flex container pl-12 p-10 text-2xl leading-[36px] xl:w-[470px] xl:pr-0 mr-0 text-justify">
              <p>
                Lorem ipsum dolor sit amet consectetur adipiscing
              </p>
            </div>
          </div>
        </div>
      </div>
      </section>
    </div>
    <div class="flex">
      <section id="pembekalan" class="relative"></section>
    </div>
    </main>
  </div>
</template>
<script>
import NavBar from "./components/NavBar.vue";
//import Pendaftaran from './components/pendaftaran.vue';
export default {
  components: {
    NavBar,
    //Pendaftaran
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
    font-size: 108px;
    word-wrap: break-word;
    color: #F8BA71;
}
.font-b {
  font-family: 'Baloo';
}
.font-number {
  font-family: 'Titan One';
}
</style>