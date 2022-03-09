<template>
  <TheInnerPageHead title="Blog List" />
  <TheWhy />
  <TheFooter />
</template>
<script>
import TheInnerPageHead from "@/components/TheInnerPageHead.vue";
import TheWhy from "@/components/TheWhy.vue";
import TheFooter from "@/components/TheFooter.vue";
export default {
  components: {
    TheInnerPageHead,
    TheWhy,
    TheFooter,
  },
};
</script>