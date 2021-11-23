<template>
    <h1>La mia prima app con Vue CLI!</h1>
</template>

<script>
export default {
  name: 'Title',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h1{
  background-color: wheat;
  margin: 0;
  max-width: 1200px;
}
</style>
