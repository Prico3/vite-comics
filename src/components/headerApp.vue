<script>
export default {}
</script>

<template>

    <header>
        <div class="header__container">
            <div class="logo">
                <img src="../assets/dc-logo.png" alt="Logo DC">
            </div>

            <div class="nav">
                <ul>
                    <li><a href="">ciao</a></li>
                    <li><a href="">ciao</a></li>
                    <li><a href="">ciao</a></li>
                    <li><a href="">ciao</a></li>
                    <li><a href="">ciao</a></li>
                    <li><a href="">ciao</a></li>
                    <li><a href="">ciao</a></li>
                    <li><a href="">ciao</a></li>
                    <li><a href="">ciao</a></li>
                </ul>
            </div>
        </div>
    </header>

</template>

<style lang="scss" scoped>
header {
    width: 70%;
    margin: 0 auto;
    padding: 1rem;

    // debug
    border: 1px solid black;
}

.header__container {
    display: flex;
    justify-content: space-between;
    align-items: center;

    ul {
        display: flex;
        list-style-type: none;

        li {
            margin-left: 20px;
        }
    }
}
</style>