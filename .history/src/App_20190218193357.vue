<template>
  <div id="app">
    <LandingComponent/>
  </div>
</template>

<script>
import LandingComponent from '@/components/LandingComponent.vue';
import Navbar from '@/components/Navbar.vue';
export default {
  name: 'app',
  components: {
    LandingComponent,
    Navbar
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
}

body {
  width: 100%;
  height: 1200px;
}

#app {

}

</style>
