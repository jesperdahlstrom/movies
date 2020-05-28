<template>
    <div>
        <movie>

        </movie>

        <p>movielist</p>
    </div>
</template>

<script lang="ts">
import Vue from 'vue';
import Movie from './Movie.vue';

export default Vue.extend({
    name: "MovieList",
    components: {
        Movie
    }
    
})
</script>

<style scoped>

</style>