<template>
  <div id="app">
    <Example1 />
  </div>
</template>

<script>
import Example1 from "./components/Example1";

export default {
  name: "app",
  components: {
    Example1
  }
};
</script>

<style lang="scss">
html {
  height: 100%;
  padding: 0;
  margin: 0;
}
body {
  height: 100%;
  padding: 0;
  margin: 0;
}

#app {
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
