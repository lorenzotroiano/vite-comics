<script>

// import HelloWorld from './components/HelloWorld.vue'
import HeaderApp from './components/HeaderApp.vue'
import IconApp from './components/IconApp.vue'
import FooterApp from './components/FooterApp.vue'

export default {
  components: {
    // HelloWorld,
    HeaderApp,
    IconApp,
    FooterApp
  }
}
</script>

<template>
  <div class="container">
    <HeaderApp />

    <main>
      Contenuto da inserire
    </main>
    <IconApp />

    <FooterApp />
  </div>
</template>

<style lang="scss">
@use './styles/partials/variables.scss' as *;
@use './styles/general.scss' as *;
</style>
