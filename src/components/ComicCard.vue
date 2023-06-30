<script>
export default {
    props: {
        thumb: Object
    }
}
</script>    

<template>
    <div class="card">
        <figure>
            <img :src="thumb.thumb" :alt="thumb.series">
            <figcaption>{{ thumb.series }}</figcaption>
        </figure>

    </div>
</template>

<style scoped>
.card {
    padding: 1rem;
    flex-basis: calc(100% / 6);
}

img {
    width: 150px;
    height: 150px;
    object-fit: cover;
}
</style>