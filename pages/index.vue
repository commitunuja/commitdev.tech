<template>
  <div class="container">
    <div>
      <img src="~/assets/logo.png" alt="" class="image-1">
      <h1 class="title">
        <b class="commit-c">#CommIT</b> Developers
      </h1>
      <h2 class="subtitle">
        A developer community based on <span class="highlight-text">Probolinggo</span>
      </h2>
      <div class="links">
        <a
          href="https://twitter.com/commit_dev"
          target="_blank"
          class="button--green"
        >
          Twitter
        </a>
        <a
          href="https://github.com/commitunuja"
          target="_blank"
          class="button--grey"
        >
          GitHub
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
/* 
.image-1{
  width: 400px;
} */

.highlight-text{
  font-weight: 500;
  background-image: linear-gradient(98deg,#ecc02d,#ecc02d,#ecc02d);
    border-radius: 35% 35% 67% 30%;
}

.commit-c{
  background: linear-gradient( to bottom,transparent 35%,#ecc02d 35%,#ecc02d 75%,transparent 75% );
}

body{
  background-color: rgb(49,50,78);
}

.container {
  
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #000000;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #000000;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
