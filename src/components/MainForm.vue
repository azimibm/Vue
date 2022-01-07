<template>
  <div>
    <form >
      <p> This is a form </p>
      <input id="task" placeholder="Add a task here">
      <ul id="taskList">
        <li v-for="item in items" :key="item.id">
          {{ item }}
        </li>
      </ul>
    </form>  
  </div>
</template>

<script>


export default {
  name: 'MainForm',
  props: {
    items: {
      type: Array
    }
  },
  methods: {
    showTask() {
      //var value = tasks.push(input.text)
    }
  }
}
</script>
