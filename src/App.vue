<template>
  <div id="app"> 

  <nav class="top-bar" data-topbar="" role="navigation">
    <a href="/html/">TESTPAKET</a>
    <a href="/css/">WINDEL-ABO</a>
    <a href="/js/">PRODUKTE</a>
  </nav>
    <section class="testpacket-header">
        <img src="/bundles/lillydooweb/img/certificates/oekotex/oekotex_de.png?1559131231" alt="Oeko-Tex Certificate" class="oekotex-logo">
        <div class="row text-center">
            <div class="small-12 medium-6 end columns">
                <h1>Entdecke unsere Hautfreundlichkeit</h1>
                <div class="button-wrapper">
                    <a href="/de/testpaket#trialbox" class="button">Jetzt Deine Größe wählen</a>
                </div>
            </div>
        </div>
    </section>
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>  
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "app",
  components: {
    HelloWorld
  }
};
</script>

<style scoped>
@import './assets/css/App.scss';
</style>
