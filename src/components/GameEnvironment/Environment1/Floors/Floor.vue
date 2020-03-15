<template>
    <div class="floors">
        <div class="ground"></div>
        <img class="grass-img" src="../../../../assets/images/grass.png" alt="">
        <img class="soil-img" src="../../../../assets/images/soil.png" alt="">
        <div class="ground-divider-1"></div>
        <div class="ground-divider-2"></div>
        <div class="home-first-floor"></div>
        <div class="home-second-floor"></div>
        <div class="home-third-floor"></div>
        <div class="outside-stage-1"></div>
        <div class="outside-stage-2"></div>
    </div>
</template>

<style scoped>
.ground {
    border-bottom: 2px solid #222;
    position: absolute;
    bottom: 20%;
    width: 100%;
}
.grass-img {
    position: absolute;
    bottom: 18%;
    width: 15%;
}
.soil-img {
    position: absolute;
    bottom: 0;
    width: 15%;
    height: 18%;
}
.ground-divider-1 {
    background: #222;
    position: absolute;
    left: 15%;
    bottom: 0;
    width: 2px;
    height: 20%;
}
.ground-divider-2 {
    background: #222;
    position: absolute;
    left: 35%;
    bottom: 0;
    width: 2px;
    height: 20%;
}
.home-first-floor {
    border-bottom: 2px solid #222;
    position: absolute;
    bottom: 40%;
    right: 0;
    width: 60%;
}
.home-second-floor {
    border-bottom: 2px solid #222;
    position: absolute;
    bottom: 60%;
    right: 0;
    width: 50%;
}
.home-third-floor {
    border-bottom: 2px solid #222;
    position: absolute;
    bottom: 80%;
    right: 0;
    width: 35%;
}
.outside-stage-1 {
    border-bottom: 2px solid #222;
    position: absolute;
    bottom: 50%;
    left: 0;
    width: 15%;
}
.outside-stage-2 {
    border-bottom: 2px solid #222;
    position: absolute;
    bottom: 70%;
    left: 0;
    width: 20%;
}
</style>