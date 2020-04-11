<template>
    <div class="social">
        <ul class="social__list">
            <li class="social__list__item">
                <a :href="github"><i class="fab fa-github"></i></a>
            </li>

            <li class="social__list__item">
                <a :href="instagram"><i class="fab fa-instagram"></i></a>
            </li>

            <li class="social__list__item">
                <a :href="twitter"><i class="fab fa-twitter"></i></a>
            </li>
        </ul>
    </div>    
</template>

<script>
export default {
    data() {
        return {
            github: 'https://github.com/fogeid',
            instagram: 'https://www.instagram.com/fuckingfogeid/',
            twitter: 'https://twitter.com/fuckingfogeid',
        }
    }
}
</script>

<style src="./social.scss" lang="scss" scoped />