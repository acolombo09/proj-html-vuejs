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
  <div class="hero-bg">
    <div class="second-bg"></div> <!-- Secondo sfondo sotto tutto -->
    <div class="parallax-bg"></div> <!-- Immagine parallax-bg sopra il secondo sfondo -->
    <div class="content"> <!-- Contenuto sopra tutto -->
      <div class="header-bottom pt-3">
        <div class="row">
          <div class="col-md-9 d-flex align-items-center justify-content-between mx-auto px-0">
            <img src="../assets/logo.PNG" alt="nexgen-logo-header">
            <ul class="nav nav-pills">
              <li class="nav-item me-3" v-for="link in navLinks">
                <a href="#" class="nav-link">{{link.name}}</a>
              </li>
              <li class="nav-item me-3">
                <a href="#" class="nav-link active rounded-1">GET IN TOUCH</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="px-4 py-5 text-center">
        <div class="col-md-4 pt-5 mx-auto d-flex flex-column justify-content-center align-items-center">
          <h2 class="display-4 pt-5 fw-bold text-body-emphasis">Ready Team</h2>
          <p class="lead mb-4">No matter what your company needs, we will be ready to assist you in the best possible way.</p>
          <div class="d-grid gap-2 d-sm-flex justify-content-center mb-5">
            <button type="button" class="btn btn-success px-4 me-sm-3 rounded-1">GET IN TOUCH</button>
            <button type="button" class="btn btn-outline-success px-4 rounded-1">READ MORE</button>
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

</style>