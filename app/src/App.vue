<template>
  <div id="app">
    
    <Title />
    <Jumbo />
  </div>
</template>

<script>

import Title from '@/components/Title.vue';
import Jumbo from '@/components/Jumbotron.vue';

export default {
  name: 'App',
  components: {
    Title,
    Jumbo
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  
}
</style>
