<template>
  <section
    class="mx-auto container w-full mt-24 mb-40 lg:px-[150px] px-5 relative"
  >
    <div class="">
      <h1 class="text-[28px] font-medium text-[#111] md:text-4xl">
        Discover the right school for your journey
      </h1>
      <p class="md:text-lg max-w-[708px] text-[#3f3f3f] mt-5 font-medium">
        Axia Africa offers you the chance to explore schools which has variety
        of courses to learn from, like product design, Front end,
      </p>
    </div>
    <img
      src="https://www.axia.africa/_nuxt/doddle2.c9d35eef.svg"
      alt="ground-nuttttttttttttttttttttttttttttttttttttttttttttttttttttttt"
      class="mt-0 sm:mt-12 absolute right-10 w-[220px] sm:w-[350px] -top-24"
    />
    <div
      class="flex flex-wrap md:mt-28 mt-20 gap-x-20 md:gap-y-32 gap-y-20 w-full justify-center"
    >
      <article class="bg-[#faf5ee] md:w-[40%] md:px-5 px-3 py-6 relative z-10">
        <div class="article"></div>
        <h3 class="md:text-2xl text-lg text-[#111] font-semibold">
          School of Product
        </h3>
        <p class="text-sm md:text-base font-medium mt-6 text-[#3f3f3f]">
          We offer you Product courses such as Product Design,Product management
          and Product marketing by equipping you with the right trainings and
          guidelines. Become a world class personnel and job-ready candidate in
          the product field.
        </p>
        <a
          class="text-base font-semibold text-[#202054] flex gap-3 pl-0 md:mt-16 mt-8 hover:gap-5 py-3 px-6"
        >
          <span class="underline">View Courses</span>
          <ion-icon name="arrow-forward-outline"></ion-icon>
        </a>
      </article>

      <article class="bg-[#faf5ee] md:w-[40%] md:px-5 px-3 py-6 relative z-10">
        <div class="article"></div>
        <h3 class="md:text-2xl text-lg text-[#111] font-semibold">
          School of Systems Engineering
        </h3>
        <p class="text-sm md:text-base font-medium mt-6 text-[#3f3f3f]">
          Begin your learning process in Front-End Web Development, Back-End Web
          Development and more. Discover career opportunities available for you.
          Speak to professionals and read through materials and the programme
          designed specifically for you.
        </p>
        <a
          class="text-base font-semibold text-[#202054] flex gap-3 pl-0 md:mt-16 mt-8 hover:gap-5 py-3 px-6"
        >
          <span class="underline">View Courses</span>
          <ion-icon name="arrow-forward-outline"></ion-icon>
        </a>
      </article>

      <article class="bg-[#faf5ee] md:w-[40%] md:px-5 px-3 py-6 relative z-10">
        <div class="article"></div>
        <h3 class="md:text-2xl text-lg text-[#111] font-semibold">
          School of Data
        </h3>
        <p class="text-sm md:text-base font-medium mt-6 text-[#3f3f3f]">
          Even as a newbie in the data analysis space, you can jumpstart your
          journey and hone your skills by kicking it off with the Axia Africa
          School of Data Analysis.
        </p>
        <a
          class="text-base font-semibold text-[#202054] flex gap-3 pl-0 md:mt-16 mt-8 hover:gap-5 py-3 px-6"
        >
          <span class="underline">View Courses</span>
          <ion-icon name="arrow-forward-outline"></ion-icon>
        </a>
      </article>
    </div>
  </section>
</template>

<script>
export default {
  name: "School",
};
</script>

<style>
.article {
  background-color: transparent;
  border-bottom: 3px solid #000;
  border-left: 3px solid #000;
  bottom: -20px;
  content: "";
  height: 90%;
  left: -12px;
  position: absolute;
  width: 95%;
  z-index: -10;
}
</style>
