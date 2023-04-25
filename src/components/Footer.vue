<template>
  <footer
    id="footer"
    class="bg-[#202054] text-white p-5 md:pt-24 md:pb-14 py-12 w-full mx-auto center-col"
  >
    <div
      class="container mx-auto md:px-[150px] px-5 flex md:justify-between flex-wrap gap-5"
    >
      <div class="flex flex-col gap-4 md:w-[40%] w-full items-start">
        <img
          src="https://www.axia.africa/_nuxt/logo-white.4357a423.svg"
          alt="logo"
          class="w-[78px]"
        />
        <p class="text-base md:max-w-[350px] text-[#ebebeb] mt-1">
          An organization that is focused on equipping African youths with the
          knowledge and skills needed in the tech space.
        </p>
        <div class="center gap-5 mt-3 md:flex hidden">
          <ion-icon name="logo-facebook" size="large"></ion-icon>
          <ion-icon name="logo-instagram" size="large"></ion-icon>
          <ion-icon name="logo-facebook" size="large"></ion-icon>
        </div>
      </div>
      <div class="flex flex-col gap-[30px] w-[15%] mt-6 md:mt-0">
        <span class="font-bold text-lg mb-2.5">COMPANY</span>
        <a> About </a>
        <a> Blog </a>
        <a>FAQs </a>
        <a> Join Our Community </a>
        <a> Partnership </a>
        <a> Blog </a>
      </div>

      <div class="flex flex-col gap-[30px] w-[20%]">
        <span class="font-bold text-lg mb-2.5">SCHOOLS</span>
        <a class="font-light"> School of Product </a>
        <a class=""> School of Data </a>
        <a class=""> School of Engineering </a>
      </div>

      <div class="flex flex-col gap-[30px] lg:w-[15%] mt-6 md:mt-0">
        <span class="font-bold text-lg mb-2.5">CONTACT</span>
        <a href="mailto:axiaafrica@gmail.com">axiaafrica@gmail.com</a>
        <a href="tel:+2349015558035">09015558035</a>
      </div>
    </div>
    <p class="center text-center w-full md:w-auto mt-32">
      © 2023 Axia Africa. All rights reserved.
    </p>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>
