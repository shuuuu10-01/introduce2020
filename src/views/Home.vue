<template>
  <div class="home">
    <div class="anime1">
      <button @click="animeOn1">anime1</button>
      <svg viewBox="0 0 500 100">
          <g class="lines" fill="none" fill-rule="evenodd" stroke="currentColor" stroke-width="1">
              <path d="M144.4,35.1c-1.1-0.7-3.4-1.7-6.4-1.7c-5.1,0-7,3.1-7,5.8c0,3.6,2.2,5.4,7.1,7.5c5.9,2.5,8.9,5.5,8.9,10.8
                  c0,5.8-4.2,10.3-12.1,10.3c-3.3,0-6.9-1-8.7-2.3l1.1-3.3c2,1.3,4.9,2.3,7.9,2.3c4.9,0,7.8-2.6,7.8-6.6c0-3.6-2-5.8-6.7-7.7
                  c-5.5-2.1-9.3-5.3-9.3-10.3c0-5.6,4.5-9.6,11.2-9.6c3.5,0,6.1,0.9,7.5,1.7L144.4,35.1z"/>
              <path d="M170.4,60.9c0,2.2,0,4.4,0.4,6.2h-3.6l-0.4-3.4h-0.1c-1.3,2.1-4,3.9-7.7,3.9c-5,0-7.6-3.6-7.6-7.4c0-6.3,5.5-9.7,15.2-9.6
                  c0-2.2,0-7.2-6-7.2c-2.3,0-4.6,0.6-6.4,1.9l-1-2.7c2.1-1.4,5-2.2,8-2.2c7.4,0,9.3,5.2,9.3,10.4V60.9z M166.4,53.6
                  c-4.9,0-11.1,0.7-11.1,6.2c0,3.4,2.1,4.8,4.5,4.8c3.9,0,6.6-3,6.6-6.1V53.6z"/>
              <path d="M213.6,67.1h-3.9V52c0-5.1-1.8-8.4-5.8-8.4c-3.2,0-6.1,3-6.1,7v16.5h-3.9V51c0-4.2-1.8-7.3-5.5-7.3c-3.4,0-6.4,3.4-6.4,7.4
                  v16H178V47.7c0-2.7-0.1-4.6-0.2-6.8h3.5l0.2,4.2h0.1c1.4-2.5,3.8-4.8,8-4.8c3.4,0,6,2.1,7.2,5.2h0.1c1.7-3.1,4.4-5.2,8.4-5.2
                  c3.2,0,8.3,2.1,8.3,11V67.1z"/>
              <path d="M225.1,45.4c1.8-3.2,4.8-5,8.9-5c6.2,0,10.7,5.3,10.7,13.3c0,9.6-5.6,14-11.4,14c-3.5,0-6.3-1.6-7.9-4.2h-0.1v14.3h-4V49.4
                  c0-3.4-0.1-6-0.2-8.4h3.6L225.1,45.4L225.1,45.4z M225.4,56.7c0,5.1,3.8,7.8,7.3,7.8c5.1,0,8-4.4,8-10.7c0-5.4-2.7-10.2-7.8-10.2
                  c-4.5,0-7.5,4.3-7.5,8.1V56.7z"/>
              <path d="M254.7,67.1h-4V28.7h4V67.1z"/>
              <path d="M281.1,66c-1.5,0.7-4.2,1.6-8.2,1.6c-7.6,0-12.2-5.4-12.2-13.2c0-8.2,4.6-14.1,11.7-14.1c8.1,0,10.1,7.4,10.1,12
                  c0,0.9,0,1.6-0.1,2.2h-17.8c0,7.2,4.2,10,8.9,10c3.3,0,5.2-0.7,6.9-1.3L281.1,66z M278.6,51.5c0-3.6-1.4-8.2-6.6-8.2
                  c-4.8,0-6.9,4.6-7.3,8.2H278.6z"/>
              <path d="M310,34h-10.8v33.2h-4V34h-10.8v-3.4H310V34z"/>
              <path d="M332.4,66c-1.5,0.7-4.2,1.6-8.2,1.6c-7.6,0-12.2-5.4-12.2-13.2c0-8.2,4.6-14.1,11.7-14.1c8.1,0,10.1,7.4,10.1,12
                  c0,0.9,0,1.6-0.1,2.2h-17.8c0,7.2,4.2,10,8.9,10c3.3,0,5.2-0.7,6.9-1.3L332.4,66z M329.9,51.5c0-3.6-1.4-8.2-6.6-8.2
                  c-4.8,0-6.9,4.6-7.3,8.2H329.9z"/>
              <path d="M358.5,41l-8.6,12.7l8.9,13.5h-4.6l-3.9-6.1c-1-1.6-1.8-3-2.8-4.7h-0.1c-0.8,1.6-1.8,3.1-2.8,4.7l-3.8,6.1h-4.4l9-13.3
                  L336.8,41h4.5l3.8,5.8c1,1.5,1.8,2.8,2.6,4.4h0.1c0.8-1.5,1.7-3,2.6-4.4l3.7-5.8H358.5z"/>
              <path d="M364.4,36.2l3.9-1.3V41h6.8v3.1h-6.8v15.1c0,3.3,1,5.1,3.6,5.1c1.2,0,2-0.1,2.7-0.4l0.2,3.1c-0.9,0.4-2.2,0.6-3.9,0.6
                  c-6.3,0-6.5-5.8-6.5-8.5v-15h-4V41h4V36.2z"/>
          </g>
      </svg>
    </div>
    <div class="timeline">
      <button @click="timeline1">timeline</button>
      <h1 class="ml6">
        <span class="text-wrapper">
          <span class="letter">s</span>
          <span class="letter">h</span>
          <span class="letter">u</span>
          <span class="letter">u</span>
          <span class="letter">u</span>
          <span class="letter">u</span>
          <span class="letter">1</span>
          <span class="letter">0</span>
          <span class="letter">_</span>
          <span class="letter">0</span>
          <span class="letter">1</span>
        </span>
      </h1>
    </div>
  </div>
</template>

<script>
import anime from 'animejs'

export default {
  name: 'Home',
  methods: {
    animeOn1 () {
      anime({
        targets: '.lines path',
        strokeDashoffset: [anime.setDashoffset, 0],
        easing: 'easeInOutSine',
        duration: 500,
        delay: function (el, i) {
          return i * 250
        }
      })
    },
    timeline1 () {
      anime.timeline({ loop: false })
        .add({
          targets: '.ml6 .letter',
          translateY: ['1.3em', 0],
          translateZ: 0,
          duration: 800,
          delay: (el, i) => 50 * i
        })
    }
  }
}
</script>

<style scoped>
#lineDrawing {
    margin: 40px auto 0;
}
.ml6 {
  position: relative;
  font-weight: 900;
  font-size: 3.3em;
}

.ml6 .text-wrapper {
  position: relative;
  display: inline-block;
  padding-top: 0.2em;
  padding-right: 0.05em;
  padding-bottom: 0.1em;
  overflow: hidden;
}

.ml6 .letter {
  display: inline-block;
  line-height: 1em;
}
</style>
