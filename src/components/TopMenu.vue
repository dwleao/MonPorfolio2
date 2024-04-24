<template>
    <div class="menu">
        <span><a href="#">Kevin LEAO</a></span>
      <ul>
        <li><a href="#about">À propos de moi</a></li>
        <li><a href="#experiences">Expériences</a></li>
        <li><a href="#projects">Projets</a></li>
        <li><a href="#contact">Me Contacter</a></li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Menu'
  }
  </script>
  
  <style scoped >
  .menu {
    font-family: "Quicksand", sans-serif;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .menu ul {
  }
  
  .menu ul li {
    display: inline;
    margin-right: 20px;
    font-weight: bold;
  }
  
  .menu ul li a {
    color: black;
    text-decoration: none;
  }

  .menu span a {
    text-decoration: none;
    color: hsla(160, 100%, 37%, 1);
    font-size: 28px;
    font-weight: bold;
  }
  
  </style>