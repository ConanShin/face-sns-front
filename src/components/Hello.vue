<template>
  <body style='margin : 0px; overflow: hidden;'>
    <a-scene embedded arjs='sourceType: webcam;'>
      <a-box position='0 0.5 0' material='opacity: 0.5;'></a-box>
      <a-marker-camera preset='hiro'></a-marker-camera>
    </a-scene>
  </body>
</template>
<script>
import { Vue, Component } from 'vue-property-decorator'

@Component
export default class Hello extends Vue {
  name = 'Hello'
}
</script>
<style>
</style>
