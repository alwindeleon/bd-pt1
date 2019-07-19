<template>
  <div class="contact-us">
    <h1 class="contact-us__main">Contact Us</h1>
    <hr class="bar">
    <form class="contact-us__form">
      <div class="form-group ">
        <input type="text" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Full Name">
      </div>
      <div class="form-group">
        <input type="Text" class="form-control" id="exampleInputPassword1" placeholder="Phone No">
      </div>
      <div class="form-group">
        <textarea class="form-control" id="exampleFormControlTextarea1" rows="3" placeholder="Message"></textarea>
      </div>
      <div class="form-check">
        <input type="checkbox" class="form-check-input" id="exampleCheck1">
        <label class="form-check-label cb-custom" for="exampleCheck1">I agree with all conditions</label>
      </div>
      
      <button type="submit" class="btn btn-primary btn-custom">Submit</button>
    </form>
  </div>
</template>

<style scoped>
.contact-us {
  width: 98.9vw;
  height: 100vh;
  background: url('../assets/images/gmaps-bg.png') no-repeat;
  background-position: 0 100%;
  background-size:100% 50%;
} 

.bar{
  height: 0px;
  width: 5rem;
  border: 3px #f8a22f solid;
  position: absolute;
  left: 5.5rem;
  margin-top: -0.3rem;
}

.contact-us__main {
  font-family: Baloo;
  color: #242424;
  margin-left: 5rem;
}

.contact-us__form {
  width: 20rem;
  margin-left: 5rem;
  margin-top: 5rem;
  background-color: #f8a22f;
  padding: 3rem;
  border-radius: 50px;
}

.btn-custom {
  color: #f8a22f;
  background-color: white;
  border: 0;
  width: 9rem;
  margin: 1rem auto;
  display: block;
}

.cb-custom {
  color: white;
}
</style>