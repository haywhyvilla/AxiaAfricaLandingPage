<template>
  <div
    class="w-full md:h-[101px] flex justify-center items-center fixed z-20 inset-x-0 !bg-[#FFFCF9]"
  >
    <div class="container md:px-[150px] mx-auto">
      <header
        class="w-full container mx-auto md:shadow-none flex justify-between z-20 px-5 md:px-0 h-[53px]"
      >
        <a class="flex justify-center items-center"
          ><img
            src="https://www.axia.africa/_nuxt/logo.a67befb6.svg"
            alt="logo"
            class="w-[78px] md:w-auto"
        /></a>
        <div class="hidden gap-7 lg:flex items-center">
          <a class="text-base font-['Sen'] font-medium">About</a>
          <span
            class="text-base font-['Sen'] font-medium relative flex gap-2 items-center cursor-pointer"
          >
            <p class="flex gap-2">Schools</p>
            <v-icon name="BiChevronCompactDown" />
          </span>
          <button class="text-base font-['Sen'] font-medium">
            Join Our Community
          </button>
          <span
            class="text-base font-['Sen'] font-medium relative flex gap-2 items-center cursor-pointer"
          >
            <p class="flex gap-2">Help</p>
          </span>
        </div>
        <div class="flex items-center justify-between gap-3">
          <a
            class="shadow-[5px_6px_0px_1px_rgba(32,32,84,1)] border-solid border-[#111] border-[3px] px-4 py-2 text-[#111] font-semibold text-base"
          >
            Apply Now
          </a>
        </div>
      </header>
    </div>
  </div>
</template>

<script>
import { BiChevronCompactDown } from "oh-vue-icons/icons";
export default {
  name: "Header",
  components: {
    "v-icon": BiChevronCompactDown,
  },
};
</script>
