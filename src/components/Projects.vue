<template>
    <h1>MES PROJETS</h1>
    <div class="container" id="experience">
        <div class="Project-1">
            <img src="../assets/Projetc1.png" alt="">
                <h2>Développement Frontend</h2>
        </div>
        <div class="Project-2">
            <img src="../assets/projet-2.png" alt="">
            <h2>Développement Backend</h2>
        </div>

        <div class="Project-3">
            <img src="../assets/Projet-3.png" alt="">
            <h2>Développement Backend</h2>
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
}
  h1 {
    font-family: "Quicksand";
    text-align: center;
    margin-top: 100px;
    margin-bottom: 50px;
  }

  ul {
    list-style-type : none;
    font-weight: bold;
 }

  .right h2 {
    text-align: center;
    width: 500px;
  }

  </style>

