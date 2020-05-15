<template>
    <div id="app" class="">
        <Header></Header>   <!-- add logo in header   -->


        <!-- Optreden rooster link -->
        <button class="pageLink">
            <img src="./assets/logo.png"/>
        </button>

      <!-- Alle events + locatie's -->
      <button class="pageLink">
            <img src="./assets/logo.png"/>
        </button>

        <Rooster></Rooster>

        <Footer></Footer>
    </div>
</template>

<script>

    import Header from "./components/Main/Header";
    import Footer from "./components/Main/Footer";
    import Rooster from "./components/Rooster";

    export default {
        name: 'App',
        components: {
            Header,
            Footer,
            Rooster

        },

    }
</script>

<style>
    #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
    }

    h1 {
        margin-top: 0;
    }

    Header{
      margin-bottom: 20px;
    }
    .pageLink{
      margin-bottom: 20px;
    }

    .fade-enter-active, .fade-leave-active {
      transition: opacity .5s;
    }
    .fade-enter, .fade-leave-to /* .fade-leave-active below version 2.1.8 */ {
      opacity: 0;
    }

</style>
