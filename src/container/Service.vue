<template>
  <section id="service" class="section__padding">
    <div class="section__title d-flex align-items-center flex-column">
      <h3 class="title">Services</h3>
      <p class="sub-title">
        AO brings your all bussiness requirement at one place. We help you to
        communicate and grow business online.
      </p>
    </div>
    <div class="service__content">
      <div class="container">
        <div class="row d-flex align-items-start">
          <div class="col-md-3">
            <div
              class="nav flex-column nav-pills me-3"
              id="v-pills-tab"
              role="tablist"
              aria-orientation="vertical"
            >
              <button
                class="nav-link active"
                id="v-pills-home-tab"
                data-bs-toggle="pill"
                data-bs-target="#v-pills-home"
                type="button"
                role="tab"
                aria-controls="v-pills-home"
                aria-selected="true"
              >
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn__left">
                    <i class="fas fa-file-invoice me-2"></i>Invoice
                  </div>

                  <i class="fas fa-chevron-right"></i>
                </div>
              </button>
              <button
                class="nav-link"
                id="v-pills-home-tab"
                data-bs-toggle="pill"
                data-bs-target="#v-pills-home"
                type="button"
                role="tab"
                aria-controls="v-pills-home"
                aria-selected="true"
              >
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn__left">
                    <i class="fas fa-calendar-check me-2"></i>Appointment
                  </div>

                  <i class="fas fa-chevron-right"></i>
                </div>
              </button>
              <button
                class="nav-link"
                id="v-pills-home-tab"
                data-bs-toggle="pill"
                data-bs-target="#v-pills-home"
                type="button"
                role="tab"
                aria-controls="v-pills-home"
                aria-selected="true"
              >
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn__left">
                    <i class="fas fa-file-invoice me-2"></i>Banner
                  </div>

                  <i class="fas fa-chevron-right"></i>
                </div>
              </button>
              <button
                class="nav-link"
                id="v-pills-home-tab"
                data-bs-toggle="pill"
                data-bs-target="#v-pills-home"
                type="button"
                role="tab"
                aria-controls="v-pills-home"
                aria-selected="true"
              >
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn__left">
                    <i class="fab fa-rocketchat me-2"></i>Chat
                  </div>

                  <i class="fas fa-chevron-right"></i>
                </div>
              </button>
              <button
                class="nav-link"
                id="v-pills-home-tab"
                data-bs-toggle="pill"
                data-bs-target="#v-pills-home"
                type="button"
                role="tab"
                aria-controls="v-pills-home"
                aria-selected="true"
              >
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn__left">
                    <i class="fas fa-edit me-2"></i>Pages
                  </div>

                  <i class="fas fa-chevron-right"></i>
                </div>
              </button>
              <button
                class="nav-link"
                id="v-pills-home-tab"
                data-bs-toggle="pill"
                data-bs-target="#v-pills-home"
                type="button"
                role="tab"
                aria-controls="v-pills-home"
                aria-selected="true"
              >
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn__left">
                    <i class="fas fa-store me-2"></i>Store
                  </div>

                  <i class="fas fa-chevron-right"></i>
                </div>
              </button>
            </div>
          </div>
          <div class="col-md-9">
            <div class="tab-content" id="v-pills-tabContent">
              <div
                class="tab-pane fade show active"
                id="v-pills-home"
                role="tabpanel"
                aria-labelledby="v-pills-home-tab"
              >
                <div class="service__tab-content-inner">
                  <div class="row d-flex align-items-center g-md-0 g-lg-0">
                    <div class="col-md-4 d-flex justify-content-center">
                      <img src="../assets/images/mobile.svg" alt="" />
                    </div>
                    <div class="col-md-8">
                      <div class="service__tab-contetn-des">
                        <h6>AO Invoice</h6>
                        <p>
                          Lorem ipsum dolor sit amet, consectetur adipiscing
                          elit. Pretium aliquam feugiat gravida id nunc
                          convallis massa fringilla. Id fringilla
                        </p>
                        <br />
                        <p>
                          Lorem ipsum dolor sit amet, consectetur adipiscing
                          elit. Pretium aliquam feugiat gravida id nunc
                          convallis massa fringilla. Id fringilla ornare ut id
                          pellentesque tortor enm.
                          Lorem ipsum dolor sit amet, consectetur adipiscing
                          elit. Pretium aliquam feugiat gravida id nunc
                          convallis massa fringilla. Id fringilla ornare ut id
                          pellentesque tortor enm.
                          convallis massa fringilla. Id fringilla ornare ut id
                          pellentesque tortor enm.
                        </p>

                        <button class=" btn learn-more">Learn More  <i class="fas fa-chevron-right"></i></button>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div
                class="tab-pane fade"
                id="v-pills-profile"
                role="tabpanel"
                aria-labelledby="v-pills-profile-tab"
              >
                ...
              </div>
              <div
                class="tab-pane fade"
                id="v-pills-messages"
                role="tabpanel"
                aria-labelledby="v-pills-messages-tab"
              >
                ...
              </div>
              <div
                class="tab-pane fade"
                id="v-pills-settings"
                role="tabpanel"
                aria-labelledby="v-pills-settings-tab"
              >
                ...
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Service",
};
</script>