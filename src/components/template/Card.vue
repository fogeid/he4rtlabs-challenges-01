<template>
    <div>       
        <div class="card">
            <h2 class="card__title">{{ titulo }}</h2>
            <p class="card__text">{{ texto }}</p>
        </div>
    </div>    
</template>

<script>
export default {
    data() {
        return {
            titulo: "Tempo diário investido no projeto",
            texto: "Agora vamos entender um pouco mais sobre esses fatores começando pelo fato tempo diário investido. Quando tratamos de freelances, há uma certa demanda do seu tempo em off. Ou seja: depois do trabalho, escola ou aquele tempinho vago no final do dia que você usa pra relaxar e descontrair. Esse tempo é algo muito valioso para qualquer pessoa, certo? Então claramente temos que levar esse fator em consideração.",
        }
    }
}
</script>

<style src="./card.scss" lang="scss">