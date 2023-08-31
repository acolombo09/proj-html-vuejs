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

    <div class="footer-upper py-3 bg-dark">
      <div class="row row-cols-md-4 py-5 my-3">
        <div class="col-md-9 d-flex justify-content-evenly align-items-center mx-auto">
          <div class="col border border-light mx-4 text-light bg-secondary">
            <p class="text-light">© 2023</p>
          </div>
          <div class="col d-flex justify-content-center border border-light mx-4 text-light bg-secondary">
            <div class="div">
              <h5 class="mb-3">About</h5>
              <ul class="nav flex-column">
                <li class="nav-item mb-2" v-for="link in AboutLinks">
                  <a href="#" class="nav-link p-0 text-decoration-none text-light">> {{ link.name }}</a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col d-flex justify-content-center border border-light mx-4 text-light bg-secondary">
            <div class="div">
              <h5 class="mb-3">Services</h5>
              <ul class="nav flex-column">
                <li class="nav-item mb-2" v-for="link in ServicesLinks">
                  <a href="#" class="nav-link p-0 text-decoration-none text-light">> {{ link.name }}</a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col d-flex justify-content-center border border-light mx-4 text-light bg-secondary">
            <div class="div">
              <h5 class="mb-3">Support</h5>
              <ul class="nav flex-column">
                <li class="nav-item mb-2" v-for="link in SupportLinks">
                  <a href="#" class="nav-link p-0 text-decoration-none text-light">> {{ link.name }}</a>
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

</style>