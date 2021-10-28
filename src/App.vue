<template>
  <div id="app">
    <current-time/>
  </div>
</template>

<script>
import CurrentTime from './components/CurrentTime.vue';

export default {
  name: 'App',
  components: {
    CurrentTime
  }
}
</script>