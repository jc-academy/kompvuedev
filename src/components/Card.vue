<template>
  <div class="card">
    <h2>{{ title }}</h2>
    <p>{{ content }}</p>
  </div>
</template>

<script>
export default {
  name: "Card",
  props: {
    title: String,
    content: String
  }
}
</script>

<style scoped>
.card {
  border: 1px solid #ddd;
  padding: 15px;
  border-radius: 8px;
  display: inline-block;
  text-align: center;
  transition: box-shadow 0.5s;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

  &:hover{
    cursor: pointer;
    box-shadow: 0px 0px 5px 5px rgba(0,0,0,0.2);
  }
}
</style>