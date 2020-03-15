<template>
    <div class="game">
        <div class="exit"><v-btn to="/exit-to-menu" class="menu">Exit to Menu</v-btn></div>
        <Stage1/>
    </div>
</template>

<script>
import Stage1 from '../components/GameEnvironment/Stages/Stage_1'
export default {
    components: {
        Stage1,
    }
}
</script>

<style scoped>
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