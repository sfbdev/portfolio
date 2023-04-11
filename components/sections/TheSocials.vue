<template>
  <div class="flex justify-between items-center">
    <div class="flex gap-1">
      <SocialIcon
        title="Github"
        link="https://github.com/sfbdev"
        icon="ant-design:github-filled"
      />
      <SocialIcon
        title="Twitter"
        link="https://twitter.com/sfbdev"
        icon="ant-design:twitter-outlined"
      />
      <SocialIcon
        title="Instagram"
        link="https://www.instagram.com/sfbdev/"
        icon="ant-design:instagram-outlined"
      />
    </div>
    <ActionButton link="mailto:sefikfurkanbayram@gmail.com"
      >Email Me</ActionButton
    >
  </div>
</template>

<script setup lang="ts">
import ActionButton from "../ui/ActionButton.ts";
import SocialIcon from "../ui/SocialIcon.ts";
</script>
