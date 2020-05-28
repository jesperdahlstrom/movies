<template>
  <div id="app">

    <b-container fluid="true">

      <b-row>

        <b-col col lg="2">
          <Sidebar>
          </Sidebar>
        </b-col>

        <b-col col lg="10" >
          <MovieList>
          </MovieList>
        </b-col>

      </b-row>
      
    </b-container>

  </div>
</template>

<script lang="ts">
import Vue from "vue";
import MovieList from "./components/MovieList.vue";
import Sidebar from "./components/Sidebar/Sidebar.vue";

export default Vue.extend({
  name: "App",
  components: {
    MovieList,
    Sidebar
  }
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>
