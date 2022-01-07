<template>
  <div id="app">
    <Header></Header>
    <MainForm :items="tasks"></MainForm>
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App    ***"/>
    
  </div>
</template>

<script>
import Header from './components/Header.vue'
import HelloWorld from './components/HelloWorld.vue'
import MainForm from './components/MainForm.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Header,
    MainForm
  },
  data () {
    tasks: [
      {
        msg: "Dentist",
        id: 0
      },
      { msg: "Dinner with Sam",
        id: 1
      }
    ]
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
