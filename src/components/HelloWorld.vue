<script setup>
  defineProps({
    msg: {
      type: String,
      required: true
    },

    msg1: {
      type: String,
      required: true
    }
  })
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h1 class="green">{{ msg1 }}</h1>
    <hr>
    <h3>
      Saya seorang Front End Developer dengan pengetahuan menyeluruh tentang desain dan website. Saya mampu bekerja di
      bawah tekanan, dan juga dapat bekerja secara individual maupun dalam tim. Saya mampu berkomunikasi dengan baik
      dengan rekan tim, dan dapat mengatur waktu.
    </h3>

    <!-- <a target="_blank" href="https://vitejs.dev/">Vite</a> +
      <a target="_blank" href="https://vuejs.org/">Vue 3</a>. -->
  </div>
</template>

<style scoped>
  h1 {
    font-weight: 500;
    font-size: 2.0rem;
    top: -10px;
  }

  h3 {
    font-size: 1.2rem;
  }

  .greetings h1,
  .greetings h3 {
    text-align: center;
  }

  @media (min-width: 1024px) {

    .greetings h1,
    .greetings h3 {
      text-align: left;
    }
  }

  .tentang {
    font-family: 'Open Sans', sans-serif;
  }

  .logo {
    width: auto;
  }
</style>