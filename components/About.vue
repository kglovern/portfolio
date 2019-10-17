<template>
  <section id="about">
    <a href="#about"></a>
    <div class="content">
      <div class="aboutWrapper">
        <div class="aboutMe">
          <h1>About Me</h1>
          <p class="highlight">I love solving problems.</p>
          <p>I love helping others solve problems, too.</p>
          <p>My love of technology led me to attend the University of Guelph, where I'll be graduating with a degree in Software Engineering (December 2019).</p>
          <p>I'm passionate about web technologies and eager to continue to expand my skillset.</p>
          <p>If  I sound like I might be a good  fit for your team, take a look at my projects below or get in touch.  I'm actively looking for an opportunity where I can grow as a developer and I'd love to chat with you!</p>
        </div>
        <div class="skills">
          <h2>Things I've used</h2>
          <ul>
            <li>React</li>
            <li>Vue.js</li>
            <li>Express</li>
            <li>Flask</li>
          </ul>
          <h2>Languages</h2>
          <ul>
            <li>Javascript</li>
            <li>C</li>
            <li>Java</li>
            <li>Python</li>

          </ul>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "About"
}
</script>

<style scoped>
  #about {
    min-height: 100vh;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  #about h1 {
    color: #75b9be;
    font-weight: 400;
  }

  .aboutWrapper {
    width: 100%;
    display: flex;
  }

  .aboutMe {
    width: 70%;
    padding: 0 2em;
    box-sizing: border-box;
  }

  .skills h2 {
    color: #75b9be;
  }
  .skills ul {
    margin-bottom: 1em;
  }
  .skills li {
    list-style-type: none;
  }
  .skills li:before {
    content: "\25CB";
    color: #75b9be;
    font-weight: bold;
    font-size: 1.3em;
    display: inline-block;
    width: 1em;
    margin-left: -1em;
  }

</style>
