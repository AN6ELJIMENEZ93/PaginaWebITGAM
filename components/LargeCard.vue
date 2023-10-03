<template>
    <div class="card">
        <img class="image" :src="require(`@/assets/images/${card.image || 'itgam.png'}`)" alt="">
        <h3 class="header">{{ card.title }}</h3>
        <p class="snippet">
            {{card.snippet }}
        </p>
    </div>
</template>

<script>
    export default {
        props: ['card'],
    }
</script>

<style scoped>
    .card {
        width: 65%;
        height: 25rem;
        border: none;
        overflow: hidden;
        padding: 0;
    }
    .image {
        height: 70%;
        width: 70%;
        border-radius: 0.5rem;
    }
    .header {
        font-size: 1.15rem;
        margin-top: 0.4rem;
    }
    .snippet {
        color: grey
    }
</style>