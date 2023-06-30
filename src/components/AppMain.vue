<script>
import MainNavbar from './MainNavbar.vue';
import ComicCard from './ComicCard.vue';
export default {
    components: { MainNavbar, ComicCard },
    props: {
        thumbs: Array
    }
}
</script>

<template>
    <main>

        <div id="jumbotron"></div>

        <!-- navbar -->
        <section id="current-series">
            <div class="container cards-container">
                <ComicCard v-for="thumb in thumbs" :thumb="thumb" />
            </div>
        </section>
        <MainNavbar />
    </main>
</template>

<style scoped>
main {
    color: white;
    background-color: black;
}

#jumbotron {
    background-image: url(../assets/img/jumbotron.jpg);
    background-size: cover;
    height: 350px;
}

#current-series {
    background-color: #1C1C1C;
}

.cards-container {
    display: flex;
    flex-wrap: wrap;
    padding: 1rem 0 1rem 0;
}
</style>