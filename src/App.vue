<template>
  <div id="app">
   <HeaderCli />
   <MainCli />
   <FooterCli />
  </div>
</template>

<script>
import HeaderCli from './components/HeaderCli.vue'
import MainCli from './components/MainCli.vue'
import FooterCli from './components/FooterCli.vue'

export default {
  name: 'App',
  components: {
    HeaderCli,
    MainCli,
    FooterCli,
  }
}
</script>

<style>
* {
 margin: 0;
 padding: 0;
 box-sizing: border-box;
}
</style>
