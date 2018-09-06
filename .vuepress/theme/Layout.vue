<template>
  <div>
    <Header :title="$site.title" :description="$site.description" />
    <Body />
  </div>
</template>

<script>
import Header from "../components/Header.vue";
import Body from "../components/Body.vue";

export default {
  components: {
    Header,
    Body
  },
  data: function() {
    return {};
  }
};
</script>

<style lang="scss" scoped>
</style>
