<template>
  <div id="app">
    <Title/>
    <hero/>
  </div>
</template>

<script>
import Title from '@/components/Title.vue'
import hero from '@/components/hero.vue'

export default {
  name: 'App',
  components: {
    Title,
    hero
  }
}
</script>

<style lang="scss">
#app {
  text-align: center;
  background-color: #37495f;
  height: 100vh;
}

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>