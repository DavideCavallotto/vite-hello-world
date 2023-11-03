<script>
import AppHero from './components/AppHero.vue'

export default {
  data() {
    return {
      message: 'La mia prima app con Vite!'
    }
  },
  components: {
    AppHero
  },
  methods: {
    imClick() {
      console.log('Ho Cliccato')
    }

  }
}
</script>

<template>
 <div @click="imClick()">  
  {{ message }} 
 </div>
  <AppHero/>
</template>

<style scoped>
</style>
