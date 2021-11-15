<template>
    <div class="footer">
        <div class="div1">
            <div class="advertising">Advertising</div>
            <div class="business">Business</div>
            <div class="how">How Search works</div>
        </div>
        <div class="div2">
            <div class="carbon">Carbon neutral since 2007</div>
        </div>
        <div class="div3">
            <div class="privacy">Privacy</div>
            <div class="terms">Terms</div>
            <div class="settings">Settings</div>
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
    text-decoration: none;
}
.advertising:hover {
    text-decoration: underline;
}
.business {
    cursor: pointer;
    margin-left: 30px;
    text-decoration: none;
}
.business:hover {
    text-decoration: underline;
}
.how {
    cursor: pointer;
    margin-left: 30px;
    text-decoration: none;
}
.how:hover {
    text-decoration: underline;
}
.carbon {
    cursor: pointer;
    margin-left: 20px;
    text-decoration: none;
}
.carbon:hover {
    text-decoration: underline;
}
.privacy {
    cursor: pointer;
    margin-right: 30px;
    text-decoration: none;
}
.privacy:hover {
    text-decoration: underline;
}
.terms {
    cursor: pointer;
    margin-right: 30px;
    text-decoration: none;
}
.terms:hover {
    text-decoration: underline;
}
.settings {
    cursor: pointer;
    margin-right: 30px;
    text-decoration: none;
}
.settings:hover {
    text-decoration: underline;
}
</style>
