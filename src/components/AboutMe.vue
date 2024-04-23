<template>
    <div class="container">
      <div class="left">
        <!-- Photo de vous -->
        <img src="../assets/portraitNB.jpg" alt="Votre photo" class="photo">
      </div>
      <div class="right">
        <div class="sections">
          <!-- Expériences -->
          <div class="section">
            <h2>Expériences</h2>
            <!-- Liste d'expériences -->
            <ul>
              <li>Expérience 1</li>
              <li>Expérience 2</li>
              <!-- Ajoutez plus d'éléments d'expérience au besoin -->
            </ul>
          </div>
          <!-- Formations -->
          <div class="section">
            <h2>Formations</h2>
            <!-- Liste de formations -->
            <ul>
              <li>Formation 1</li>
              <li>Formation 2</li>
              <!-- Ajoutez plus d'éléments de formation au besoin -->
            </ul>
          </div>
        </div>
        <!-- Description -->
        <div class="description">
          <h2>À propos de moi</h2>
          <p>Votre description ici...</p>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Description',
  }
  </script>
  
  <style scoped >
  .container {
    display: flex;
    align-items: center;
    margin-top: 50px;

  }
  
  .left {
    margin-right: 20px;
  }
  
  .photo {
    border-radius: 0px;
    width: 250px;
    height: 250px;
  }
  
  .right {
    text-align: left;
  }
  
  .sections {
    display: flex;
  }
  
  .section {
    border: solid 1px;
    border-radius: 10px;
    margin-right: 20px;
    padding-left: 10px;
    padding-right: 10px;
  }
  
  .section:last-child {
    margin-right: 0;
  }
  
  .section h2 {
    font-size: 20px;
    margin-bottom: 10px;
  }
  
  .description {
    margin-top: 30px;
  }
  
  .description h2 {
    font-size: 20px;
    margin-bottom: 10px;
  }
  
  .description p {
    font-size: 16px;
    line-height: 1.5;
  }
  </style>