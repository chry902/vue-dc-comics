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
      <section class="sec_nav d-flex align-center justify-content-center">
        <div class="">
          <div>
            <img src="./assets/buy-comics-digital-comics.png" alt="" />
            <h6 class="">DIGITAL COMICS</h6>
          </div>
          <div>
            <img src="./assets/buy-comics-merchandise.png" alt="" />
            <h6 class="">DC MERCHANDISE</h6>
          </div>
          <div>
            <img src="./assets/buy-comics-shop-locator.png" alt="" />
            <h6 class="">SUBSCRIPTIONS</h6>
          </div>
          <div>
            <img src="./assets/buy-comics-subscriptions.png" alt="" />
            <h6 class="">COMIC SHOP LOCATOR</h6>
          </div>
          <div>
            <img class="pay" src="./assets/buy-dc-power-visa.svg" alt="" />
            <h6 class="">DC POWER VISA</h6>
          </div>
        </div>
      </section>
    </main>

    <footer class="">
      <div class="d-flex">
        <div class="footer_list col-6 d-flex flex-wrap">
          <ul>
            <li>dvwvwvwv</li>
            <li>dvwvwvwv</li>
            <li>dvwvwvwv</li>
            <li>dvwvwvwv</li>
            <li>dvwvwvwv</li>
          </ul>
          <ul>
            <li>dvwvwvwv</li>
            <li>dvwvwvwv</li>
            <li>dvwvwvwv</li>
            <li>dvwvwvwv</li>
            <li>dvwvwvwv</li>
          </ul>
          <ul>
            <li>dvwvwvwv</li>
            <li>dvwvwvwv</li>
            <li>dvwvwvwv</li>
            <li>dvwvwvwv</li>
            <li>dvwvwvwv</li>
          </ul>
          <ul>
            <li>dvwvwvwv</li>
            <li>dvwvwvwv</li>
            <li>dvwvwvwv</li>
            <li>dvwvwvwv</li>
            <li>dvwvwvwv</li>
          </ul>
        </div>
        <div class="dc_image col-6">
          <img src="./assets/dc-logo-bg.png" alt="" />
        </div>
      </div>
    </footer>
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
@import "style.scss";
$backg_card: rgba(28, 28, 28, 1);
$backg_second_nav: rgba(2, 130, 249, 1);
$backg_footer_botton: rgba(48, 48, 48, 1);
$backg_buttom: rgba(2, 130, 249, 1);

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
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
        object-fit: cover;
        width: 100%;
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
          width: 200px;
          height: 40px;
          color: white;
          background-color: rgba(2, 130, 249, 1);
        }
      }
    }
    .sec_nav {
      background-color: rgba(2, 130, 249, 1);

      div {
        width: 100%;
        background-color: rgba(2, 130, 249, 1);
        display: flex;
        justify-content: center;
        align-items: center;
        color: white;
        h6 {
          font-size: 11px;
        }
        img {
          display: flex;
          padding: 2rem 0.5rem;
          width: 40px;
        }
        .pay {
          width: 43px;
        }
      }
    }
  }
  footer {
    height: 250px;
    width: 100%;
    img {
    }
  }
}
</style>
