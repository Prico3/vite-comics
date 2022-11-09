<script>
export default {}
</script>

<template>
    <footer>

        <div class="section__top">
            <div class="top__container">

                <div class="left flex">

                    <div class="col">
                        <ul>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>

                        </ul>
                        <ul>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>

                        </ul>
                    </div>

                    <div class="col">
                        <ul>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                        </ul>

                    </div>

                    <div class="col">
                        <ul>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>
                            <li><a href="">DC COMICS</a></li>


                        </ul>
                    </div>


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

    ul {
        list-style-type: none;
        font-size: xx-small;

        li {
            margin-top: 1rem;
            color: grey;

            a {
                color: inherit;
            }
        }
    }

    li:first-child a {
        color: white;
    }

    .col {
        margin-right: 1rem;
    }



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