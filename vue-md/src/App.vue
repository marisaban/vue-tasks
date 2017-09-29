<template>
  <div id="app">
    <md-layout :md-gutter="12">
      <md-layout>
            <md-toolbar>
        <h1 class="md-title">Title</h1>
      </md-toolbar>

      <div class="main-content">
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quo, rerum? Error sunt, aperiam dolores, atque expedita molestiae tenetur. Quis eveniet accusamus velit explicabo adipisci reiciendis modi eaque quas, officia excepturi.
        </p>
      </div>
      </md-layout>
    </md-layout>
   <!--  <router-view></router-view> -->
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
