<template>
  <div class="hero">
    <div>
      <h1 class="display-3 title">For the creators.</h1>
      <p class="lead title">Harnessing the collective intelligence</p>
      <b-button variant="light">Start exploring</b-button>
      <b-button >Whitepaper</b-button>
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
    background-size: 100vw;
    filter: grayscale(10%)
  }
  .hero .lead {
    font-weight: 200;
    font-size: 1.5rem;
  }
  .title {
    color: white;
  }
</style>
