<script>
import NewsList from '@/components/NewsList.vue'

    export default {
        data() {
            return {};
        },
        components: { NewsList }
    };
</script>

<template>
    <div class="news-container">
        <h2>News</h2>
        <NewsList />
    </div>
</template>

<style>
.news-container {
    width: 98%;
}
h2, form, p {
    display: flex;
    justify-content: center;
}


</style>