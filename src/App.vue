<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <DropdownWithPills :options="options" />
  </div>
</template>

<script>
import options from "./options";
import DropdownWithPills from "./components/DropdownWithPills.vue";
export default {
  name: "app",
  components: {
    DropdownWithPills
  },
  data: () => ({ options })
};
</script>

<style lang="scss"></style>
