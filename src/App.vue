<template>
  <welcome-message class="welcome-message" />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import WelcomeMessage from "./components/WelcomeMessage.vue";

export default defineComponent({
  name: "App",
  components: {
    WelcomeMessage,
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
