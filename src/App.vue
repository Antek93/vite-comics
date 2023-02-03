<script>
import AppHead from './components/AppHead.vue'; //importare ogni singolo componente che creiamo tramite queste linee di codice
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import AppMerchandise from './components/AppMerchandise.vue';

export default { //questa formula serve ad importante i componenti ed utilizzarli nel mio file
    name: 'App', //Name richiama il nome del file

    data () { //In data utilizziamo e richiamiamo gli elementi key che dichiariamo
        return { 
            msg: 'Ciao',
            count: 0,
            
        }

    },
    components: { //Qui richiamamo il nome dei file che abbiamo importato
      AppHead,
      AppMain,
      AppFooter,
      AppMerchandise
    }
}
</script>

<template>

    <div>
      <AppHead /> <!--Intestazione - header -->
    </div>
    <div>
      <AppMain /> <!--Corpo del sito - main -->
    </div> 
    <div>
      <AppMerchandise /> <!-- Sezione vendite - merchandise-->
    </div>
    <div>
      <AppFooter /> <!--Pié di pagina - footer -->
    </div>

</template>

<style lang="scss">
@use "./styles/main";
</style>

