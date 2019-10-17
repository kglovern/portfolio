<template>
    <div class="project">
        <div class="img">
            <img :src="imageURL" alt="Image">
        </div>
        <div class="content">
            <h3>{{title}}</h3>
            <slot></slot>
            <div class="technologies">Built with: {{techs}}</div>
            <a class="githubRef" :href="url">View Source</a>
        </div>

    </div>
</template>

<script>
  export default {
    name: "Project",
    props: {
      title: String,
      description: String,
      url: String,
      imageURL: String,
      techs: String
    }
  }
</script>

<style scoped>
    .project {
        width: 80%;
        background: white;
        opacity: 0.8;
        padding: 2em;
        margin: 1em 0;
        border-radius: 5px;
        box-sizing: border-box;
        display: flex;
        justify-content: space-between;
        align-items: center;
        transition: transform 0.5s;
        -webkit-box-shadow: 7px 10px 5px 0px rgba(0,0,0,0.24);
        -moz-box-shadow: 7px 10px 5px 0px rgba(0,0,0,0.24);
        box-shadow: 7px 10px 5px 0px rgba(0,0,0,0.24);
    }

    .project:hover {
        transform: scale(1.05);
    }

    img {
        border: solid 1px #eeeeee;
    }

    h3 {
        color: #75b9be;
        margin: 0.5em 0;
    }

    .project:nth-child(odd) {
        flex-direction: row-reverse;
    }

    a.githubRef {
        color: #dd8b87;
        text-decoration: none;
    }
    .technologies {
        font-style: italic;
        font-size: 0.8rem;
        margin: 0.5em 0;
    }

</style>
