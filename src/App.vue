<template>
  <v-app>
    <v-main>
      <Home/>
      <HelloWorld/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Home from './components/Home.vue'
export default {
  name: 'App',

  components: {
    HelloWorld,
    Home,
  },

  data: () => ({
    //
  }),
}
</script>
