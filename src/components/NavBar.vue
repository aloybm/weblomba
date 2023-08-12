<template>

  <header class="mx-auto pt-[70px]">
    <nav>
      <div class="max-w-screen-xl flex flex-wrap items-center justify-end text-lg mx-auto p-4">
        <div class="flex md:order-2">
          <button data-collapse-toggle="navbar-default" type="button" class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm  md:hidden" aria-controls="navbar-default" aria-expanded="false">
            <span class="sr-only">Open main menu</span>
            <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 17 14">
               <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 1h15M1 7h15M1 13h15"/>
            </svg>
          </button>
        </div>
        <div class="hidden w-full md:block md:w-auto" id="navbar-default">
          <ul class="font-medium flex flex-col p-4 md:p-0  md:flex-row md:space-x-8 md:mt-0 md:border-1 md:bg-white"git>
            <li>
              <a href="#beranda" class="text-black font-medium cursor-pointer border-b-4 border-orange-100 mx-1.5 sm:mx-6">Beranda</a>
            </li>
            <li>
              <a href="#pendaftaran" class="border-b-4 border-transparent text-gray-300 hover:text-black hover:font-mediun cursor-pointer  hover:border-orange-100 mx-1.5 sm:mx-6">Pendaftaran</a>
            </li>
            <li>
              <a href="#peraturan" class="border-b-4 border-transparent text-gray-300 hover:text-black font-medium cursor-pointer  hover:border-orange-100 mx-1.5 sm:mx-6">Peraturan</a>
            </li>
            <li>
               <a href="#klasemen" class="border-b-4 border-transparent text-gray-300 hover:text-black font-medium cursor-pointer  hover:border-orange-100 mx-1.5 sm:mx-6">Klasemen</a>
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
};
</script>