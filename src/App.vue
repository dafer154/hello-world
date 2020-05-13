<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="David Fernando Zuluaga" title="TEST" />
    <hr />
    <MyComponent /> -->
    <!-- <StartPage /> -->
    <!-- <Login/> -->
    <invitationStudents/>
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
// import MyComponent from "./components/MyComponent.vue";
// import StartPage from './components/StartPage.vue';
import InvitationStudents from './components/InvitationStudents.vue';
// import Login from './components/Login.vue'

export default {
  name: "App",
  components: {
    // HelloWorld,
    // MyComponent
    // StartPage
    // Login
    InvitationStudents
  }
};
</script>

<style>

body{
  margin: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
