<template>
  <div :class="style.box">
    <div :class="style.left"><div :class="style.rectangle"></div></div>
    <div :class="style.right"><div :class="style.round"></div></div>
  </div>
</template>

<script>
import style from "./style.module.scss";
export default {
  name: "Example1",
  computed: {
    style: () => style
  }
};
</script>

<style scoped></style>
