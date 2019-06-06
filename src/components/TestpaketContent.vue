<template>
  <div>
    <div id="wrapper">
      <div id="left">         
       <div class="oekotex-wrapper">
                  <div class="trialpack-slider flexslider">
                    <ul class="slides">
                        <li 
                          v-for="(item, index) in testPaket"                       
                          :key="index"
                          v-show="isActive(index)">
                          <img :src="require(`../assets/images/lillydoo-testpaket-${item.testpaket}.jpg`)">         
                        </li>                        
                    </ul>
                </div>
            </div>
      </div>
      <div id="right">
           <form class="addToCartTrialbox">
              <h2>Unser gratis Testpaket</h2>
       <div class="tb-button-container">
                  <p>Wähle Deine Größe</p>
                  <ul>
                    <li 
                     v-for="(item, index) in testPaket"
                     v-on:click="method_1(index)" 
                     :class="{active: isActive(index)}"
                     :key="index">
                        <p>{{item.size}}</p>
                        <span>({{item.weight}} KG)</span> 
                    </li>                     
                  </ul>
                  
              </div>
              <p>Teste jetzt unsere Windeln und Feuchttücher - In Größe 1 - 3 enthält unser Testpaket unsere Feuchttücher mit 99 % Wasser, ab Gr. 4 erhältst Du unsere Sensitiven Feuchttücher. Wir zahlen die Produkte, Du nur den Versand.</p>
            <ul class="product-list">
                <!--<li>10 LILLYDOO Windeln <span class="diaper-design">im Design "Little Blowballs"</span> +&nbsp;15 unserer sensitiven Feuchttücher</li>
                        <li class="size-explanation-holder">Größe 4 für ein Gewicht von 4-9 Kilo</li>-->
                <li class="primary-color">Automatischer Übergang ins jederzeit kündbare Windel-Abo für 49,50&nbsp;€ pro Lieferung.</li>
                <li>Preise inkl. MwSt., ggf. zzgl. <a href="/de/zahlung-und-versand" target="_blank" rel="noreferrer noopener">Versandkosten</a></li>
            </ul>
            <div class="trialbox-button">
                <button data-in-stock-label="In den Warenkorb legen" data-out-of-stock-label="Derzeit leider nicht verfügbar" data-config-url="/de/testpaket/konfigurator/REPLACESKU"><span>In den Warenkorb legen</span></button>
            </div>
        </form>

      </div>
    </div>
 </div>
</template>

<script>
export default {
  name: "TestpaketContent",
  props: ['testPaket'],
  data() {
    return { activeIndex: 0 }
  },
  methods: {
  method_1: function(index){
   this.activeIndex = index; 
  },
  isActive: function (index) {
      return this.activeIndex === index
    } 
}
};
</script>
<style scoped>
@import '../assets/css/TestPaket.scss';
</style>
