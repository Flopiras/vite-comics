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
                    <li v-for="link in links" :key="link.text">
                        <a :href="link.url">{{ link.text }}</a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<style lang="scss"  scoped>
.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

ul {
    display: flex;

    a {
        text-decoration: none;
        color: #4C4646;
        padding: 2rem 1rem;
        text-transform: uppercase;
    }
}
</style>