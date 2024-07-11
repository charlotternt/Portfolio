<template>
  <div class="contact-form">
    <div class="header">
      <h1>Mes réseaux</h1>
      <a href="/cv.pdf" target="_blank" class="cv-link">Mon Curriculum Vitae</a>
    </div>
    <div class="contact-item">
      <a href="https://github.com/charlotternt" target="_blank"><img src="../assets/github.svg" class="icon" /></a>
      <a href="https://github.com/charlotternt" target="_blank">Github: https://github.com/charlotternt</a>
    </div>
    <div class="contact-item">
      <a href="https://www.linkedin.com/in/charlotte-renault-94b23915b/" target="_blank"><img src="../assets/linkedin.svg" class="icon" /></a>
      <a href="https://www.linkedin.com/in/charlotte-renault-94b23915b/" target="_blank">LinkedIn: https://www.linkedin.com/in/charlotte-renault-94b23915b/</a>
    </div>
    <h2>Si vous voulez me contacter</h2>
    <div class="contact-item">
      <a href="mailto:charlotterenault3@gmail.com"><img src="../assets/mail.svg" class="icon" /></a>
      <a href="mailto:charlotterenault3@gmail.com">Email: charlotterenault3@gmail.com</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Social_',
};
</script>

<style>
.contact-form {
  max-width: 650px;
  margin: 40px auto;
  padding: 20px;
  background-color: #6540ca;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  color: #fff;
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}

.contact-form h1 {
  color: #fff;
}

.cv-link {
  color: #fff;
  background-color: #532fa3;
  padding: 10px 20px;
  border-radius: 4px;
  text-decoration: none;
}

.cv-link:hover {
  background-color: #6540ca;
}

.contact-item {
  display: flex;
  align-items: center;
  margin-bottom: 15px;
}

.contact-item img.icon {
  margin-right: 10px;
  width: 24px;
  height: 24px;
}

.contact-item a,
.contact-item p {
  color: #fff;
  text-decoration: none;
}

.contact-item a:hover {
  text-decoration: underline;
}
</style>
