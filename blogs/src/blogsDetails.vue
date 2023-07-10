<script setup>
import Navbar from "./components/navbar.vue";
import Cards from "./components/cards.vue";
import Footer from "./components/footer.vue";
</script>

<template>
  <div>
    <navbar />
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
        src="../../public/images/first-page-img.png"
        alt=""
        class="max-w-[1280px] w-full"
      />
    </div>

    <div class="max-w-[840px] mx-auto my-[90px]">
      <p class="text-[38px] font-semibold leading-[56px] text-[#282938] mb-8">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit.
      </p>
      <p
        class="text-base font-normal text-[#282938] opacity-70 leading-7 mb-10"
      >
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
        veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
        commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
        velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint
        occaecat cupidatat non proident, sunt in culpa qui officia deserunt
        mollit anim id est laborum. Ut enim ad minim veniam, quis nostrud
        exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        Duis aute irure dolor in reprehenderit in voluptate velit esse cillum
        dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
        proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
      <p
        class="text-[38px] font-semibold font-semibold leading-[56px] text-[#282938] mb-8"
      >
        Ut enim ad minim veniam, quis nostrud.
      </p>

      <p class="text-base font-normal text-[#282938] opacity-70 leading-7 mb-6">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
        veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
        commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
        velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint
        occaecat cupidatat non proident, sunt in culpa qui officia deserunt
        mollit anim id est laborum. Ut enim ad minim veniam, quis nostrud
        exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        Duis aute irure dolor in reprehenderit in voluptate velit esse cillum
        dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
        proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
      <ul
        class="list-disc text-base font-normal text-[#282938] opacity-70 leading-7"
      >
        <li class="mb-3">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
        </li>
        <li class="mb-3">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
        </li>
        <li class="mb-6">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
        </li>
      </ul>
      <p class="text-base font-normal text-[#282938] opacity-70 leading-7 mb-8">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
        veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
        commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
        velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint
        occaecat cupidatat non proident, sunt in culpa qui officia deserunt
        mollit anim id est laborum. Ut enim ad minim veniam, quis nostrud
        exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        Duis aute irure dolor in reprehenderit in voluptate velit esse cillum
        dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
        proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
      <img src="../../public/images/page-2-img.jpg" class="mb-14" />
      <p
        class="text-[38px] font-semibold font-semibold leading-[56px] text-[#282938] mb-8"
      >
        Ut enim ad minim veniam, quis nostrud.
      </p>
      <p
        class="text-base font-normal text-[#282938] opacity-70 leading-7 mb-24"
      >
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
        veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
        commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
        velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint
        occaecat cupidatat non proident, sunt in culpa qui officia deserunt
        mollit anim id est laborum. Ut enim ad minim veniam, quis nostrud
        exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        Duis aute irure dolor in reprehenderit in voluptate velit esse cillum
        dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
        proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
    </div>
    <Footer/>
  </div>
</template>
