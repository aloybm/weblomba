<template>

  <header class="mx-auto pt-[70px]">
    <nav >
      <div class="hidden lg:flex max-w-screen-xl flex-wrap items-center justify-between mx-auto py-4 px-20">
        
        <img src="../assets/logo.svg" class="self-center left-20" alt="">
            <!-- <div class="flex flex-row mx-auto lg:hidden gap-16">
              <img src="../assets/logo.svg" class="self-center mx-auto left-20" alt="">
              <h1 class="font-beranda text-4xl lg:text-8xl my-auto">MBACA.</h1>
            </div> -->
            <!-- <div class="flex md:order-2 justify-end">
              <button data-collapse-toggle="navbar-default" type="button" class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm  md:hidden" aria-controls="navbar-default" aria-expanded="false">
                <span class="sr-only">Open main menu</span>
                <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 17 14">
                  <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 1h15M1 7h15M1 13h15"/>
                </svg>
              </button>
            </div> -->
        <div class="hidden w-full lg:block md:w-auto" id="navbar-default">
          <ul class="font-medium flex flex-col p-4 md:p-0 md:flex-row md:space-x-5 md:mt-0 md:border-1 md:bg-none">
            <li>
              <a href="#beranda" class="text-black font-medium cursor-pointer border-b-4 border-orange-100 mx-1.5 sm:mx-6">Beranda</a>
            </li>
            <li>
              <a href="#penilaian" class="border-b-4 border-transparent text-white hover:text-black hover:font-mediun cursor-pointer  hover:border-orange-100 mx-1.5 sm:mx-6">Penilaian</a>
            </li>
            <li>
              <a href="#pendaftaran" class="border-b-4 border-transparent text-white hover:text-black hover:font-mediun cursor-pointer  hover:border-orange-100 mx-1.5 sm:mx-6">Pendaftaran</a>
            </li>
            <li>
              <a href="#peraturan" class="border-b-4 border-transparent text-white hover:text-black font-medium cursor-pointer  hover:border-orange-100 mx-1.5 sm:mx-6">Peraturan</a>
            </li>
            <li>
              <a href="#klasmen" class="border-b-4 border-transparent text-white hover:text-black font-medium cursor-pointer  hover:border-orange-100 mx-1.5 sm:mx-6">Klasmen</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="lg:hidden max-w-screen flex flex-wrap items-center justify-between mx-auto py-4 px-20">
        <img src="../assets/logo.svg" class="self-center left-20" alt="">

        <svg xmlns="http://www.w3.org/2000/svg" id="menu-button" class="h-6 w-6 cursor-pointer lg:hidden block" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h16M4 18h16"
          />
        </svg>

        <div class="hidden w-full mx-auto text-right" id="menu">
          <ul class="py-4 px-3 text-base max-w-fit ml-auto bg-[#EF94D6] rounded-xl lg:hidden text-end space-y-4">
            <li class="">
              <a href="#beranda" class="border-b-4 border-transparent text-white hover:text-black hover:font-mediun cursor-pointer  hover:border-orange-100 mx-1.5 sm:mx-6"
                >Beranda</a
              >
            </li>
            <li class="">
              <a href="#penilaian" class="border-b-4 border-transparent text-white hover:text-black hover:font-mediun cursor-pointer  hover:border-orange-100 mx-1.5 sm:mx-6"
                >Penilaian</a
              >
            </li>
            <li class="">
              <a href="#pendaftaran" class="border-b-4 border-transparent text-white hover:text-black hover:font-mediun cursor-pointer  hover:border-orange-100 mx-1.5 sm:mx-6"
                >Pendaftaran</a
              >
            </li>
            <li class="">
              <a href="#peraturan" class="border-b-4 border-transparent text-white hover:text-black hover:font-mediun cursor-pointer  hover:border-orange-100 mx-1.5 sm:mx-6"
                >Peraturan</a
              >
            </li>
            <li class="">
              <a
                href="#klasmen" class="border-b-4 border-transparent text-white hover:text-black hover:font-mediun cursor-pointer  hover:border-orange-100 mx-1.5 sm:mx-6"
                >Klasmen</a
              >
            </li>
          </ul>
        </div>
      </div>
      
    </nav>
  </header>
</template>

<script>
export default {
  name: "NavBar",

  mounted() {
    const button = document.querySelector('#menu-button');
    const menu = document.querySelector('#menu');

    button.addEventListener('click', () => {
      menu.classList.toggle('hidden');
    });
  }
};
</script>