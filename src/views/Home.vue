<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <PrimaryButton content="Submit" />
  </div>
</template>

<script>
// @ is an alias to /src
import PrimaryButton from "@/components/PrimaryButton.vue";

export default {
  name: "Home",
  components: {
    PrimaryButton,
  },
};
</script>
