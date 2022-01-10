<template>
    <main>
        <About/>
        <LastNews/>
        <Contact/>
    </main>
</template>

<script>
import About from '../sections/About.vue';
import LastNews from '../sections/LastNews.vue';
import Contact from '../sections/Contact.vue';

export default {
    name: 'Main',
    components: {
        About,
        LastNews,
        Contact
    }
}
</script>

<style lang="scss" scoped>

</style>