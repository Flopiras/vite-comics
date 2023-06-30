<script>
import MainNavbar from './MainNavbar.vue';
export default {
    components: { MainNavbar },
    data() {
        return {
        }
    }
}
</script>

<template>
    <main>

        <div id="jumbotron"></div>

        <!-- navbar -->
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
</style>