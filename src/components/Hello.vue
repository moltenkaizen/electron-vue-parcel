<template>
    <div>
        <p>This is the Hello component</p>
        <button @click="onClickGo">Go</button>
    </div>
</template>

<script>
  export default {
    name: 'Hello',
    methods: {
      onClickGo() {
        this.$router.push('/hello2')
      }
    }
  }
</script>


<style scoped>
    p {
        color: deeppink;
    }
</style>
