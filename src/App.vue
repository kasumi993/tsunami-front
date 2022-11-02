<template>
  <img src="./assets/circle-top.svg" class="circle-left">
  <img src="./assets/circle-left.svg" class="circle-right">
  <div class="flex row">
    <LeftMenu></LeftMenu>
    <RightSection></RightSection>
  </div>
</template>

<script>
import LeftMenu from "@/components/LeftMenu.vue";
import RightSection from "@/components/RightSection.vue";

export default {
  name: 'App',
  components: {
    RightSection,
    LeftMenu,
  }
}
</script>

<style>
@import "style/style.scss";
</style>
