<template>
  <div id="app">
    <Menu/>
    <Restaurant/>
  </div>
</template>

<script>
import Menu from './components/Menu'
import Restaurant from './components/Restaurant'

export default {
  name: "app",
  components: {
    Menu,
    Restaurant,
  }
};
</script>