<template>
  <div id="app">
    <vue-double-list></vue-double-list>
  </div>
</template>

<script>
import VueDoubleList from './VueDoubleList';

export default {
  name: 'app',
  components: {
    VueDoubleList
  }
}
</script>

<style>
#app{
  text-align: center;
}
</style>
