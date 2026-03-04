<script setup>
    import Header from "./components/Header.vue"
    import Card from "./components/Card.vue"
    import Footer from "./components/Footer.vue"
</script>

<template>
  <Header title="jCoders Academy"/>
  <div class="cardcontainer">
    <Card title="Agon Gashi" content="Trainer"/>
    <Card title="Albert Zenuni" content="Trainer"/>
    <Card title="Alketa Abazi" content="Trainer"/>
    <Card title="Andi Cakolli" content="Trainer"/>
    <Card title="Armela Hajra" content="Trainer"/>
    <Card title="Blina Islamaj" content="Trainer"/>
    <Card title="Bujar Bushi" content="Trainer"/>
    <Card title="Edon Abdullahu" content="Trainer"/>
    <Card title="Elena Muhaxheri" content="Trainer"/>
    <Card title="Enis Thaqi" content="Trainer"/>
    <Card title="Erolinda Shabani" content="Trainer"/>
    <Card title="Fatlume Zekaj" content="Trainer"/>
    <Card title="Finesa Berisha" content="Trainer"/>
    <Card title="Florent Sahiti" content="Trainer"/>
    <Card title="Florinda Hasani" content="Trainer"/>
  </div>
  <Footer />
</template>

<style>
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  .cardcontainer{
    width: 100%;
    display: grid;
    padding: 10px 0;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    grid-gap: 10px;
    justify-content: center;
  }
</style>
