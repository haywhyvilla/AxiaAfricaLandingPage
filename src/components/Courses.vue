<template>
  <section
    class="container w-full md:mt-28 mt-12 mb-40 px-5 lg:px-[150px] mx-auto"
  >
    <h1 class="text-[#111] md:text-4xl font-medium text-[28px]">
      Courses for you
    </h1>
    <p class="text-base md:text-lg text-[#3f3f3f] max-w-[478px] mt-5">
      Here are some courses from our schools that we offer. Enroll and kickstart
      your tech career.
    </p>
    <div
      class="grid mt-12 lg:grid-cols-3 grid-cols-1 place-content-center sm:grid-cols-2 gap-10"
    >
      <article class="bg-[#faf5ee] flex flex-col relative z-10">
        <img
          src="../assets/course1.png"
          alt="image"
          class="md:h-[233px] h-[141px]"
        />
        <div class="md:p-5 p-3.5">
          <h3 class="text-lg md:text-[22px] text-[#111] font-semibold">
            Product Design
          </h3>
          <p class="text-sm md:text-base font-medium mt-3 text-[#3F3F3F]">
            Design user experiences for products in today’s digital world. Build
            a portfolio that showcases your ability to transform products.
          </p>
          <a
            href="/enroll/product_designer"
            class="font-semibold text-base flex gap-3 text-[#202054] pl-0 mt-4 hover:gap-5 transite"
          >
            <span class="underline"> Enroll Now </span>
          </a>
        </div>
      </article>

      <article class="bg-[#faf5ee] flex flex-col relative z-10">
        <img
          src="../assets/course2.png"
          alt="image"
          class="md:h-[233px] h-[141px]"
        />
        <div class="md:p-5 p-3.5">
          <h3 class="text-lg md:text-[22px] text-[#111] font-semibold">
            Data Analytics
          </h3>
          <p class="text-sm md:text-base font-medium mt-3 text-[#3F3F3F]">
            Use Python, SQL, and statistics to uncover insights, communicate
            critical findings, and create data-driven solutions.
          </p>
          <a
            href="/enroll/product_designer"
            class="font-semibold text-base flex gap-3 text-[#202054] pl-0 mt-4 hover:gap-5 transite"
          >
            <span class="underline"> Enroll Now </span>
          </a>
        </div>
      </article>

      <article class="bg-[#faf5ee] flex flex-col relative z-10">
        <img
          src="../assets/course3.png"
          alt="image"
          class="md:h-[233px] h-[141px]"
        />
        <div class="md:p-5 p-3.5">
          <h3 class="text-lg md:text-[22px] text-[#111] font-semibold">
            Front-End Development
          </h3>
          <p class="text-sm md:text-base font-medium mt-3 text-[#3F3F3F]">
            Begin our front-end development program structured to help students
            launch a new career in web development.
          </p>
          <a
            href="/enroll/product_designer"
            class="font-semibold text-base flex gap-3 text-[#202054] pl-0 mt-4 hover:gap-5 transite"
          >
            <span class="underline"> Enroll Now </span>
          </a>
        </div>
      </article>
    </div>
  </section>
</template>

<script>
export default {
  name: "Courses",
};
</script>

<style>
.transite {
  transition-duration: 0.15s;
  transition-property: all;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-timing-function: cubic-bezier(0.4, 0, 1, 1);
}
</style>
