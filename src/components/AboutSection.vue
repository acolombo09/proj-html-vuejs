<script>

export default {
  data() {
    return {
      
    };
  },
};
</script>

<template>
  <!-- About section The Company -->
  <div class="about-section px-4 py-5" style="background-color: #111117;">
    <div class="col-md-9 mx-auto my-5">
      <div class="row flex-lg-row justify-content-center align-items-center g-5">
        <div class="col-md-6">
          <h5 class="fw-bold text-icons-color lh-1 mb-3">ABOUT THE NETWORK</h5>
          <h2 class="display-5 fw-bold text-white lh-1 mb-3"><mark class="highlight-text">The</mark> Company</h2>
          <p class="mt-4 lead text-secondary">For 12 years we have been providing audit and warranty, financial advice, 
            risk advice, taxes and related services to select clients.
          </p>
          
          <div class="col my-5">
            <div class="row row-cols-1 row-cols-sm-2 g-4">
              <div class="col d-flex flex-column gap-2">
                <div class="d-flex align-items-center">
                  <div class="d-inline-flex align-items-center justify-content-center me-2 fs-5 rounded-3 text-icons-color">
                    <i class="fa-solid fa-award"></i>
                  </div>
                  <h4 class="fw-semibold mb-0 text-white">Tradition</h4>
                </div>
                <p class="text-secondary">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
              </div>
              <div class="col d-flex flex-column gap-2">
                <div class="d-flex align-items-center">
                  <div class="d-inline-flex align-items-center justify-content-center me-2 fs-5 rounded-3 text-icons-color">
                    <i class="fa-solid fa-lock"></i>
                  </div>
                  <h4 class="fw-semibold mb-0 text-white">Security</h4>
                </div>
                <p class="text-secondary">Lorem ipsum dolor sit amet consectetur adipiscing elit..</p>
              </div>
              <div class="col d-flex flex-column gap-2">
                <div class="d-flex align-items-center">
                  <div class="d-inline-flex align-items-center justify-content-center me-2 fs-5 rounded-3 text-icons-color">
                    <i class="fa-regular fa-pen-to-square"></i>
                  </div>
                  <h4 class="fw-semibold mb-0 text-white">Certificate</h4>
                </div>
                <p class="text-secondary">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
              </div>
              <div class="col d-flex flex-column gap-2">
                <div class="d-flex align-items-center">
                  <div class="d-inline-flex align-items-center justify-content-center me-2 fs-5 rounded-3 text-icons-color">
                    <i class="fa-solid fa-graduation-cap fa-flip-horizontal"></i>
                  </div>
                  <h4 class="fw-semibold mb-0 text-white">Expertise</h4>
                </div>
                <p class="text-secondary">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
              </div>
            </div>
          </div>

          <div class="d-grid gap-2 d-md-flex justify-content-md-start">
            <button type="button" class="btn btn-outline-light text-icons-color border border-icons-color px-4 me-3 custom-button-hover">GET IN TOUCH</button>
            <button type="button" class="btn btn-outline-light text-icons-color border border-icons-color px-4 custom-button-hover">READ MORE</button>
          </div>
        </div>
        <div class="col-md-6">
          
        </div>
      </div>
    </div>
    <img src="../assets/svgs/svg-0.svg" class="bullets top" alt="bullets">
    <img src="../assets/svgs/svg-0.svg" class="bullets bottom" alt="bullets">
  </div>
</template>

<style lang="scss" scoped>

@use "../styles/partials/variables" as *;

.about-section {
  background: 
    linear-gradient(to left, transparent 50%, #111117 50%), 
    url(../assets/images/about-4.jpg) no-repeat right center; 
  object-fit: contain;
  min-height: 100vh; 
  background-position: center right;
  position: relative;
}

.text-icons-color {
  color: $text-icons-color !important;
}

.header-footer-color {
  color: $header-footer-text-color !important;
}

.border-icons-color {
  border-color: $text-icons-color !important;
}

.custom-button {
  background-color: $text-icons-color !important;
  color: white !important;
  border: none !important;
}

.custom-button-hover:hover {
  background-color: $text-icons-color !important;
  color: white !important;
  border: none !important;
}

.highlight-text {
  background-color: rgba(#00A6A6, 0.2); 
  color: inherit; 
}

.bullets {
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
  filter: invert(27%) sepia(73%) saturate(1915%) hue-rotate(169deg) brightness(88%) contrast(87%) opacity(0.3);
}

.top {
  top: -27px;
}

.bottom {
  bottom: -72px;
}



</style>