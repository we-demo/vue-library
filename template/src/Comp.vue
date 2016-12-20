<style scoped>
h1 {
  font-weight: normal;
}
</style>

<template>
  <div>
    <img src="./assets/logo.png">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'Comp',
  props: {
    img: String,
    msg: String
  }
}
</script>
