<template>
  <div class="container">
    <HeaderBlock />
    <AcceptCookies />
  </div>
</template>

<script>
import HeaderBlock from "@/components/HeaderBlock/HeaderBlock.vue";
import AcceptCookies from "@/components/AcceptCookies/AcceptCookies.vue";

export default {
  name: "HomePage",
  data() {
    return {
      isChecked: false,
    };
  },
  methods: {},
  components: {
    HeaderBlock,
    AcceptCookies,
  },
};
</script>

<style lang="scss" scoped></style>
