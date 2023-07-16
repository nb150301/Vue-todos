<script>
// eslint-disable-next-line no-unused-vars
import Header from "@/components/Header.vue";
import Todos from "@/components/Todos.vue";

export default ({
  name: "App",
  components: {Header, Todos}
})
</script>

<template>
  <div id="app">
    <p>Đây là app Vue</p>
    <Header/>
    <Todos/>
  </div>
</template>

<style scoped>

</style>