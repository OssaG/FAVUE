<template>
  <HelloWorld msg="Formulär"/>
  <div id="app">
    <SearchAutocomplete
      :items="[
        'Apple',
        'Banana',
        'Orange',
        'Mango',
        'Pear',
        'Peach',
        'Grape',
        'Tangerine',
        'Pineapple'
      ]"
    />
  </div>
</template>

<script>
import SearchAutocomplete from './components/ContactSearch.vue'

import HelloWorld from './components/HelloWorld.vue';
// import TextField from './components/TextField.vue';


export default {
  name: 'App',
  created () {
            document.title = "Favue - Felanmälning";
        },
  components: {
    HelloWorld,
    SearchAutocomplete
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: rgb(255, 255, 255);
}
</style>
