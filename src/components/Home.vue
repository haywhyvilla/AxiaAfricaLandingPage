<template>
  <section
    class="container w-full relative h-[700px] px-5 lg:px-[150px] mx-auto sm:mt-20"
  >
    <h1
      class="text-[32px] text-center font-medium text-[#111] md:text-start md:text-[45px] max-w-[560px]"
    >
      Accelerate your career with
      <span id="bg">Job-ready </span>tech skills.
    </h1>
    <p
      class="text-base md:text-lg text-[#3f3f3f] text-center md:text-start max-w-[480px] md:mt-7 mt-2.5"
    >
      Begin your tech journey and expand your career opportunities in the tech
      space by learning tech skills in demand.
    </p>
    <div
      class="flex flex-col justify-center md:justify-start md:flex-row gap-6 items-center mt-12"
    >
      <a
        class="shadow-[5px_6px_0px_1px_rgba(32,32,84,1)] border-solid border-[#111] border-[3px] text-[#111] font-semibold text-base px-4 py-2"
      >
        Apply Now
      </a>
      <button
        class="font-semibold text-base flex justify-center items-center gap-3 text-[#202054] hover:gap-5 transite"
      >
        <span class="underline">Speak with an Advisor</span>
        <ion-icon name="arrow-forward-outline"></ion-icon>
      </button>
    </div>
    <img
      src="https://www.axia.africa/_nuxt/doddle.efbf3eb9.svg"
      class="w-[30vw] mt-12 absolute left-10 pc max-w-[500px] bouncy-up"
      alt="grountsssssssssssssssssssssssssssssss"
    />
    <img
      src="https://www.axia.africa/_nuxt/hero.0d0e9f28.svg"
      class="md:absolute md:top-0 md:right-6 md:w-[57vw] w-[90%] mt-5 md:mt-0 max-w-[700px] mx-auto md:mx-0"
      alt="grountsssssssssssssssssssssssssssssss"
    />
  </section>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style>
#bg {
  -webkit-text-fill-color: transparent;
  background: linear-gradient(65deg, #ab2638, #f0b73f);
  -webkit-background-clip: text;
}
</style>
