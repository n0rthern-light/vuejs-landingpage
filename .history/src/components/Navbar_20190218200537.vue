<template>
  <div class="nav-content" id="navbar">
    <div class="nav-element disHighlight" style="flex: 16;">
      supernatural.net
    </div>
    <div class="nav-element disHighlight" style="flex: 11;">
      merchendise
    </div>
    <div class="nav-element disHighlight" style="flex: 5;">
      about
    </div>
    <div class="nav-element disHighlight" style="flex: 7;">
      sign up
    </div>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  data () {
    return {
      dark: false
    }
  },
  methods: {
    handleScroll () {
      if(window.scrollY  >= (window.innerHeight * 0.5) - 25){
        this.dark = true;
      } else {
        this.dark = false;
      }

      if(this.dark) {
        document.getElementById('navbar').classList.add("sticky");
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
.nav-content {
  z-index: 9999;
  position: fixed;
  top: 0;
  width: 100%;
  color: white;
  display: flex;

}

.nav-element {
  padding: 15px 25px;
  flex: 1;
  text-align: center;
  transition: all 0.5s ease;
  letter-spacing: 0.3em;
}

.nav-element:hover {
  cursor: pointer;
  background-color: rgba(255,255,255,0.8);
  color: black;
}

</style>
