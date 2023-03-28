<script>
import HomeMain from '../components/HomeMain.vue'
import NavInput from '../components/NavInput.vue'

export default {
  components: {
    HomeMain,
    NavInput
  }
}
</script>

<template>
    <NavInput/>
  <main class="my-8">
    <HomeMain />
  </main>
</template>
