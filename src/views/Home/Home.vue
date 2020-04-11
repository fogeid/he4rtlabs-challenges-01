<template>
  <div id="app">
    <header class="header">
      <app-logo />
      <app-social-midia />      
    </header>
    <section>
      <app-form />
    </section>
  </div>
</template>

<script>
import Logo from '@/components/template/Logo.vue';
import Social from '@/components/template/Social.vue';
import Formulario from '@/components/template/Formulario.vue';

export default {
  name: 'Home',
  components: {
    'app-logo': Logo,
    'app-social-midia': Social,
    'app-form': Formulario,
  }
}
</script>

<style src="./style.scss" lang="scss" scoped />