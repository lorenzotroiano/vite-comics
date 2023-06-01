<script>

// import HelloWorld from './components/HelloWorld.vue'
import HeaderApp from './components/HeaderApp.vue'
import IconApp from './components/IconApp.vue'
import FooterApp from './components/FooterApp.vue'
import MainApp from './components/MainApp.vue'

export default {
  components: {
    // HelloWorld,
    HeaderApp,
    IconApp,
    FooterApp,
    MainApp
  }
}
</script>

<template>
  <HeaderApp />

  <MainApp />
  <IconApp />

  <FooterApp />
</template>

<style lang="scss">
@use './styles/partials/variables.scss' as *;
@use './styles/general.scss' as *;
</style>
