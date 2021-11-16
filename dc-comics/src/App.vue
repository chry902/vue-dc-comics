<template>
  <div id="app">
    <header>
      <nav>
        <img src="../img" alt="" />
      </nav>
    </header>
    <!-- jumbo image -->
    <section></section>
    <!-- card -->
    <section></section>
    <!-- second's nav -->
    <section></section>

    <footer></footer>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
