<template>
  <div>
    <div>
      <b-nav tabs>
        <b-nav-item to="/" exact exact-active-class="active">Home</b-nav-item>
        <b-nav-item to="/about" exact exact-active-class="active">About</b-nav-item>
        <b-nav-item>Another Link</b-nav-item>
        <b-nav-item disabled>Disabled</b-nav-item>
      </b-nav>
    </div>
    <Nuxt />
  </div>
</template>
