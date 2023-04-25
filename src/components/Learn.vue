<template>
  <section class="w-full md:py-36 py-20 bg-[#202054]">
    <div
      class="container w-full mx-auto flex flex-col lg:flex-row lg:items-center gap-10 justify-between px-5 lg:px-[150px]"
    >
      <div class="max-w-[440px] mb-16">
        <h1 class="text-[28px] md:text-[36px] text-white headline font-medium">
          Confused about what to learn?
        </h1>
        <p class="mt-5 md:text-lg text-[#ebebeb] font-medium">
          Speak with our professional tech advisors to help kick start your tech
          journey and pilot you to being an expert in your desired field.
        </p>
        <button
          class="shadow-[5px_6px_0px_1px_rgba(256,256,256,1)] border-solid border-[#fff] border-[3px] text-white mt-8 px-4 py-2"
        >
          Speak with an Advisor
        </button>
      </div>
      <img
        src="https://www.axia.africa/_nuxt/advisor.525dee5a.svg"
        alt="advisor"
        class="w-full sm:w-[50%]"
      />
    </div>
  </section>
</template>

<script>
export default {
  name: "Learn",
};
</script>
