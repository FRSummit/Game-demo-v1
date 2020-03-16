<template>
    <div class="character-1">
        <img class="char1" @click="goRight" src="../../../../assets/images/fire-char-1.png" alt="">
    </div>
</template>

<script>
import $ from 'jquery'

export default {
    created() {
        console.log('working')
        let char1 = $('.char1').position()
        console.log(char1)
    },
    mounted() {
        window.addEventListener("keypress", function(e) {
            console.log(String.fromCharCode(e.keyCode));
        }.bind(this));
    },
    methods: {
        goRight() {
            console.log('click')
            // $(document).keypress(function (eventObject) {
                // console.log('eventObject.keyCode');
            // });
            // let top = document.querySelector('char1').offsetTop
            // console.log(top)
            // $('char1').css()
            let char1 = parseInt(document.querySelector('.char1').style.bottom)
            // document.querySelector('.char1').style.left = char1 + 'px';
            console.log(char1)
        }
        
    }
}
</script>

<style scoped>
.character-1 {
    position: absolute;
    bottom: 20%;
    left: 0;
    z-index: 15;
}
</style>