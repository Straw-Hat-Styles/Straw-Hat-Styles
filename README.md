@charset "UTF-8";
/* CSS Document */

body {
	background-color: #F7F5EE;
}

p {
	font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
	font-size: 20px;
	color: #616057;
	text-align: center;
}

h1 {
	font-family: "Lucida Grande", "Lucida Sans Unicode", "Lucida Sans", "DejaVu Sans", Verdana, "sans-serif";
	font-size: 40px;
	color: #202020;
	text-align: center;
	margin-top: 5%;
}

h2 {
	font-family: "Lucida Grande", "Lucida Sans Unicode", "Lucida Sans", "DejaVu Sans", Verdana, "sans-serif";
	font-size: 45px;
	color: #616057;
	text-align: center;
}

h3 {
	font-family: "Lucida Grande", "Lucida Sans Unicode", "Lucida Sans", "DejaVu Sans", Verdana, "sans-serif";
	font-size: 40px;
	color: #F8F5EE;
	text-align: center;
}

h4 {
	font-family: Arial, Helvetica, sans-serif;
	font-size: 15px;
	color: #F8F5EE;
	text-align: center;
}

h5 {
	font-family: "Lucida Grande", "Lucida Sans Unicode", "Lucida Sans", "DejaVu Sans", Verdana, "sans-serif";
	font-size: 40px;
	color: #616057;
	text-align: center;
}

h6 {
	font-family: Arial, Helvetica, sans-serif;
	font-size: 15px;
	color: #616057;
	text-align: center;
}

hr {
	height: 2px;
	background-color: #41403A;
	margin-left: 0px;
	margin-right: 0px;
}

table, th, tr {
	font-family: Verdana, Geneva, Tahoma, sans-serif;
	font-size: 15px;
	color: #616057;
	margin: auto;
	border: 2px;
	border-color: #202020;
	border-collapse: collapse;
}

td {
	text-align: center;
	color: #616057;
	height: 22px;
	vertical-align: middle;
	border: 0px;
	width: 16.66%;
	padding-bottom:10px;
}

table, th, tr {
	font-family: Verdana, Geneva, Tahoma, sans-serif;
	font-size: 15px;
	color: #616057;
	margin: auto;
	border: 2px;
	border-color: #202020;
	border-collapse: collapse;
}

td {
	text-align: center;
	color: #616057;
	height: 22px;
	vertical-align: middle;
	border: 0px;
	width: 16.66%;
}

a {
	text-decoration: none;
	color: #616057;
	text-align:center;
}

