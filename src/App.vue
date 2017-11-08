<template>
  <div id="app">
    <img src="@/assets/logo.png">
	<img :src="require('@/assets/logo.png')">
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
    }
  }
}
</script>
