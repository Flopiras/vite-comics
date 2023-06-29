<template>
    <div class="bottom-footer">
        <div class="container">
            <div class="button">
                <a href="#">sign-up now!</a>
            </div>
            <div class="socials">
                <h2>follow us</h2>
                <ul>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-facebook.png" alt="facebook">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-twitter.png" alt="twitter">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-youtube.png" alt="YouTube">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-pinterest.png" alt="Pinterest">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-periscope.png" alt="Periscope">
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../assets/sass/utils' as *;


.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    text-transform: uppercase;
}

.bottom-footer {
    background-color: #303030;
    padding: 2rem 0;
}

.button {
    padding: 1rem;
    border: 2px solid $blue;

    a {
        font-weight: 600;
        font-size: 1.2rem;
    }
}

h2 {
    color: $blue;
}

.socials {
    display: flex;

    ul {
        display: flex;

        li {
            margin-left: 1rem;
        }
    }
}
</style>