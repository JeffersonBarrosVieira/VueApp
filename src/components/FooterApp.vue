<template>
    <div id="footer">
        <div class="child">
            <img alt="" src="../assets/logov5.png">
            <h1> Copyright © 2022 Jefferson Barros Vieira </h1>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'FooterApp'
    }
</script>

<style scoped>
    #footer {
        width: calc(100% - 40px);
        height: auto;
        padding: 40px 20px;
        background-color: #10141b;
        display: flex;
        align-items: center;
        justify-content: center;
        color: #fff;
        font-size: 8px;
    }

    #footer .child {
        width: 100%;
        height: 100%;
        border: 1px solid #696b78;

    }
</style>