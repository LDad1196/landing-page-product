<script>
export default {
    name: "AppHeader",
    data() {
        return {
            nav: [
                { name: "Home", id: "section1" },
                { name: "i punti di forza", id: "section2" },
                { name: "Recensioni", id: "section3" },
                { name: "Paperelle", id: "section4" },
                { name: "FAQs", id: "section5" },
                { name: "Newsletter", id: "section6" }
            ],
        }
    },

    methods: {
        
    },

    mounted() {

    }
}
</script>

<template>
    <header class="container d-flex justify-content-between align-items-center p-2">
        <div class="row m-0">
            <div class="col-3 p-0">
                <img src="/logo.png" alt="logo" class="img-fluid">
            </div>
            <div class="col-9 d-flex justify-content-end align-items-center">
                <div class="d-block d-md-none" data-bs-toggle="offcanvas" data-bs-target="#offcanvasRight" aria-controls="offcanvasRight">
                    <i class="fa-solid fa-bars text-black"></i>
                </div>
        
                <!-- Offcanvas -->
                <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasRight" aria-labelledby="offcanvasRightLabel" style="width: 70%;">
                    <div class="offcanvas-header">
                        <div class="img-container mx-4">
                            <img src="./img/logo.png" alt="Logo" style="width: 4rem; padding-bottom: 1rem;" />
                        </div>
                        <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
                    </div>
                    <div class="offcanvas-body">
                        <nav>
                            <ul v-for="(nav, name) in nav"></ul>
                        </nav>
                    </div>
                </div>
    
                <!-- Menu di navigazione per schermi più grandi -->
                 
                <ul class=" ul-header d-none d-md-flex justify-content-between align-items-center">
                    <!-- JavaScript -->
                </ul>
            </div>
        </div>
    </header>
</template>

<style scoped>
</style>