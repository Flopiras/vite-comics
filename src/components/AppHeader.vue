<script>
export default {
    data() {
        return {
            links: [
                {
                    text: 'Characters',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Comics',
                    url: '#',
                    current: true,
                },
                {
                    text: 'Movies',
                    url: '#',
                    current: false,
                },
                {
                    text: 'TV',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Games',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Collectibles',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Videos',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Fans',
                    url: '#',
                    current: false,
                },
                {
                    text: 'News',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Shop',
                    url: '#',
                    current: false,
                },
            ],
        }
    },
    methods: {
    }
}
</script>

<template>
    <header>
        <div class="container">

            <figure>
                <img src="../assets/img/dc-logo.png" alt="DC logo">
            </figure>
            <nav>
                <ul>
                    <li v-for="link in links" :key="link.text" :class="{ active: link.current }">
                        <a :href="link.url">{{ link.text }}</a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<style lang="scss"  scoped>
@use '../assets/sass/utils' as *;

.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-family: monospace;
    font-size: 1rem;
}

figure {
    margin: 1.5rem 0;
}

img {
    display: block;
    max-width: 80px;
}

ul {
    display: flex;

    a {
        text-decoration: none;
        color: #4C4646;
        padding: 2rem 1rem;
        text-transform: uppercase;
        font-weight: 600;

        .active {
            color: $blue;
        }
    }
}
</style>