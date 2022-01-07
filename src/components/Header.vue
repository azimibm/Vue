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
      default: 'No TODOS'
    }
  }
}
</script>
