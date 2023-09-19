<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" type="text/css" href="styleweb1.css">
	<script src="https://cdn.jsdelivr.net/gh/cferdinandi/smooth-scroll/dist/smooth-scroll.polyfills.min.js"></script>
	<title>Our House</title>
	<style>
		*{
	margin: 0;
	padding: 0;
	font-family: sans-serif;
}
.banner{
	width: 100%;
	height: 100vh;
	background-image: linear-gradient(rgba(0,0,0,0.75),rgba(0, 0, 0, 0.75)),url(background1.jpg);
	background-size: cover;
	background-position: center;

}
.navbar img{
	width: 150px;
	height: 150px;
	border-radius: 100%;
	cursor: pointer;
}
.navbar{
	width: 85%;
	margin: auto;
	padding: 10px 0;
	display: flex;
	align-items: center;
	justify-content: space-between;	
}
.navbar ul li{
	list-style: none;
	display: inline-block;
	margin: 0 20px;
	position: relative;
}
.navbar ul li a{
	text-decoration: none;
	color: #fff;
	text-transform: uppercase;
}
.navbar ul li::after{
	content: '';
	height: 3px;
	width: 0;
	background: #009688;
	position: absolute;
	left: 0;
	bottom: -10px;
}
.navbar ul li:hover::after{
	width: 100%;
	transition: 0.5s;
}
.content{
	width: 100%;
	position: absolute;
	top: 50%;
	transform: translateY(-50%);
	text-align: center;
	color: #fff;
}
.content h1{
	font-size: 70px;
	margin-top: 80px;
}
.content p{
	margin: 20px auto;
	font-weight: 100;
	line-height: 25px;
	font-size: 33px;
}
button{
	width: 200px;
	padding: 15px 0;
	text-align: center;
	margin: 20px 10px;
	border-radius: 25px;
	font-weight: bold;
	border: 2px solid #009688;
	background: transparent;
	color: 	#fff;
	cursor: pointer	;
	position: relative;
	overflow: hidden;
}
span{
	background: #009688;
	height: 100%;
	width: 0%;
	border-radius: 25px;
	position: absolute;
	left: 0;
	bottom: 0;
	z-index: -1;
}
button:hover span{
	width: 100%;
	transition: 0.5s;
}
button:hover{
	border: none;
}
.banner2{
	width: 100%;
	height: 100vh;
	background-image: linear-gradient(rgba(0,0,0,0.5),#fd4a47),url(background.jpg);
	background-size: cover;
	background-position: center;
}
#menuBtn{
	width: 50px;
	height: 50px;
	background: #009688;
	text-align: center;
	position: fixed;
	right: 30px;
	top: 20px;
	border-radius: 3px;
	z-index: 3;
	cursor: pointer;
}
#menuBtn img{
	width: 20px;
	margin-top: 15px;
}
#sideNav{
	width: 250px;
	height: 100vh;
	position: fixed;
	right: -250px;
	top: 0;
	background: #009688;
	z-index: 2;
	transition: 0.5s;
}
nav ul li{
	list-style: none;
	margin: 50px 20px;
}
nav ul li a{
	text-decoration: none;
	color: #fff;
}
.banner2 img{
	width: 150px;
	height: 150px;
	border-radius: 50%;
	cursor: pointer;
	margin-top: 10px;
	margin-left: 100px;
}
.content2{
	width: 100%;
	position: absolute;
	top: 150%;
	transform: translateY(-50%);
	text-align: center;
	color: #fff;
}
.content2 h1{
	font-size: 70px;
	margin-top: 80px;
}
.content2 p{
	margin: 20px auto;
	font-weight: 100;
	line-height: 25px;
	font-size: 33px;
}
.banner3{
	width: 100%;
	height: 100vh;
	background-image: linear-gradient(rgba(42,58,74,0.85),rgba(42,58,74,0.85)),url(kitchen.jpg);
	background-size: cover;
	background-position: center;
}
.banner3 img{
	width: 150px;
	height: 150px;
	border-radius: 50%;
	cursor: pointer;
	margin-top: 10px;
	margin-left: 100px;
}
.content3{
	width: 100%;
	position: absolute;
	top: 250%;
	transform: translateY(-50%);
	text-align: center;
	color: #fff;
}
.content3 h1{
	font-size: 70px;
	margin-top: 80px;
}
.content3 p{
	margin: 20px auto;
	font-weight: 100;
	line-height: 25px;
	font-size: 33px;
}
.banner4{
	width: 100%;
	height: 100vh;
    background-image: linear-gradient(to right, rgba(255,0,0,0), rgba(255,0,0,1)),url(bath.jpg);
	background-size: cover;
	background-position: center;
}
.banner4:hover overlay{
	opacity: 1;
}

