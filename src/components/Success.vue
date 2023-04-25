<template>
  <section class="w-full mt-24 mb-20">
    <div class="w-full container mx-auto md:px-[150px] px-5">
      <h1 class="font-medium text-[28px] text-[] md:text-4xl">
        Our success story
      </h1>
      <p class="text-lg max-w-[708px] text-[#3f3f3f] mt-5 font-medium">
        What our students are saying about their learning experience.
      </p>
    </div>
    <div class="flex gap-4 mt-24" id="column">
      <article
        class="bg-[#faf5ee] md:w-[40%] md:px-5 px-3 py-6 z-10 flex flex-col justify-between ml-5 mr-5 relative"
      >
        <p class="font-medium md:text-base text-sm text-[#3f3f3f]">
          I had no clue where to start in learning Product design, then Axia
          Africa started an online training and I joined. Within few weeks of
          coaching I was able to understand both UX &amp; UI. The classes are
          interesting and gives room to ask questions. Materials provided were
          helpful.&nbsp;It was a great to learning experience led by the
          fantastic teachers. I would highly recommend this training if you are
          a beginner
        </p>
        <div class="flex items-center">
          <img
            alt="Blessing Fabilola"
            class="h-[56px] md:h-auto"
            src="../assets/person1.png"
          />
          <h3 class="font-bold ml-5 md:text-xl text-lg text-[#3f3f3f]">
            Blessing Fabilola
          </h3>
        </div>
      </article>
      <article
        class="bg-[#faf5ee] md:w-[40%] md:px-5 px-3 py-6 relative z-10 flex flex-col justify-between ml-5 mr-5"
      >
        <p class="font-medium md:text-base text-sm text-[#3f3f3f]">
          Axia Africa’s product design class has been an eye opener and a good
          starter for me as someone who is a graphic designer but struggles a
          lot with UX in particular. I’ve become more confident in my UX process
          and prowess as a designer and I won’t stop learning!. Thank you Axia.
        </p>
        <div data-v-f01c123e="" class="flex items-center">
          <img
            alt="Samuel Osunleke"
            class="h-[56px] md:h-auto"
            src="../assets/person2.png"
          />
          <h3 class="font-bold ml-5 md:text-xl text-lg text-[#3f3f3f]">
            Samuel Osunleke
          </h3>
        </div>
      </article>

      <article
        class="bg-[#faf5ee] md:w-[40%] md:px-5 px-3 py-6 relative z-10 flex flex-col justify-between ml-5 mr-5"
      >
        <p class="font-medium md:text-base text-sm text-[#3f3f3f]">
          Axia Africa has been so helpful to me. I got into tech with zero
          knowledge of it, didn’t even know my way around a good system. But
          right now, I know more than I would’ve imagined that I can before I
          got into the academy. Very helpful, kind, patient and thoughtful
          teachers too.&nbsp;This training has really helped me! I highly
          recommend it! Thank youuu.
        </p>
        <div class="flex items-center">
          <img
            alt="Oyinlola Babalola"
            class="h-[56px] md:h-auto"
            src="../assets/person3.png"
          />
          <h3 class="font-bold ml-5 md:text-xl text-lg text-[#3f3f3f]">
            Oyinlola Babalola
          </h3>
        </div>
      </article>
    </div>
  </section>
</template>

<script>
export default {
  name: "Success",
};
</script>

<style>
@media (max-width: 768px) {
  #column {
    display: flex;
    flex-direction: column;
  }
}
</style>
