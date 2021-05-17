<template>

  <div id="app">
    <Nav></Nav>
    <Hero></Hero>
    <About></About>
    <Resume></Resume>
  </div>
</template>

<script>
import Nav from "./components/Nav";
import Hero from "@/components/Hero";
import About from "@/components/About";
import Resume from "@/components/Resume";

export default {
  name: 'App',
  components: {
    Nav,
    Hero,
    About,
    Resume
  }
}
</script>

<style scoped >

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
