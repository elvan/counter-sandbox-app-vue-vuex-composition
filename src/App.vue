<template>
  <the-counter></the-counter>
  <control-center></control-center>
</template>

<script>
import ControlCenter from './components/ControlCenter.vue';
import TheCounter from './components/TheCounter.vue';

export default {
  components: {
    ControlCenter,
    TheCounter,
  },
};
</script>

<style>
* {
  box-sizing: border-box;
}

html {
  font-family: sans-serif;
}

body {
  margin: 0;
  text-align: center;
}

.container {
  max-width: 30rem;
  margin: 3rem auto;
  padding: 1rem;
  border-radius: 12px;
  text-align: center;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
}
</style>
