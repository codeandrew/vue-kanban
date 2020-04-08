<template>
  <v-app>
    <Nav />
    <v-content>
      <Template />
    </v-content>
  </v-app>
</template>

<script>
import Template from './pages/template';
import Nav from './commons/nav';

export default {
  name: 'App',

  components: {
    Nav,
    Template
  },

  data: () => ({
    //
  }),
};
</script>
