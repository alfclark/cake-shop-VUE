<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
  <FooterComp />
</template>

<script>
// @ is an alias to /src
import FooterComp from "@/components/FooterComp.vue";

export default {
  name: "AboutView",
  components: {
    FooterComp,
  },
};
</script>

<style scoped>
.about {
  height: 90vh;
}
</style>
