<template>
  <v-app>
    <Nav />
    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import Nav from './commons/nav';

export default {
  name: 'App',

  components: {
    HelloWorld,
    Nav
  },

  data: () => ({
    //
  }),
};
</script>
