<template>
  <div>
    <Title />
    <Hero />
    <Square />
    <SquareII />
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Hero from './components/Hero.vue'
import Square from './components/Square.vue'
import SquareII from './components/SquareII.vue'

export default {
  name: 'App',
  components: {
    Title,
    Hero,
    Square,
    SquareII
  }
}
</script>

<style>
.container {
  width: 80%;
  height: 300px;
  margin: 10px auto;
  background-color: rgb(246, 220, 220);
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
  color: rgb(99, 86, 86);
}

h1 {
  text-align: center;
  color: rgb(99, 86, 86);
}
</style>
