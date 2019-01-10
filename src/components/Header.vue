<template>
    <header>
        <i class="material-icons icon">person</i>
        <h3>Witaj {{ user_name }} !</h3>
    </header>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      user_name: 'Kamila'
    }
  }
}
</script>

<style scoped>
    h3 {
        float: left;
        margin: 10px;
        color: #fff;
    }
    i {
        float: left;
        margin-left: 15px;
    }
    header {
        position: absolute;
        top: 0;
        left: 0;
    }
</style>
