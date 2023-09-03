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
  <div class="px-4 py-5 bg-black">
    <div class="col-md-9 mx-auto">
      <div class="row flex-lg-row-reverse align-items-center g-5">
        <div class="col-md-6">
          <img src="../assets/images/about-4.jpg" class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes" width="700" height="500" loading="lazy">
        </div>
        <div class="col-md-6">
          <h5 class="fw-bold text-success lh-1 mb-3">ABOUT THE NETWORK</h5>
          <h2 class="display-5 fw-bold text-white lh-1 mb-3">The Company</h2>
          <p class="lead text-white">For 12 years we have been providing audit and warranty, financial advice, 
            risk advice, taxes and related services to select clients.
          </p>
          
          <div class="col my-5">
            <div class="row row-cols-1 row-cols-sm-2 g-4">
              <div class="col d-flex flex-column gap-2">
                <div class="feature-icon-small d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-4 rounded-3">
                  <svg class="bi" width="1rem" height="1rem">
                    <use xlink:href="#collection"></use>
                  </svg>
                </div>
                <h4 class="fw-semibold mb-0 text-white">Tradition</h4>
                <p class="text-white">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
              </div>
              <div class="col d-flex flex-column gap-2">
                <div class="feature-icon-small d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-4 rounded-3">
                  <svg class="bi" width="1rem" height="1rem">
                    <use xlink:href="#gear-fill"></use>
                  </svg>
                </div>
                <h4 class="fw-semibold mb-0 text-white">Security</h4>
                <p class="text-white">Lorem ipsum dolor sit amet consectetur adipiscing elit..</p>
              </div>
              <div class="col d-flex flex-column gap-2">
                <div class="feature-icon-small d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-4 rounded-3">
                  <svg class="bi" width="1rem" height="1rem">
                    <use xlink:href="#speedometer"></use>
                  </svg>
                </div>
                <h4 class="fw-semibold mb-0 text-white">Certificate</h4>
                <p class="text-white">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
              </div>
              <div class="col d-flex flex-column gap-2">
                <div class="feature-icon-small d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-4 rounded-3">
                  <svg class="bi" width="1rem" height="1rem">
                    <use xlink:href="#table"></use>
                  </svg>
                </div>
                <h4 class="fw-semibold mb-0 text-white">Expertise</h4>
                <p class="text-white">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
              </div>
            </div>
          </div>

          <div class="d-grid gap-2 d-md-flex justify-content-md-start">
            <button type="button" class="btn btn-success btn-lg px-4 me-md-2">GET IN TOUCH</button>
            <button type="button" class="btn btn-outline-success btn-lg px-4">READ MORE</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>

@use "../styles/partials/variables" as *;



</style>