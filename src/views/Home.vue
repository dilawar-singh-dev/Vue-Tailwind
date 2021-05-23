<template>
  <div class="home text-center">
    <img alt="Vue logo" class="mx-auto" src="../assets/logo.png">
    <button class="btn ring-4 ring-yellow-500 ring-opacity-50">
  Button
</button>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
