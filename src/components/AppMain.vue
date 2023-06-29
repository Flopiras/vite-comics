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
        <div class="container">
            <h1> -- Content goes here -- </h1>
        </div>
        <!-- navbar -->
        <MainNavbar />
    </main>
</template>

<style scoped>
main {
    color: white;
    background-color: black;
    padding: 3rem 0;
}
</style>