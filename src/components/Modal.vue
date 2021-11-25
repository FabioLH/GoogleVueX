<template>
    <div class="backdrop">
        <div class="modal">
            <div class="configs">
                <a class="a" href="https://www.google.com.br/preferences?hl=en-BR&fg=1">Search settings</a>
                <a class="a" href="https://www.google.com.br/advanced_search?hl=en-BR&fg=1">Advanced search</a>
                <a class="a" href="https://myaccount.google.com/yourdata/search?utm_source=googlemenu&fg=1&pli=1">Your data in Search</a>
                <a class="a" href="https://myactivity.google.com/product/search?utm_source=google&hl=en-BR&fg=1">Search history</a>
                <a class="a" href="https://support.google.com/websearch/?visit_id=637734675220427229-373449732&hl=en-BR&rd=2#topic=3378866">Search help</a>
                <a class="a2" href="">Send feedback</a>
                <a class="a" href="">Dark theme: Off</a>
            </div>
        </div>
    </div>
</template>

<script>

export default {
  name: "Modal",
};
</script>

<style lang="scss" scoped>
.backdrop {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    width: 100%;
    height: 100%;
    overflow: auto;
    background-color: rgba(0, 0, 0, 0.5);
    z-index: 99;
    display: flex;
    justify-content: flex-end;
    align-items: flex-end;
}
.modal {
    position: relative;
    bottom: 50px;
    right: 20px;
    width: 200px;
    height: 290px;
    padding-top: 15px;
    padding-bottom: 15px;
    font-family: sans-serif;
    font-size: 14px;
    background-color: white;
    border: 1px solid black;
}
.configs {
    display: flex;
    flex-direction: column;
    height: 100%;
    width: 100%;
}
.a {
    cursor: pointer;
    margin-left: 15px;
    margin-bottom: 30px;
    color: rgb(105, 105, 105);
    text-decoration: none;
}
.a:hover {
    text-decoration: underline;
}
.a2 {
    cursor: pointer;
    border-bottom: 1px solid rgb(219, 219, 219);
    width: 92%;
    color: rgb(105, 105, 105);
    padding-left: 15px;
    padding-bottom: 15px;
    margin-bottom: 15px;
    text-decoration: none;
}
.a2:hover {
    text-decoration: underline;
}

</style>
