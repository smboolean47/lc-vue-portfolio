<template>
    <header class="header bg-primary-color">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-4">
                    <h1>Samuele Madrigali</h1>
                </div>
                <div class="col-8">
                    <NavBar />
                </div>
            </div>
        </div>
    </header>
</template>

<script>
import NavBar from '../elements/NavBar.vue';

export default {
    name: 'Header',
    components: {
        NavBar
    }
}
</script>

<style lang="scss" scoped>
.header {
    position: sticky;
    top: 0;
    z-index: 10;
    padding: 20px 0;
    border-bottom: 1px solid #fff;
}
</style>