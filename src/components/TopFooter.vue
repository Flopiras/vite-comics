<template>
    <div class="top-footer">
        <div class="container">
            <nav>
                <ul class="nav-list">
                    <li>
                        <ul>
                            <li>
                                <h3>dc comics</h3>
                            </li>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>
                    </li>
                    <li>
                        <ul>
                            <li>
                                <h3>dc</h3>
                            </li>
                            <li><a href="#">Terms Of Use</a></li>
                            <li><a href="#">Privacy policy (New)</a></li>
                            <li><a href="#">Ad Choices</a></li>
                            <li><a href="#">Advertising</a></li>
                            <li><a href="#">Jobs</a></li>
                            <li><a href="#">Subscriptions</a></li>
                            <li><a href="#">Talent Workshops</a></li>
                            <li><a href="#">CPSC Certificates</a></li>
                            <li><a href="#">Ratings</a></li>
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contact Us</a></li>
                        </ul>
                    </li>
                    <li>
                        <ul>
                            <li>
                                <h3>sites</h3>
                            </li>
                            <li><a href="#">DC</a></li>
                            <li><a href="#">MAD Magazine</a></li>
                            <li><a href="#">DC Kids</a></li>
                            <li><a href="#">DC Universe</a></li>
                            <li><a href="#">DC Power Visa</a></li>
                        </ul>
                    </li>
                    <li>
                        <ul>
                            <li>
                                <h3>shop</h3>
                            </li>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectables</a></li>
                        </ul>
                    </li>
                </ul>
            </nav>

        </div>
    </div>
</template>

<style lang="scss" scoped>
.top-footer {
    background-image: url(../assets/img/dc-logo-bg.png), url(../assets/img/footer-bg.jpg);
    background-position: 71% 51%, left bottom;
    background-size: 36%, cover;
    background-repeat: no-repeat;
    padding: 3rem 0;
}

.container {
    position: relative;
    display: flex;
    justify-content: space-between;
}

nav {
    flex-basis: 50%;
}

.nav-list {
    display: flex;
    flex-wrap: wrap;

    ul {
        margin-right: 2rem;
    }

}

a {
    font-size: 0.9rem;
    color: #959595;
    text-align: 1.5rem;
}


h3 {
    color: white;
    font-size: 1.3rem;
    text-transform: uppercase;
}

#logo {
    position: absolute;
    top: -142px;
    right: 50px;
}
</style>