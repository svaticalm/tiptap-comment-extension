<script lang="ts">
import { defineComponent } from 'vue'
import Tiptap from './components/Tiptap.vue'
import ThemeSwitchButton from './components/ThemeSwitchButton.vue'

export default defineComponent({
  name: 'App',
  components: {
    Tiptap,
    ThemeSwitchButton
  },
})
</script>

<template>
  <div id="app">
    <tiptap />

    <theme-switch-button />
  </div>
</template>

<style lang="scss">
/* #app {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell,
    "Open Sans", "Helvetica Neue", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  // text-align: center;
  color: #2c3e50;
  height: 100vh;
  // margin-top: 60px;
} */
</style>
