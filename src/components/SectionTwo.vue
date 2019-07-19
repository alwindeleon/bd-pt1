<template>
  <div class="section-two">
    <img src="../assets/images/pizza-woodtable-2.png" alt="woodtable" class="section-two__bg">
    <img src="../assets/images/woodtable-accessory-2.png" alt="woodtable" class="section-two__bg__accessory">
    <div class="section-one__right">
      <h2 class="section-one__right__main">OUR FOOD</h2>
      <hr class="bar"> 
      <div class="section-two__right__item">
        <img src="../assets/images/plus.png" alt="plus" class="inline plus">
        <div class="divider inline">
          <h4 class="item__title">Signature Pizzas</h4>
          <span class="item__description">Choose one of our plans, enter delivery time.</span>
        </div>
      </div>
      <div class="section-two__right__item">
        <img src="../assets/images/plus.png" alt="plus" class="inline plus">
        <div class="divider inline">
          <h4 class="item__title">Oven-Baked Subs</h4>
          <span class="item__description">Choose one of our plans, enter delivery time
            and enjoy delicious food without leaving your home!
          </span>
        </div>
      </div>
      <div class="section-two__right__item">
        <img src="../assets/images/plus.png" alt="plus" class="inline plus">
        <div class="divider inline">
          <h4 class="item__title">Wings, Sides & More</h4>
          <span class="item__description">Choose one of our plans, enter delivery time.</span>
        </div>
      </div>
    <button class="btn btn-custom">Order Food</button>
    </div>
  </div>
</template>

<style scoped>
.section-two {
  width: 95vw;
  height: 100vh;
} 

.section-two__bg {
  width: 50vw;
  height: 75vh;
  position: absolute;
  top: 115%;
}

.section-two__bg__accessory{
  height: 75vh;
  position: absolute;
  top: 115%;
  z-index: 10;
}

.section-one__right {
  float: right;
  width: 40vw;
  margin-top: 7%;
  margin-right: 4rem;
}

.section-one__right__main {
  font-family: Baloo;
  color: #242424;
  font-size: 2.5rem;
  text-align: left;
  margin-left: 7rem;
}

.bar  {
  max-width: 12rem;
  max-height: 0;
  border: 3px solid #f8a22f;
  margin-right: 13rem;
  margin-top: 0rem;
}

.inline {
  display: inline-block;
}

.section-two__right__item {
  margin-top: 2rem;
  margin-left: 21%;
  width: 30rem;
}

.item__title {
  color: #242424;
  font-family: Raleway;
  font-size: 1.5rem;
  font-weight: 600;
  line-height: 3rem;
}

.item__description {
  opacity: 0.5;
  color: #242424;
  font-family: Raleway;
  font-size: 1rem;
  font-weight: 400;
  display: block;
  width: 21rem;
}
.plus {
  float: left;
  display: inline-block;
}

.divider {
  margin-left: 1rem;
  display: inline-block;
}

.btn-custom {
   background-color: #f8a22f;
    color: white;
    padding: 0.5rem 2.5rem;
    margin-top: 2rem;
    border-radius: 600px;
    margin-left: 7rem;
}
</style>