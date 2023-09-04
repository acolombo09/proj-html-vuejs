<script>

export default {
  data() {
    return {
      
    };
  },
};
</script>

<template>
  <!-- Results  & Sponsors Section -->
  <div class="results-section px-4 py-5">
    <div class="col-md-9 mx-auto my-5">
      <div class="d-flex flex-column justify-content-center align-items-center">
        <h6 class="pb-2 text-success">WHAT ARE WE DOING</h6>
        <h2 class="pb-2 text-white fw-bold">Results in Numbers</h2>
      </div>
      <div class="row row-cols-md-4 g-4 py-5 justify-content-center">
          <div class="col d-flex flex-column justify-content-center align-items-center">
            <h3 class="fw-bold mb-3 fs-4 text-success">128</h3>
            <h6 class="fw-bold text-white">Certifications</h6>
          </div>
          <div class="col d-flex flex-column justify-content-center align-items-center">
            <h3 class="fw-bold mb-3 fs-4 text-success">230</h3>
            <h6 class="fw-bold text-white">Employees</h6>
          </div>
          <div class="col d-flex flex-column justify-content-center align-items-center">
            <h3 class="fw-bold mb-3 fs-4 text-success">517</h3>
            <h6 class="fw-bold text-white">Customers</h6>
          </div>
          <div class="col d-flex flex-column justify-content-center align-items-center">
            <h3 class="fw-bold mb-3 fs-4 text-success">94</h3>
            <h6 class="fw-bold text-white">Countries Served</h6>
          </div>
        </div>
    </div>
  </div>
  <!-- Sponsor div IN Results section -->
  <div class="sponsor-div px-4 py-5">
    <div class="container">
      <footer class="py-3">
        <ul class="nav justify-content-center align-items-center">
          <li class="nav-item">
            <a href="#" class="nav-link mx-3">
              <img src="../assets/images/logo-4.png" alt="jquery">
            </a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link mx-3">
              <img src="../assets/images/logo-5.png" alt="less">
            </a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link mx-3">
              <img src="../assets/images/logo-1.png" alt="woocommerce">
            </a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link mx-3">
              <img src="../assets/images/logo-2.png" alt="wordpress">
            </a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link mx-3">
              <img src="../assets/images/logo-3.png" alt="pingdom">
            </a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link mx-3">
              <img src="../assets/images/logo-4.png" alt="jquery2">
            </a>
          </li>
        </ul>
      </footer>
    </div>
  </div>
</template>

<style lang="scss" scoped>

@use "../styles/partials/variables" as *;

.results-section {
  background-image: url('../assets/images/bg-7.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  min-height: 60vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

.sponsor-div {
  background-color: #111117;

  .nav-item a img {
  width: 90px;
  height: auto;
  }
}


</style>