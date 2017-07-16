<template>
  <div>
    <h1>{{siteName}}</h1>
  </div>
</template>

<script>
export default {
  props: ['siteName']
}
</script>

<style lang="sass" scoped>
h1
  color: green
</style>
