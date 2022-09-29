<template>
  <v-app>
    <v-app-bar id="app-bar" absolute>
      <v-app-bar-title>タイトル</v-app-bar-title>
    </v-app-bar>
    
    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'App',

  data () {
    return {
      //
    }
  },
})
</script>
