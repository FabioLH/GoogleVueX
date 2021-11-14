<template>
<div class="body">
  <div>
    <input type="text" class="search"
    v-bind:style="{boxShadow:bgColor}" @mouseout="hoverOut()" @mouseover="hoverIn()">
    <img alt="Mic" class="mic" src="../assets/Mic.png">
  </div>
  <div class="div2">
    <button class="button" v-bind:style="{boxShadow:bgColor2}"
    @mouseout="hoverOut2()" @mouseover="hoverIn2()">Google Search</button>
    <button class="button" v-bind:style="{boxShadow:bgColor3}"
    @mouseout="hoverOut3()" @mouseover="hoverIn3()">I'm Feeling Lucky</button>
  </div>
  <div class="div3">
    <span class="span1">Google offered in:</span>
    <span class="span2">Português (Brasil)</span>
  </div>
</div>
</template>

<script>
export default {
  name: "Body",
  props: {
    msg: String,
  },
  data() {
    return {
      bgColor: "",
      bgColor2: "",
      bgColor3: "",
    };
  },
  methods: {
    hoverIn() {
      this.bgColor = "0px 0px 3px 0px #c5c5c5";
    },
    hoverOut() {
      this.bgColor = "none";
    },
    hoverIn2() {
      this.bgColor2 = "0px 0px 1px 0px";
    },
    hoverOut2() {
      this.bgColor2 = "none";
    },
    hoverIn3() {
      this.bgColor3 = "0px 0px 1px 0px";
    },
    hoverOut3() {
      this.bgColor3 = "none";
    },
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.body {
  border: 0px solid black;
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.div2 {
  border: 0px solid black;
  margin-top: 0px;
  width: 100%;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  padding: 0px;
}
.div3 {
  border: 0px solid black;
  margin-top: 23.5px;
  width: 100%;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  padding: 0px;
}
.search {
  outline: none;
  border-radius: 50px;
  border: 1px solid #ece8e8;
  padding: 12px;
  background: white;
  margin-top: 0px;
  height: 20px;
  width: 37.7vw;
  padding-left: 50px;
  padding-right: 50px;
  margin-top: 25px;
  background-image: url("../assets/lupa.png");
  background-repeat: no-repeat;
  background-position: 1.9% 48%;
  background-size: 27px;
}
.mic {
  width: 14px;
  height: 20px;
  position: absolute;
  margin-top: 39px;
  margin-left: -36px;
  cursor: pointer;
}
.button {
  outline: none;
  border-radius: 3px;
  border: 0px solid #d1d1d1;
  background-color: #f8f8f8;
  font-family: sans-serif;
  font-size: 14px;
  padding: 10px;
  padding-left: 17px;
  padding-right: 17px;
  margin: 6px;
  cursor: pointer;
  margin-top: 30px;
}
.span1 {
  font-family: sans-serif;
  font-size: 13px;
  margin-right: 6.8px;
}
.span2 {
  font-family: sans-serif;
  font-size: 13px;
  cursor: pointer;
  color: rgb(0, 0, 248);
  margin-right: 3.2px;
}
</style>
