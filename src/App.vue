<template>
  <div id="app">
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Head from './components/index/head.vue';
import Banner from './components/index/banner.vue';
import Entries from './components/index/entries.vue';
import Welfare from './components/index/welfare.vue';
import Nav from './components/index/nav.vue';
import Adviser from './components/index/adviser.vue';
import Aboutus from './components/index/aboutus.vue';
import Company from './components/index/company.vue';
import Contact from './components/index/contact.vue';
import {replaceChn} from './plugins/util.js'
export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
