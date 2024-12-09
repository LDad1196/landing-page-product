<script>
export default {
    name: "AppHome",
    data() {
        return {
            
        }
    },

    methods: {
        
    },

    mounted() {

    }
}
</script>
    
<template>
    <section class="text-center">
        <div class="background py-3">
            <h1>Rubber Ducks</h1>
            <p>
                Spiegare il codice ad un paperella di gomma aiuta i programmatori a
                chiarire il pensiero e individuare errori nascosti.
            </p>
            <img class="img-banner" src="../assets/banner-image.png" alt="">
        </div>
    </section>
</template>

<style scoped>
    .background {
        background-image: url('./banner-bg.png');
        background-size: cover;
    };

    .img-banner {
        width: 50px;
        height: 50px;
    };
</style>