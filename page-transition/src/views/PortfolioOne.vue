<template>
  <div class="home main-content">
    <div class="left-content slideUp">
      <h1>PAINT</h1>
      <p>The fluid space of memory, influenced by time, place and experience forms the foundation of content for my paintings and works on paper.</p>

      <router-link to="/portfolio/two"><img src="../assets/arrow-down.svg" class="arrow arrow-down"></router-link>
    </div>

    <div class="right-content img2">
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'one',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss" scoped>
  
  $page_color: #625B7E;

  h1 {
    color: $page_color !important;
  }

  .img2 {
    background: url('../assets/painting.jpg');
    background-size: cover;
    background-pozition: 50%;

    img {
      width: 70%;
    }

  }
</style>