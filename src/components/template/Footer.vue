<template>
    <div>       
        <div class="footer">
            <p>2020 &copy; Developed by <a :href="site" target="_blank">Diego Batista</a></p>
        </div>
    </div>    
</template>

<script>
export default {
    data() {
        return {
            site: 'https://fogeid.github.io',            
        }
    }
}
</script>

<style src="./footer.scss" lang="scss">