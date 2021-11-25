<template>
  <div class="root">
  <div class="r-header">
    <Header />
  </div>
  <div class="r-body"><router-view/>
  </div>
  <div class="r-footer">
    <Footer />
  </div>
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";

export default {
  components: {
    Header,
    Footer,
  },
};
</script>

<style lang="scss" scoped>
  .root {
    display: flex;
    flex-direction: column;
    height: 100vh;
    width: 100vw;
    background-color: white;
    position: relative;
  }
  .r-header {
    background-color: white;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin: 0px;
    position: relative;
  }
  .r-body {
    background-color: white;
    flex-grow: 1;
    border: 0px solid black;
  }
  .r-footer {
    border: 0px solid green;
    display: flex;
    font-family: sans-serif;
    font-size: 14px;
    width: 100%;
    color: #6e6e6e;
    background-color: #f0f0f0;
  }
</style>
