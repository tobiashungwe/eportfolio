<template>
  <nav id="navbar">
    <div>
      <h1>JDP</h1>
      <button v-on:click="swapNav()">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-three-dots-vertical" viewBox="0 0 16 16">
          <path d="M9.5 13a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0zm0-5a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0zm0-5a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0z"></path>
        </svg>
      </button>
    </div>
    <ul id="navList" class="">
      <li class="active">
        <a class="" href="#Hero">Home</a>
      </li>
      <li class="">
        <a class="" href="#About">About</a>
      </li>
      <li class="">
        <a class="" href="#">Resume</a>
      </li>
      <li class="">
        <a class="" href="#">Portofolio</a>
      </li>
      <li class="">
        <a class="" href="#">&lt;Contact&gt;</a>
      </li>

    </ul>
  </nav>

</template>
<script>


import $ from "jquery";

export default {

  name: "Nav",
  props: {
    msg: String
  }, methods:{
    swapNav: function () {
      console.log("Test")
      $('#navList').toggle();
    }
  }
}


</script>

<style scoped>

</style>
