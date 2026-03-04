<template>
  <footer class="footer">
    <p>{{ text }}</p>
  </footer>
</template>

<script>
export default {
  name: "Footer",
  props: {
    text: String
  }
}
</script>

<style scoped>
.footer {
  background: #333;
  color: white;
  padding: 10px 0;
  text-align: center;
}
</style>