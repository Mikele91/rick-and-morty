<template>
  <div id="app">
      <Header title="Rick and Morty App"/>
      <Characters/>

  </div>
</template>

<script>

import Header from './components/Header.vue';
import Characters from './components/Characters.vue';


export default {
  name: 'App',
  components: {
    Header,
    Characters
  }
}
</script>

<style lang="scss">
@import './assets/style/common.scss';
</style>
