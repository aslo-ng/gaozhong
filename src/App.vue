<template>
  <div id="app">
    <Header/>
    <router-view/>
    <footere/>
  </div>
</template>
<script>
import Header from "@/components/header/header.vue";

import footere from '@/components/footer/footer.vue'

export default {
    components:{
        Header,
        footere,
    }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
