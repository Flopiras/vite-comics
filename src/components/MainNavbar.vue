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
                        </figure>
                        <a href="#">digital comics</a>
                    </li>
                    <li>
                        <figure>
                            <img src="../assets/img/buy-comics-merchandise.png" alt="Merchandise">
                        </figure>
                        <a href="#">dc merchandise</a>
                    </li>
                    <li>
                        <figure>
                            <img src="../assets/img/buy-comics-subscriptions.png" alt="Subscriptions">
                        </figure>
                        <a href="#">subscriptions</a>
                    </li>
                    <li>
                        <figure>
                            <img src="../assets/img/buy-comics-shop-locator.png" alt="Shop Locator">
                        </figure>
                        <a href="#">comic shop locator</a>
                    </li>
                    <li>
                        <figure>
                            <img src="../assets/img/buy-dc-power-visa.svg" alt="Power Visa">
                        </figure>
                        <a href="#">dc power vvisa</a>
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
    max-width: 60px;
    max-height: 70px;
    margin-right: 1rem;
}
</style>