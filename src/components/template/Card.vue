<template>
    <div>       
        <div class="card">
            <h2 class="card__title">{{ title }}</h2>
            <p class="card__text">{{ text }}</p>
        </div>
    </div>    
</template>

<script>
export default {    
    props:['title', 'text'],
}
</script>

<style src="./card.scss" lang="scss">