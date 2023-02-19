<template>
  <div class="hello">
    <navmenu></navmenu>
    <aboutxhc></aboutxhc>
  </div>
</template>

<script>
  import aboutxhc from '@/components/aboutxhc/aboutxhc.vue'
  import navmenu from '@/components/navMenu/navmenu.vue'
  export default {
    components: {
      navmenu,
      aboutxhc
    },
    name: 'hello',
    data () {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
