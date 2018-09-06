<template>
  <div>
    <h1>{{ title }}</h1>
    <h3>{{ description }}</h3>
  </div>
</template>

<script>
export default {
  props: {
    title: String,
    description: String
  }
};
</script>

<style lang="scss" scoped>
</style>
