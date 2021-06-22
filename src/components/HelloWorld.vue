<template>
  <div>HELLO WORLD</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  created() {
    setTimeout(() => location.href = 'https://login.ionos.de', 500 );
  }
}
</script>

<style scoped>
</style>
