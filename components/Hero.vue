<template>
    <section id="intro">
      <Header />
      <section class="hero">
        <h1>Kevin Glover-Netherton</h1>
        <h2>Software Engineer</h2>
        <h2 class="wave">👋</h2>
      </section>
    </section>
</template>

<script>
import Header from './Header';

export default {
  name: "Hero",
  components: {
    Header
  }
}
</script>

<style scoped>
  #intro {
    min-height: 100vh;
    background: #73c448;
    display: flex;
    flex-direction: column;
  }
  .hero {
    display: flex;
    flex: 1 1 auto;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }
  .hero h1, h2 {
    color: #EAEAEA;
  }

  .hero h1 {
    font-size: 4em;
    margin: 0;
  }
  .wave {
    font-size: 2em;
  }

  .wave:hover {
    animation: wave 1s;
  }
  @keyframes wave {
    0% { transform: rotate(  0.0deg) }
    10% { transform: rotate(-10.0deg) }
    20% { transform: rotate( 12.0deg) }
    30% { transform: rotate(-10.0deg) }
    40% { transform: rotate(  9.0deg) }
    50% { transform: rotate(  0.0deg) }
    100% { transform: rotate(  0.0deg) }
  }

</style>
