<template>
  <div id="app">
    <product-list-one v-bind:products="products"> </product-list-one>
  </div>
</template>

<script>
import ProductListOne from './components/productlistone.vue';

export default {
  components: {
    'product-list-one' : ProductListOne
  },
  name: 'app',
  data () {
    return {
     
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
