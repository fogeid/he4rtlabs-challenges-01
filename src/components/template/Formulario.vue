<template>
    <div>
        <form class="form">
            <label class="form__label" for="tempo-diario">Tempo Diário</label>
            <input class="form__input" type="text" id="diaria">
            <label class="form__label" for="tempo-diario">Dias Efetivos</label>
            <input class="form__input" type="text" id="efetivos">
            <label class="form__label" for="tempo-diario">Dias de Férias</label>
            <input class="form__input" type="text" id="ferias">
            <label class="form__label" for="tempo-diario">Valor Total do Projeto</label>
            <input class="form__input" type="text" id="valor-total">
            <div class="form__btn">
                <button class="btn" type="submit">Calcular</button>
            </div>
        </form>
    </div>    
</template>

<script>
export default {

}
</script>

<style src="./formulario.scss" lang="scss">

</style>