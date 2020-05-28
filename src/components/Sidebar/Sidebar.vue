<template>
    <div class="sidebar-div">
        <Explore>

        </Explore>

        <Genres>

        </Genres>
    </div>
</template>

<script lang="ts">
import Vue from 'vue';
import Explore from './Explore.vue';
import Genres from './Genres.vue';

export default Vue.extend({
    name: "sidebar",
    components: {
        Explore,
        Genres
    }
    
})
</script>

<style scoped>

.sidebar-div{
    border-right: 1px solid gray;
    height: 100vh;
}




</style>