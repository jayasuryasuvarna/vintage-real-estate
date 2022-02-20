<template>
  <v-app>
    <v-app-bar app color="white" flat>
      <Header />
    </v-app-bar>
    <v-main>
      <Carousel />
      <Introduction />
    </v-main>
  </v-app>
</template>
<script>
import Header from "./components/Header";
import Carousel from "./components/Carousel.vue";
import Introduction from "./components/Introduction.vue";

export default {
  name: "App",

  components: {
    Header,
    Carousel,
    Introduction,
  },

  data: () => ({}),
};
</script>
