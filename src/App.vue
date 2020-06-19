<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
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


---HOMESCREEN---
(Arrow keys) hover on deck ---> EMPHASIZE DECK
(alt + N) create deck --> NAME DECK
study/edit deck for each deck button
(alt + F) search decks 
---NAME DECK---
input box for deck name
input box for description (optional)
cancel button ---> HOME SCREEN
(ENTER) create button ---> EDIT DECK

---EDIT DECK (LIST VIEW)---
