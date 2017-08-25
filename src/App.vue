<template>
  <div id="app">
    <header-component></header-component>
    <router-view></router-view>
    <header></header>
    <footer-component></footer-component>
  </div>
</template>

<script>
import HeaderComponent from '@/components/template/Header'
import FooterComponent from '@/components/template/Footer'
export default {
  components: {
    HeaderComponent,
    FooterComponent
  },
  name: 'app'
}
</script>
