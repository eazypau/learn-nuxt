<template>
  <div>
    <div class="p-5">
      <div>
        <h1>Photo Collections</h1>
        <hr />
      </div>
      <div class="d-flex align-items-start flex-wrap">
        <a class="text-dark text-decoration-none" href="/gallery/2020">
          <b-card
            title="2020"
            img-src="~/assets/sunset2.jpg"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 20rem; cursor: pointer"
            class="mb-5 mr-5 targetImg"
          >
            <b-card-text> Highlights on my short trip in Miri. </b-card-text>
          </b-card>
        </a>

        <a class="text-dark text-decoration-none" href="/gallery/2019">
          <b-card
            title="2019"
            img-src="~/assets/grad.jpg"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 20rem; cursor: pointer"
            class="mb-5 mr-5 targetImg"
          >
            <b-card-text>
              Final year
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="currentColor"
                class="bi bi-arrow-right"
                viewBox="0 0 16 16"
              >
                <path
                  fill-rule="evenodd"
                  d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8z"
                />
              </svg>
              Graduation
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="currentColor"
                class="bi bi-arrow-right"
                viewBox="0 0 16 16"
              >
                <path
                  fill-rule="evenodd"
                  d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8z"
                />
              </svg>
              Working.
            </b-card-text>
          </b-card>
        </a>
        <a class="text-dark text-decoration-none" href="/gallery/2018">
          <b-card
            title="2018"
            img-src="~/assets/jump.jpg"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 20rem; cursor: pointer"
            class="mb-5 targetImg"
          >
            <b-card-text> During my delta year in university. </b-card-text>
          </b-card>
        </a>
      </div>
      <div>
        <h3>Photo viewer:</h3>
        <hr />
        <!-- <NuxtLink to="/gallery/2020">To child component...</NuxtLink> -->
        <NuxtChild />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // data() {
  //   return {
  //     collections: [
  //       {
  //         collectionTitle: '2020',
  //         src: '~/assets/sunset.jpg',
  //         collectionDescription: 'Highlights on my short trip in Miri.',
  //       },
  //       {
  //         collectionTitle: '2019',
  //         src: '~/assets/sunset.jpg',
  //         collectionDescription:
  //           'Graduated from university and started working.',
  //       },
  //       {
  //         collectionTitle: '2018',
  //         src: '~/assets/sunset.jpg',
  //         collectionDescription: 'During my delta year in university.',
  //       },
  //     ],
  //   }
  // },
}
</script>

<style>
.targetImg img {
  max-height: 250px;
}
.targetImg:hover {
  box-shadow: 5px 10px 18px #888888;
  transition: 0.5s ease-out;
}
</style>
