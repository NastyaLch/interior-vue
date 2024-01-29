<script setup>
defineProps({
  title1: String,
  imageUrl1: String,
  foreman1: String,
  date1: Number,
  designer1: String
})
</script>

<template>
  <div class="flex">
    <div class="w-1/2 bg-gray-100 p-20 mt-7">
      <div class="bg-gray-100 text-center">
        <h2 class="text-2xl font-medium mb-2">{{ title1 }}</h2>
        <p class="text-slate-400 italic mt-4">
          Дизайнер: {{ designer1 }}
          <br />
          Прораб: {{ foreman1 }}
          <br />
          Дата реализации: {{ date1 }}
        </p>

        <button
          class="mt-5 bg-gray-500 text-white px-6 py-3 rounded-full uppercase text-sm tracking-wide font-semibold hover:bg-gray-800 transition"
        >
          Смотреть
        </button>
      </div>
    </div>

    <img
      :src="imageUrl1"
      alt="studiya2"
      class="w-1/2 mt-7 hover:shadow-xl hover:scale-110 transition duration-200"
    />
  </div>
</template>
