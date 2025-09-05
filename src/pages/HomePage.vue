<script lang="ts" setup>
import SocialRow from '@/components/SocialRow.vue'
import Image from '../assets/images/kdiry-headshot.png'
import Resume from '../assets/tarik_kdiry_resume.pdf'
</script>

<template>
  <div class="flex flex-wrap justify-center items-center w-screen">
    <div class="flex profile mr-0 md:lg:mr-10">
      <img :src="Image" />
    </div>
    <div class="flex flex-col">
      <p>Hey! I'm</p>
      <h1 class="!text-[73px]">Tarik Kdiry</h1>
      <h3 class="!text-[40px] hover:text-red-200">software engineer. actor, sometimes.</h3>
      <h4 class="!text-[20px]">
        I've got some
        <a :href="Resume" class="!no-underline !text-[#fd9374]" target="_blank">skills</a>, but if
        you prefer socials, let's connect!
      </h4>
      <div class="mt-4">
        <SocialRow />
      </div>
    </div>
  </div>
</template>

<style scoped>
p {
  color: #fd9374;
}
h1,
h2,
h3 {
  color: #f0f0f2;
}

h4 {
  color: #81878c;
}

.profile {
  aspect-ratio: 16 / 9;

  img {
    width: 250px;
    height: 250px;
    border-radius: 50%;
    display: block;
    transition: 0.5s;
    object-fit: cover;
  }
}
</style>
