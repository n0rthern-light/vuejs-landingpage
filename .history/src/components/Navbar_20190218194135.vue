<template>
  <div class="nav-content">
    <div class="nav-element disHighlight">
      <span>supernatural.net</span>
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

.nav-elemet span {

}

.nav-element:hover {
  text-decoration: underline;
  cursor: pointer;
}

</style>
