<template>
  <div class="section-one">
      <img src="../assets/images/pizza-woodtable.png" alt="woodtable" class="section-one__bg">
      <img src="../assets/images/woodtable-accessory.png" alt="woodtable" class="section-one__bg-accessory">
      <div class="section-one__left">
        <h1 class="section-one__left__main"> Have no time <br> to prepare <span class="highlight">food</span> ?</h1>
        <p class="section-one__left__sub">Choose one of our plans, enter delivery time <br>
and enjoy delicious food without leaving your home!</p>
        <button class="btn btn-custom">Order Food</button>
        <img src="../assets/images/social-media.png" alt="social-media" class="img-social-media">
        <img src="../assets/images/scroll-down.png" alt="scroll" class="scroll-btn">
      </div>
    </div>
</template>

<style scoped>
.section-one {
  width: 95vw;
  height: 90vh;
}

.section-one__bg {
  width: 60vw;
  height: 94vh;
  position: absolute;
  text-align: right;
  right: 0%;
  top: 0;
  z-index: 0;
}

.section-one__bg-accessory {
  width: 60vw;
  height: 10vh;
  position: absolute;
  text-align: right;
  right: 0%;
  top: 0;
  z-index: 0;
}

.section-one__left {
  max-width: 60vw;
  display: block;
  float: left;
  margin-top: 9rem;
  margin-left: 5.5rem;
}

.section-one__left__main {
  font-family: Baloo;
  color: #242424;
  font-size: 3rem;
}

.section-one__left__sub {
  opacity: 0.5;
  color: #242424;
  font-family: Raleway;
  font-size: 1rem;
  font-weight: 400;
  line-height: 41px;
  margin-top: 2rem;
}

.highlight {
  color: #f8a22f;
}

.btn-custom {
    background-color: #f8a22f;
    color: white;
    padding: 0.5rem 2.5rem;
    margin-top: 2rem;
    border-radius: 600px;
}

.img-social-media {
  display: block;
  max-width: 20vw;
  position: absolute;
  bottom: 6%;
}

.scroll-btn {
  position: absolute;
  left: 50%;
  bottom: 3%;
  width: 1.5rem;
}
</style>