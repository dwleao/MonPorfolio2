<template>
    <h1>MES PROJETS</h1>
    <div class="container" id="projects">
        <div class="Project-1">
            <img src="../assets/Projetc1.png" alt="">
                <h2>Projet Mon CV</h2>
                <a href="https://github.com/dwleao/MonCVenLigne">Voir</a>
        </div>
        <div class="Project-2">
            <img src="../assets/projet-2.png" alt="">
            <h2>Projet Cahier des Charges</h2>
            <a href="https://github.com/dwleao/MonCVenLigne">Voir</a>        </div>

        <div class="Project-3">
            <img src="../assets/Projet-3.png" alt="">
            <h2>Projet My Home Space</h2>
            <a href="https://github.com/dwleao/mon_home_space">Voir</a>
        </div>
    </div>
</template>
  
  <style scoped >
  .container {
    font-family: "Quicksand", sans-serif;
    display: flex;
    justify-content: center;
  }

.container div {
    width: 350px;
    height: 500px;
    padding-top: 20px;
    border: solid 1px;
    border-radius: 30px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding-bottom: 20px;
    margin-right: 20px;
    padding-left: 10px;
    padding-right: 10px;
}
.container div img {
    width: 280px;
    border-radius: 30px;
    height: 360px;
}
  h1 {
    font-family: "Quicksand";
    text-align: center;
    margin-top: 200px;
    margin-bottom: 50px;
  }

  ul {
    list-style-type : none;
    font-weight: bold;
 }

 h2 {
    width: 350px;
    text-align: center;
 }

    .container div a {
      background-color: hsla(160, 100%, 37%, 1);
    margin-right: 10px;
    padding: 10px 20px;
    border: none;
    border-radius: 20px;
    color: white;
    font-size: 16px;
    font-weight: bold;
    text-decoration: none;
    
  }

   .Project-2 img {
    border: solid 1px;
   }
  </style>

