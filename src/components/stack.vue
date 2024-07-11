<template>
  <div class="stack">
    <p>Au cours de mes études j'ai pu découvrir et apprendre quelques langages. Nous avions commencer par voir les bases en HTML, CSS ,PHP et Javascript ensuite on a du réaliser des petits projets en react, vue js ,python, java, ruby. Je suis plus à l'aise avec le language Vue Js.</p>
    <div class="images-container">
      <img src="../assets/html.png"/>
      <img src="../assets/css.png"/>
      <img src="../assets/php.png"/>
      <img src="../assets/javascript.svg"/>
      <img src="../assets/laravel.png"/>
      <img src="../assets/vuejs.png"/>
      <img src="../assets/react.png"/>
    </div>
  </div>
</template>

<script>
export default {
  name: 'stack_'
}
</script>

<style>
.stack {
  text-align: left; 
  margin: 100px;
}

.images-container {
  display: flex; 
  justify-content: center; 
  flex-wrap: wrap; 
  margin-top: 20px; 
}

.images-container img {
  margin: 10px; 
  width: 50px;
  height: 50px; 
}

</style>
