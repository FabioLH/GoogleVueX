<template>
    <div class="root-div">
        <div class="div2">
            <div class="about" v-on:click="about">About</div>
            <div class="store" v-on:click="store">Store</div>
        </div>

        <div class="div3">
            <div class="gmail" v-on:click="gmail">Gmail</div>
            <div class="images" v-on:click="images">Images</div>
            <img class="dots" src="https://cdn-icons-png.flaticon.com/512/17/17704.png" alt="">
            <img class="account" v-on:click="user" src="https://cdn-icons-png.flaticon.com/512/147/147144.png" alt="">
        </div>
    </div>
</template>

<script>

export default {
// setup() {
// },
  methods: {
    about() {
      window.location.href = "https://about.google/?fg=1&utm_source=google-US&utm_medium=referral&utm_campaign=hp-header";
    },
    store() {
      window.location.href = "https://store.google.com/US?utm_source=hp_header&utm_medium=google_ooo&utm_campaign=GS100042&hl=en-US";
    },
    gmail() {
      window.location.href = "https://accounts.google.com/signin/v2/identifier?service=mail&passive=true&rm=false&continue=https%3A%2F%2Fmail.google.com%2Fmail%2F%26ogbl%2F&ss=1&scc=1&ltmpl=default&ltmplcache=2&emr=1&osid=1&flowName=GlifWebSignIn&flowEntry=ServiceLogin";
    },
    images() {
      window.location.href = "https://www.google.com.br/imghp?hl=en&authuser=0&ogbl";
    },
    user() {
      window.location.href = "https://accounts.google.com/signin/v2/identifier?hl=pt-BR&passive=true&continue=https%3A%2F%2Fwww.google.com.br%2F%3Fgws_rd%3Dssl&ec=GAZAmgQ&flowName=GlifWebSignIn&flowEntry=ServiceLogin";
    },
  },
};

</script>

<style lang="scss" scoped>
.root-div {
    display: flex;
    font-family: sans-serif;
    flex-direction: row;
    justify-content: space-between;
    font-size: 14px;
    width: 100%;
}
.div2 {
    display: flex;
    flex-direction: row;
}
.div3 {
    display: flex;
    flex-direction: row;
    font-size: 13px;
}
.about {
    margin-top: 22px;
    margin-left: 26px;
    cursor: pointer;
}
.store {
    margin-top: 22px;
    margin-left: 20px;
    cursor: pointer;
}
.gmail {
    margin-right: 15px;
    margin-top: 22.5px;
    cursor: pointer;
}
.images {
    margin-right: 31px;
    margin-top: 22.5px;
    cursor: pointer;
}
.dots {
    cursor: pointer;
    width: 16px;
    height: 16px;
    margin-top: 22px;
    margin-right: 23px;
    cursor: pointer;
}
.account {
    width: 33px;
    height: 33px;
    margin-top: 12px;
    margin-right: 18px;
    cursor: pointer;
}

</style>
