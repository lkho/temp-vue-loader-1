<template>
  <div id="app">
    1<img src="@/assets/logo.png"><br/>
	2<img src="./assets/logo.png"><br/>
	3<img :src="require('@/assets/logo.png')">
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
