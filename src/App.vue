<template>
  <div class="h-screen bg-gray-200">
    <Navbar />
    <div class="flex">
      <Calendar />
    </div>
  </div>
</template>

<script>
  import Navbar from './components/Navbar.vue'
  import Calendar from './components/Calendar.vue';

  export default {
    name: 'App',
    components: {
      Navbar,
      Calendar
    },
  }
</script>

<style scoped>

</style>