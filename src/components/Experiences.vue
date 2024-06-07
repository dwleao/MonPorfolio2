<template>
    <h1>EXPERIENCES</h1>
    <div class="container" id="experiences">
        <div class="left">
            <div class="left-1">
                <h2>Développement Frontend</h2>
            </div>
            <div class="left-2">
                <ul>
                    <li class="container"><div class="col"><img src="../assets/certificatelogo.png" alt=""></div>HTML</li>
                    <li class="container"><div class="col"><img src="../assets/certificatelogo.png" alt=""></div>CSS</li>
                </ul>
            </div>
            <div class="left-3">
                <ul>
                    <li class="container"><div class="col"><img src="../assets/certificatelogo.png" alt=""></div>JavaScript</li>
                    <li class="container"><div class="col"><img src="../assets/certificatelogo.png" alt=""></div>VueJS</li>
                </ul>
            </div>

        </div>
        <div class="right">
            <h2>Développement Backend</h2>
            <ul>
              <li class="container"><div class="col"><img src="../assets/certificatelogo.png" alt=""></div>GitHub</li>
            </ul>
        </div>
    </div>
</template>
  
  <style scoped >
  .container {
    font-family: "Quicksand", sans-serif;
    display: flex;
    justify-content: center;
  }

.container img {
    width: 25px;
}


  .right {
    padding-top: 20px;
    padding-bottom: 20px;
    width: 500px;
    height: 200px;
    border: solid 1px;
    border-radius: 10px;
    margin-right: 20px;
    padding-left: 10px;
    padding-right: 10px;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
  }

  .left {
    display: flex;
    flex-wrap: wrap;
    padding-top: 20px;
    padding-bottom: 20px;
    width: 500px;
    height: 200px;
    border: solid 1px;
    border-radius: 10px;
    margin-right: 20px;
    padding-left: 10px;
    padding-right: 10px;

  }

  .left-1 {
    width: 500px;
    text-align: center;
  }


  .left-2 {
    width: 250px;

  }

  .left-3 {
    width: 250px;

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

  .right h2 {
    text-align: center;
    width: 500px;
  }
 
  ul li div {
    padding-bottom: 2px;
  }



  .competences {
    padding-top: 2px;
  }
  </style>











