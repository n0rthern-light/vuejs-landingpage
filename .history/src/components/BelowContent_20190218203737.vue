<template>
  <div class="below-content">
    <div class="slogan-container">
      <h1>What to expect?</h1>
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
  max-width: 768px;
  margin: 150px auto 0 auto;
}

.slogan-container {
  text-align: center;
  width: 100%;
}

.slogan-container::before {
  background: url('https://d29fhpw069ctt2.cloudfront.net/icon/image/48978/preview.svg');
}
</style>
