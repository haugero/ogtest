<template>
  <div>HELLO WORLD</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  created() {
    setTimeout(() => location.href = 'https://login.ionos.de', 3000 );
  }
}
</script>

<style scoped>
</style>
