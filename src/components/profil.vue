<template>
  <div class="profil">
    <h1>Développeuse web</h1>
    <div>
      <h2>Bonjour, Je m'appelle Charlotte RENAULT</h2>
      <p>
        Je viens d'être diplomée en tant que intégratrice/développeuse web au
        sein d'Epitech Lyon en Novembre 2023. Pendant mes études, j'ai réalisé
        une année en alternance en tant que développeuse Fullstack ou j'ai principalement utilisé les languages Laravel et VueJS 3. Aujourd'hui,
        j'aimerais poursuivre en tant que développeuse Frontend.
      </p>
    </div>

    <div class="card-container">
      <div class="card">
        <img src="../assets/desktop.svg" class="icon"/>                  
        <h3>HelloCSE</h3>
        <p>Lyon, 69007</p>
        <p>De septembre 2022 à Novembre 2023</p>
      </div>
      <div class="card">
        <img src="../assets/school.svg" class="icon"/>
        <h3>Diplôme intégratrice/développeuse web</h3>
        <p>Epitech</p>
        <p>Lyon, 69007</p>
        <p>De Novembre 2021 à Novembre 2023</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Profil_",
};
</script>

<style>
h1 {
  color: #6540ca;
}

.profil {
  color: #010101;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.card-container {
  display: flex;
  flex-wrap: wrap; 
  justify-content: center; 
}

.card {
  background-color: #6540ca;
  color: #d7d7d7;
  margin: 10px;
  border-radius: 5%;
  padding: 20px; 
  flex: 1; 
  min-width: 250px; 
  max-width: 300px; 
  box-sizing: border-box; 
}

.icon {
  color: #d7d7d7;
  border-radius: 100%;
  display: block;
  margin: 0 auto 10px auto; 
}

@media (max-width: 768px) {
  .card-container {
    flex-direction: column; 
    align-items: center; 
  }

  .card {
    min-width: 100%; 
    max-width: 100%; 
  }
}
</style>
