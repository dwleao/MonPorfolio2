<template>
    <div class="container">
      <div class="left">
        <img src="../assets/pp.jpg" alt="Votre photo" class="photo">
      </div>
      <div class="right">
        <h1>Kevin LEAO</h1>
        <h2>Développeur Web</h2>
        <div class="buttons">
          <button class="CV">Mon CV</button>
          <button class="contact">Contact</button>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Description',

    }
  
  </script>
  
  <style>
  .container {
    display: flex;
    align-items: center;
  }
  
  .left {
    margin-right: 20px;
  }
  
  .photo {
    width: 150px;
    height: 150px;
    border-radius: 50%;
  }
  
  .right {
    text-align: left;
  }
  
  .buttons {
    margin-top: 10px;
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
  </style>