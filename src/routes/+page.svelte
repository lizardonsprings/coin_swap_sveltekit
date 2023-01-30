<body><div class="main">
    <img src="./assets/TCS_Logo_Full.png" width="350" alt="">
  <h2>Which coins would you like to swap?</h2>
  <h4>Coins:</h4>
  <form id="coinSwap" action="http://localhost:8080/" method="POST">
    <select name="coin1" id="coin1">
      <option disabled selected hidden>Select coin to exchange</option>
      <option value="bitcoin">Bitcoin</option>
      <option value="dogecoin">Dogecoin</option>
    </select>
   
    <select name="coin2" id="coin2">
      <option disabled selected hidden>Select coin to exchange</option>
      <option value="bitcoin">Bitcoin</option>
      <option value="dogecoin">Dogecoin</option>
    </select>
  <br>
  <h4>Amount:</h4>
    <input type="text" id="amount1"><input type="text" id="amount2">
  <br><br><br>
    <button type="submit">Next</button>
    </form><br>
  </div>
</body>

  <style>
    

    body {
      background-image: url("./assets/bg.png");
    
      -moz-background-size: cover;
      -webkit-background-size: cover;
      background-size: cover;
      background-position: top center !important;
      background-repeat: no-repeat !important;
      background-attachment: fixed;
    }
    
    .main {
    
      width: 500px;
      padding: 20px;
      margin: 150px auto;
      background: #fcfbf3;
      border-radius: 10px;
      font-family: Avenir, Helvetica, Arial, sans-serif;
      -webkit-font-smoothing: antialiased;
      -moz-osx-font-smoothing: grayscale;
      text-align: center;
      margin-top: 60px;
    }
    
    h2 {
      color: #3f4547;
    }
    
    h4 {
      color: #3888e2;
    }
    
    select {
      display: inline-block;
      padding-right: 20px;
      padding-left: 20px;
      padding-top: 8px;
      padding-bottom: 8px;
      margin-left: 20px;
      margin-right: 20px;
    }
    
    input {
      display: inline-block;
      padding-right: 22px;
      padding-left: 30px;
      padding-top: 8px;
      padding-bottom: 8px;
      margin-left: 20px;
      margin-right: 20px;
    }
    
    button {
      color: white;
      background: #3888e2;
      border: 0 none;
      cursor: pointer;
      border-radius: 5px;
      padding-right: 30px;
      padding-left: 30px;
      padding-top: 10px;
      padding-bottom: 10px;
    }
    </style>