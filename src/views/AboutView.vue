<template>
  <TheInnerPageHead title="About us" />
  <TheWhy />
  <TheArrival />
  <TheFooter />
</template>
<script>
import TheInnerPageHead from "@/components/TheInnerPageHead.vue";
import TheWhy from "@/components/TheWhy.vue";
import TheArrival from "@/components/TheArrival.vue";
import TheFooter from "@/components/TheFooter.vue";
export default {
  components: {
    TheInnerPageHead,
    TheWhy,
    TheArrival,
    TheFooter
  },
};
</script>

