<template>
  <div class="flex flex-col h-screen justify-between">
    <header class="h-10 bg-red-500">Header</header>
    <main class="mb-auto h-10 bg-green-500">Content</main>
    <Footer></Footer>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage'
})
</script>
