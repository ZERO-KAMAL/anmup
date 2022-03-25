<template>
  <section id="delivery" class="section__padding">
    <div class="section__title d-flex align-items-center flex-column">
      <h3 class="title">Platform Designed For You</h3>
    </div>

    <div class="delivery__content">
      <div class="container">
        <div class="row">
          <div
            class="col-md-3"
            :key="delivery.id"
            v-for="delivery in deliveries"
          >
            <div class="delivery__box h-100">
              <div class="delivery__box-img">
                <img :src="delivery.image" :alt="delivery.title" />
              </div>
              <div class="delivery__box-content">
                <h4>{{ delivery.title }}</h4>
                <p>{{ delivery.des }}</p>
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
  data() {
    return {
      deliveries: [
        {
          id: 1,
          title: "24 hour support",
          des: "We are available 24/7 to support your businesss",
          image: require("../assets/images/feature.svg"),
        },
        {
          id: 2,
          title: "Easy to customize",
          image: require("../assets/images/feature-1.svg"),
          des: "AO can be customize on your own and using your own branding.",
        },
        {
          id: 3,
          title: "Ease of use",
          image: require("../assets/images/feature-2.svg"),
          des: "AO is responsive and  is available for all device.",
        },
        {
          id: 4,
          title: "AO Coins",
          image: require("../assets/images/feature-3.svg"),
          des: "We provide 100 coins for our new user.  Learn More ",
        },
      ],
    };
  },
};
</script>
