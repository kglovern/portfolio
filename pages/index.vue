<template>
<main>
  <Hero />
  <About />
  <Projects />
  <Contact />
</main>
</template>

<script>

import Hero from '../components/Hero';
import Footer from '../components/Footer';
import About from '../components/About';
import Contact from '../components/Contact';
import Projects from '../components/Projects';

export default {
  components: {
    Hero,
    About,
    Contact,
    Projects
  },
  head() {
    return {
      title: 'If I press these buttons in the right order, magic will happen'
    }
  }
}
</script>

<style>
  section {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  .content {
    width: 60%;
  }

  html, body {
    margin: 0;
    min-height: 10vh;
    background: #EAEAEA;
    font-family: 'Roboto', sans-serif;
    font-size: 1.125rem;
    color: #666666;
  }
  p {
    font-size: 1.2em;
    color: #666666;
    margin: 0.8em 0;
  }
  h1, h2, h3, h4, h5, h6 {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    padding: 0;
  }
  .highlight {
    color: #dd8b87;
  }
</style>
