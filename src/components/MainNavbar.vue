<script>
export default {
    data() {
        return {
        }
    }
}
</script>

<template>
    <section>
        <div class="container">
            <nav>
                <ul>
                    <li>
                        <figure>
                            <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital Comics">
                            <figcaption><a href="#">digital comics</a></figcaption>
                        </figure>

                    </li>
                    <li>
                        <figure>
                            <img src="../assets/img/buy-comics-merchandise.png" alt="Merchandise">
                            <figcaption><a href="#">dc merchandise</a></figcaption>
                        </figure>

                    </li>
                    <li>
                        <figure>
                            <img src="../assets/img/buy-comics-subscriptions.png" alt="Subscriptions">
                            <figcaption><a href="#">subscriptions</a></figcaption>
                        </figure>

                    </li>
                    <li>
                        <figure>
                            <img src="../assets/img/buy-comics-shop-locator.png" alt="Shop Locator">
                            <figcaption><a href="#">comic shop locator</a></figcaption>
                        </figure>

                    </li>
                    <li>
                        <figure>
                            <img src="../assets/img/buy-dc-power-visa.svg" alt="Power Visa">
                            <figcaption>
                                <a href="#">dc power vvisa</a>
                            </figcaption>
                        </figure>

                    </li>
                </ul>
            </nav>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@use '../assets/sass/_utils' as *;

section {
    padding: 3rem;
    background-color: $blue;
}

ul {
    display: flex;
}

li {
    display: flex;
    align-items: center;
    margin: 0 1rem;

    a {
        cursor: pointer;
        text-decoration: none;
        color: white;
        text-transform: uppercase;

    }
}

img {
    display: block;
    width: 55px;
    height: 60px;
}

figure {
    display: flex;
    justify-content: center;
    align-items: center;

    figcaption {
        margin-left: 1rem;
    }
}
</style>