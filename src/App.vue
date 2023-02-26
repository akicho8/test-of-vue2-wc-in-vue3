<template>
<div id="app">
  <MyTag foo_bar="OK" foo-bar="OK" />
</div>
</template>

<script>
import MyTag from "./components/MyTag.vue"

export default {
  name: "App",
  components: {
    MyTag,
  },
}
</script>

<style>
</style>
