<template>
  <Header></Header>
  <Service></Service>
  <Delivery></Delivery>
  <!-- <RangeValue></RangeValue> -->
  <Estimate></Estimate>
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
</template>

<script>

import Header from "./components/Header.vue";
import Service from "./container/Service.vue";
import Delivery from "./container/Delivery.vue";
// import RangeValue from "./container/RangeValue.vue";
import Estimate from "./container/Estimate.vue";

export default {
  name: "App",
  components: {
    Header,
    Service,
    Delivery,
    // RangeValue,
    Estimate,
  },
};
</script>
