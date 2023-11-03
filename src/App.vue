<script>
import appHero from './components/appHero.vue'
export default {
  data() {
    return {
      message: "It's Alive!"
    }
  },
  components: {
    appHero
  }
}
</script>

<template>
  <appHero />
  <div class="message">{{ message }}</div>
</template>

<style scoped>
.message {
  text-align: center;
  font-size: 36px;
}
</style>
