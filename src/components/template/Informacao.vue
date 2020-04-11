<template>
    <div>
        <div class="info">
            <h1 class="info__title">Calculadora de Freelas</h1>
            <p class="info__text">
                Uma calculadora que irá te mostrar o valor da sua hora perante o freelance cotado.<br>
                Um projeto proposto pelo grupo <a :href="link">He4rt Developers</a>
            </p>
            <div class="info-btn">
                <a href="#cards" class="btn">Mais</a>
            </div>
        </div>
    </div>    
</template>

<script>
export default {
    data() {
        return {
            link: 'https://heartdevs.com/',
        }
    }
}
</script>

<style src="./informacao.scss" lang="scss" />