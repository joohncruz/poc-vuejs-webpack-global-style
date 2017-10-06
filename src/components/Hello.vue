<template>
  <div class="hello">
    <div class="teste"> AA</div>
    <div class="teste-url"> BB</div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">

.teste {
  color: $auxiliary-color;
  background-image: url('../assets/icons/ico_atalho.png')
}

</style>
