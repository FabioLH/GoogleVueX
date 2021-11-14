<template>
  <div class="home">
    <img class="google-logo" alt="Google" src="../assets/googlelogo.png">
    <Body msg=""/>
  </div>
</template>

<script>
// @ is an alias to /src
import Body from "@/components/Body.vue";

export default {
  name: "Home",
  components: {
    Body,
  },
};
</script>

<style scoped>
.home {
  border: 0px solid blue;
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  align-content: center;
}
.google-logo {
  width: 272px;
  height: 92px;
  border: 0px solid red;
  margin-top: 15px;
}
</style>
