<template>
    <div class="container">
      <div class="left">
        <img src="../assets/portraitCard.jpg" alt="Votre photo" class="photo">
      </div>
      <div class="right">
        <h1>Kevin LEAO</h1>
        <h2>Développeur Web</h2>
        <div class="buttons">
         <button class="CV">Mon CV</button>
        <a href="mailto:kevinleaopro@gmail.com" target="_blank"><button class="contact">Contact</button></a>
        </div>
        <div class="medias">
            <a href="https://www.linkedin.com/in/kevin-leao-10a6161aa/" target="_blank"><img src="../assets/linkedinLogo.png" alt=""></a>
            <a href="https://github.com/dwleao" target="_blank"><img src="../assets/githubLogo.png" alt=""></a>
        </div>
      </div>
    </div>
  </template>
  


  <style scoped>
  .container {
    font-family: "Quicksand", sans-serif;
    height: 600px;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  h1 {
    font-size: 42px;
  }

  .left {
    margin-right: 40px;
  }
  
  .photo {
    width: 308px;
    height: 308px;
    border-radius: 50%;
  }
  
  .right {
    text-align: center;
    margin-left: 40px
  }
  
  .buttons {
    margin-top: 10px;
  }
  
.medias img {
  width: 30px;
}

  .CV {
    background-color: hsla(160, 100%, 37%, 1) ;
    margin-right: 10px;
    padding: 10px 20px;
    border: none;
    border-radius: 20px;
    color: white;
    font-size: 16px;
    font-weight: bold;
  }

  .contact {
    color:  hsla(160, 100%, 37%, 1) ;
    background-color: white;
    margin-right: 10px;
    padding: 10px 20px;
    border: solid 2px;
    border-color:  hsla(160, 100%, 37%, 1) ;
    border-radius: 20px;
    font-size: 16px;
    font-weight: bold;
  }

  .medias {
    margin-top: 20px;
  }

  .medias img {
    margin-right: 10px;
  }
  </style>