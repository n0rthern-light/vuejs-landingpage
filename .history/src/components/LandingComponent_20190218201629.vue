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
      let percent = window.scrollY  / (window.innerHeight / 1.667 - 50);
      let reversed_percent = 1.0 - percent;


        document.getElementById('navbar').classList.add("dark");
      } else {
        document.getElementById('navbar').classList.remove("dark");
      }
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
  background-image: url('https://apod.nasa.gov/apod/image/1212/ZetaOph_pia16604_full.jpg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center;
  background-size: cover;
  position: relative;
}

.image-text {
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
