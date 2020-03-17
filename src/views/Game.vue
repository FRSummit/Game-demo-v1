<template>
  <div class="home">
      <div class="menu-section">
        <div><img src="../assets/images/bullet-icon.png"/><v-btn to="/new-game" class="menu">New Game</v-btn></div>
        <div><img src="../assets/images/bullet-icon.png"/><v-btn to="/change-environment" class="menu">Change Environment</v-btn></div>
        <div><img src="../assets/images/bullet-icon.png"/><v-btn to="/change-character" class="menu">Change Character</v-btn></div>
        <div><img src="../assets/images/bullet-icon.png"/><v-btn to="/change-background" class="menu">Change Background</v-btn></div>
        <div><img src="../assets/images/bullet-icon.png"/><v-btn to="/high-score" class="menu">Highest Score</v-btn></div>
        <div><img src="../assets/images/bullet-icon.png"/><v-btn to="/exit" class="menu">Exit</v-btn></div>
      </div>
  </div>
</template>

<script>

export default {
  name: 'Home',
  components: {
  }
}
</script>

<style scoped>
.menu-section {
  width: 50%;
  margin: 20px auto;
  text-align: center;
}
.menu-section button,
.menu-section a {
  width: 80%;
  background-color: #5a270f !important;
  border: 1px solid #272727;
  margin: 4px;
  font-size: 16px;
  letter-spacing: 2px;
  color: #FFF;
  display: inline-block;
  font-weight: bold;
  padding-top: 8px !important;
}
.menu-section img {
  display: inline-block;
  width: 36px;
  vertical-align: middle;
}
</style>
