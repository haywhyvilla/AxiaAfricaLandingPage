<template>
  <Header />
  <div class="pt-28">
    <Home />
    <Courses />
    <Learn />
    <GetOnboard />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Home from "./components/Home.vue";
import Courses from "./components/Courses.vue";
import Learn from "./components/Learn.vue";
import GetOnboard from "./components/GetOnboard.vue";
export default {
  name: "App",
  components: {
    Header,
    Home,
    Courses,
    Learn,
    GetOnboard,
  },
};
</script>
