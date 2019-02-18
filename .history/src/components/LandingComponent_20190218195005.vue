<template>
  <div class="image">
    <span class="image-text disHighlight">
      discover supernatural.
    </span>
  </div>
</template>

<script>
export default {
  name: 'LandingComponent'
}
</script>

<style scoped>
.image {
  width: 100%;
  height: 50vh;
  background-image: url('https://apod.nasa.gov/apod/image/1212/ZetaOph_pia16604_full.jpg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center;
  background-size: cover;
  position: relative;
}

.image-text {
  font-size: 1.6em;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  color:white;
  background-color: rgba(255,255,255,0.1);
  padding: 10px;
  letter-spacing: 0.5em;
}



</style>
