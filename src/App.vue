<template>
  <div id="app">
    <h1>Hello World</h1>
  </div>
</template>

<script>
import game from '@/game'

document.onkeydown = e => {
  if (e.code != 'Enter') return
  alert(game.next())
}

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
  margin-top: 60px;
}
</style>