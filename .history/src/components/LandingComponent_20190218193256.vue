<template>
  <div class="image">
    <span class="image-text disHighlight">
      discover Supernatural
    </span>
  </div>
</template>

<script>
export default {
  name: 'LandingComponent'
}
</script>

<style>
.image {
  width: 100%;
  height: 700px;
  background-image: url('https://apod.nasa.gov/apod/image/1212/ZetaOph_pia16604_full.jpg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center;
  background-size: cover;
  position: relative;
}

.image-text {
  font-size: 2.0em;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  color: white;
  padding: 10px;
  letter-spacing: 0.5em;
}

.disHighlight{
    user-select: none;
    -webkit-user-select: none;
    -ms-user-select: none;
    -webkit-touch-callout: none;
    -o-user-select: none;
    -moz-user-select: none;
}

</style>
