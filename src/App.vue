<template id="app">
  <div>
    <MyVue1></MyVue1>

  </div>
</template>

<script>
import MyVue1 from './components/MyVue1.vue';

export default {
  name: 'App',
  components: {
    MyVue1,
  },
  data() {
    return {

    };
  },

};
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
