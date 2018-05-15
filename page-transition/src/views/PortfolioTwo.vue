<template>
  <div class="two main-content">
    <div class="left-content slideUp">
      <router-link to="/portfolio/one"><img src="../assets/arrow-up.svg" class="arrow arrow-up"></router-link>

      <h1>MOBILE UI</h1>
      <p>Since software is intangible, the only way a user can control or interact with it is through a designed user interface. A well-designed user interface creates a user experience that the designer intended and/or a user experience that the user appreciates.</p>

      <router-link to="/portfolio/three"><img src="../assets/arrow-down.svg" class="arrow arrow-down"></router-link>
    </div>

    <div class="right-content img2">
    </div>
  </div>
</template>

<script>

export default {
  name: 'two',
}
</script>

<style lang="scss" scoped>
  
  $page_color: #48b886;

  h1 {
    color: $page_color !important;
  }

  .img2 {
    background: url('../assets/mobileui.jpg');
    background-size: cover;
    background-position: 50%;

    img {
      width: 70%;
    }

  }


</style>