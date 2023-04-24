<template>
  <Header />
  <div class="pt-28">
    <Home />
    <Courses />
    <Learn />
    <GetOnboard />
    <School />
    <Forter />
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
  },
};
</script>
