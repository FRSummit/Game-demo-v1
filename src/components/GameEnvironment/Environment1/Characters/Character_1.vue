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
    },
    methods: {
        goRight() {
            // $(document).keypress(function (eventObject) {
                // console.log('eventObject.keyCode');
            // });
            // let top = document.querySelector('char1').offsetTop
            // console.log(top)
            // $('char1').css()
            let top = $('.char1').position()
            console.log(top)
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