<template>
  <div class="three main-content">
    <div class="left-content slideUp">
      <router-link to="/portfolio/two"><img src="../assets/arrow-up.svg" class="arrow arrow-down"></router-link>

      <h1>BOOK ILLUSTRATION</h1>
      <p>Einstein said, "Imagination is more important than knowledge." Imagination is the door to possibilities. It is where creativity, ingenuity, and thinking outside the box begin for child development. Imaginative and creative play is how children learn about the world.</p>

    </div>

    <div class="right-content img2">
    </div>
  </div>
</template>

<script>
export default {
  name: 'three',
}
</script>

<style lang="scss" scoped>
  
  $page_color: #5487a8;

  h1 {
    color: $page_color !important;
  }

  .img2 {
    background: url('../assets/book.jpg');
    background-size: cover;
    background-position: 50%;

    img {
      width: 70%;
    }

  }</style>