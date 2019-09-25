<template>
  <nav>
    <a href="#">LOGO</a>
    <div>
      <a href="#">About Me</a>
      <a href="#">Projects</a>
      <a href="#">Contact</a>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
  nav {
    background: #EAEAEA;
    display: flex;
    justify-content: space-between;
    /* border-top: solid 10px #dd8b87;*/
  }
  nav a, nav a > * {
    color: darkgray;
    text-decoration: none;
    padding: 2em;
    transition: color 2s ease, background-color 2s ease;
  }

  nav a:hover, nav a:hover > * {
    color: #73c448;
    background-color: #D5EDC8;
  }

  nav div {
    display: flex;
  }
</style>
