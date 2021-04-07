<!DOCTYPE html>
<html lang="en">
<style>
body {
  font-family: "Lato", sans-serif;
}

.sidenav {
  height: 100%;
  width: 0;
  position: fixed;
  z-index: 1;
  top: 0;
  left: 0;
  overflow-x: hidden;
  transition: 0.10s;
  padding-top: 70px;
}

.sidenav a {
  padding: 8px 8px 8px 50px;
  text-decoration: none;
  font-size: 25px;
  color: #000000;
  display: block;
  transition: 0.2s;
}

.sidenav a:hover {
  color: #f1f1f1;
}

.sidenav .closebtn {
  position: absolute;
  top: 0;
  right: 25px;
  font-size: 36px;
  margin-left: 60px;
}

@media screen and (max-height: 200px) {
  .sidenav {padding-top: 10px;}
  .sidenav a {font-size: 18px;}
}
</style>
</head>
<body>

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
  <a href="#">Home</a>
  <a href="index1.html">Services</a>
  <a href="#">Clients</a>
  <a href="tel:+917021442794">Contact</a>
  <a href="https://api.whatsapp.com/send?phone=+917021442794">whatsapp</a>
  <a href="https://www.speedtest.net">Speed Test</a>
</div>
<span style="font-size:30px;cursor:pointer" onclick="openNav()" >&#9776;</span>

<script>
function openNav() {
  document.getElementById("mySidenav").style.width = "280px";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0";
}
</script>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link href="style.css" rel="stylesheet">
  <title>S Link Broadband</title>
</head>
<body>
  <section>
    <h1><span>Welcome</span><span>To S Link Broadband</span></h1>
  </section>
    <p>Discover a Wider World of Recreation
      S Link Broadband is a leading Internet Service Provider Mumbai,India. With over 5 years of experience and expertise, we will bring both wired and wireless technology at your service, with dedicated 24X7 customer support.</p>

</body>
</html>
