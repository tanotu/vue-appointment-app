<template>
  <div id="app">

    <CalendarWeek />
    <CalendarEntry />

  </div>
</template>

<script>
import CalendarWeek from "./components/CalendarWeek";
import CalendarEntry from "./components/CalendarEntry";

export default {
  name: 'App',
  components: {
    CalendarWeek,
    CalendarEntry
  }
}
</script>

<style scoped>
</style>