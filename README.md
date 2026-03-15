# my-website
create a website that generates real instagram followers
{
  <!DOCTYPE html>
<html>
<head>
<title>GrowFollowers</title>
<style>
body{
font-family: Arial;
background:#f2f2f2;
text-align:center;
}
.container{
background:white;
width:350px;
margin:auto;
padding:20px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,0.2);
}
button{
background:#ff2d55;
color:white;
border:none;
padding:10px 20px;
border-radius:5px;
cursor:pointer;
}
</style>
</head>

<body>

<div class="container">
<h2>Get Instagram Followers</h2>

<input id="username" placeholder="Instagram username">
<br><br>

<button onclick="register()">Start</button>

<p id="result"></p>

</div>

<script>
function register(){
let user=document.getElementById("username").value;

if(user==""){
document.getElementById("result").innerHTML="Enter username";
}
else{
document.getElementById("result").innerHTML=
"Welcome "+user+"! Start following users to earn followers.";
}
}
</script>

</body>
</html>
