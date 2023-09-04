<script>
export default {
  data() {
    return {
      AboutLinks: [
        { name: "The Company"},
        { name: "Institutional" },
        { name: "Social & Events"},
        { name: "Innovation"},
        { name: "Environment"},
        { name: "Technology"},
        ],
      ServicesLinks:[
        { name: "Audit & Assurance"},
        { name: "Financial Advisory" },
        { name: "Analytics M&A"},
        { name: "Middle Marketing"},
        { name: "Legal Consulting"},
        { name: "Regulatory Risk"},
        ],
      SupportLinks:[
        { name: "Responsibility"},
        { name: "Terms of Use" },
        { name: "About Cookies"},
        { name: "Privacy Policy"},
        { name: "Accessibility"},
        { name: "Information"},
        ],
    };
  },
}
</script>

<template>
  <footer>

    <div class="footer-upper py-3" style="background-color: #111117;">
      <div class="row row-cols-md-4 py-5 my-3">
        <div class="col-md-9 d-flex justify-content-evenly align-items-center mx-auto">
          <div class="col mx-4 text-light">
            <div class="p-4">
              <div class="mb-3">
                <img src="../assets/logo.PNG" alt="nexgen-logo-footer">
                <p class="text-secondary my-4">
                  A Functional HTML Template for Corporate & Business
                </p>
              </div>
              <div class="dbox w-100 d-flex align-items-start my-2">
                <div class="icon d-flex align-items-center justify-content-center">
                  <i class="fa-solid fa-phone"></i>
                </div>
                <div class="ms-4">
                  <a href="#">
                    <p class="d-inline-block text-secondary">+1 (305) 1234-5678</p>
                  </a>
                </div>
              </div>
              <div class="dbox w-100 d-flex align-items-start my-2">
                <div class="icon d-flex align-items-center justify-content-center">
                  <i class="fa-solid fa-envelope"></i>
                </div>
                <div class="ms-4">
                  <a href="#">
                    <p class="d-inline-block text-secondary">hello@example.com</p>
                  </a>
                </div>
              </div>
              <div class="dbox w-100 d-flex align-items-start my-2">
                <div class="icon d-flex align-items-center justify-content-center">
                  <i class="fa-solid fa-location-dot"></i>
                </div>
                <div class="ms-4">
                  <a href="#">
                    <p class="d-inline-block text-secondary">Main Avenue, 987</p>
                  </a>
                </div>
              </div>
              <div class="dbox w-100 d-flex align-items-start my-2">
                <button type="button" class="btn btn-outline-success px-4 rounded-1">GET IN TOUCH</button>
              </div>
            </div>
          </div>
          <div class="col d-flex justify-content-center mx-4 py-5 text-light" style="background-color: #19191f;">
            <div class="div">
              <h5 class="mb-3 fw-bold">About</h5>
              <ul class="nav flex-column">
                <li class="nav-item mb-2" v-for="link in AboutLinks">
                  <a href="#" class="nav-link p-0 text-decoration-none text-secondary">> {{ link.name }}</a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col d-flex justify-content-center mx-4 py-5 text-light" style="background-color: #19191f;">
            <div class="div">
              <h5 class="mb-3 fw-bold">Services</h5>
              <ul class="nav flex-column">
                <li class="nav-item mb-2" v-for="link in ServicesLinks">
                  <a href="#" class="nav-link p-0 text-decoration-none text-secondary">> {{ link.name }}</a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col d-flex justify-content-center mx-4 py-5 text-light" style="background-color: #19191f;">
            <div class="div">
              <h5 class="mb-3 fw-bold">Support</h5>
              <ul class="nav flex-column">
                <li class="nav-item mb-2" v-for="link in SupportLinks">
                  <a href="#" class="nav-link p-0 text-decoration-none text-secondary">> {{ link.name }}</a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="footer-bottom py-3 bg-black">
      <div class="row">
        <div class="col-md-9 d-flex justify-content-between align-items-center mx-auto px-0">
          <p class="col-md-4 mb-0 text-light">Enjoy the low price. We are tracking any intention of piracy.</p>
          <div class="col-md-4 mb-0 d-flex justify-content-end align-items-center">
            <p class="mb-0 text-light">&copy; 2020 NEXGEN is Proudly Powered by</p>
            <a href="#" class="nav-link text-success ms-1">Codings.</a>
          </div>
          
        </div>
      </div>
    </div>

  </footer>
</template>

<style lang="scss" scoped>

@use "../styles/partials/variables" as *;

.footer-upper img {
  width: 150px;
}

</style>