<template>
  <header class="flex justify-between border-b border-slate-300 px-10 py-8 bg-gray-100">
    <div class="flex items-center gap-4">
      <img src="/icons.svg" alt="icons" class="w-10" />
      <div>
        <h2 class="font-medium text-xl uppercase">Interior</h2>
        <p class="text-slate-400">Услуги по ремонту и отделке квартир</p>
      </div>
    </div>
    // src\components\Header.vue
    <ul class="flex items-center gap-3">
      <li class="flex items-center cursor-pointer gap-3 text-gray-500 hover:text-black">
        <b>Главная</b>
      </li>

      <li class="flex items-center cursor-pointer gap-3 text-gray-500 hover:text-black">
        <b>Услуги</b>
      </li>

      <li class="flex items-center cursor-pointer gap-3 text-gray-500 hover:text-black">
        <b>Профиль</b>
      </li>

      <li class="flex items-center cursor-pointer gap-3 text-gray-500 hover:text-black">
        <b>О компании</b>
      </li>

      <ul class="flex items-center gap-1">
        <li>
          <button class="hover:scale-110 transition duration-200">
            <img src="/insta.png" alt="insta" class="w-5" />
          </button>
        </li>
        <li>
          <button class="hover:scale-110 transition duration-200">
            <img src="/whatsApp.png" alt="whatsApp" class="w-8" />
          </button>
        </li>
        <li>
          <button class="hover:scale-110 transition duration-200">
            <img src="/telegram.png" alt="telegram" class="w-6" />
          </button>
        </li>
      </ul>
    </ul>
  </header>
</template>
