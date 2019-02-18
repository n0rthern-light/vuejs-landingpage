<template>
  <div class="image">
    <span class="image-text disHighlight" id="herotext">
      discover supernatural.
    </span>
  </div>
</template>

<script>
export default {
  name: 'LandingComponent',
  methods: {
    handleScroll () {
      let percent = window.scrollY  / (window.innerHeight / 4);
      let reversed_percent = 1.0 - percent;


     document.getElementById('herotext').style.opacity = reversed_percent;
    }
  },
  created () {
    window.addEventListener('scroll', this.handleScroll);
  },
  destroyed () {
    window.removeEventListener('scroll', this.handleScroll);
  }
}
</script>

<style scoped>
.image {
  width: 100%;
  height: 59vh;
  background-image: url('https://images.unsplash.com/photo-1530482817083-29ae4b92ff15?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1351&q=80');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center;
  background-size: cover;
  position: relative;
}

.image-text {
  width: 100%;
  text-align: center;
  font-size: 1.6em;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  color:white;
  padding: 10px;
  letter-spacing: 0.5em;
  transform: background-color 0.5s ease;
}

</style>
