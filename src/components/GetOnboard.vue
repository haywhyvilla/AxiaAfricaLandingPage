<template>
  <section class="w-full md:py-28 py-12 bg-[#111111]">
    <div class="container px-5 lg:px-[150px] mx-auto">
      <header
        class="container w-full font-medium text-[28px] md:text-[36px] lg:pl-12 text-white"
      >
        Get onboard with us
      </header>
      <div
        class="container w-full mx-auto gap-10 md:gap-20 flex flex-col-reverse lg:flex-row items-start justify-between md:mt-20 mt-12"
      >
        <img
          src="../assets/onboard.svg"
          alt="advisor"
          class="object-cover w-full md:w-[55%]"
        />
        <div class="w-full md:w-[45%] text-[#ebebeb]">
          <p class="mt-10 md:text-base font-medium">
            Axia Africa is an organization that is focused on equipping African
            youths with the knowledge and digital skills needed today Our aim is
            to make tech knowledge accessible to every individual irrespective
            of age, literacy, and location. We are looking forward to building a
            strong community of ready-to-work personnel and employable
            candidates around the world in the tech space.
          </p>
        </div>
      </div>

      <div
        class="container w-full mx-auto flex flex-col items-start justify-between mt-14 md:px-0 text-[#ebebeb]"
      >
        <h2
          class="text-[28px] md:text-3xl font-medium text-white relative ml-24 before:border-black"
        >
          <div class="line"></div>
          Why choose us
        </h2>
        <p class="mt-6 md:text-base font-medium text-[#ebebeb]">
          We at Axia Africa are intentional about our students and focused about
          building a community. The tech space in Africa is fast growing and we
          have the necessary programmes to help launch you into that space. We
          sharpen your skills to give you leverage in your career while
          navigating the job market
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "GetOnboard",
};
</script>

<style>
.line {
  border-bottom: 3px solid;
  bottom: 50%;
  content: "";
  height: 1px;
  position: absolute;
  right: 110%;
  width: 77px;
}
</style>
