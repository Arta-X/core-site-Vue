<template>
  <div class="component-container">
    <video
      :src="video_src"
      poster="https://play.teleporthq.io/static/svg/videoposter.svg"
      class="component-video"
    ></video>
  </div>
</template>

<script>
export default {
  name: 'AppComponent',
  props: {
    video_src: String,
  },
}
</script>

<style scoped>
.component-container {
  display: flex;
  position: relative;
}
.component-video {
  width: 320px;
  height: 180px;
}
</style>
