<script>

export default {
  data() {
    return {
      projectsLinks: [
        { name: "ALL"},
        { name: "INSTITUTIONAL"},
        { name: "SOCIAL"},
        { name: "EVENTS"},
        { name: "INNOVATION"},
        { name: "ENVIRONMENT"},
        { name: "TECHNOLOGY"},
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
  <!-- Cards section Portfolio actions & Projects -->
  <div class="px-4 py-5 my-5 bg-white">
    <div class="col-md-9 mx-auto my-4">
      <div class="d-flex flex-column justify-content-center align-items-center">
        <h6 class="pb-2 fw-semibold text-icons-color">WE DO MORE FOR EVERYONE</h6>
        <h2 class="pb-2 mb-3 display-4 fw-bold text-body-emphasis">Actions & <mark class="highlight-text">Projects</mark></h2>
        <ul class="nav nav-pills">
          <li class="nav-item me-3" v-for="link in projectsLinks">
            <a href="#" class="nav-link text-secondary"
              v-bind:class="{ 'nav-link-hover': isHovered }" 
              @mouseover="handleMouseOver" 
              @mouseout="handleMouseOut">{{link.name}}</a>
          </li>
        </ul>
      </div>
      
      <div class="row row-cols-3 g-4 my-3">
        <div class="col">
          <div class="card rounded-3" style="background-image: url('../assets/images/project-1.jpg');">
            <div class="overlay"></div>
            <div class="d-flex flex-column justify-content-end h-100 p-5 pb-3">
              <h4 class="mb-5 fw-bold text-white" style="position: relative; z-index: 2;">Academic professional program in social media</h4>
            </div>
          </div>
        </div>

        <div class="col">
          <div class="card rounded-3" style="background-image: url('../assets/images/project-2.jpg');">
            <div class="overlay"></div>
            <div class="d-flex flex-column justify-content-end h-100 p-5 pb-3">
              <h4 class="mb-5 fw-bold text-white" style="position: relative; z-index: 2;">President's speech at the annual meeting</h4>
            </div>
          </div>
        </div>

        <div class="col">
          <div class="card rounded-3" style="background-image: url('../assets/images/project-3.jpg');">
            <div class="overlay"></div>
            <div class="d-flex flex-column justify-content-end h-100 p-5 pb-3">
              <h4 class="mb-5 fw-bold text-white" style="position: relative; z-index: 2;">International business trip in Shanghai</h4>
            </div>
          </div>
        </div>

        <div class="col">
          <div class="card rounded-3" style="background-image: url('../assets/images/project-4.jpg');">
            <div class="overlay"></div>
            <div class="d-flex flex-column justify-content-end h-100 p-5 pb-3">
              <h4 class="mb-5 fw-bold text-white" style="position: relative; z-index: 2;">Technology workshop with education theme</h4>
            </div>
          </div>
        </div>

        <div class="col">
          <div class="card rounded-3" style="background-image: url('../assets/images/project-5.jpg');">
            <div class="overlay"></div>
            <div class="d-flex flex-column justify-content-end h-100 p-5 pb-3">
              <h4 class="mb-5 fw-bold text-white" style="position: relative; z-index: 2;">Donation of clothes and food to the partner NGO</h4>
            </div>
          </div>
        </div>

        <div class="col">
          <div class="card rounded-3" style="background-image: url('../assets/images/project-6.jpg');">
            <div class="overlay"></div>
            <div class="d-flex flex-column justify-content-end h-100 p-5 pb-3">
              <h4 class="mb-5 fw-bold text-white" style="position: relative; z-index: 2;">Confraternization of the procurement team</h4>
            </div>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>

@use "../styles/partials/variables" as *;


.card {
  border: none;
  background-size: cover;
  background-position: center;
  width: 390px;
  aspect-ratio: 1/1; 
  position: relative;
  overflow: hidden;
}

.overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.5);
  opacity: 1;
}

.highlight-text {
  background-color: rgba(#00A6A6, 0.2);
  color: $main-color;
}

// .hover-content {
//   display: none; /* Nascondi il contenuto all'inizio */
//   position: absolute;
//   top: 0;
//   left: 0;
//   width: 100%;
//   height: 100%;
//   flex-direction: column;
//   justify-content: center;
//   align-items: center;
//   background-color: rgba(0, 0, 0, 0.8); /* Sfondo nero trasparente */
// }

// .card:hover .hover-content {
//   display: flex; /* Mostra il contenuto all'hover */
//   flex-direction: column;
//   justify-content: center;
//   align-items: center;
// }


.nav-link-hover:hover {
  background-color: rgba(#00A6A6, 0.2) !important;
  color: $text-icons-color !important;
}

.text-icons-color {
  color: $text-icons-color !important;
}

</style>