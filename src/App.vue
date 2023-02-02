<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
    name: 'App',

    data () {
        return {
            msg: 'Ciao',
            count: 0,
        }

    },
    components: {
      AppTitle,
      AppHero
    }
}
</script>

<template>
    <div>
      <AppTitle />
    </div>
    <div>
      <AppHero />
    </div>
</template>

<style scoped>

</style>
