<template>
  <div id="MyComponent">
    <h1 v-bind:title="message">Este es mi component</h1>
    <h2>{{subtitle}}</h2>
    <span v-if="seen">Now you see me</span>
    <hr>
        <label >computed {{reversedUUU}}</label>
    <div>
      <ul>Test</ul>
      <li v-bind:key="todo" v-for="todo in todos">{{todo}}</li>
    </div>
    <span v-once v-bind:style="styleObject">This will never change: {{ message }}</span>
    <p>{{binding}}</p>

    <input v-model="binding">
    <button v-on:click="reverseMessage">Reverse Sutitle</button>
  </div>
</template>

<script>
export default {
  name: "MyComponent",
  data() {
    return {
      subtitle: "Soy el subtitulo de mi componente",
      message: "You loaded this page on " + new Date().toLocaleString(),
      seen: true,
      todos: ["David", "Ana", "Felipe", "Jairo", "Mary"],
      binding: 'David', 
      styleObject: {
          color: 'blue',
          fontSize: '14px'
      }
    };
  },
  methods: {
    reverseMessage() {
      console.log("waaa");
      this.subtitle = this.subtitle
        .split("")
        .reverse()
        .join("");
    }
  },
  computed:{
      reversedUUU(){
          return this.subtitle.split('').reverse().join('')
      }
  }
};
</script>