<template>
  <div class="nav-content">
    <div class="nav-element disHighlight">
      supernatural.net
    </div>
    <div class="nav-element disHighlight">
      supernatural.net
    </div>
    <div class="nav-element disHighlight">
      supernatural.net
    </div>
    <div class="nav-element disHighlight">
      supernatural.net
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
  padding: 15px 25px;
  display: flex;
}

.nav-element {
  flex: 1;
}

.nav-element:hover {
  text-decoration: underline;
  cursor: pointer;
}

</style>
