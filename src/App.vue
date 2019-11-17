<template>
  <div id="app">
    <navbar />
    <text1 />
    <aboutbar />
    <codefield />
    <githubfield />
    <coinsort />
    <vuefooter />
  </div>
</template>

<script>
import "@/assets/css/main.css";
import navbar from "./components/navbar";
import text1 from "./components/text1";
import aboutbar from "./components/aboutbar";
import codefield from "./components/codefield";
import githubfield from "./components/githubfield";
import coinsort from "./components/coinsort";
import vuefooter from "./components/vuefooter";

export default {
  name: "app",
  components: {
    navbar,
    text1,
    aboutbar,
    codefield,
    githubfield,
    coinsort,
    vuefooter
  }
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
}

body {
  font-family: "Open Sans", sans-serif;
}

button:focus {
  outline: 0;
}
</style>
