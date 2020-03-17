<template>
    <div class="character-1">
        <img class="char1" src="../../../../assets/images/fire-char-1.png" alt="">
    </div>
</template>

<script>
// import $ from 'jquery'

export default {
    created() {
        // console.log('working')
        // let char1 = $('.char1').position()
        // console.log(char1)
        // var bottom = $(window).height() - $('.character-1').height();
        // console.log(bottom)
    },
    mounted() {
        window.addEventListener("keypress", function(e) {
            // console.log(String.fromCharCode(e.keyCode));
            // console.log(e.keyCode);
            // if(e.key == "Enter") {
            //     console.log("enter pressed!");
            // }
            this.goRight(e)
        }.bind(this));
    },
    methods: {
        goRight(e) {
            // let charPosition_X = $(window).height() - $('.character-1').height();
            // console.log(charPosition_X)
            // console.log(document.querySelector('.char1').getBoundingClientRect())
            // // let charPosition_X = $(window).height() - $('.char1').height();
            // console.log(String.fromCharCode(e.keyCode));

            if(String.fromCharCode(e.keyCode) === 'W' || String.fromCharCode(e.keyCode) === 'w') {
                // console.log('I am W/w')
                document.querySelector('.character-1').style.bottom += 100 + 'px'
            }
            if(String.fromCharCode(e.keyCode) === 'S' || String.fromCharCode(e.keyCode) === 's') {
                // console.log('I am S')
                document.querySelector('.character-1').style.bottom += 200 + 'px'
            }
        }
        
    }
}
</script>

<style scoped>
.character-1 {
    position: absolute;
    bottom: 20%;
    bottom: 50px;
    left: 0;
    z-index: 15;
}
</style>