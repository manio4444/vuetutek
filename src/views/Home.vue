<template>
  <!-- <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div> -->
  <div class="wrapper">
    <h1>Homepage</h1>
    <Search />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue';
import Search from './Search.vue';

export default {
  name: 'home',
  components: {
    // HelloWorld,
    Search,
  },
};
</script>
