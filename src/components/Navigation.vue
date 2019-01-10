<template lang="html">
  <nav>
    <ul>
      <li><a href=""></a><i class="material-icons icon active">home</i></li>
      <li><a href=""></a><i class="material-icons icon">search</i></li>
      <li><a href=""><i class="material-icons icon">favorite</i></a></li>
      <li><a href=""><i class="material-icons icon">menu</i></a></li>
    </ul>
  </nav>
</template>

<script lang="js">
export default {
  name: 'Navigation'
}
</script>

<style lang="scss" scoped>
  nav {
    position: fixed;
    bottom: 0;
    left: 0;
  }
  ul {
    padding: 0;
    display: grid;
    grid-template-columns: auto auto auto auto;
    width: 75%;
    margin: auto;
    list-style: none;
  }
  li {
    float: left;
    margin: 10px auto 10px auto;
  }
</style>
