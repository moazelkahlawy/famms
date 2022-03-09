<template>
  <TheInnerPageHead title="Product Grid" />
  <TheProduct />
  <TheFooter />
</template>
<script>
import TheInnerPageHead from "@/components/TheInnerPageHead.vue";
import TheProduct from "@/components/TheProduct.vue";
import TheFooter from "@/components/TheFooter.vue";
export default {
  components: {
    TheInnerPageHead,
    TheProduct,
    TheFooter,
  },
};
</script>