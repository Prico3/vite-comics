<script>
export default {}
</script>


<template>
    <section>
        <div class="section__container">

            <div class="card__container">

                <div class="card">

                    <div class="card__logo">
                        <img src="../assets/buy-comics-digital-comics.png" alt="digital comics">
                    </div>
                    <div class="card__text">
                        <p>DIGITAL COMICS</p>
                    </div>

                </div>

                <div class="card">

                    <div class="card__logo">
                        <img src="../assets/buy-comics-digital-comics.png" alt="digital comics">
                    </div>
                    <div class="card__text">
                        <p>DIGITAL COMICS</p>
                    </div>

                </div>
                <div class="card">

                    <div class="card__logo">
                        <img src="../assets/buy-comics-digital-comics.png" alt="digital comics">
                    </div>
                    <div class="card__text">
                        <p>DIGITAL COMICS</p>
                    </div>

                </div>

                <div class="card">

                    <div class="card__logo">
                        <img src="../assets/buy-comics-digital-comics.png" alt="digital comics">
                    </div>
                    <div class="card__text">
                        <p>DIGITAL COMICS</p>
                    </div>

                </div>

                <div class="card">

                    <div class="card__logo">
                        <img src="../assets/buy-comics-digital-comics.png" alt="digital comics">
                    </div>
                    <div class="card__text">
                        <p>DIGITAL COMICS</p>
                    </div>

                </div>



            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
section {
    width: 100%;
    margin: 0 auto;
    color: white;
    padding: 1rem;

    // DEBUG
    background-color: blue;
}

.section__container {
    width: 70%;
    margin: 0 auto;
}

.card__container {
    display: flex;

}

.card {
    width: calc(100% / 5);
    display: flex;
    align-items: center;

}
</style>