<template>
    <div>
        <form class="form">
            <label class="form__label" for="tempo-diario">Tempo Diário</label>
            <input v-model="horasDiarias" class="form__input" type="text" id="horasDiarias">
            <label class="form__label" for="diasEfetivos">Dias Efetivos</label>
            <input v-model="diasEfetivos" class="form__input" type="text" id="efetivos">
            <label class="form__label" for="tempo-diario">Dias de Férias</label>
            <input v-model="diasFerias" class="form__input" type="text" id="diasFerias">
            <label class="form__label" for="tempo-diario">Valor Total do Projeto</label>
            <input v-model="valorProjeto" class="form__input" type="text" id="valorProjeto">
            <div class="form__btn">
                <button @click="calcFreela" class="btn" type="submit">Calcular</button>
            </div>
        </form>
        <div v-if="valorHora != 0" class="resultado">
            <span class="resultado__title">Valor da Hora</span><br>
            <span class="resultado__valor">R$ {{ valorHora }}</span>
        </div>        
    </div>    
</template>

<script>
export default {
    data() {
        return {
            horasDiarias: '',
            diasEfetivos: '',
            diasFerias: '',
            valorProjeto: '',
            valorHora: '',
        }
    },
    methods: {
        calcFreela() {
            this.valorHora = '';        
            return this.valorHora += (this.valorProjeto / (this.diasEfetivos * 4 * this.horasDiarias)) + ((this.diasFerias * this.diasEfetivos * this.horasDiarias));
        }        
    }
}
</script>

<style src="./formulario.scss" lang="scss">

</style>