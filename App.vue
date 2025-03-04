<template>
  <div class="container">
    <Header />
    <hr />
    <div class="row">
      <Server />
      <ServerDetails />
    </div>
    <hr />
    <Footer />
  </div>
</template>

<script>
import MainApp from "./components/MainApp.vue";
import Server from "./components/server/Server.vue";
import Header from "./components/shared/Header.vue";
import Footer from "./components/shared/Footer.vue";
import ServerDetails from "./components/server/ServerDetails.vue";
export default {
  components: {
    MainApp,
    Server,
    Header,
    Footer,
    ServerDetails,
  },
};
</script>

<style>
p {
  text-align: center;
}
</style>
