<script>
export default {}
</script>

<template>
    <footer>

        <div class="section__top">
            <div class="top__container">

                <div class="left">

                </div>

                <div class="right">

                </div>

            </div>
        </div>

        <div class="section__bottom">

        </div>

    </footer>
</template>

<style lang="scss" scoped>
.section__top {
    height: 400px;
    background-image: url('../assets/footer-bg.jpg');
}

.top__container {
    width: 70%;
    margin: 0 auto;
    display: flex;
}

.left {
    width: 50%;
    height: 400px;
    border: 1px solid green;
}

.right {
    width: 50%;
    height: 400px;
    border: 1px solid green;
    background-image: url('../assets/dc-logo-bg.png');
    background-repeat: no-repeat;
    background-position: 0;
}
</style>