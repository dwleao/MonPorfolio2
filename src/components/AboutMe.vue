<template>
    <h1>A PROPOS DE MOI</h1>
    <div class="container" id="about">
      <div class="left">
        <!-- Photo de vous -->
        <img src="../assets/portraitAbout.jpg" alt="Votre photo" class="photo">
      </div>
      <div class="right">
        <div class="sections">
          <!-- Expériences -->
          <div class="section">
            <img src="../assets/experienceLogo.png" alt="">
            <h2>Expériences</h2>
            <!-- Liste d'expériences -->
            <ul>
              <li>HTML</li>
              <li>CSS</li>
              <li>JavaScript</li>
              <li>VueJS</li>
              <!-- Ajoutez plus d'éléments d'expérience au besoin -->
            </ul>
          </div>
          <!-- Formations -->
          <div class="section">
            <img src="../assets/formationLogo.png" alt="">
            <h2>Formations</h2>
            <!-- Liste de formations -->
            <ul>
              <li>Développeur Web et Mobile</li>
              <li>Centre Européen de Formations</li>
              <!-- Ajoutez plus d'éléments de formation au besoin -->
            </ul>
          </div>
        </div>
        <!-- Description -->
        <div class="description">
          <p>À 28 ans, après deux années dans l'armée et sept ans à gravir les échelons de la restauration jusqu'à devenir Responsable d'une grande brasserie à Strasbourg, je me lance dans le développement web. Ma transition reflète ma détermination et mon esprit d'équipe, acquis dans l'armée et consolidés dans la restauration. Animé par une passion croissante pour la technologie, je suis prêt à mettre à profit ma polyvalence dans cette nouvelle aventure professionnelle.</p>
        </div>
      </div>
    </div>
  </template>
  
  
  <style scoped >
  h1 {
    font-family: "Quicksand";
    text-align: center;
  }
  .container {
    font-family: "Quicksand", sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 50px
  }
  
  ul {
    list-style-type : none;
  }

  .left {
    margin-right: 25px;
  }
  
  .photo {
    border-radius: 0px;
    width: 602px;
    height: 491px;
    border-radius: 30px;
  }
  
  .right {
    text-align: left;
    width: 700px;
    margin-left: 25px;
  }
  
  .sections {
    display: flex;
  }
  
  .section {
    padding-top: 20px;
    padding-bottom: 20px;
    width: 300px;
    border: solid 1px;
    border-radius: 10px;
    margin-right: 20px;
    padding-left: 10px;
    padding-right: 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  
.section img {
  width: 30px;
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