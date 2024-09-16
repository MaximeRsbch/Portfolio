<script setup>
import Contact from "./Contact.vue";
import Project from "./Project.vue";
</script>

<template>
  <div class="flex justify-start items-center pt-10 pl-6">
    <div>
      <img
        class="h-16 w-16 rounded-full"
        src="../assets/img/image.jpg"
        alt=""
      />
    </div>
    <div class="pl-4">
      <h1 class="text-[#D6E1FF]">Rossbach Maxime</h1>
    </div>
  </div>
  <div class="pl-6 pt-4">
    <p class="text-[#9EB1FF]">Junior developer</p>
  </div>
  <div class="pt-20">
    <div class="text-justify">
      <p class="text-[#9EB1FF] text-center mt-2">
        I am a junior developer who is passionate about web development. I am
        currently learning Vue.js and I am looking for an internship to improve
        my skills.
      </p>
    </div>

    <div class="flex justify-center items-center pt-20">
      <div class="px-4">
        <img class="h-12 rounded-md" src="../assets/img/angular.png" alt="" />
      </div>
      <div>
        <img class="h-12 rounded-md" src="../assets/img/vue.png" alt="" />
      </div>
      <div>
        <img class="h-12 rounded-md" src="../assets/img/spring.png" alt="" />
      </div>
    </div>
  </div>
  <Project />
  <Contact />
</template>
