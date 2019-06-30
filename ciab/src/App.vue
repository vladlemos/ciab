<template>
  <div id="app">
    <router-view/>

    <footer-vue></footer-vue>
  </div>
</template>

<script>

import FooterVue from '@/components/layouts/FooterVue'

export default {
  name: 'App',
  components:{
    FooterVue
  }
}
</script>

<style>

</style>
