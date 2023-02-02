<script>
import AppHead from './components/AppHead.vue'; //importare ogni singolo componente che creiamo tramite queste linee di codice
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

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
      AppFooter
    }
}
</script>

<template>
  <div class="mainContainer">
    <div>
      <AppHead /> <!--Intestazione - header -->
    </div>
    <div>
      <AppMain /> <!--Corpo del sito - main -->
    </div> 
    <div>
      <AppFooter /> <!--Pié di pagina - footer -->
    </div>
  </div>
</template>

<style lang="scss">
@use "./styles/main";
.mainContainer {
    width: 70%;
    margin: 0 auto;
}
</style>


