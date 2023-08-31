<script>
export default {
  data() {
    return {
      navLinks: [
        { name: "HOME"},
        { name: "SERVICES"},
        { name: "ABOUT"},
        { name: "PROJECTS"},
        { name: "RESULTS"},
      ],
    };
  },
};
</script>

<template>
  <header>

    <div class="header-top bg-dark py-2">
      <div class="row">
        <div class="col-md-9 d-flex flex-wrap justify-content-between align-items-center mx-auto px-0">
          <div class="col-md-4 d-flex align-items-center">
            <a href="#" class="mb-3 me-2 mb-md-0 text-body-secondary text-decoration-none lh-1">
              <i class="fa-solid fa-clock text-light"></i>
              <p class="ms-2 mb-3 mb-md-0 text-light d-inline-block">Open Hours: Mon - Sat - 9:00 - 18:00</p>
            </a>
          </div>
          <ul class="nav col-md-5 d-flex justify-content-evenly">
            <li class="ms-1">
              <a class="text-light" href="#">
                <i class="fa-solid fa-phone text-light"></i>
                <p class="ms-2 mb-0 text-light d-inline-block">+1 (305) 1234-5678</p>
              </a>
            </li>
            <li class="ms-1">
              <a class="text-light" href="#">
                <i class="fa-solid fa-envelope text-light"></i>
                <p class="ms-2 mb-0 text-light d-inline-block">hello@example.com</p>
              </a>
            </li>
            <li class="ms-1"><a class="text-light" href="#"><i class="fa-brands fa-facebook"></i></a></li>
            <li class="ms-1"><a class="text-light" href="#"><i class="fa-brands fa-twitter"></i></a></li>
            <li class="ms-1"><a class="text-light" href="#"><i class="fa-brands fa-linkedin"></i></a></li>
          </ul>
        </div>
      </div>
    </div>

    <div class="header-bottom bg-transparent py-3">
      <div class="row">
        <div class="col-md-9 d-flex align-items-center justify-content-between mx-auto px-0">
          <img src="../assets/logo.PNG" alt="nexgen-logo-header">
          <ul class="nav nav-pills">
            <li class="nav-item me-3" v-for="link in navLinks">
              <a href="#" class="nav-link">{{link.name}}</a>
            </li>
            <li class="nav-item me-3">
              <a href="#" class="nav-link active">GET IN TOUCH</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
    
  </header>
</template>

<style lang="scss" scoped>

@use "../styles/partials/variables" as *;

header img {
  width: 150px;
}

// header .nav-link {
//   color: black;
// }

// li {
//   position: relative;

// }

// li::after{
//   content: "";
//   position: absolute;
//   left: 0;
//   bottom: -2rem;
//   height: 5px;
//   width: 100%;
//   background-color: $color-primary;
//   scale: 0 1;
//   transition: scale 250ms;
// }

// li:hover::after{
//   scale: 1 1;
// }

// a:hover,
// a:focus-visible {
//   color: $color-primary;
// }

</style>