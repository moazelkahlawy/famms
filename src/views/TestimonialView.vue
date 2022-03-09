<template>
  <TheInnerPageHead title="Testimonial" />
  <TheClient />
  <TheFooter />
</template>
<script>
import TheInnerPageHead from "@/components/TheInnerPageHead.vue";
import TheClient from "@/components/TheClient.vue";
import TheFooter from "@/components/TheFooter.vue";
export default {
  components: {
    TheInnerPageHead,
    TheClient,
    TheFooter,
  },
};
</script>
