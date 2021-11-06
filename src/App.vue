<template>
  <cabezera msg="App de tareas"></cabezera>
  <cuerpo></cuerpo>
</template>

<script>
import cabezera from './components/cabezera.vue'
import cuerpo from './components/body.vue'

export default {
  name: 'App',
  components: {
    cabezera, cuerpo
  }
}
</script>

<style>

</style>
