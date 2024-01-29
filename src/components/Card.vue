<script setup>
defineProps({
  imageUrl: String,
  title: String,
  designer: String,
  foreman: String,
  date: Number
})
</script>

<template>
  <div class="flex">
    <img
      :src="imageUrl"
      alt="studiya1"
      class="w-1/2 mt-7 hover:shadow-xl hover:scale-110 transition duration-200"
    />

    <div class="w-1/2 bg-gray-100 p-20 mt-7">
      <div class="bg-gray-100 text-center">
        <h2 class="text-2xl font-medium mb-2">{{ title }}</h2>
        <p class="text-slate-400 italic mt-4">
          Дизайнер: {{ designer }}
          <br />
          Прораб: {{ foreman }}
          <br />
          Дата реализации: {{ date }}
        </p>

        <button
          class="mt-5 bg-gray-500 text-white px-6 py-3 rounded-full uppercase text-sm tracking-wide font-semibold hover:bg-gray-800 transition"
        >
          Смотреть
        </button>
      </div>
    </div>
  </div>
</template>
