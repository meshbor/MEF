<template>
  <v-app>


    <v-main>
      <Mef/>
    </v-main>
  </v-app>

</template>

<script>

import Mef from './components/Mef'

export default {
  name: 'App',

  components: {
    Mef,
  },

  data: () => ({
    //
  }),
};
</script>
