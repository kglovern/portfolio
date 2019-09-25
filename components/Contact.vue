<template>
  <section id="contact">
    <div class="content">
      <h1>Get in touch!</h1>
      <form action="#">
        <input type="text" name="name" placeholder="Your Name"/>
        <input type="text" name="email" placeholder="Your email"/>
        <textarea name="content" id="formbody" cols="30" rows="10" placeholder="What's on your mind?"></textarea>
        <button type="submit">Hit me up</button>
      </form>
    </div>
  </section>
</template>

<script>
export default {
    name: "Contact"
}
</script>

<style scoped>
  #contact {
    background: #666666;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    color: #dd8b87;
  }
  #contact form > * {
    display: flex;
    flex-direction: column;
    width: 50%;
  }
</style>
