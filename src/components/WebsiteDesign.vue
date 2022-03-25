<template>
  <div class="website__design">
    <div class="container">
      <div class="estimate__title">
        <span>Website Design</span>
      </div>
      <div class="website__design-box">
        <div class="website__design-box__top">
          <div class="estimate__subTitle">
            <span> Sele‍‍‍ct a style</span>
          </div>
          <div class="row">
            <div class="col-md-12">
              <div
                class="
                  website__design-sele‍‍‍ct__style
                  d-flex
                  align-items-center
                  justify-content-between
                "
              >
                <p>simple template</p>
                <p>complex custom</p>
              </div>
              <div class="range__slider">
                <div class="options">
                  <input
                    class="slider w-100"
                    type="range"
                    min="1000"
                    max="10000"
                    step="1000"
                    list="steplist"
                    v-model="value_1"
                  />
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="website__design-box__bottom">
          <div class="row">
            <div class="col-md-12 d-flex">
              <div>
                <p>Number of page</p>
              </div>
              <div class="range__slider w-100">
                <div class="options">
                  <input
                    class="slider w-100"
                    type="range"
                    min="0"
                    max="25"
                    step="5"           
                    v-model="value_2"
                  />

                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="design-cost d-flex justify-content-end align-items-center">
          <div class="estimate__subTitle d-flex align-items-center">
            <span> Design Cost:</span>
            <div class="ms-4 total__sum">Rs.{{ total }}</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: "WebsiteDesign",
  data() {
    return {
      value_1: "1000",
      value_2: "1000",
    };
  },
  computed: {
    total() {
      return parseInt(this.value_1) * parseInt(this.value_2);
    },
  },
  
};

</script>