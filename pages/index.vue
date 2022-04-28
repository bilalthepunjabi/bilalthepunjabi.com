<template>
  <div class="flex flex-col h-screen justify-between">
    <Header></Header>
    <main class="mb-auto h-10"></main>
    <Footer></Footer>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Header from "~/components/Header.vue";

export default Vue.extend({
    name: "IndexPage",
    components: { Header }
});
</script>
