<template>
  <div id="app">
    <Navbar/>
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

.disHighlight{
    user-select: none;
    -webkit-user-select: none;
    -ms-user-select: none;
    -webkit-touch-callout: none;
    -o-user-select: none;
    -moz-user-select: none;
}

#app {

}

</style>
