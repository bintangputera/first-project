<template>
    <button>{{ content }}</button>
</template>

<script>
export default {
  name: "PrimaryButton",
  props: {
    content: String,
  },
};
</script>