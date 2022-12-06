 
<!--BSIT-2A--> 
<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE-edge">
  <meta name="viewport" content="width=device-width,initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <script src="https://kit.fontawesome.com/49c67b1048.js" crossorigin="anonymous"></script>
<body>
<style>
* {
  margin: 0;
  padding: 0;
  outline: none;
  border: none;  
  text-decoration: none;
  box-sizing: border-box;
  font-family: Helvetica, Sans-Serif;
}
body {
  background: url("https://images.unsplash.com/photo-1607282729548-e1d13feae36f?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1932&q=80") no-repeat center fixed;
  background-size: cover;
  min-height: 100vh;
  filter: blur(0.4);
}
nav {
  position: fixed;
  top: 0;
  bottom: 0;
  height: 100%;
  left: 100;
  background: grey;
  width: 90px;
  overflow: hidden;
  transition: width 0.2s linear;
  box-shadow: 0 2px 35px rgba(0,0,0,alpha);
  backdrop-filter: blur(6px);
  background: rgba(28,28,38,0.7);
  border: 1px solid rgba(255,255,255,0.18);
  left: 0;
  font-size: 15px;
}
.logo {
  text-align: center;
  display: flex;
  transition: all 0.5s ease;
  margin: 10px 0 0 10px;
  color: white;
}
.logo img{
  width: 45px;
  height: 45px;
  border-radius: 50%;
}
.logo span {
  font-weight: bold;
  padding-left: 15px ;
  font-size: 15px;
  text-transform: uppercase;
  color: #D3D3D3;
}
a {
  position: relative;
  font-size: 15px;
  display: table;
  width: 300px;
  padding: 10px;
  color: white;
}

.fa-solid {
  position: relative;
  width: 70px;
  height: 40px;
  top: 14px;
  font-size: 20px;
  text-align: center;
}
.nav-item {
  position: relative;
  top: 12px;
  margin-left: 10px;
  color: white;
}
a:hover{
  background: grey; 
}
nav:hover {
  width: 280px;
  transition: all 0.5 ease;
} 
button {
  background-color: black;
  color: white;
  padding: 10px;
  width: 100px;
  margin: 8px 8px;
  border: 1px solid black;
  cursor: pointer;
  width: 50%;
  height: 10%;
  font-size: 15px;
  outline: none;
  text-align: center;
  transition: 0.7s;
  font-weight: 100;
  outline: none;
}

button:hover {
  opacity: 0.5;
  background: pink;
  color: black;
  box-shadow:    0 0 5px  #ff1818,
                 0 0 25px  #ff1818,
                 0 0 50px  #ff1818,
                 0 0 100px  #ff1818;
  transition: opacity 0.5s;
}
hr {
  border: 1px white solid;]
  width: 90%;
  margin: 0 auto;
}
.img {
  margin: 50px 0 12px 100px;
  width: 50px;
  height: 50px;
}
.img1 {
  margin: 55px 258px;
  position: absolute;
  top: 0;
}
.time { 
    margin: 25px 1600px;
    background: rgb(12, 12, 12);
    color: #fff;
    border: 3px solid rgb(0, 0, 0);
    padding: 10px;
    text-align: center;
    width: 260px;
    float: right;
    padding-top: 20px  ;
    padding-bottom: 15px  ;
    box-shadow: 0px 0px 10px 5px blue;
    position: fixed;
    top: 0;
    background: rgba(255, 255, 255, 0.19);
    border-radius: 16px;
    backdrop-filter: blur(8px);
    -webkit-backdrop-filter: blur(8px);
}
.hm {
    font-size: 38pt;
    font-weight: 200;
}
.amp {
    font-size: 20pt;
}
.date {
    font-size: 13pt;
}
h1{
    font-family: Verdana, Tahoma, sans-serif;
    font-size: 150px;
    letter-spacing: 10px;
    opacity: 0.8;
    background-image: linear-gradient(99deg, red, blue, white, red, blue);
    background-size: 100%;
    -webkit-background-clip: text;
    -moz-background-clip: text;
    -webkit-text-fill-color: transparent;
    -webkit-text-fill-color: transparent;
    margin: 300px 350px;
    position: fixed;
    top: 0;
}

</style>
<div class="img">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/84/Coat_of_arms_of_the_Philippines.svg/1200px-Coat_of_arms_of_the_Philippines.svg.png" alt="" width="130" height="130" >
  </div>
   <div class="img1">
    <img src="https://itsmorefuninthephilippines.co.uk/wp-content/uploads/IMFITP_multicolored.png" alt="" style="width:200px" height="60px" positiion="left"; >
  </div>
  
