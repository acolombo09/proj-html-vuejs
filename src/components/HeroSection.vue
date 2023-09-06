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
        { name: "GET IN TOUCH"},
      ],
      isHovered: false,
    };
  },
  methods: {
    handleMouseOver() {
      this.isHovered = true;
    },
    handleMouseOut() {
      this.isHovered = false;
    },
  },
};
</script>

<template>
  <div class="hero-bg">
    <div class="second-bg"></div> <!-- Secondo sfondo sotto tutto -->
    <div class="parallax-bg"></div> <!-- Immagine parallax-bg sopra il secondo sfondo -->
    <div class="content"> <!-- Contenuto sopra tutto -->
      <div class="header-bottom pt-3">
        <div class="row">
          <div class="col-md-9 d-flex align-items-center justify-content-between mx-auto px-0">
            <a href="#">
              <img src="../assets/logo.PNG" alt="nexgen-logo-header">
            </a>
            <ul class="nav nav-pills">
              <li class="nav-item me-3" v-for="link in navLinks">
                <a href="#" class="nav-link text-header-secondary"
                v-bind:class="{ 'nav-link-hover': isHovered }" 
                @mouseover="handleMouseOver" 
                @mouseout="handleMouseOut">{{link.name}}</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="px-4 py-5 text-center">
        <div class="col-md-4 pt-5 mx-auto d-flex flex-column justify-content-center align-items-center">
          <h2 class="display-4 pt-5 mb-4 fw-bold text-body-emphasis">Ready <mark class="highlight-text">Team</mark></h2>
          <p class="lead mb-4 text-secondary">No matter what your company needs, we will be ready to assist you in the best possible way.</p>
          <div class="d-grid gap-2 d-sm-flex justify-content-center mb-5">
            <button type="button" class="btn btn-outline-light text-icons-color border border-icons-color px-4 me-3 custom-button-hover">GET IN TOUCH</button>
            <button type="button" class="btn btn-outline-light text-icons-color border border-icons-color px-4 custom-button-hover">READ MORE</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>

@use "../styles/partials/variables" as *;

.hero-bg {
  position: relative;
  height: 100vh;
  overflow: hidden; /* Nasconde il contenuto oltre l'altezza specificata */
}

.nav-link-hover:hover {
  background-color: $text-icons-color !important;
  color: white !important;
  border: none !important;
}

.second-bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: url(../assets/extra_imgs/second-bg.jpg) no-repeat center top;
  background-size: cover;
  z-index: 1; /* Posiziona sopra il contenuto */
}

.content {
  position: relative;
  /* Stile per il contenuto */
  z-index: 3; /* Posiziona sopra il secondo sfondo */
}

.parallax-bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: url(../assets/images/bg-parallax.png) no-repeat center top;
  background-size: cover;
  z-index: 2; /* Posiziona sopra il secondo sfondo, ma sotto il contenuto */
}

.header-bottom img {
  width: 150px;
}

.text-icons-color {
  color: $text-icons-color !important;
}

.header-footer-color {
  color: $header-footer-text-color !important;
}

.text-header-secondary {
  color: $text-color !important;
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
  color: $main-color;
}

</style>