<template>
  <div class="below-content">
    <div class="slogan-container">
      <div class="image-slogan"></div>
      <h1>What to expect?</h1>
    </div>
    <div class="slogan-def-container">
      <div>
          <div class="image-slogan"></div>
          <h1>What to expect?</h1>
      </div>
      <div>
          <div class="image-slogan"></div>
          <h1>What to expect?</h1>
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
  width: 96px;
  height: 96px;
}

.slogan-def-container {
  width: 100%;
  display: flex;
}

.slogan-def-items {
  display: flex;
}

</style>
