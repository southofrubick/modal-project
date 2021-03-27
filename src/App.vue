<template>
  <h1>{{ title }}</h1>
  <Modal />
</template>

<script>
import Modal from './components/Modal.vue'

export default {
  name: 'App',
  components: { Modal },
  data(){
    return{
      title: 'First real thing'
    }
  }
}
</script>

<style>
body{
  text-align: center;
}
</style>
