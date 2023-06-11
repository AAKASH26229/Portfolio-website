<!-- Home.vue -->
<template>
    <div class="home">
      <Header />
      <Projects />
      <Experience />
      <Education />
      <Skills />
      <Contact />
    </div>
  </template>
  
  <script>
  import Header from "../components/Header.vue";
  import Projects from "../components/Projects.vue";
  import Experience from "../components/Experience.vue";
  import Education from "../components/Education.vue";
  import Skills from "../components/Skills.vue";
  import Contact from "../components/Contact.vue";
  
  export default {
    name: "AppHome",
    components: {
      Header,
      Projects,
      Experience,
      Education,
      Skills,
      Contact,
    },
  };
  </script>
  