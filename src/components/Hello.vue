<template>
  <div class="hero">
    <div>
      <h1 class="display-3 title">For the creators.</h1>
      <b-form-input class="my-3" v-model="text" placeholder="Enter your email address"></b-form-input>
      <b-button>Register your interest</b-button>

    </div>
  </div>
</template>

<style>
  .hero {
    height: 90vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    background-image: url("https://www.itvscience.com/wp-content/uploads/2016/07/Cortex.jpg");
    background-size: 100vw 80vh;
    filter: grayscale(10%);
    background-repeat: no-repeat;
  }
  .hero .lead {
    font-weight: 200;
    font-size: 1.5rem;
  }
  .title {
    color: white;
  }
</style>

<script>
  export default {
    data () {
      return {
        text: ''
      }
    }
  }
</script>