<template>
    <a href="#" class="card text-decoration-none">
        <img :src="article.image" class="card-img-top" alt="...">
        <div class="card-body">
            <h5 class="card-title">{{ article.title }}</h5>
        </div>
    </a>
</template>

<script>
export default {
    props: {
        article: Object
    }
}
</script>

<style scoped>
    .card img {
            height: 200px;
            object-fit: cover;
        }
</style>