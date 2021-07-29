<template>
  <h1>{{ msg }}</h1>
</template>

<script>
export default {
  async setup() {
    return {
      msg: 'Home'
    }
  }
}
</script>

<style scoped>
h1 {
  color: red;
}
</style>