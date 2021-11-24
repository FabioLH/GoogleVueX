<template>
    <div class="footer">
        <div class="div1">
            <a class="advertising" href="https://ads.google.com/intl/pt-BR_br/home/?subid=ww-ww-et-g-awa-a-g_hpafoot1_1!o2&utm_source=google.com&utm_medium=referral&utm_campaign=google_hpafooter&fg=1">Advertising</a>
            <a class="business" href="https://smallbusiness.withgoogle.com/intl/pt-BR_br/help/#!/">Business</a>
            <a class="how" href="https://www.google.com/search/howsearchworks/?fg=1">How Search works</a>
        </div>
        <div class="div2">
            <a class="carbon" href="https://sustainability.google/commitments/?utm_source=googlehpfooter&utm_medium=housepromos&utm_campaign=bottom-footer&utm_content=">Carbon neutral since 2007</a>
        </div>
        <div class="div3">
            <a class="privacy" href="https://policies.google.com/privacy?hl=en&fg=1">Privacy</a>
            <a class="terms" href="https://policies.google.com/terms?hl=en&fg=1">Terms</a>
            <a class="settings" href="">Settings</a>
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
    color: black;
    text-decoration: none;
}
.advertising:hover {
    text-decoration: underline;
}
.business {
    cursor: pointer;
    color: black;
    margin-left: 30px;
    text-decoration: none;
}
.business:hover {
    text-decoration: underline;
}
.how {
    cursor: pointer;
    margin-left: 30px;
    color: black;
    text-decoration: none;
}
.how:hover {
    text-decoration: underline;
}
.carbon {
    cursor: pointer;
    margin-left: 20px;
    color: black;
    text-decoration: none;
}
.carbon:hover {
    text-decoration: underline;
}
.privacy {
    cursor: pointer;
    margin-right: 30px;
    color: black;
    text-decoration: none;
}
.privacy:hover {
    text-decoration: underline;
}
.terms {
    cursor: pointer;
    margin-right: 30px;
    color: black;
    text-decoration: none;
}
.terms:hover {
    text-decoration: underline;
}
.settings {
    cursor: pointer;
    margin-right: 30px;
    color: black;
    text-decoration: none;
}
.settings:hover {
    text-decoration: underline;
}
</style>
