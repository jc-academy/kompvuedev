<template>
  <header class="header">
    <h1>{{ title }}</h1>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: {
    title: String
  }
}
</script>

<style scoped>
.header {
  background-color: #40b1e5;
  color: white;
  padding: 10px 0;
  text-align: center;
}
</style>