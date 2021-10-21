<template>
  <Header />
  <div class="container">
    <router-view/>
  </div>
</template>

<script>
import Header from '@/components/Header'

export default {
  components: {
    Header
  }
}
</script>


<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
a {text-decoration: none;color:inherit}
#app {
  font-family: Arial, sans-serif;
}
.container {
  width: 90%;
  max-width: 800px;
  margin: 0 auto;
}
</style>
