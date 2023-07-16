<script>
import {defineComponent} from 'vue'

export default defineComponent({
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Header",
})
</script>

<template>
  <header class="header">
    <h1>Những việc cần làm</h1>
  </header>
</template>

<style scoped>
h1 {
  color: #fff;
  background-color: #42b983;
  padding: 10px;
  text-align: center;
}
</style>