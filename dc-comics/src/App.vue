<template>
  <div id="app">
    <header>
      <nav>
        <div>
          <img src="./assets/dc-logo.png" alt="" />
        </div>
        <div class="items_nav">
          <ul>
            <li>CHARACTER</li>
            <li>COMICS</li>
            <li>MOVIES</li>
            <li>TV</li>
            <li>GAMES</li>
            <li>COLLECTIBLES</li>
            <li>VIDEOS</li>
            <li>FANS</li>
            <li>NEWS</li>
            <li>SHOP</li>
          </ul>
        </div>
      </nav>
    </header>

    <main>
      <!-- jumbo image -->
      <section class="jumbotron">
        <img src="./assets/jumbotron.jpg" alt="" />
      </section>
      <!-- card -->
      <section class="card">
        <div class="card_container">
          <div class="card_img">
            <div class="">
              <img src="" alt="" />
            </div>
            <div class="">
              <p></p>
            </div>
          </div>
          <div class="button">
            <button>LOAD MORE</button>
          </div>
        </div>
      </section>
      <!-- second's nav -->
      <section class="sec_nav">
        <div>
          <img src="./assets/buy-comics-digital-comics.png" alt="" />
          <img src="./assets/buy-comics-merchandise.png" alt="" />
          <img src="./assets/buy-comics-subscriptions.png" alt="" />
          <img src="./assets/buy-comics-shop-locator.png" alt="" />
          <img src="./assets/buy-dc-power-visa.svg" alt="" />
        </div>
      </section>
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
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  width: 100vw;
  header {
    padding: 1rem 0;
    nav {
      display: flex;
      justify-content: space-around;

      .items_nav {
        display: flex;
        align-items: center;
        ul {
          display: flex;

          li {
            list-style: none;
            padding: 0 0.5rem;
          }
        }
      }
    }
  }
  main {
    .jumbotron {
      width: 100%;
      height: 250px;
      img {
        background-position: center;
        background-repeat: no-repeat;
        width: 100%;
        height: 100%;
      }
    }
    .card {
      width: 100%;
      height: 400px;
      background-color: rgba(28, 28, 28, 1);
      /*  .card_container {
        width: calc(70% / 6);
        height: 100%;
      } */
      .button {
        width: 100%;
        display: flex;
        justify-content: center;

        button {
          width: 153px;
          height: 50px;
          color: white;
          background-color: rgba(2, 130, 249, 1);
        }
      }
    }
    .sec_nav {
      width: 100%;
      height: 100px;
      background-color: rgba(2, 130, 249, 1);
      div {
        display: flex;
        justify-content: center;
        align-items: center;
        img {
          margin: 0 1rem;
          width: 60px;
          height: 60px;
        }
      }
    }
  }

  /* $backg_card: rgba(28, 28, 28, 1);
    $backg_second_nav: rgba(2, 130, 249, 1);
    $backg_footer_botton: rgba(48, 48, 48, 1);
    $backg_buttom: rgba(2, 130, 249, 1); */
}
</style>
