<template>
  <welcome class="welcome-message" />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Welcome from "./components/Welcome.vue";

export default defineComponent({
  name: "App",
  components: {
    Welcome,
  },
});
</script>

<style>
#app {
  font-family: ProximaNova, sans-serif;
}

.welcome-message {
  margin-top: 5%;
}
</style>
