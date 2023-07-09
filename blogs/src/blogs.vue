<script setup>
import Navbar from "./components/navbar.vue";
import Cards from "./components/cards.vue";
import Footer from "./components/footer.vue";
</script>

<template>
  <div>
    <Navbar />
   
    <div class="max-w-[1280px] mx-auto text-center mt-24">
      <h1
        class="text-[#282938] text-5xl font-semibold text-center leading-[64px] max-w-4xl mx-auto"
      >
        A UX Case Study on Creating a Studious Environment for Students
      </h1>
      <p class="text-[#282938] text-base font-medium leading-7 mt-4 mb-8">
        Andrew Jonson Posted on 27th January 2021
      </p>
      <img
        src="/images/first-page-img.png"
        alt=""
        class="max-w-[1280px] w-full"
      />
    </div>
    <div class="max-w-[830px] mx-auto mb-28">
      <p class="text-base text-[#282938] font-normal opacity-70 leading-7 text-center mt-12 max-w-[831px]">
        Apparently we had reached a great height in the atmosphere, for the sky
        was a dead black, and the stars had ceased to twinkle. By the same
        illusion which lifts the horizon of the sea to the level of the
        spectator on a hillside.
      </p>
      <p
        class="text-base leading-7 text-[#2405F2] opacity-70 cursor-pointer text-center mt-4"
      >
        Read more
      </p>
    </div>
    <p class="text-5xl text-[#282938] font-semibold leading-[64px] text-center mt-32 mb-12">Our Blog</p>
    <Cards />

    <Footer/>
  </div>
</template>