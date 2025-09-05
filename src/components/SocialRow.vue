<script lang="ts" setup>
import Email from '../assets/social/email.png'
import Github from '../assets/social/github.png'
import Instagram from '../assets/social/instagram.png'
import LinkedIn from '../assets/social/linkedin.png'
</script>

<template>
  <div class="flex flex-row flex-wrap">
    <div class="container">
      <a href="mailto:tarik.kdiry@gmail.com">
        <img :src="Email" class="flex h-[30px] mt-[50%] ml-[50%] mr-[50%]" />
      </a>
    </div>
    <div class="container">
      <a href="https://github.com/tarikkdiry" target="_blank">
        <img :src="Github" class="flex h-[30px] mt-[50%] ml-[50%] mr-[50%]" />
      </a>
    </div>
    <div class="container">
      <a href="https://www.instagram.com/tarik_kdiry/" target="_blank">
        <img :src="Instagram" class="flex h-[30px] mt-[50%] ml-[50%] mr-[50%]" />
      </a>
    </div>
    <div class="container">
      <a href="https://www.linkedin.com/in/tarik-kdiry-0b62b8100/" target="_blank">
        <img :src="LinkedIn" class="flex h-[30px] mt-[50%] ml-[50%] mr-[50%]" />
      </a>
    </div>
  </div>
</template>

<style scoped>
.container {
  display: flex;
  background-color: white;
  border-radius: 50px;
  height: 60px;
  width: 60px;
  margin-right: 20px;
  margin-bottom: 20px;
  transition: 0.5s;
}

.container:hover {
  transform: translate(5px, 3px);
}
</style>
