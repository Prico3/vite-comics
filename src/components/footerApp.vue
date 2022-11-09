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
            <div class="bottom__container flex">
                <div class="sign-up">
                    <button>SIGN-UP NOW!</button>
                </div>

                <div class="socials flex">
                    <p> <a href="">FOLLOW US</a> </p>
                    <img src="../assets/footer-facebook.png" alt="">
                    <img src="../assets/footer-twitter.png" alt="">
                    <img src="../assets/footer-youtube.png" alt="">
                    <img src="../assets/footer-pinterest.png" alt="">
                    <img src="../assets/footer-periscope.png" alt="">

                </div>
            </div>

        </div>

    </footer>
</template>

<style lang="scss" scoped>
// SECTION TOP
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
    border: 1px solid green;
    padding: 10px 0;

    ul {
        list-style-type: none;
        font-size: xx-small;

        li {

            color: grey;
            margin-bottom: 0.5rem;

            a {
                color: inherit;
            }
        }
    }

    li:first-child {
        color: white;
        margin-top: 1rem;
    }

    .col {
        margin-right: 1rem;
    }



}

.right {
    width: 50%;
    border: 1px solid green;
    background-image: url('../assets/dc-logo-bg.png');
    background-repeat: no-repeat;
    background-position: 0;
}

// SECTION BOTTOM
.section__bottom {
    background-color: lightgrey;
}


.bottom__container {
    justify-content: space-between;
    align-items: center;
    width: 70%;
    margin: 0 auto;
    padding: 20px 0;
}

.sign-up {
    button {
        padding: 0.5rem;
        border: 2px solid blue;
        background-color: lightgrey;
        color: white;
    }
}

.socials {
    align-items: center;

    p {
        color: blue;
    }

    * {
        padding-left: 10px;
    }
}
</style>