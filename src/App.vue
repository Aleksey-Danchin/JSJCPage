<template lang="pug">
  v-app
    nav-bar
    v-content
      Fase-segment
</template>

<script>
import NavBar from '@/components/NavBar'
import FaseSegment from '@/components/FaseSegment'

export default {
  name: 'App',

  components: {
    NavBar,
    FaseSegment
  },

  data: () => ({
    //
  }),
};
</script>
