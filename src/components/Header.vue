<template>
    <div class="root-div">
        <div class="div2">
            <a class="about" href="https://about.google/?fg=1&utm_source=google-US&utm_medium=referral&utm_campaign=hp-header">About</a>
            <a class="store" href="https://store.google.com/US?utm_source=hp_header&utm_medium=google_ooo&utm_campaign=GS100042&hl=en-US">Store</a>
        </div>

        <div class="div3">
            <a class="gmail" href="">Gmail</a>
            <a class="images" href="">Images</a>
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
    text-decoration: none;
    color: #000000;
}
.about:hover {
    text-decoration: underline;
}
.store {
    margin-top: 22px;
    margin-left: 20px;
    cursor: pointer;
    text-decoration: none;
    color: #000000;
}
.store:hover {
    text-decoration: underline;
}
.gmail {
    margin-right: 15px;
    margin-top: 22.5px;
    cursor: pointer;
    text-decoration: none;
    color: #000000;
}
.gmail:hover {
    text-decoration: underline;
}
.images {
    margin-right: 31px;
    margin-top: 22.5px;
    cursor: pointer;
    text-decoration: none;
    color: #000000;
}
.images:hover {
    text-decoration: underline;
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
