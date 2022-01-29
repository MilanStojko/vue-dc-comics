<template>
  <main>
    <div class="jumbotron"></div>
    <div class="container">
      <div class="containercomic">
        <h2>CURRENT SERIES</h2>
        <Comic v-for="(comic, index) in comics" :key="index" :comics="comic" />
      </div>
    </div>
  </main>
</template>

<script>
import Comic from "../components/commons/comic.vue";
import comicdata from "../assets/data/comic-data.json";

export default {
  name: "Main",
  components: {
    Comic,
  },
  data() {
    return {
      comics: comicdata,
    };
  },
};
</script>

<style lang="scss" scoped>
@import "../assets/style/global.scss";

.jumbotron {
  height: 450px;
  background-image: url("../assets/img/jumbotron.jpg");
  background-size: cover;
}
main {
  background-color: #1c1c1c;

  div {
    min-height: 200px;

    h1 {
      color: white;
    }
  }
}
.containercomic {
  padding: 100px 0;
  position: relative;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 50px 30px;
  h2 {
    position: absolute;
    background-color: $mainColor;
    width: max-content;
    padding: 10px 25px;
    top: -20px;
    left: -20px;
  }
}
</style>