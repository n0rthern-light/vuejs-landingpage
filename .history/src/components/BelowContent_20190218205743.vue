<template>
  <div class="below-content">
    <div class="slogan-container">
      <div class="image-slogan"></div>
      <h1>What to expect?</h1>
      <div class="divider-image"></div>
    </div>
    <div class="slogan-def-container">
      <div class="slogan-def-items">
          <div class="image-slogan"></div>
          <h1>Stable Enviroment</h1>
      </div>
      <div class="slogan-def-items">
          <div class="image-slogan"></div>
          <h1>Real Industries</h1>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'BelowContent'
}
</script>

<style>
.below-content {
  width: 90%;
  max-width: 1024px;
  margin: 150px auto 0 auto;
}

.slogan-container {
  text-align: center;
}

.image-slogan {
  margin: 0 auto 10px auto;
  background: url('https://d29fhpw069ctt2.cloudfront.net/icon/image/48978/preview.svg');
  background-repeat: no-repeat;
  width: 96px;
  height: 96px;
}

.divider-image {
  margin: 150px auto;
  background: url('https://d29fhpw069ctt2.cloudfront.net/icon/image/50495/preview.svg');
  background-repeat: no-repeat;
  background-size: 100%;
  width: 96px;
  height: 96px;
  transform: rotate(90deg);
}

.slogan-def-container {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}

.slogan-def-items {
  flex: 1;
  text-align: center;
}

</style>
