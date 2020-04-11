<template>
  <div id="app">
    <header class="header">
      <app-logo />
      <app-social-midia />
    </header>    
  </div>
</template>

<script>
import Logo from '@/components/template/Logo.vue';
import Social from '@/components/template/Social.vue';

export default {
  name: 'Home',
  components: {
    'app-logo': Logo,
    'app-social-midia': Social,
  }
}
</script>

<style src="./style.scss" lang="scss" scoped />