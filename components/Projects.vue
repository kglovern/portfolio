<template>
  <section id="projects">
    <div class="content">
      <h1>Projects</h1>
      <Project title="Attendance System"
                url="https://github.com/kglovern/attendanceMobile"
                techs="Typescript, Express, Kotlin, Anko"
      >
        <ul>
          <li>Mobile app that can track attendance using the University of Guelph student card.</li>
          <li>RESTful Web API written in Typescript accessible through mobile and web interfaces.</li>
          <li>Mobile app written in Kotlin tracks attendance through unique barcodes belonging to each student.</li>
        </ul>
      </Project>
      <Project title="Immediate Feedback System"
               url="https://github.com/ian-james/IFS"
               techs="Javascript, SQL, HTML, Python"
      >
        <ul>
          <li>Allows the running of multiple verification tools against uploaded student code or written english assignments in order to receive feedback about potential errors.</li>
          <li>Express server with AngularJS frontend.  Most tools written in Python.</li>
          <li>Part of an ongoing research project into how first and second year students approach problem solving.</li>
        </ul>
      </Project>
      <Project title="Prokudin-Gorskii Registration"
               url="https://github.com/kglovern/pg_registration"
               techs="Python, Numpy, SciKit"
      >
        <ul>
          <li>Algorithm for the automatic linear registration of the Prokudin-Gorskii image set.</li>
          <li>Results in colour photos with a very high SSIM rating to the original panes.</li>
        </ul>
      </Project>
      <Project title="GEDCOM Parser"
               url="https://github.com/kglovern/GEDCOM-system"
               techs="C, Javascript, JQuery, SQL, HTML"
      >
        <ul>
          <li>Web interface allowing the parsing of the GEDCOM genealogical format.</li>
          <li>Parser written in C.</li>
          <li>Client provided through Express is written in JQuery and interacts with the parser using a FFI.</li>
        </ul>
      </Project>
    </div>
  </section>
</template>

<script>
import Project from "./Project"
export default {
  name: "Projects",
  components: { Project },
}
</script>

<style scoped>
  #projects {
    min-height: 100vh;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    background: #75b9be
  }
  li {
    font-size: 0.8em;
    margin: 1em 0;
  }
</style>
