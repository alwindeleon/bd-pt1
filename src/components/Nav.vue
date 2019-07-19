<template>
  <nav class="navbar navbar-light bg-light justify-content-between">
    <a class="navbar-brand"><img src="../assets/images/logo.png" alt="logo" class="logo"></a>
    <!-- <div class="collapse navbar-collapse" id="navbarNavAltMarkup"> -->
    <div class="inline">
      <div class="nav-item nav-link active" href="#">ABOUT</div>
      <div class="nav-item nav-link" href="#">OUR FOOD</div>
      <div class="nav-item nav-link" href="#">PLANS</div>
      <div class="nav-item nav-link btn-contact" href="#" >CONTACT US</div>
    </div>
  </div>
  </nav>
</template>

<script>
export default {
}
</script>

<style scoped>
.inline * {
  display: inline-block;
}

.navbar {
  background: rgba(256,256,256,0) !important;
  padding-top: 2rem;
  z-index: 10;
}

.nav-item {
  color: white;
  opacity: 0.7;
  font-weight: bold;
  margin: 0 2.5rem;
}


.active {
  opacity: 1;
  border-bottom: 3px solid #f8a22f;
  padding-bottom: 0;
}

.btn-contact {
  background-color: #f8a22f;
    color: white;
    padding: 0.5rem 2rem;
    border-radius: 600px;
    opacity: 1;
}

.logo {
  width: 11rem;
  margin-left: 5.5rem;
}
</style>
