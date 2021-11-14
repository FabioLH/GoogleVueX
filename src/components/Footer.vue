<template>
    <div class="footer">
        <div class="div1">
            <div class="advertising" v-on:click="about" >Advertising</div>
            <div class="business" v-on:click="store">Business</div>
            <div class="how" v-on:click="store">How Search works</div>
        </div>
        <div class="div2">
            <div class="carbon" v-on:click="about" >Carbon neutral since 2007</div>
        </div>
        <div class="div3">
            <div class="privacy" v-on:click="about" >Privacy</div>
            <div class="terms" v-on:click="store">Terms</div>
            <div class="settings" v-on:click="store">Settings</div>
        </div>
    </div>
</template>

<script>

export default {
// setup() {
// },
  methods: {
    about() {
      window.location.href = "";
    },
    store() {
      window.location.href = "";
    },
    gmail() {
      window.location.href = "";
    },
    images() {
      window.location.href = "h";
    },
    user() {
      window.location.href = "";
    },
  },
};

</script>

<style lang="scss" scoped>
.footer {
    width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    flex-wrap: wrap;
}
.div1 {
    display: flex;
    padding-top: 16px;
    padding-bottom: 16px;
    flex-wrap: wrap;
    width: 27%;
    margin-left: 5px;
}
.div2 {
    display: flex;
    text-align: center;
    flex-wrap: wrap;
    padding-top: 16px;
    padding-bottom: 16px;
    width: 23.5%;
    background-image: url("../assets/leaf.png");
    background-size: 15px;
    background-position: 0% 44%;
    background-repeat: no-repeat;
}
.div3 {
    display: flex;
    padding-top: 16px;
    padding-bottom: 16px;
    flex-wrap: wrap;
    justify-content: flex-end;
    width: 18%;
    margin-right: 5px;
}
.advertising {
    cursor: pointer;
    margin-left: 30px;
}
.business {
    cursor: pointer;
    margin-left: 30px;
}
.how {
    cursor: pointer;
    margin-left: 30px;
}
.carbon {
    cursor: pointer;
    margin-left: 20px;
}
.privacy {
    cursor: pointer;
    margin-right: 30px;
}
.terms {
    cursor: pointer;
    margin-right: 30px;
}
.settings {
    cursor: pointer;
    margin-right: 30px;
}
</style>
