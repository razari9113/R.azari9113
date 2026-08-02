<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Reza Azari</title>

<link rel="preload" as="image" href="profile.webp">


<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:-apple-system,BlinkMacSystemFont,
"SF Pro Display","Segoe UI",Arial;
-webkit-tap-highlight-color:transparent;
}


body{

min-height:100vh;

display:flex;
justify-content:center;
align-items:center;

overflow:hidden;

background:#050505;

color:white;

}


/* Animated Background */

body::before{

content:"";

position:absolute;

width:700px;
height:700px;

background:
radial-gradient(circle,#1e3a8a55,transparent 60%);

top:-250px;
left:-200px;

animation:move 12s infinite alternate ease-in-out;

}


body::after{

content:"";

position:absolute;

width:600px;
height:600px;

background:
radial-gradient(circle,#2563eb44,transparent 60%);

bottom:-250px;
right:-200px;

animation:move2 15s infinite alternate ease-in-out;

}


@keyframes move{

from{
transform:translate(0,0);
}

to{
transform:translate(150px,120px);
}

}


@keyframes move2{

from{
transform:translate(0,0);
}

to{
transform:translate(-120px,-100px);
}

}



/* Card */

.card{

position:relative;
z-index:2;

width:90%;
max-width:390px;

padding:38px 25px;

text-align:center;

background:
rgba(255,255,255,.08);

backdrop-filter:blur(25px);

-webkit-backdrop-filter:blur(25px);

border-radius:35px;

border:
1px solid rgba(255,255,255,.18);


box-shadow:
0 30px 80px #000;


animation:
show .8s ease;

}



@keyframes show{

from{

opacity:0;

transform:
translateY(40px)
scale(.95);

}

to{

opacity:1;

transform:
translateY(0)
scale(1);

}

}



/* Profile */


.profile-box{

position:relative;

display:inline-block;

}


.profile-box::before{

content:"";

position:absolute;

inset:-8px;

border-radius:50%;

background:
linear-gradient(
45deg,
#2563eb,
#ffffff,
#1e40af
);


filter:blur(12px);

opacity:.7;

animation:
rotate 5s linear infinite;

}


@keyframes rotate{

from{
transform:rotate(0deg);
}

to{
transform:rotate(360deg);
}

}



.profile{

position:relative;

width:135px;

height:135px;

border-radius:50%;

object-fit:cover;

border:3px solid rgba(255,255,255,.8);

box-shadow:
0 15px 40px #000;

}



h1{

margin-top:22px;

font-size:30px;

letter-spacing:1px;

}



.text{

margin-top:8px;

font-size:15px;

opacity:.65;

letter-spacing:.5px;

}



/* Buttons */


button{

width:100%;

height:58px;

margin-top:18px;

border:none;

border-radius:20px;

color:white;

font-size:17px;

font-weight:600;

cursor:pointer;

display:flex;

justify-content:center;

align-items:center;


transition:.2s;

box-shadow:
0 10px 25px #0005;

}


button:active{

transform:scale(.94);

}



.instagram{

background:
linear-gradient(
45deg,
#f9ce34,
#ee2a7b,
#6228d7
);

}



.telegram{

background:
#229ED9;

}



.phone{

background:
#16a34a;

}



.footer{

margin-top:25px;

font-size:12px;

opacity:.5;

}


</style>


</head>


<body>


<div class="card">


<div class="profile-box">

<img 
src="profile.webp"
class="profile"
loading="eager">

</div>



<h1>
Reza Azari
</h1>


<div class="text">

Personal Profile

</div>




<button class="instagram" id="instagram">

Instagram

</button>



<button class="telegram" id="telegram">

Telegram

</button>



<button class="phone" id="phone">

Call Me

</button>




<div class="footer">

© Reza Azari

</div>



</div>



<script>


document
.getElementById("instagram")
.onclick=function(){

window.location.href=
"instagram://user?username=r.azari.9113";

}



document
.getElementById("telegram")
.onclick=function(){

window.location.href=
"tg://resolve?domain=AL_LTO_ONE";

}



document
.getElementById("phone")
.onclick=function(){

window.location.href=
"tel:+989938435526";

}


</script>


</body>

</html>
