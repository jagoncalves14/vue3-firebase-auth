<template>
  <div class="home">
    <img class="home__logo" alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Vue3 Firebase Auth" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

export default defineComponent({
  name: "Home",
  components: {
    HelloWorld
  }
});
</script>

<style lang="scss">
.home__logo {
  max-width: 150px;
}
</style>
