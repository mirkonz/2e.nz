<template>
<div class="min-h-screen flex justify-center items-center  bg-gradient-to-b from-gray-500 to-gray-100">


    <svg viewBox="0 0 165 160" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xml:space="preserve" xmlns:serif="http://www.serif.com/" style="fill-rule:evenodd;clip-rule:evenodd;stroke-linejoin:round;stroke-miterlimit:2;" class="h-40">
      <g transform="matrix(0.998597,0,0,1,-0.93129,-0.266394)">
          <rect x="0.933" y="0.266" width="165.232" height="159.975"/>
      </g>
      <g transform="matrix(1.02782,0,0,0.996523,-0.316029,0.301973)">
          <rect x="21.712" y="19.767" width="19.459" height="118.409" style="fill:white;"/>
      </g>
      <g transform="matrix(1.02782,0,0,0.996523,42.684,0.301973)">
          <rect x="21.712" y="19.767" width="19.459" height="118.409" style="fill:white;"/>
      </g>
      <g transform="matrix(2.3126,0,0,0.169055,49.7889,16.6583)">
          <rect x="21.712" y="19.767" width="19.459" height="118.409" style="fill:white;"/>
      </g>
      <g transform="matrix(2.3126,0,0,0.169055,49.7889,66.6583)">
          <rect x="21.712" y="19.767" width="19.459" height="118.409" style="fill:white;"/>
      </g>
      <g transform="matrix(2.3126,0,0,0.169055,49.7889,114.658)">
          <rect x="21.712" y="19.767" width="19.459" height="118.409" style="fill:white;"/>
      </g>
    </svg>

    <div class="ml-6 text-7xl font-medium">
      Digital<br>
      Works
    </div>

  </div>

</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  head() {
    return {
      script: [
        { src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }
      ]
    }
  }
})
</script>
