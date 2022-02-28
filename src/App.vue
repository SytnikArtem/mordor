<template>
  <div id="app">
    <LanguageSwitcher />
    <HelloWorld />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import LanguageSwitcher from "./components/LanguageSwitcher.vue";

export default {
  name: "App",
  components: {
    LanguageSwitcher,
    HelloWorld,
  },
};
</script>

<style></style>