<nav> 
  <ul> 
    <li>
      <a href="MAIN.html" class="logo">
        <img src="https://www.pngkey.com/png/full/118-1185109_3d-waving-graphics-flag-of-philippines-philippine-flag.png" alt="">
        <span class="nav-item">About Philippines</span>
      </a>
    </li>
    <li>
      <a href="ok.html">
        <i class="fa-solid fa-book"></i>
        <span class="nav-item">History</span>
      </a>
    </li>
    <li>
      <a href="GEO&ENV.html">
        <i class="fa-solid fa-mountain-sun"></i>
        <span class="nav-item">Geography & Environment</span>
      </a>
    </li>
    <li>
      <a href="DEMOGRAPH.html">
        <i class="fa-solid fa-id-card-clip"></i>
        <span class="nav-item">Demographics</span>
      </a>
    </li>
    <li>
      <a href="CULTURE.html">
        <i class="fa-solid fa-church"></i>
        <span class="nav-item">Culture</span>
      </a>
    </li>
  </ul>

   <ul> 
   <li>
      <a href="#" class="logo">
        <img src="https://freepngimg.com/thumb/beach/28398-7-beach-transparent.png" alt="">
        <span class="nav-item">Tourist Attractions</span>
      </a>
    </li>
    <li>
      <a href="LUZON.html">
        <i class="fa-solid fa-l"></i>
        <span class="nav-item">Luzon</span>
      </a>
    </li>
    <li>
      <a href="VISAYAS.html">
        <i class="fa-solid fa-v"></i>
        <span class="nav-item">Visayas</span>
      </a>
    </li>
    <li>
      <a href="MINDANAO.html">
        <i class="fa-solid fa-m"></i>
        <span class="nav-item">Mindanao</span>
      </a>
    </li>
  </ul>
  <hr>
  <ul>
      <li>
      <a href="VideoGallery.Html">
        <i class="fa-solid fa-video" style="color:red"></i>
        <button>Video Gallery</button>
      </a>
    </li>
  </ul>
  <ul>
     <li>
      <a href="#">
        <i class="fa-solid fa-right-to-bracket"></i>
        <button onClick="javascript:window.open('Login.html', '_blank');">Log in </button>
      </a>
    </li>
  </ul>
   <ul>
     <li>
      <a href="#">
        <i class="fa-solid fa-address-book"></i>
        <span class="nav-item">Contact Us</span>
      </a>
    </li>
  </ul>
</nav>
<h1>PHILIPPINES</h1>

<div class="time">
        <span class="hm"></span>
        <span class="amp"></span>
        <br>
        <span class="date"></span>
      </div>
<script>
   function updateTime() {
  var dateInfo = new Date();

  var hr,
    _min = (dateInfo.getMinutes() < 10) ? "0" + dateInfo.getMinutes() : dateInfo.getMinutes(),
    sec = (dateInfo.getSeconds() < 10) ? "0" + dateInfo.getSeconds() : dateInfo.getSeconds(),
    amp = (dateInfo.getHours() >= 12) ? "PM" : "AM";

  if (dateInfo.getHours() == 0) {
    hr = 12;
  } else if (dateInfo.getHours() > 12) {
    hr = dateInfo.getHours() - 12;
  } else {
    hr = dateInfo.getHours();
  }

  var currentTime = hr + ":" + _min + ":" + sec;

  document.getElementsByClassName("hm")[0].innerHTML = currentTime;
  document.getElementsByClassName("amp")[0].innerHTML = amp;

  var dow = [
      "Sunday",
      "Monday",
      "Tuesday",
      "Wednesday",
      "Thursday",
      "Friday",
      "Saturday"
    ],
    month = [
      "January",
      "February",
      "March",
      "April",
      "May",
      "June",
      "July",
      "August",
      "September",
      "October",
      "November",
      "December"
    ],
    day = dateInfo.getDate();

  var currentDate = dow[dateInfo.getDay()] + ", " + month[dateInfo.getMonth()] + " " + day;

  document.getElementsByClassName("date")[0].innerHTML = currentDate;
};

updateTime();
setInterval(function() {
  updateTime()
}, 1000);
      </script>
          <footer>
            <p>Copyright ©2022. All Rights Reserved</p>
        </footer>
    </body>
  </head>
</html>
