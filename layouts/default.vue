<template>
  <div>
    <div>
      <b-navbar toggleable="lg" type="light" variant="light">
        <b-navbar-brand class="font-weight-bold" href="#">Po's Gallery</b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav class="font-weight-bold">
            <b-nav-item to="/" exact exact-active-class="active"
              >Home</b-nav-item
            >
            <!-- <b-nav-item to="/about" exact exact-active-class="active"
              >About</b-nav-item
            > -->
            <b-nav-item to="/gallery/2020" exact exact-active-class="active"
              >Gallery</b-nav-item
            >
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
    <Nuxt />
    <div class="p-5 bg-light font-weight-bold">All photos copyrights reserved by Po YZ.</div>
  </div>
</template>

<style></style>
