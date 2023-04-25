<template>
  <div class="relative">
    <Header />
    <div class="pt-28">
      <Home />
      <Courses />
      <Learn />
      <GetOnboard />
      <School />
      <Forter />
      <Success />
      <Partner />
    </div>
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Home from "./components/Home.vue";
import Courses from "./components/Courses.vue";
import Learn from "./components/Learn.vue";
import GetOnboard from "./components/GetOnboard.vue";
import School from "./components/School.vue";
import Forter from "./components/Foster.vue";
import Success from "./components/Success.vue";
import Partner from "./components/Partner.vue";
import Footer from "./components/Footer.vue";
export default {
  name: "App",
  components: {
    Header,
    Home,
    Courses,
    Learn,
    GetOnboard,
    School,
    Forter,
    Success,
    Partner,
    Footer,
  },
};
</script>
