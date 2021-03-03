<template>
  <div id="app">
    <navbar />
    <landing />
    <company />
    <teamActivity />
    <TeamProject />
    <customerSupport />
    <detail />
    <Footer />
  </div>
</template>

<script>
import navbar from "./components/navbar.vue";
import landing from "./components/landing.vue";
import company from "./components/company.vue";
import teamActivity from "./components/teamActivity.vue";
import TeamProject from "./components/TeamProject.vue";
import customerSupport from "./components/customerSupport.vue";
import detail from "./components/detail.vue";
import Footer from "./components/Footer";

export default {
  name: "App",
  components: {
    navbar,
    landing,
    company,
    teamActivity,
    TeamProject,
    customerSupport,
    detail,
    Footer,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
