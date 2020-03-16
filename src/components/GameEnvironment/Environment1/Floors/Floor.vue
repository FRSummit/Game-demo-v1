<template>
    <div class="floors">
        <div class="ground"></div>
        <img class="grass-img" src="../../../../assets/images/grass.png" alt="">
        <img class="soil-img" src="../../../../assets/images/soil.png" alt="">
        <img class="water-pool-img" src="../../../../assets/images/water-pool-3.png" alt="">
        <div class="ground-divider-1"></div>
        <div class="ground-divider-2"></div>
        <div class="home-first-floor"></div>
        <div class="home-second-floor"></div>
        <div class="home-third-floor"></div>
        <img class="home-first-floor-img" src="../../../../assets/images/floor-1.png" alt="">
        <img class="home-second-floor-img" src="../../../../assets/images/floor-2.png" alt="">
        <img class="home-third-floor-img" src="../../../../assets/images/floor-3.png" alt="">
        <div class="outside-stage-1"></div>
        <div class="outside-stage-2"></div>
        <img class="outside-stage-img-1" src="../../../../assets/images/outside-stage.png" alt="">
        <img class="outside-stage-img-2" src="../../../../assets/images/outside-stage.png" alt="">
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
.water-pool-img {
    position: absolute;
    bottom: 0;
    left: 15%;
    width: 20%;
    height: 21%;
    z-index: 3;
}
/* .ground-divider-1 {
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
} */
/* .home-first-floor {
    border-bottom: 2px solid #4c2626;
    position: absolute;
    bottom: 39%;
    right: 0;
    width: 65%;
    z-index: 2;
} */
.home-first-floor-img {
    position: absolute;
    bottom: 20%;
    right: 0;
    width: 65%;
    height: 25%;
    z-index: 2;
}
/* .home-second-floor {
    border-bottom: 2px solid #222;
    position: absolute;
    bottom: 60%;
    right: 0;
    width: 50%;
} */
.home-second-floor-img {
    position: absolute;
    bottom: 40%;
    right: 0;
    width: 55%;
    height: 25%;
}
/* .home-third-floor {
    border-bottom: 2px solid #222;
    position: absolute;
    bottom: 80%;
    right: 0;
    width: 35%;
} */
.home-third-floor-img {
    position: absolute;
    bottom: 65%;
    right: 0;
    width: 40%;
    height: 25%;
    z-index: 2;
}
/* .outside-stage-1 {
    border-bottom: 2px solid #222;
    position: absolute;
    bottom: 50%;
    left: 0;
    width: 15%;
} */
.outside-stage-img-1 {
    position: absolute;
    bottom: 40%;
    left: 0;
    width: 15%;
    height: 15%;
}
/* .outside-stage-2 {
    border-bottom: 2px solid #222;
    position: absolute;
    bottom: 70%;
    left: 0;
    width: 20%;
} */
.outside-stage-img-2 {
    position: absolute;
    bottom: 60%;
    left: 0;
    width: 20%;
    height: 15%;
}
</style>