.banner4 img{
	width: 150px;
	height: 150px;
	border-radius: 50%;
	cursor: pointer;
	margin-top: 10px;
	margin-left: 100px;
}
.content4{
	width: 100%;
	position: absolute;
	top: 350%;
	transform: translateY(-50%);
	text-align: center;
	color: #fff;
}
.content4 h1{
	font-size: 70px;
	margin-top: 80px;
}
.content4 p{
	margin: 20px auto;
	font-weight: 100;
	line-height: 25px;
	font-size: 33px;
}
.banner5{
	width: 100%;
	height: 100vh;
    background-image: linear-gradient(to left, rgba(255,0,0,0), rgba(0,0,255,1)),url(liv-room.jpg);
	background-size: cover;
	background-position: center;
}
.banner5 img{
	width: 150px;
	height: 150px;
	border-radius: 50%;
	cursor: pointer;
	margin-top: 10px;
	margin-left: 100px;
}
.content5{
	width: 100%;
	position: absolute;
	top: 450%;
	transform: translateY(-50%);
	text-align: center;
	color: #fff;
}
.content5 h1{
	font-size: 70px;
	margin-top: 80px;
}
.content5 p{
	margin: 20px auto;
	font-weight: 100;
	line-height: 25px;
	font-size: 33px;
}
	</style>
</head>
<body>
	<section id="home">
	<div class="banner">
		<div class="navbar">
			<img src="fam-logo.png" class="logo">
		</div>

		<div class="content">
			<h1>Introduce My House.</h1>
			<p>Please Follow me in Robocontest>>><a href = "https://robocontest.uz/profile/temurbek_0912" class="l" target="_blank">Click Me!</a></p>
			<button	type="button"><span></span>Like</button>
			<button	type="button"><span></span>Subscribe</button>
		</div>
	</div>
	</section>
	<div id="sideNav">
	<nav>
	<ul>
		<li><a href="#home">Home</a></li>
		<li><a href="#bedroom">BedRoom</a></li>
		<li><a href="#kitchen">Kitchen</a></li>
		<li><a href="#bath">Bath</a></li>
		<li><a href="#livingroom">Living Room</a></li>
	</ul>
	</nav>
</div>
<div id="menuBtn">
	<img src="menu.png" id="menu">
</div>
	<section id="bedroom">
		<div class="banner2">
				<img src="bed-logo.png">
		</div>
		<div class="content2">
			<h1>My bedroom!
			</h1>
			<p>It Is My bedroom and this bed is so soft and I like <br>sleep in this bed</p>
			<button	type="button"><span></span>Like</button>
			<button	type="button"><span></span>Subscribe</button>

		</div>
	</section>
<section id="kitchen">
	<div class="banner3">
		<img src="kit-logo.png">
	</div>
		<div class="content3">
			<h1>Introduce My Kitchen.</h1>
			<p>My kitchen is very Big and in My kitchen has Refrigerator,<br> Table, foods and sweets.</p>
			<button	type="button"><span></span>Like</button>
			<button	type="button"><span></span>Subscribe</button>
		</div>
</section>
<section id="bath">
	<div class="banner4">
		<img src="bath-logo.png">
	</div>
		<div class="content4">
			<h1>Introduce My Bath.</h1>
			<p>My Bath is very Big and in My Bath has Toilet,<br> Bath, sink and mirror</p>
			<button	type="button"><span></span>Like</button>
			<button	type="button"><span></span>Subscribe</button>
		</div>
</section>
<section id="livingroom">
	<div class="banner5">
		<img src="liv-logo.png">
	</div>
		<div class="content5">
			<h1>Introduce My Living Room.</h1>
			<p>My Living room is so big and When Guests coming <br>They sit here.</p>
			<button	type="button"><span></span>Like</button>
			<button	type="button"><span></span>Subscribe</button>
		</div>
</section>
<script>
var menuBtn = document.getElementById("menuBtn")
var sideNav = document.getElementById("sideNav")
var menu = document.getElementById("menu")

sideNav.style.right= "-250px" 

menuBtn.onclick = function(){
	if (sideNav.style.right== "-250px" ){
		sideNav.style.right="0";
		menu.src = "close.png"
	}
	else{
		sideNav.style.right="-250px";
		menu.src = "menu.png"

	}
}
var scroll = new SmoothScroll('a[href*="#"]', {
	speed: 1000,
	speedAsDuration: true
});
</script>
</body>
</html>
