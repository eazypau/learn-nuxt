<template>
  <div>
    <div class="content">
      <b-carousel
        id="carousel-fade"
        style="text-shadow: 0px 0px 2px #000"
        fade
        indicators
        img-width="1120"
        img-height="504"
        class="imageContainer"
      >
        <b-carousel-slide
          caption="Green Field"
          img-src="../assets/photo1.jpg"
        ></b-carousel-slide>
        <b-carousel-slide
          caption="City Of Clouds"
          img-src="../assets/photo2.jpg"
        ></b-carousel-slide>
        <b-carousel-slide
          caption="Big Blue Sky"
          img-src="../assets/photo3.jpg"
        ></b-carousel-slide>
      </b-carousel>
    </div>
    <div class="content">
      <div class="py-5 px-3 contentWidth">
        <h1>Hi there!</h1>
        <hr />
        <p class="text-justify text-break">
          There is a personal project of mine dedicated to show some of the
          photos that I have taken over the pass few years. Before you continue,
          I would highly recommend you read the website from your
          <strong>tablet/computer/laptop</strong>.
        </p>
        <p class="text-justify text-break">
          As you can see in the carousel. Those are the photos that I have taken
          recently at
          <a
            style="text-decoration: underline"
            target="_blank"
            href="https://www.google.com/maps/place/Malacca+Sand+Dunes/@2.2053566,102.1853731,17z/data=!3m1!4b1!4m5!3m4!1s0x31d1f11e5efb7615:0x40a2d1236788831e!8m2!3d2.2053512!4d102.1875618"
            >Klebang Sand Dune</a
          >
          on 16th September 2021 (Malaysia Day). You may refer to the
          <a
            style="text-decoration: underline"
            target="_blank"
            href="https://pokokkelapa.wordpress.com/2017/10/16/white-sand-dunes-pantai-klebang-melaka/comment-page-1/"
            >guide</a
          >
          here if you are planning to go there some day.
        </p>
        <br />
        <p>Here are some of my favorites.</p>
        <div>
          <!-- <b-img
            src="../assets/photo5.jpg"
            fluid
            alt="Responsive image"
          ></b-img>
          <p class="text-center pt-2 photoCaption">
            The person in the photo is my friend. We went to Klebang Melaka Sand
            Dune together during that day.
          </p> -->
          <b-jumbotron class="shadow-lg">
            <b-container>
              <b-row>
                <!-- <b-col
                  ><p class="pt-2 photoCaption bg-white p-2 rounded">
                    The person in the photo is my friend. We went to Klebang
                    Melaka Sand Dune together during that day.
                  </p></b-col
                > -->
                <b-col
                  ><b-img
                    src="../assets/photo5.jpg"
                    fluid
                    alt="Responsive image"
                  ></b-img
                ></b-col>
              </b-row>
              <b-row
                ><b-col
                  ><p class="pt-2 photoCaption bg-white p-2 rounded">
                    The person in the photo is my friend. We went to Klebang
                    Melaka Sand Dune together during that day.
                  </p></b-col
                ></b-row
              >
            </b-container>
          </b-jumbotron>
        </div>
        <div class="mt-5">
          <b-jumbotron class="shadow-lg">
            <b-container>
              <b-row>
                <b-col
                  ><b-img
                    src="../assets/photo4.jpg"
                    fluid
                    alt="Responsive image"
                  ></b-img
                ></b-col>
              </b-row>
              <b-row
                ><b-col
                  ><p class="pt-2 photoCaption bg-white p-2 rounded">
                    This was taken around 7:00pm when we were about to go back.
                  </p></b-col
                ></b-row
              >
            </b-container>
          </b-jumbotron>

          <!-- <b-img
            src="../assets/photo4.jpg"
            fluid
            alt="Responsive image"
          ></b-img>
          <p class="text-center pt-2 photoCaption">
            This was taken around 7:00pm when we were about to go back.
          </p> -->
        </div>
        <div class="mt-5">
          <!-- <b-img
            src="../assets/photo6.jpg"
            fluid
            alt="Responsive image"
          ></b-img>
          <p class="text-center pt-2 photoCaption">
            This is me trying to act cool 😂
          </p> -->
          <b-jumbotron class="shadow-lg">
            <b-container>
              <b-row>
                <b-col
                  ><b-img
                    src="../assets/photo6.jpg"
                    fluid
                    alt="Responsive image"
                  ></b-img
                ></b-col>
              </b-row>
              <b-row>
                <b-col
                  ><p class="pt-2 photoCaption bg-white p-2 rounded">
                    This is me trying to act cool 😂
                  </p></b-col
                >
              </b-row>
            </b-container>
          </b-jumbotron>
        </div>
        <div>
          <p class="text-justify">
            That's about it for my little adventure at Klebang Sand Dune. If you
            want to see more photos, click
            <a href="/gallery/2020">here</a> or the gallery at the navigation bar to
            view other awesome photos.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.content {
  display: flex;
  align-items: center;
  flex-direction: column;
}
.imageContainer {
  max-width: 1280px;
  max-height: 576px;
}
@media (max-width: 1440px) {
  .imageContainer {
    max-width: 1120px;
    max-height: 504px;
  }
}
@media (max-width: 1024px) {
  .imageContainer {
    max-width: 896px;
    max-height: 403px;
  }
}
@media (max-width: 768px) {
  .imageContainer {
    max-width: 560px;
    max-height: 252px;
  }
}
.contentWidth {
  width: 60%;
}
@media (max-width: 1024px) {
  .contentWidth {
    width: 70%;
  }
}
@media (max-width: 768px) {
  .contentWidth {
    width: 75%;
  }
}
.screenHeight {
  height: 100vh;
}
.photoCaption {
  font-size: 14px;
  text-align: center;
  /* text-decoration: underline; */
}
/* body {
  background-color: #808080;
} */
</style>
