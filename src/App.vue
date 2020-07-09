<template>
  <v-app>
    <v-content>
      <Header/>
      <NotFound/>
      <Footer/>
    </v-content>

  </v-app>
</template>

<script>
import Header from './components/Header.vue';
import NotFound from './components/Not-found.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',

  components: {
    Header,
    NotFound,
    Footer
  },

  data: () => ({
    //
  }),
};
</script>
<style>
  @import './assets/css/style.css';
</style>
