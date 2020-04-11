<template>
  <div id="app">
    <div class="container">
      <section class="col-1">
        <app-logo />
        <app-informacao />
      </section>
      <section class="col-2">      
        <app-social-midia />
        <app-form />
      </section>
    </div>
  </div>
</template>

<script>
import Logo from '@/components/template/Logo.vue';
import Social from '@/components/template/Social.vue';
import Informacao from '@/components/template/Informacao.vue';
import Formulario from '@/components/template/Formulario.vue';

export default {
  name: 'Home',
  components: {
    'app-logo': Logo,
    'app-social-midia': Social,
    'app-informacao': Informacao,
    'app-form': Formulario,
  }
}
</script>

<style src="./style.scss" lang="scss" scoped />