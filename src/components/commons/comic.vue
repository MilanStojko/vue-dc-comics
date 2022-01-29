<template>
  <div class="comicwrapper">
    <img :src="comics.thumb" :alt="comics.series" />
    <h3>{{ comics.series }}</h3>
  </div>
</template>

<script>
export default {
  name: "Comic",
  props: {
    comics: Object,
  },
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/global.scss";

.comicwrapper {
  width: 200px;
  img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    object-position: 0 0;
  }
  h3{
      font-weight: normal;
      font-size: 0.9rem;
      padding: 10px 0;
      text-transform: uppercase;
  }
}
</style>