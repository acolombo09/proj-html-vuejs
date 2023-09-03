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
    <div class="col-md-9 mx-auto">
      <div class="row flex-lg-row-reverse align-items-center g-5">
        <div class="col-md-6">
          
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
                <div class="d-flex align-items-center">
                  <div class="d-inline-flex align-items-center justify-content-center me-2 fs-5 rounded-3">
                    <i class="fa-solid fa-award" style="color: #ffffff;"></i>
                  </div>
                  <h4 class="fw-semibold mb-0 text-white">Tradition</h4>
                </div>
                <p class="text-white">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
              </div>
              <div class="col d-flex flex-column gap-2">
                <div class="d-flex align-items-center">
                  <div class="d-inline-flex align-items-center justify-content-center me-2 fs-5 rounded-3">
                    <i class="fa-solid fa-lock" style="color: #ffffff;"></i>
                  </div>
                  <h4 class="fw-semibold mb-0 text-white">Security</h4>
                </div>
                <p class="text-white">Lorem ipsum dolor sit amet consectetur adipiscing elit..</p>
              </div>
              <div class="col d-flex flex-column gap-2">
                <div class="d-flex align-items-center">
                  <div class="d-inline-flex align-items-center justify-content-center me-2 fs-5 rounded-3">
                    <i class="fa-regular fa-pen-to-square" style="color: #ffffff;"></i>
                  </div>
                  <h4 class="fw-semibold mb-0 text-white">Certificate</h4>
                </div>
                <p class="text-white">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
              </div>
              <div class="col d-flex flex-column gap-2">
                <div class="d-flex align-items-center">
                  <div class="d-inline-flex align-items-center justify-content-center me-2 fs-5 rounded-3">
                    <i class="fa-solid fa-graduation-cap fa-flip-horizontal" style="color: #ffffff;"></i>
                  </div>
                  <h4 class="fw-semibold mb-0 text-white">Expertise</h4>
                </div>
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
    <!-- <img src="../assets/images/about-4.jpg" class="about-image" alt="Background Image"> -->
  </div>
</template>

<style lang="scss" scoped>

@use "../styles/partials/variables" as *;

.about-section {
  background: url(../assets/images/about-4.jpg) no-repeat center right; /* Imposta l'immagine come sfondo, posizionata al centro a destra */
  background-size: cover; /* Copre tutto lo sfondo */
  background-color: #111117; /* Colore di sfondo */
  min-height: 600px; /* Altezza minima del div */
  padding: 20px; /* Spazio interno */
}

</style>