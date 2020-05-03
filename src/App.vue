<template>
  <div id="app" class="container">

<h1 class="text-primary mt-3"> {{name}} </H1>
<p @click="showDescription=!showDescription" > <font-awsome-icon icon="play" /> <span v-if="showDescription"> {{description}} </span> </p>
    
    
  </div>
</template>

<script>


export default {
  name: "app",

  data () {
  return {
showDescription:true,
name: "Modern Hard Rock",
description: "L'hard rock è una forma particolarmente grintosa e aggressiva di musica rock[1]. La chitarra elettrica viene spesso enfatizzata tramite la distorsione e altri effetti, sia durante l'uso come chitarra ritmica, sia come chitarra solista[1]"
  }
  },
};
</script>

<style lang="scss">
/*#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}*/
</style>
