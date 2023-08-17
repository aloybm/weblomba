<template>
  <div class="container mx-auto py-24 md:flex-row items-center">
    <div class="flex justify-center items-center text-center">
      <h1 class="font-normal font-beranda w-auto text-black text-3xl sm:text-5xl">Peraturan Lomba</h1>
    </div>
    
    <div class=" container mx-auto flex py-24 md:flex-row flex-col items-center space-x-10">
      <div class="lg:ml-40 lg:flex-row flex flex-col leading-none lg:text-9xl text-7xl">
        <h1 class="vertical-text font-bold">PERA</h1>
        <h1 class="vertical-text font-bold mt-20 xl:mt-40 pl-auto xl:pl-20">TURAN</h1>
      </div>
      <section class="flex items-center justify-center">
      <div class="hidden lg:flex flex-col sm:flex-col p-5 sm:space-x-0 sm:space-y-10 w-1/2">
        <div class="lg:w-10/12 md:w-1/2 w-5/6 mb-10 md:mb-0">
          <img src="../assets/peraturan/1.svg" class="" alt="">
        </div>
        <div class="lg:w-full md:w-1/2 w-5/6 mb-10 md:mb-0 pl-20">
          <img src="../assets/peraturan/2.svg" class="" alt="">
        </div>
        <div class="lg:w-10/12 md:w-1/2 w-5/6 mb-10 md:mb-0">
          <img src="../assets/peraturan/3.svg" class="" alt="">
        </div>
        <div class="lg:w-full md:w-1/2 w-5/6 mb-10 md:mb-0 pl-20">
          <img src="../assets/peraturan/4.svg" class="" alt=""> 
        </div>
        <div class="lg:w-10/12 md:w-1/2 w-5/6 mb-10 md:mb-0">
          <img src="../assets/peraturan/5.svg" class="" alt="">
        </div>
        <div class="lg:w-full md:w-1/2 w-5/6 mb-10 md:mb-0 pl-20">
          <img src="../assets/peraturan/6.svg" class="" alt=""> 
        </div>
      </div>
      <div class="flex flex-col space-y-14 lg:hidden">
        <img src="../assets/peraturan/1.svg" class="" alt="">
        <img src="../assets/peraturan/2.svg" class="" alt="">
        <img src="../assets/peraturan/3.svg" class="" alt="">
        <img src="../assets/peraturan/4.svg" class="" alt="">
        <img src="../assets/peraturan/5.svg" class="" alt="">
        <img src="../assets/peraturan/6.svg" class="" alt="">
      </div>
      </section>
    </div>
  </div>
  <img src="../assets/klasmen.svg" class="absolute right-0" alt="">
</template>

<script>
export default {
  name: "Peraturan",
};
</script>
