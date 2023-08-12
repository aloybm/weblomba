<template>
  <div id="app" class="relative">
    <NavBar />
    <main>
      <section id="#beranda">
        <div class="xl:pl-36 container mx-auto flex px-5 py-24 md:flex-row flex-col items-center xl:pr-28">
            <div class=" lg:w-1/3 md:w-1/2 w-5/6 mb-10 md:mb-0">
              <img   src="../public/gambar1.png">
            </div>
          <div class="lg:flex-grow md:w-1/2 lg:pl-40 md:pl-16 flex flex-col md:items-start md:text-left items-center text-center ">       
            <h1 class="font-normal font-beranda w-auto  text-black text-3xl sm:text-5xl">Lorem Ipsum dolor Sit amet</h1>
            <p class="text-black text-lg sm:text-xl w-auto mt-4 md:mt-6 text-justify  leading-relaxed  font-medium">
              Lorem ipsum dolor sit amet consectetur adipiscing elit Ut et massa mi. Aliquam in hendrerit urna. Pellentesque sit amet sapien.
            </p>
            <div class="flex justify-center">
              <button class="bg-[#EED4B5] hover:bg-orange-200 text-white py-2 px-4 rounded-full text-xl mt-12 xl:w-[254px] xl:h-[64px] xl:text-[36px]">Daftar</button>
            </div>
          </div>
        </div>
      </section>
    <section id="pendaftaran" class="">
      <div class=" container mx-auto flex px-5 py-24 md:flex-row flex-col items-center justify-center">
      <div class="flex flex-row">
        <div class="lg:flex-row flex flex-col leading-none lg:text-8xl text-7xl">
          <h1 class="vertical-text font-bold">APA</h1>
          <h1 class="vertical-text  font-bold mt-20 xl:mt-28 pl-auto xl:pl-20">ITU ?</h1>
        </div>
        <div class="xl:ml-40 ml-10 flex  flex-col md:items-start md:text-left items-center text-center justify-center  ">
          <h1 class="font-normal font-b w-auto xl:w-[353px] h-auto xl:h-[168px] text-black text-5xl leading-[60px] g:text-6xl ">Lorem Ipsum dolor Sit amet</h1>
          <p class="text-black text-lg md:text-xl mt-4 md:mt-6 text-justify w-auto xl:w-80 xl:h-46 font-medium">
            Lorem ipsum dolor sit amet consectetur adipiscing elit Ut et massa mi. Aliquam in hendrerit urna. Pellentesque sit amet sapien.
          </p>
        </div>
        <div class="flex flex-col pl-7 ">
          <div class="flex ">
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
      </div>
      </section>
    
    <div class="flex">
      <section id="pembekalan" class="flex">
        <h1>
    
        </h1>
      </section>
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