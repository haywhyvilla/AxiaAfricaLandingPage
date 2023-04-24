<template>
  <section class="w-full md:py-28 py-20 bg-[#111111]">
    <div class="container mx-auto md:px-[150px] px-5">
      <header
        class="w-full sm:mx-auto headline text-[28px] md:text-[36px] text-white md:px-0 max-w-[332px] sm:container"
      >
        Foster your tech knowledge
      </header>
      <div
        class="container w-full mx-auto flex flex-col items-start justify-between mt-14 gap-[50px] text-white"
      >
        <img
          src="https://www.axia.africa/_nuxt/foster.96ed8018.png"
          alt="foster"
          class="h-auto w-full object-cover"
        />
        <p
          class="md:text-lg font-medium text-lighestgrey max-w-[580px] md:px-0"
        >
          Don’t just wait around, Register and join our students ready to enroll
          and kick start their tech career.
        </p>
        <a href="/application" class="btn-secondary text-white mt-8 md:mx-0">
          Apply Now
        </a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Foster",
};
</script>
