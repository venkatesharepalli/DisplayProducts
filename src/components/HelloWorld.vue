<template>
  <div>
    <div id="wrapper">
      <div id="left">
       <div class="oekotex-wrapper">
                  <div class="trialpack-slider flexslider">
                    <ul class="slides">
                        <li class="flex-active-slide" style="width: 100%; float: left; margin-right: -100%; position: relative; opacity: 1; display: block; z-index: 2;">
                            <img itemprop="image" src="../assets/images/lillydoo-testpaket-10.jpg" alt="Lillydoo Testpaket mit Windeln in Größe 1 und 15 Feuchttüchern" draggable="false">
                        </li>
                        <li style="width: 100%; float: left; margin-right: -100%; position: relative; opacity: 0; display: block; z-index: 1;">
                            <img itemprop="image" src="../assets/images/lillydoo-testpaket-20.jpg" alt="Lillydoo Testpaket mit Windeln in Größe 2 und 15 Feuchttüchern" draggable="false">
                        </li>
                        <li style="width: 100%; float: left; margin-right: -100%; position: relative; opacity: 0; display: block; z-index: 1;">
                            <img itemprop="image" src="../assets/images/lillydoo-testpaket-30.jpg" alt="Lillydoo Testpaket mit Windeln in Größe 3 und 15 Feuchttüchern" draggable="false">
                        </li>
                        <li style="width: 100%; float: left; margin-right: -100%; position: relative; opacity: 0; display: block; z-index: 1;">
                            <img itemprop="image" src="../assets/images/lillydoo-testpaket-40.jpg" alt="Lillydoo Testpaket mit Windeln in Größe 4 und 15 Feuchttüchern" draggable="false">
                        </li>
                        <li style="width: 100%; float: left; margin-right: -100%; position: relative; opacity: 0; display: block; z-index: 1;">
                            <img itemprop="image" src="../assets/images/lillydoo-testpaket-50.jpg" alt="Lillydoo Testpaket mit Windeln in Größe 5 und 15 Feuchttüchern" draggable="false">
                        </li>
                    </ul>
                </div>
            </div>
      </div>
      <div id="right">
       <div class="tb-button-container">
                  <p>Wähle Deine Größe</p>
                  <ul>
                      <li data-size="10" data-prdctimg="../assets/images/diaperdesign_little_blowballs.jpg?1559131231" data-design="./assets/images/diapers_design_lilly_d_hover.png?1559131231" class="flex-active">
                          <p>1</p>
                          <span>(2-3 KG)</span>
                      </li>
                      <li data-size="20" data-prdctimg="../assets/images/diaperdesign_little_blowballs.jpg?1559131231" data-design="./assets/images/diapers_design_lilly_d_hover.png?1559131231">
                          <p>2</p>
                          <span>(3-4 KG)</span>
                      </li>
                      <li data-size="30" data-prdctimg="../assets/images/diaperdesign_little_blowballs.jpg?1559131231" data-design="./assets/images/diapers_design_lilly_d_hover.png?1559131231">
                          <p>3</p>
                          <span>(4-7 KG)</span>
                      </li>
                      <li data-size="40" data-prdctimg="../assets/images/diaperdesign_lilly_d.jpg?1559131231" data-design="./assets/images/diapers_design_little_blowballs_hover.png?1559131231">
                          <p>4</p>
                          <span>(7-10 KG)</span>
                      </li>
                      <li data-size="50" data-prdctimg="../assets/images/diaperdesign_the_new_baby_blue.jpg?1559131231" data-design="./assets/images/diapers_design_the_new_baby_blue.png?1559131231">
                          <p>5</p>
                          <span>(10-12 KG)</span>
                      </li>
                  </ul>
              </div>

      </div>
    </div>
 </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>
<style scoped>
@import '../assets/css/HelloWorld.scss';
</style>
