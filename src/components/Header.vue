<template>
  <div class="relative">
    <div
      class="w-full md:h-[101px] center fixed z-20 inset-x-0 bg-clear !bg-[#FFFCF9]"
    >
      <div class="inner container md:px-[150px] mx-auto">
        <header
          class="w-full container mx-auto shadow-nav md:shadow-none flex justify-between z-20 px-5 md:px-0 h-[53px]"
        >
          <a data-v-45ffb379="" href="/" class="center"
            ><img
              data-v-45ffb379=""
              src="https://www.axia.africa/_nuxt/logo.a67befb6.svg"
              alt="logo"
              class="w-[78px] md:w-auto"
          /></a>
          <div class="hidden gap-7 lg:flex items-center">
            <a href="/#onboard" class="nav-item">About</a>
            <span
              to="#"
              class="nav-item option relative group flex gap-2 items-center cursor-pointer"
            >
              <p class="flex gap-2">Schools</p>
            </span>
            <button data-v-45ffb379="" to="/application" class="nav-item">
              Join Our Community
            </button>
            <span
              to="#"
              class="nav-item option relative group flex gap-2 items-center cursor-pointer"
            >
              <p class="flex gap-2">Help</p>
            </span>
          </div>
          <div class="flex items-center justify-between gap-3 pc">
            <a href="/application" class="btn-primary"> Apply Now </a>
          </div>
          <svg viewBox="0 0 24 24" class="mobile w-4 cursor-pointer z-50">
            <use
              xlink:href="https://www.axia.africa/_nuxt/sprite.6082407c.svg#menu"
            ></use>
          </svg>
        </header>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>
