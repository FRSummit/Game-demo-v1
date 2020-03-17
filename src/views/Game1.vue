<template>
    <div class="game" id="game">
        <div class="exit" @click="exitClick"><v-btn to="/" class="menu">Exit to Menu</v-btn></div>
        <Stage1/>
        <Background1/>
        <Character1 id="character"/>
    </div>
</template>

<script>
import Stage1 from '../components/GameEnvironment/Environment1/Stages/Stage_1'
import Background1 from '../components/GameEnvironment/Environment1/Backgrounds/Background_1'
import Character1 from '../components/GameEnvironment/Environment1/Characters/Character_1'
import $ from 'jquery'

export default {
    components: {
        Stage1,
        Background1,
        Character1,
    },
    methods: {
        exitClick() {
            $('.navbar').css('display', 'block')
        },
        // goRight(e) {
        //     let charPosition_X = $(window).height() - $('#character').height();
        //     console.log(charPosition_X)
        //     if(String.fromCharCode(e.keyCode) === 'W' || String.fromCharCode(e.keyCode) === 'w') {
        //         console.log('I am W/w')
        //         document.getElementById('.character').style.bottom = charPosition_X + 300 + 'px'
        //     }
        // }
    },
    created() {
        $('.navbar').css('display', 'none')
    },
    mounted() {
        // window.addEventListener("keypress", function(e) {
        //     this.goRight(e)
        // }.bind(this));
    }
}
</script>

<style scoped>
.game {
  /* position: relative;
  height: 500px; */
  background: #BDF2FD;
  /* margin-top: -48px; */
}
.exit a {
  background-color: #380101 !important;
  border: 1px solid #272727;
  margin: 4px;
  font-size: 16px;
  letter-spacing: 2px;
  color: #FFF;
  text-transform: none;
  padding: 0 6px !important;
  height: 24px !important;
  position: absolute;
  left: 0;
  z-index: 10;
}
</style>