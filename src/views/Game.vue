<template>
    <div class="game" id="game">
        <div class="exit"><v-btn to="/" class="menu">Exit to Menu</v-btn></div>
        <Stage1/>
        <Background1/>
        <Character1/>
    </div>
</template>

<script>
import Stage1 from '../components/GameEnvironment/Stages/Stage_1'
import Background1 from '../components/GameEnvironment/Backgrounds/Background_1'
import Character1 from '../components/GameEnvironment/Characters/Character_1'
// import $ from 'jquery'

export default {
    components: {
        Stage1,
        Background1,
        Character1,
    },
    methods: {
    },
    created() {
    },
    mounted() {
    }
}
</script>

<style scoped>
.game {
  position: relative;
  height: 500px;
}
.exit a {
  background-color: #380101 !important;
  border: 1px solid #272727;
  margin: 4px;
  font-size: 16px;
  letter-spacing: 2px;
  color: #FFF;
  position: absolute;
  right: 0;
  text-transform: none;
  padding: 0 6px !important;
  height: 24px !important;
}
</style>