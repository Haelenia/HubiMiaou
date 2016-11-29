<template>
  <div id="app">
    <Test></Test>
    <InitialPage></InitialPage>

  </div>
</template>

<script>

import InitialPage from './components/InitialPage.vue'
import Test from './components/Test.vue'

export default {
  name: 'app',
  components: {
	  InitialPage,
      Test
  }
}
</script>

<style>
</style>
