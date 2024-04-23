<template>
    <div class="menu">
        <span><a href="#">Kevin LEAO</a></span>
      <ul>
        <li><a href="#about">À propos de moi</a></li>
        <li><a href="#experience">Expériences</a></li>
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
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  .menu ul {
  }
  
  .menu ul li {
    display: inline;
    margin-right: 20px;
  }
  
  .menu ul li a {
    color: black;
    text-decoration: none;
  }

  .menu span a {
    text-decoration: none;
    color: black;
    font-size: 28px;
  }
  
  </style>