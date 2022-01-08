<template>
  <div>  
    <h1>{{ message }}</h1>
  </div>
</template>

<script>

export default {
  name: 'Header',
  props: {
    message: {
      type: String,
      default: 'TODO List'
    }
  }
}
</script>

<style scoped>
  header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}
</style>
