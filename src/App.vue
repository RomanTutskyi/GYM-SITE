<script>
import Header from './components/Header.vue'

export default {
  components: {Header},
}
</script>

<template>
  <div class="wrapper">
    <div class="container">
      <Header />

    </div>
  </div>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&family=Oswald:wght@200..700&family=Playfair+Display:ital,wght@0,400..900;1,400..900&family=Raleway:ital,wght@0,100..900;1,100..900&display=swap');

*{
  margin: 0;
  padding: 0;
}

.container{
  width: 100%;
  height: 100vh;
  background-image: url("../public/pexels-pixabay-416778.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  font-family: 'Oswald', sans-serif;
  position: absolute;
  font-size: 1em;
  color: white;
}

</style>
