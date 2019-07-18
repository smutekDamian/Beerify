<template>
  <div id="app">
    <Header/>
    <PhotoSlider/>
    <PhotoSliderArrowed title="Nowości"/>
    <img src="./assets/logo.png">
    <router-view/>
    <Navigation/>
  </div>
</template>

<script>

import Navigation from './components/Navigation'
import Header from './components/Header'
import PhotoSlider from './components/PhotoSlider'
import PhotoSliderArrowed from './components/PhotoSliderArrowed'

export default {
  name: 'App',
  components: {
    Navigation,
    Header,
    PhotoSlider,
    PhotoSliderArrowed
  }
}
</script>

<style>
@import 'sass/main.scss';
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  text-align: center;
  color: #fff;
  margin-top: 60px;
}

</style>
