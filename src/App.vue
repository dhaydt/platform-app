<template>
  <div id="app">
    <Navbar />
    <router-view/>
  </div>
</template>

<script>
import Navbar from './components/navbar';
import Home from './views/Home';

export default {
  name: 'App',

  components: {
    Navbar,
    Home
  },
};
</script>
