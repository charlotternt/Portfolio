<template>
  <div class="app-container">
    <Navbar class="margin-container"/>
    <main class="content margin-container">
      <Profil/>
      <Stack/>
      <Project/>
      <Social/>
    </main>
    <Footer/>
  </div>
</template>

<script>
import Navbar from './components/navbar.vue';
import Profil from './components/profil.vue';
import Project from './components/project.vue';
import Footer from './components/footer.vue';
import Stack from './components/stack.vue';
import Social from './components/social.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    Profil,
    Stack,
    Project,
    Footer,
    Social,
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Dosis:wght@200..800&display=swap');

body {
  width: 100%;
  height: 100%;
  margin: 0;
  background-color: #cccac5;
  font-family: 'Dosis', sans-serif;
  display: flex;
  flex-direction: column;
}

html, body, #app {
  height: 100%;
}

p{
  font-size: 18px;
}

.app-container {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.margin-container {
  margin: 20px; 
}

.content {
  flex: 1;
}

footer {
  width: 100%;
  background-color: #6540ca;
  color: white;
  text-align: center;
  padding: 10px;
}
</style>
