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
    <section class="cards" id="cards">
      <app-cards
        title="Tempo diário investido no projeto"
        text="Agora vamos entender um pouco mais sobre esses fatores começando pelo fator tempo diário investido. Quando tratamos de freelances, há uma certa demanda do seu tempo em off. Ou seja: depois do trabalho, escola ou aquele tempinho vago no final do dia que você usa pra relaxar e descontrair. Esse tempo é algo muito valioso para qualquer pessoa, certo? Então claramente temos que levar esse fator em consideração."
        class="cards__item" />
      <app-cards
        title="Dias efetivos trabalhando"
        text="Outro fator é a quantidade de dias efetivos que você irá disponibilizar para trabalhar no projeto. Não há nenhuma garantia que você poderá trabalhar todos os dias e de fato lidar com o processo de confirmar tudo com o cliente. Logo, você terá que cotar uma quantidade de dias específicos para lidar com todo o processo, sendo ele a parte comercial e desenvolvimento."
        class="cards__item" />
      <app-cards
        title="Dias de Férias por projeto"
        text="Qualquer modalidade de trabalho, seja CLT ou PJ, há seus encargos referentes à verba de férias e não seria diferente para lidar com um freela. Uma parte do valor da sua hora reflete diretamente na quantidade de dias que você deseja tirar 'férias' com o valor total projeto."
        class="cards__item" />
      <app-cards
        title="Valor total do Projeto"
        text="Não podemos esquecer do principal fator que é o total a ser recebido pelo freela. A partir desse valor, do quanto você desejaria ganhar em cima do trabalho, é feito o cálculo maior."
        class="cards__item" />
    </section>
    <app-footer />
  </div>
</template>

<script>
import Logo from '@/components/template/Logo.vue';
import Social from '@/components/template/Social.vue';
import Informacao from '@/components/template/Informacao.vue';
import Formulario from '@/components/template/Formulario.vue';
import Card from '@/components/template/Card.vue';
import Footer from '@/components/template/Footer.vue';

export default {
  name: 'Home',
  components: {
    'app-logo': Logo,
    'app-social-midia': Social,
    'app-informacao': Informacao,
    'app-form': Formulario,
    'app-cards': Card,
    'app-footer': Footer,
  }
}
</script>

<style src="./style.scss" lang="scss" scoped />