<template>
  <div class="carouselBlock">
    <v-carousel hide-delimiters cycle show-arrows-on-hover>
      <v-carousel-item
        v-for="(item, i) in items"
        :key="i"
        :src="item.src"
        reverse-transition="fade-transition"
        transition="fade-transition"
      >
        <v-row class="fill-height title" align="center" justify="center">
          <div class="text-h2">{{ item.title }}</div>
        </v-row>
      </v-carousel-item>
    </v-carousel>
  </div>
</template>
<script>
export default {
  name: "Carousel",
  data() {
    return {
      items: [
        {
          src: require("../assets/carousel/image1.jpeg"),
          title: "We Are Professional",
        },
        {
          src: require("../assets/carousel/image2.jpeg"),
          title: "We Work Harder",
        },
        {
          src: require("../assets/carousel/image3.jpeg"),
          title: "We Are Professional",
        },
        {
          src: require("../assets/carousel/image4.jpeg"),
          title: "We Work Harder",
        },
        {
          src: require("../assets/carousel/image5.jpeg"),
          title: "We Work Harder",
        },
        {
          src: require("../assets/carousel/image6.jpeg"),
          title: "We Are Professional",
        },
        {
          src: require("../assets/carousel/image7.jpeg"),
          title: "We Work Harder",
        },
        {
          src: require("../assets/carousel/image8.jpeg"),
          title: "We Are Professional",
        },
        {
          src: require("../assets/carousel/image9.jpeg"),
          title: "We Work Harder",
        },
        {
          src: require("../assets/carousel/image10.jpeg"),
          title: "We Are Professional",
        },
        {
          src: require("../assets/carousel/image11.jpeg"),
          title: "We Work Harder",
        },
      ],
    };
  },
};
</script>
