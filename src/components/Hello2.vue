<template>
    <div>
     <p>This is the Hello2 component</p>
        <button @click="onClickHello">Back</button>
    </div>
</template>

<script>
  export default {
    name: 'Hello2',
    methods: {
      onClickHello() {
        this.$router.push('/')
      }
    }
  }
</script>

<style scoped>

</style>