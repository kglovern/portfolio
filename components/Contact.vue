<template>
  <section id="contact">
    <a href="#contact"></a>
    <div class="content">
      <div class="contact">
        <div><a href="mailto:kevin.glovernetherton@gmail.com">kevin.glovernetherton@gmail.com</a></div>
        <div><a href="https://github.com/kglovern">github.com/kglovern</a></div>
        <div><a href="https://www.linkedin.com/in/kglovern/">linkedin.com/in/kglovern</a></div>
      </div>

    </div>
  </section>
</template>

<script>
export default {
    name: "Contact"
}
</script>

<style scoped>
  .cta {
    font-size: 1.6em;
    margin-bottom: 1em;
    color: #dd8b87;
  }
  .contact {
    width: 80%;
    padding: 2em 0;
    box-sizing: border-box;
    font-size: 0.8rem;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
  }
  .contact a{
    text-decoration: none;
    color: #75b9be;
    padding: 1em;
    transition: color 1s ease-in-out;
  }
  .contact a:hover {
    color: #dd8b87;
  }
  #contact {
    background: #666666;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    color: #EAEAEA;
  }
  #contact form > * {
    display: flex;
    flex-direction: column;
    width: 50%;
  }
</style>
