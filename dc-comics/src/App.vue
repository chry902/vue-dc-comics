<template>
  <div id="app">
    <header>
      <nav>
        <div>
          <img src="./assets/dc-logo.png" alt="" />
        </div>
        <div>
          <ul>
            <li>wqdwqdwq</li>
            <li>ewfwefewf</li>
            <li></li>
            <li>wecewc</li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
          </ul>
        </div>
      </nav>
    </header>
    <!-- jumbo image -->
    <main>
      <section class="jumbotron">
        <img src="./assets/jumbotron.jpg" alt="" />
      </section>
      <!-- card -->
      <section></section>
      <!-- second's nav -->
      <section></section>
    </main>

    <footer></footer>
  </div>
</template>

<script>
/* import HelloWorld from "./components/HelloWorld.vue"; */

export default {
  name: "App",
  components: {
    //HelloWorld,
  },
};
</script>

<style lang="scss">
#app {
  width: 100vw;
  header {
    nav {
      display: flex;
      justify-content: space-between;
    }

    ul {
      display: flex;

      li {
        list-style: none;
        padding: 0 0.5rem;
      }
    }
  }
  main {
    .jumbotron {
      width: 100%;
      height: 100%;
    }
  }
}
</style>
