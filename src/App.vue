<template>
  <Header></Header>
  <Service></Service>
  <Delivery></Delivery>
  <RangeValue></RangeValue>
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
</template>

<script>
import Header from "./components/Header.vue";
import Service from "./container/Service.vue";
import Delivery from "./container/Delivery.vue";
import RangeValue from "./container/RangeValue.vue";
export default {
  name: "App",
  components: {
    Header,
    Service,
    Delivery,
    RangeValue
  },
};
</script>



