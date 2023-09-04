<script>

export default {
  data() {
    return {
      
    };
  },
};
</script>

<template>
  <!-- Contact Section -->
  <div class="px-4 py-5">
    <div class="col-md-9 mx-auto">
      <div class="row justify-content-center">
        <div class="col-lg-10 col-md-12">
          <div class="wrapper">
            <div class="row no-gutters">
              <div class="col-md-7 d-flex">
                <div class="contact-wrap w-100 p-5">
                  <div class="mb-4">
                    <h6 class="text-success mb-3 fw-bold">SEND A MESSAGE</h6>
                    <h2 class="mb-4 fw-bold">Get in Touch</h2>
                    <p class="text-secondary">
                      We will respond to your message as soon as possible.
                    </p>
                  </div>

                  <form method="POST" id="contactForm" name="contactForm" novalidate="novalidate">
                    <div class="row mt-5">
                      <div class="col-md-6 my-2">
                        <div class="form-group">
                        <input type="text" class="form-control rounded-1" name="name" id="name" placeholder="Name">
                        </div>
                      </div>
                      <div class="col-md-6 my-2">
                        <div class="form-group">
                          <input type="email" class="form-control rounded-1" name="email" id="email" placeholder="Email">
                        </div>
                      </div>
                      <div class="col-md-6 my-2">
                        <div class="form-group">
                          <input type="text" class="form-control rounded-1" name="phone" id="phone" placeholder="Phone">
                        </div>
                      </div>
                      <div class="col-md-6 my-2">
                        <div class="form-group">
                          <select class="form-select rounded-1" id="exampleSelect">
                            <option selected="">More Info</option>
                            <option value="1">One</option>
                            <option value="2">Two</option>
                            <option value="3">Three</option>
                          </select>
                        </div>
                      </div>
                      <div class="col-md-12 my-2">
                        <div class="form-group">
                          <textarea name="message" class="form-control rounded-1" id="message" cols="30" rows="7" placeholder="Message"></textarea>
                        </div>
                      </div>
                      <div class="col-md-12 my-2">
                        <div class="form-group">
                          <input type="submit" value="SEND" class="btn btn-success rounded-1">
                          <div class="submitting"></div>
                        </div>
                      </div>
                    </div>
                  </form>
                </div>
              </div>
              <div class="col-md-5 d-flex">
                <div class="info-wrap w-100 p-5">
                  <div class="mb-3">
                    <h3 class="mb-3 fw-bold">Example Inc.</h3>
                    <p class="text-secondary mb-4">
                      Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    </p>
                    <p class="text-secondary mb-5">
                      Praesent diam lacus, diapibus sed imperdiet consectetur.
                    </p>
                  </div>
                  
                  <div class="dbox w-100 d-flex align-items-start my-3">
                    <div class="icon d-flex align-items-center justify-content-center">
                      <i class="fa-solid fa-phone"></i>
                    </div>
                    <div class="ms-4">
                      <a href="#">
                        <p class="d-inline-block text-success">+1 (305) 1234-5678</p>
                      </a>
                    </div>
                  </div>
                  <div class="dbox w-100 d-flex align-items-start my-3">
                    <div class="icon d-flex align-items-center justify-content-center">
                      <i class="fa-solid fa-envelope"></i>
                    </div>
                    <div class="ms-4">
                      <a href="#">
                        <p class="d-inline-block text-success">hello@example.com</p>
                      </a>
                    </div>
                  </div>
                  <div class="dbox w-100 d-flex align-items-start my-3">
                    <div class="icon d-flex align-items-center justify-content-center">
                      <i class="fa-solid fa-location-dot"></i>
                    </div>
                    <div class="ms-4">
                      <a href="#">
                        <p class="d-inline-block text-success">Main Avenue, 987</p>
                      </a>
                    </div>
                  </div>
                  <div class="dbox w-100 d-flex align-items-start my-3">
                    <button type="button" class="btn btn-outline-success px-4 rounded-1">VIEW MAP</button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>

@use "../styles/partials/variables" as *;

.form-control, select {
  background-color: $form-bg-color;
}

</style>