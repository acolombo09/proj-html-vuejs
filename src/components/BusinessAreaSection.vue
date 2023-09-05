<script>

export default {
  data() {
    return {
      
    };
  },
};
</script>

<template>
  <!-- Cards section business areas -->
  <div class="px-4 py-5" style="background-color: #eef4ed;">
    <div class="col-md-9 mx-auto my-5">
      <div class="cards-heading d-flex justify-content-between">
        <div class="col-9 d-flex flex-column align-content-end">
          <h6 class="pb-2 fw-bold text-success text-icons-color">OUR BUSINESS AREAS</h6>
          <h2 class="pb-2 fw-bold">Excellence in <mark class="highlight-text">Services</mark></h2>
          <p class="lead text-secondary mb-0">
            We are leaders in providing consultancy services with a set of cutting-edge technologies
            and a team of experience and renowned professionals. These are some options that you can hire.
          </p>
        </div>
        <div class="col-3 d-flex justify-content-end align-items-end">
          <button class="btn btn-success px-4 rounded-1 custom-button">SEE ALL</button>
        </div>
      </div>
      <div class="row row-cols-3 g-4 py-5">
        <div class="col">
          <div class="card card-cover h-100 overflow-hidden rounded-3 arrow-container">
            <div class="d-flex flex-column h-100 p-5">
              <ul class="d-flex list-unstyled mt-auto">
                <li class="me-auto">
                  <img src="../assets/svgs/svg-1.svg" width="39" height="39" alt="svg-1">
                </li>
                <li class="d-flex align-items-center">
                  <a href="#"><i class="fa-solid fa-arrow-right fs-4 arrow-icon" style="color: #82c1c1;"></i></a>
                </li>
              </ul>
              <h4 class="pt-3 mb-4 fw-bold">Audit & Assurance</h4>
              <p class="lead text-secondary">
                Lorem ipsum dolor sit amet consectetur adipiscing elit.
              </p>
            </div>
            <div class="circle"></div>
          </div>
        </div>

        <div class="col">
          <div class="card card-cover h-100 overflow-hidden rounded-3 arrow-container">
            <div class="d-flex flex-column h-100 p-5">
              <ul class="d-flex list-unstyled mt-auto">
                <li class="me-auto">
                  <img src="../assets/svgs/svg-2.svg" width="39" height="39" alt="svg-2">
                </li>
                <li class="d-flex align-items-center">
                  <a href="#"><i class="fa-solid fa-arrow-right fs-4 arrow-icon" style="color: #82c1c1;"></i></a>
                </li>
              </ul>
              <h4 class="pt-3 mb-4 fw-bold">Audit & Assurance</h4>
              <p class="lead text-secondary">
                Lorem ipsum dolor sit amet consectetur adipiscing elit.
              </p>
            </div>
            <div class="circle"></div>
          </div>
        </div>

        <div class="col">
          <div class="card card-cover h-100 overflow-hidden rounded-3 arrow-container">
            <div class="d-flex flex-column h-100 p-5">
              <ul class="d-flex list-unstyled mt-auto">
                <li class="me-auto">
                  <img src="../assets/svgs/svg-3.svg" width="39" height="39" alt="svg-3">
                </li>
                <li class="d-flex align-items-center">
                  <a href="#"><i class="fa-solid fa-arrow-right fs-4 arrow-icon" style="color: #82c1c1;"></i></a>
                </li>
              </ul>
              <h4 class="pt-3 mb-4 fw-bold">Audit & Assurance</h4>
              <p class="lead text-secondary">
                Lorem ipsum dolor sit amet consectetur adipiscing elit.
              </p>
            </div>
            <div class="circle"></div>
          </div>
        </div>

        <div class="col">
          <div class="card card-cover h-100 overflow-hidden rounded-3 arrow-container">
            <div class="d-flex flex-column h-100 p-5">
              <ul class="d-flex list-unstyled mt-auto">
                <li class="me-auto">
                  <img src="../assets/svgs/svg-4.svg" width="39" height="39" alt="svg-4">
                </li>
                <li class="d-flex align-items-center">
                  <a href="#"><i class="fa-solid fa-arrow-right fs-4 arrow-icon" style="color: #82c1c1;"></i></a>
                </li>
              </ul>
              <h4 class="pt-3 mb-4 fw-bold">Audit & Assurance</h4>
              <p class="lead text-secondary">
                Lorem ipsum dolor sit amet consectetur adipiscing elit.
              </p>
            </div>
            <div class="circle"></div>
          </div>
        </div>

        <div class="col">
          <div class="card card-cover h-100 overflow-hidden rounded-3 arrow-container">
            <div class="d-flex flex-column h-100 p-5">
              <ul class="d-flex list-unstyled mt-auto">
                <li class="me-auto">
                  <img src="../assets/svgs/svg-5.svg" width="39" height="39" alt="svg-5">
                </li>
                <li class="d-flex align-items-center">
                  <a href="#"><i class="fa-solid fa-arrow-right fs-4 arrow-icon" style="color: #82c1c1;"></i></a>
                </li>
              </ul>
              <h4 class="pt-3 mb-4 fw-bold">Audit & Assurance</h4>
              <p class="lead text-secondary">
                Lorem ipsum dolor sit amet consectetur adipiscing elit.
              </p>
            </div>
            <div class="circle"></div>
          </div>
        </div>

        <div class="col">
          <div class="card card-cover h-100 overflow-hidden rounded-3 arrow-container">
            <div class="d-flex flex-column h-100 p-5">
              <ul class="d-flex list-unstyled mt-auto">
                <li class="me-auto">
                  <img src="../assets/svgs/svg-6.svg" width="39" height="39" alt="svg-6">
                </li>
                <li class="d-flex align-items-center">
                  <a href="#"><i class="fa-solid fa-arrow-right fs-4 arrow-icon" style="color: #82c1c1;"></i></a>
                </li>
              </ul>
              <h4 class="pt-3 mb-4 fw-bold">Audit & Assurance</h4>
              <p class="lead text-secondary">
                Lorem ipsum dolor sit amet consectetur adipiscing elit.
              </p>
            </div>
            <div class="circle"></div>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>

@use "../styles/partials/variables" as *;

.card img {
  fill: $text-icons-color;
}

.text-icons-color {
  color: $text-icons-color !important;
}

.highlight-text {
  background-color: rgba(#00A6A6, 0.2);
  color: $main-color;
}

.custom-button {
  background-color: $text-icons-color !important;
  color: white !important;
  border: none !important;
}

.arrow-container:hover .circle {
  opacity: 1;
  z-index: 1;
}

.arrow-container:hover .arrow-icon {
  color: $highlight-bg-color;
  z-index: 2;
}

.arrow-container .circle {
  position: absolute;
  top: 22%;
  right: 5%;
  transform: translate(-50%, -50%);
  width: 40px;
  height: 40px;
  background-color: $highlight-bg-color;
  border-radius: 50%;
  opacity: 0;
  transition: opacity 0.3s ease-in-out;
}

.arrow-container .arrow-icon {
  position: relative;
  z-index: 2;
  color: $text-icons-color;
}

</style>