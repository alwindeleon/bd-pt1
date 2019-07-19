<template>
  <div class="section-three">
    <h1 class="section-three__main">PLANS</h1>
    <hr class="bar">

    <div class="tabs">
      <div class="tab tab--left">
        <div class="left__descriptor"> FLAT <span class="highlight"> 20</span> <span class="highlight--two">%</span></div>
        <div class="left__descriptor--two">Min. Order Value ₹300 </div>
      </div>
      <div class="tab tab--right">
        <div class="right__descriptor right__descriptor--one">GET 2 MEDIUM</div>
        <div class="right__descriptor right__descriptor--two">PIZZA </div>
        <div class="right__descriptor right__descriptor--three">AT  ₹199 EACH </div>
      </div> 
    </div>
  </div>
</template>

<style scoped>
.section-three {
  width: 98.9vw;
  height: 100vh;
  background: url('../assets/images/pizza-bg.png') no-repeat;
  background-size: 100% 80%;
} 

.section-three__main {
  text-align: center;
  font-family: Baloo;
  padding-top: 6.5rem;
  font-size: 3.5rem;
}

.bar{
  height: 0px;
  width: 5rem;
  border: 3px white solid;
}

.tabs {
  width: 98.9vw;
  
}

.tab {
  width: 41%;
  height: 50vh;
  background-size: 95% 95% !important;

}

.tab--left {
  float: left;
  background: url('../assets/images/pizza-1.png') no-repeat;
  margin-left: 3.5rem;
}

.tab--right {
  float:right;
  background: url('../assets/images/pizza-2.png') no-repeat;
  margin-right: 3rem;
}

.highlight {
  color: #f8a22f;
  font-size: 4rem;
}


.highlight--two {
  color: #f8a22f;
  font-size: 1.5rem;
}

.left__descriptor {
  color: white;
  position: relative;
  top: 57%;
  left: -7%;
  font-family: Raleway;
  font-size: 1.5rem;
  text-align: right;
}

.left__descriptor--two {
  color: white;
  position: relative;
  top: 52%;
  left: -10%;
  font-family: Raleway;
  font-size: 1.5rem;
  text-align: right;
}


.right__descriptor {
  color: white;
  position: relative;
  font-family: Raleway;
  font-size: 1.5rem;
  text-align: left;
  top: 55%;
  left: 4%;
}


.right__descriptor--two {
  color: #f8a22f;
  font-weight: 500;
  font-size: 2rem;
}

</style>