td:hover {background-color: #dfdbccdc;}

button {
	position:relative;
	height:50px; width:100px;
	background-color: #616057;
}

button:hover {background-color: #F7F5EE;}

.container {
	align-items: center;
	justify-content: center;
}

.column1 {
	float: left;
	width: 35px;
	padding: 5px;
  }

  .column2 {
	float: right;
	width: 35px;
	padding: 5px;
  }
  
  .row::after {
	content: "";
	clear: both;
	display: table;
  }

.text {
	font-size: 40px;
	color: #202020;
	padding-left: 10px;
	padding-top: 0px;
	float: center;
}

.box {
	width:750px;
	height:250px;
	border:2px #F8F5EE;
	background-color:#f7f5eec9;
	padding: 10px;
	margin:auto;
	justify-content:center;
	align-items:center;
}

.box1 {
	width:250px;
	height:15px;
	border:2px #F8F5EE;
	background-color:#f7f5eec9;
	padding: 10px;
	margin:auto;
	justify-content:center;
	align-items:center;
}

.box2 {
	width:1400px;
	height:70px;
	border:2px #202020;
	background-color:#202020;
	padding: 10px;
	margin:auto;
	justify-content:center;
	align-items:center;
}

.box3 {
	width:1400px;
	height:300px;
	border:2px #616057;
	background-color:#616057;
	padding: 10px;
	margin:auto;
	justify-content:center;
	align-items:center;
}

.box4 {
	width:1400px;
	height:300px;
	border:2px #F8F5EE;
	background-color:#F8F5EE;
	padding: 5px;
	margin:auto;
	justify-content:center;
	align-items:center;
}

section {
	background-image: url("banner.jpeg")
}

.centered {
	position:absolute;
	top: 42%;
	left:25%;
}

.centered:hover {transform: scale(1.1);}

.center {
	position:absolute;
	top:415%;
	left:49.5%;
}

<!doctype html>
<html>
<head>
<meta charset="UTF-8">
<title>Straw Hat Styles</title>
<link href="strawhatstyles.css" rel="stylesheet" type="text/css">
</head>

<body>
<div class="row">
    <div class="column1">
        <img src="user_icon.svg" alt="Account Icon" class="image1">
</div>
<div class="column">
    <h1>STRAW HAT STYLES</h1>
</div>
<div class="column2">
    <img src="cart_icon.svg" alt="Shopping Cart Icon" class="image3"> 
</div>
<div style="text-align:right;">
    <img src="search bar.png" alt="Search Bar" class="image2" width="250px" height="40px"> 
</div>
</div>

<hr>

<nav>
<table>
<tr>
<td>
    <a href="home_page.html">Home</a>
</td>
<td>
    <a href="#">Shop All</a>
</td>
<td>
    <a href="#">Shop By Anime</a>
</td>
<td>
    <a href="#">Shop By Category</a>
</td>
<td>
    <a href="#">Store Policies</a>
</td>
<td>
    <a href="#">Help</a>
</td>
</tr>
</table>
</nav>

<div class="container">
<div style="text-align:center;">
    <img src="banner.jpeg" alt="Banner" width="1400px" height="400px" margin-right="10px"> 
    <div class="centered"><div class="box">
        <h2>WELCOME</h2>
        <p>Check out our latest and most popular products!</p>
        <div style="text-align:center;">
        <button type=""button">Start Now ></button>
        </div>
        </div></div>
</div>
</div>

<div class="box1"></div>

<table>
    <tr>
        <td>
            <img src="one piece keychain.webp" alt="Devil Fruit Keychain - One Piece" class="image2" width="250px" height="250px">
        <p>Devil Fruit Keychain - One Piece<br><b>$10.00</b></p>
        </td>
        <td>
            <img src="one piece tote bag.webp" alt="Devil Fruit Keychain - One Piece" class="image2" width="250px" height="250px">
        <p>Tote Bag - One Piece<br><b>$15.00</b></p>
        </td>
        <td>
            <img src="oen piece phone case.webp" alt="Devil Fruit Keychain - One Piece" class="image2" width="250px" height="250px">
            <p>Phone Case - One Piece<br><b>$15.00</b></p>
        </td>
        <td>
            <img src="one piece airpods case.webp" alt="Devil Fruit Keychain - One Piece" class="image2" width="250px" height="250px">
        <p>Devil Fruit Airpods Case - One Piece<br><b>$12.00</b></p>
        </td>
    </tr>
</table>

<div class="box2"></div>

<img src="shop by anime.png" alt="Shop By Anime" width="1400px" height="500px">
<br>
<img src="shop by category.png" alt="Shop By Category" width="1400px" height="500px">

<div class="box3">
<h3>THE STORY OF STRAW HAT STYLES</h3>
<h4>From a fellow weeb (the creator)
    <br>
    <br>
    There aren't many Australian anime shops out there. As a weeb myself, my goal is to create a reliable website where
    <br>
    Aussies can safely purchase all the anime goods they could ever want.
    <br>
    <br>
    <br>
    Enjoy your time here and feel free to contact us if you have any queries.</h4>
</div>

<div class="box4">
<h5>CONTACT US</h5>
<h6>NSW, Australia
    <br>
    <br>
    <br>
    strawhatstyles@gmail.com
</h6>
<h6>STRAW HAT STYLES</h6>
<a href="https://www.instagram.com/strawhatstyles/?utm_source=qr&igshid=ZDc4ODBmNjlmNQ%3D%3D">
    <img src="link icon.png" alt="Instagram Link" width="25px" height="25px" class="center">
</a>
<br>
<h6>©2022 by Straw Hat Styles</h6>
<br>

</div>

</body>
</html>
