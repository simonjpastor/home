<head>

<style>
body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.topnav {
  overflow: hidden;
  top: 50%;
  background-color: #5DADE2;
  border-top-left-radius: 10px;
  border-bottom-left-radius: 10px;
  border-top-right-radius: 10px;
  border-bottom-right-radius: 10px;

}

.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
  width: 17.72%;
  margin:0;
  border-top-left-radius: 4px;
  border-bottom-left-radius: 4px;
  border-top-right-radius: 4px;
  border-bottom-right-radius: 4px;
}


.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: #3498DB;
  color: white;
}
      /* The dropdown container */
      .dropdown {
      float: left;
      overflow: hidden;
      color: #3498DB;
      }
      /* Dropdown button */
      .dropdown .dropbtn {
      float: center;
      color: #3498DB;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
      font-size: 17px;
      min-width:18%;
      margin:0;
      }
      /* Dropdown content (hidden by default) */
      .dropdown-content {
      display: none;
      position: absolute;
      background-color: #f9f9f9;
      min-width: 19%;
      box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
      z-index: 1;
      }
      /* Links inside the dropdown */
      .dropdown-content a {
      float: none;
      color: black;
      padding: 12px 16px;
      text-decoration: none;
      display: block;
      text-align: center;
      min-width:100%;
      }
      /* Add a grey background color to dropdown links on hover */
      .dropdown-content a:hover {
      min-width:100%;
      background-color: #cc2;
      }
      /* Show the dropdown menu on hover */
      .dropdown:hover .dropdown-content {
      display: block;
      }
.row {
  display: flex;
  flex-wrap: wrap;
  padding: 0 4px;
}

/* Create two equal columns that sits next to each other */
.column {
  flex: 50%;
  padding: 0 4px;
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
}

.container {
  position: relative;
  width: 50%;
}

.image {
  display: block;
  width: 100%;
  height: auto;
}

.overlay {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  height: 100%;
  width: 100%;
  opacity: 0;
  transition: .5s ease;
  background-color: #008CBA;
}

.container:hover .overlay, .container:focus .overlay {
  opacity: 0.9;
}

.text {
  color: white;
  font-size: 20px;
  position: absolute;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  text-align: center;
}


@media screen and (max-width: 600px) {
  .topnav {position: relative;}
  .topnav a {
    float: left;
    display: block;
    text-align: center;
    width:100%;
  }
  .topnav a.icon {
    float: right;
    display: block;
  }

}

.btn {
  border: none;
  outline: none;
  padding: 10px 16px;
  background-color: #ddd;
  cursor: pointer;
  font-size: 18px;
}

.btn:hover {
  background-color: #666;
}

.btn.active {
  background-color: #666;
}

.btn.active a{
  background-color: #666;
}

.btn:focus{
    background-color:#666;
}
</style>
</head>
<body>


  <div class="topnav">
    <a href="https://simonpastor.com">Home</a>
    <a class="active" href="">Portfolio</a>
    <!-- <div class="dropdown"> */
      <button class="dropbtn">
        <a href="#contact">SimonSays</a>
      <i class="fa fa-caret-down"></i>
      </button>
      <div class="dropdown-content">
         <a href="#">Emperor Gaius Trump</a>
         <a href="#">Harmless Tradition or (Khat)astrophe?</a>
         <a href="#">Post-Covid Social Status:Unclear</a>
      </div>
    </div> -->
    <a href="https://simonpastor.substack.com">SimonSays</a>
    <a href="#news">Resume</a>
    <a href="https://simonpastor.com/Contact">Contact</a>
  </div>

<br>
  <!-- Header -->
<div class="header" id="myHeader">
  <center><p><font color='#5DADE2'>Click on the buttons to change the grid view. Click on an image to check out the project!</font></p></center>
  <center>
    <button class="btn" onclick="one()">1</button>
    <button class="btn active" onclick="two()">2</button>
    <button class="btn" onclick="four()">4</button>
  </center>
</div>

<br>

<div class="container">
  <img src="images/memorable_people.png" class="image" onclick="URL_sports()">
  <div class="overlay" onclick="URL_sports()">
    <div class="text">Click to check out!!</div>
  </div>
</div>

<div class="row">
  <div class="column">
    <div class="container"><img src="images/memorable_people.png" class="image" onclick="URL_sports()"><div class="overlay" onclick="URL_sports()"><div class="text">Memorable Sportspeople <br>Click to check out!!</div></div></div>
    <div class="container"><img src="images/memorable_people2.png" class="image" onclick="URL_sports()"><div class="overlay" onclick="URL_sports()"><div class="text">Memorable Sportspeople <br>Click to check out!!</div></div></div>
    <div class="container"><img src="images/delphes_1.png" class="image" onclick="URL_delphes()"><div class="overlay" onclick="URL_sports()"><div class="text">Delphes <br>Click to check out this project!</div></div></div>
  </div>
  <div class="column">
    <a href="https://simonpastor.com/2017-French-Presidential-Elections" target="__blank"><img src="images/elections_general.png"></a>
    <a href="https://simonpastor.com/2017-French-Presidential-Elections" target="__blank"><img src="images/elections_general3.png"></a>
    <a href="https://simonpastor.com/2017-French-Presidential-Elections" target="__blank"><img src="images/elections_fillon.png"></a>
    <a href="https://simonpastor.com/2017-French-Presidential-Elections" target="__blank"><img src="images/elections_lepen.png"></a>
  </div>
  <div class="column">
    <a href="https://twitter.com/Twitt_Lists" target="__blank"><img src="images/twittlists1.png"></a>
    <a href="https://twitter.com/Twitt_Lists" target="__blank"><img src="images/twittlists2.png"></a>
    <a href="https://twitter.com/Twitt_Lists" target="__blank"><img src="images/twittlists3.png"></a>
  </div>
  <div class="column">
    <a href="https://simonpastor.com/citizenlab-participatory-budgets" target="__blank"><img src="images/pb-0.png"></a>
    <a href="https://simonpastor.com/citizenlab-participatory-budgets" target="__blank"><img src="images/pb-1.png"></a>
    <a href="https://simonpastor.substack.com" target="__blank"><img src="images/simonsays3.png"></a>
  </div>
</div>

<script>
// Get the elements with class="column"
var elements = document.getElementsByClassName("column");

// Declare a loop variable
var i;

// Full-width images
function one() {
    for (i = 0; i < elements.length; i++) {
    elements[i].style.msFlex = "100%";  // IE10
    elements[i].style.flex = "100%";
  }
}

// Two images side by side
function two() {
  for (i = 0; i < elements.length; i++) {
    elements[i].style.msFlex = "50%";  // IE10
    elements[i].style.flex = "50%";
  }
}

// Four images side by side
function four() {
  for (i = 0; i < elements.length; i++) {
    elements[i].style.msFlex = "25%";  // IE10
    elements[i].style.flex = "25%";
  }
}

function URL_sports() {
    location.href = 'https://simonpastor.com/memorable-sportspeople-map';
}

function URL_delphes() {
    location.href = 'https://politicalpred.herokuapp.com/';
}


// Add active class to the current button (highlight it)
var header = document.getElementById("myHeader");
var btns = header.getElementsByClassName("btn");
for (var i = 0; i < btns.length; i++) {
  btns[i].addEventListener("click", function() {
    var current = document.getElementsByClassName("active");
    current[0].className = current[0].className.replace(" active", "");
    this.className += " active";
  });
}
</script>

</body>
