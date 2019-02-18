<template>
  <div class="nav-content">
    <div class="nav-element disHighlight" style="flex: 16;">
      supernatural.net
    </div>
    <div class="nav-element disHighlight" style="flex: 16;">
      merchendise
    </div>
    <div class="nav-element disHighlight" style="flex: 16;">
      about
    </div>
    <div class="nav-element disHighlight" style="flex: 16;">
      sign up
    </div>
  </div>
</template>

<script>
export default {
  name: 'Navbar'
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
  background-color: rgba(255,255,255,0.9);
  color: black;
}

</style>
