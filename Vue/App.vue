<template>
  <div id="app">
    <MagicHud />
  </div>
</template>

<script>
import './assets/fonts/main.css';

import MagicHud from './components/MagicHud/MagicHud.vue';

export default {
  name: 'App',

  components: {
    MagicHud
  }
}
</script>

<style>
*, html, body {
    margin: 0;
    padding: 0;
}

html, body {
    overflow: hidden;
}

#app {
    position: absolute;

    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;

    width: 100%;
    height: 100%;
}
</style>
