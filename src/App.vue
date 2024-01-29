<script setup>
import Header from './components/Header.vue'
import Card from './components/Card.vue'
import Card2 from './components/Card2.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <div class="bg-white w-4/5 m-auto rounded-xl shadow-xl mt-14">
    <Header />

    <div class="p-7">
      <div class="text-center mt-7">
        <h1 class="text-3xl font-medium">Авторский дизайн</h1>
        <p class="text-gray-500 text-shadow">Идеи для интерьера по помещениям:</p>
      </div>
    </div>

    <Card
      date="2024"
      foreman="Александр Иванов"
      designer="Константин Николаев"
      title="Просто и со вкусом"
      imageUrl="/studiya1.jpg"
    />

    <Card2
      date1="2024"
      foreman1="Алексей Гвинеев"
      designer1="Мария Орлова"
      title1="Яркая и просторная однушка"
      imageUrl1="/studiya2.jpg"
    />

    <Card
      date="2023"
      foreman="Александр Иванов"
      designer="Дарья Сергеева"
      title="Современная и стильная евротрешка"
      imageUrl="/studiya3.jpg"
    />

    <Card2
      date1="2023"
      foreman1="Иван Давыдов"
      designer1="Алиса Шмелева"
      title1="Стильная двухкомнатная квартира"
      imageUrl1="/studiya4.jpg"
    />

    <Footer />
  </div>
</template>
