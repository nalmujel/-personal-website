# -personal-website

<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}
h2 { 
font-family: Century Gothic, CenturyGothic, AppleGothic, sans-serif;
text-align:center;
font-weight: bold;
color: grey;
} p{
color:#A9A9A9;
font-family: Century Gothic, CenturyGothic, AppleGothic, sans-serif;
}

html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

.column {
  float: left;
  width: 33.3%;
  margin-bottom: 16px;
  padding: 0 8px;
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  margin: 8px;
}


.container {
  padding: 0 20px;
}

.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
  text-align: center;
}

.title {
  color: grey;
}

.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color:#E6E6FA;
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: #555;
}

@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}html {
  height:100%;
}

body {
  margin:0;
}

.bg {
  animation:slide 3s ease-in-out infinite alternate;
  background-image: linear-gradient(-60deg, #E6E6FA 50%, #FFF0F5 50%);
  bottom:0;
  left:-50%;
  opacity:.5;
  position:fixed;
  right:-50%;
  top:0;
  z-index:-1;
} 
ul.a{
  list-style-type: circle;
font-family: Century Gothic, CenturyGothic, AppleGothic, sans-serif;
text-align:left;
font-weight: bold;
color:#D3D3D3;

}

.bg2 {
  animation-direction:alternate-reverse;
  animation-duration:4s;
}

.bg3 {
  animation-duration:5s;
}



h1 {
  font-family:monospace;
}

@keyframes slide {
  0% {
    transform:translateX(-25%);
  }
  100% {
    transform:translateX(25%);
  }
}
</style>
</head>
<body>


<div class="bg bg2"></div>
<div class="bg bg3"></div>
<div class="content"> <h1></h1>
<h2 style="text-align:center">
MY PERSONAL WEBSITE</h2>



<div class="about-section">

</div> 


<div class="row">
  <div class="column">
    <div class="card">
   
      <div class="container">
        <h2>Nawal Almuajel</h2>
        <p class="title">Co-Founder of Booklee</p>
               <p> My Interests:</p>
        <ul class="a">
 
        <li>AI</li>
        <li>Digital Marketing</li>
        <li> Web Development</li>
        <li>Voulnteering</li>
        <li>Data Analaysis</li>
        
        
        </ul>
        <p>Projects I worked on </p>
       
    
  <a href="https://drive.google.com/file/d/1z1teHrhDYLMaNeBh-SWWfvuDEf0zrXrZ/view?usp=sharing" class="button">Car2Share</a>
</div>

<p>contact me at:</p>
<li>nalmujel@gmail.com</li>
<li>a</li>
      </div>
    </div>
  </div>
 


</body>
</html>
