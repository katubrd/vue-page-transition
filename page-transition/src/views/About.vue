<template>
  <div class="about main-content">
    <div class="left-content">
      <h1>About me</h1>
      <p class="subtxt">I design, code, and painting.</p>

      <button><router-link to="/portfolio/one">Look at my work</router-link></button>
    </div>
    <div class="right-content">
      <p>Getting outside is good for the soul. Through my artwork, I try to bring the outside in. While I make no attempt to portray actual plants or animals, I do want my creations to look like they could have lived or grown somewhere. Living with beautiful objects that pay tribute to the natural world reminds us to slow down and helps us reconnect with nature.</p>
      <p>Celebrate the human, the marks people make on the world. Treasure the local, the small-scale, the eccentric, the ordinary: whatever is made out of caring. Respect what people have built for themselves. Find the beauty in some battered old porch or cluttered, human-scale storefront, while it still stands.</p>
    </div>

  </div>
</template>

<style lang="scss" scoped>

  .left-content {
    background-color: #ffe476;
  }

  .right-content {
    background: #fff;
    padding: 50px;
    margin-top: 80px;
    display: block;
  }

  button {
    font-size: 1.5em;
    margin-top: 100px;
  }

  .subtxt {
    font-size: 1.5em;
    margin-top: 30px;
  }

</style>
