<template>

  <div id="app">
    <Nav></Nav>
    <Hero></Hero>
    <About></About>
    <Skills></Skills>
    <Resume></Resume>
    <Portfolio></Portfolio>
    <Contact></Contact>
  </div>
</template>

<script>
import Nav from "./components/Nav";
import Hero from "@/components/Hero";
import About from "@/components/About";
import Resume from "@/components/Resume";
import Skills from "@/components/Skills";
import Portfolio from "@/components/Portfolio";
import Contact from "@/components/Contact";

export default {
  name: 'App',
  components: {
    Nav,
    Hero,
    Skills,
    About,
    Resume,
    Portfolio,
    Contact
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
