<script>
import AppTitle from './components/AppTitle.vue'; //importare ogni singolo componente che creiamo tramite queste linee di codice
import AppHero from './components/AppHero.vue';

export default { //questa formula serve ad importante i componenti ed utilizzarli nel mio file
    name: 'App', //Name richiama il nome del file

    data () { //In data utilizziamo e richiamiamo gli elementi key che dichiariamo
        return { 
            msg: 'Ciao',
            count: 0,
        }

    },
    components: { //Qui richiamamo il nome dei file che abbiamo importato
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
