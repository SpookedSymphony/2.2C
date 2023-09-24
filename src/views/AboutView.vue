<script setup>
  import Footer from '../components/Footer.vue'
  import '@/assets/column.css';
</script>

<template>
  <main>
    <div class="row">
      <div class="column">
        <img src='@/assets/man.jpg' alt="man" style="width:200px;height:150px;">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed consequat urna eget tristique. Maecenas sagittis massa id ante dignissim, ac interdum odio pellentesque. Nullam et enim in tortor varius interdum.</p>
      </div>
      <div class="column">
        <img src='@/assets/woman.jpg' alt="woman" style="width:200px;height:150px;">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed consequat urna eget tristique. Maecenas sagittis massa id ante dignissim, ac interdum odio pellentesque. Nullam et enim in tortor varius interdum.</p>



      </div>
    </div>
    <Footer/>
  </main>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
