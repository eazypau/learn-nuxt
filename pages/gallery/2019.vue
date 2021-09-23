<template>
  <div class="overflow-auto d-flex flex-column align-items-center">
    <!-- <p class="mt-3">Current Page: {{ currentPage }}</p> -->

    <b-img
      id="myImg"
      :src="items[currentPage - 1].src"
      :per-page="perPage"
      :current-page="currentPage"
      fluid
      alt="Responsive image"
      class="imgWidth"
    ></b-img>

    <b-pagination
      v-model="currentPage"
      :total-rows="rows"
      :per-page="perPage"
      aria-controls="myImg"
      class="mt-3"
    ></b-pagination>
  </div>
</template>

<script>
export default {
  data() {
    return {
      perPage: 1,
      currentPage: 1,
      items: [
        { id: 1, src: require("~/assets/grad.jpg") },
        { id: 2, src: require("~/assets/2019/photo2.jpg") },
        { id: 3, src: require("~/assets/2019/photo3.jpg") },
        { id: 4, src: require("~/assets/2019/photo4.jpg") },
        { id: 5, src: require("~/assets/2019/photo5.jpg") },
        { id: 6, src: require("~/assets/2019/photo1.jpg") },
      ],
    }
  },
  computed: {
    rows() {
      return this.items.length
    },
  },
}
</script>

<style>
.imgWidth {
    /* max-width: 60%; */
    max-height: 80vh;
}
</style>
