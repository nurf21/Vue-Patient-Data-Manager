<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
@font-face {
  font-family: 'Airbnb Cereal App';
  src: url(./assets/font/AirbnbCerealBook.ttf);
}
#app {
  font-family: Airbnb Cereal App, Helvetica, Arial, sans-serif;
}
</style>
