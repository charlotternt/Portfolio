<template>
  <div class="navbar">
    <img src="../assets/terminal.svg" class="logo" />
    <a href="mailto:charlotterenault3@gmail.com"><img src="../assets/mail.svg" class="icon"/></a>
  </div>
</template>

<script>
export default {
  name: "Navbar_",
};
</script>

<style>
.navbar {
  width: 95%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 20px; 
  box-sizing: border-box; 
}

.navbar img {
  max-width: 100px; 
  height: auto;
}

.navbar a {
  color: #6540ca;
  text-decoration: none;
  font-weight: bold;
}
</style>
