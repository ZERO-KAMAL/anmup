<template>
  <section id="estimate__pricing" class="section__padding">
    <div class="section__title d-flex align-items-center flex-column">
      <h3 class="title">Let’s Estimate Pricing</h3>
      <p class="sub-title">
        You can estimate you pricing for your requirements all by yourself.
        Contact us for further discount and discussion.
      </p>
    </div>

    <div class="estimate__pricing-content">
      <WebsiteDesign></WebsiteDesign>
    </div>
  </section>
</template>

<script>
import WebsiteDesign from "@/components/WebsiteDesign.vue";
export default {
  components: { WebsiteDesign },
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Estimate",
};
</script>
