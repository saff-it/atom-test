<template>
  <div id="app">

    <HeaderComponent/>
    <MainComponent/>
    <FooterComponent/>

  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import MainComponent from './components/MainComponent.vue'
import FooterComponent from './components/FooterComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainComponent,
    FooterComponent,
    
  }
}
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap.scss";
@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.3/font/bootstrap-icons.css");
@import "./styles/general.scss";
@import "./styles/mediaQuery.scss";


</style>
