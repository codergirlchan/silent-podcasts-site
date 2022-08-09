<template>
  <section>
    <video loop autoplay muted>
      <source src="../assets/sp-intro.mp4" type="video/mp4" />
      Sorry, your browser doesn't support embedded videos.
    </video>
    <div class="header-wrapper">
      <h1>We're anything but Silent</h1>
    </div>
  </section>
</template>

<style scoped>
video {
  width: 100%;
  display: block;
}
h1 {
  text-transform: uppercase;
  font-family: impact;
  color: black;
  text-align: center;
  font-size: 42px;
}
.header-wrapper {
  width: 100%;
  background: #ffd900;
  font-size: 42px;
  padding: 40px 0;
}
</style>
