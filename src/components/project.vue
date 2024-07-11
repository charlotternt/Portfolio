<template>
  <div>
    <h1>Mes projets</h1>
    <p>Voici quelques projets que j'ai réalisés pour m'amuser et me challenger.</p>
    <div class="projects">
      <div class="project">
        <a href="https://effervescent-kangaroo-6c4cd4.netlify.app" target="_blank">
          <div class="overlay">
            <img src="../assets/weather app.png" alt="weather app" class="picture"/>
            <div class="text">Weather App</div>
          </div>
        </a>
        <div class="project-details">
          <h2>Weather App</h2>
          <p>Il s'agit d'une page web faite en Vue Js qui donne la météo.</p>
        </div>
      </div>
      <div class="project">
        <a href="https://challenge-age-calculator.netlify.app" target="_blank">
          <div class="overlay">
            <img src="../assets/calculator age.png" alt="calculator age" class="picture"/>
            <div class="text">Age Calculator</div>
          </div>
        </a>
        <div class="project-details">
          <h2>Age Calculator</h2>
          <p>C'est une page web qui permet de calculer l'âge en fonction de la date de naissance. Je l'ai réalisé en HTML et JS.</p>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  name: "project_",
};
</script>

<style>
h2 {
  color: #6540ca;
  margin: 5px 0;
}

.projects {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.project {
  display: flex;
  align-items: center;
  margin: 20px 0;
}

.picture {
  width: 350px;
  height: 220px;
  border-radius: 5%;
  transition: 0.3s ease;
}

.overlay {
  position: relative;
  width: 350px;
  height: 220px;
  border-radius: 5%;
  overflow: hidden;
}

.overlay::after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.281);
  transition: 0.3s ease;
  opacity: 0;
}

.overlay:hover::after {
  opacity: 1;
}

.text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: #6540ca;
  font-size: 20px;
  font-weight: bold;
  visibility: hidden;
  opacity: 0;
  transition: visibility 0s, opacity 0.3s ease;
}

.overlay:hover .text {
  visibility: visible;
  opacity: 1;
}

.project-details {
  margin-left: 20px;
  max-width: 350px;
}

.project-details h2 {
  margin-top: 0;
}

.project-details p {
  margin-top: 5px;
}

</style>
