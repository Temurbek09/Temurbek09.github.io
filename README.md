<html>
<head>
	<title>Navoi Presidental School</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" type="text/css" href="style1.css">
	<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.1/css/fontawesome.min.css">
	<script src="https://cdn.jsdelivr.net/gh/cferdinandi/smooth-scroll/dist/smooth-scroll.polyfills.min.js"></script>
	<style>
		@import url('https://fonts.googleapis.com/css2?family=Kaushan+Script&display=swap');

*{
	margin: 0;
	padding: 0;
	font-family: 'Poppins', sans-serif;
	
}

#banner{
	background: linear-gradient(rgba(0,0,0,0.5),#009688),url(school.jpg);
	background-size: cover;
	background-position: center;
	height: 100vh;
}

.logo{
	width: 140px;
	height: 140px;
	position: absolute;
	top: 2%;
	left: 1%;
	border-radius: 50%;
}
.banner-text{
	text-align: center;
	color: #fff;
	padding-top: 180px;
}

.banner-text h1{
	font-size: 130px;
	color: #fd4a47;
	font-family: 'Kaushan Script', cursive;
}

.banner-text p{
	font-size: 20px;
	font-style: italic;
	color: #000;
	font-family: 'Kaushan Script', cursive;
}

.banner-btn{
	margin: 70px auto 0;
	font-family: 'Kaushan Script', cursive;
}

.banner-btn a{
	width: 150px;
	text-decoration: none;
	display: inline-block;
	margin: 0 10px;
	padding: 12px 0;
	color: #fff;
	border: .5px solid #0000FF;
	position: relative;
	z-index: 1;
	transition: color 0.5s;
}

.banner-btn a span{
	width: 0;
	height: 100%;
	position: absolute;
	top:0;
	left: 0;
	background: #fff;
	z-index: -1;
	transition: 0.5s;
}

.banner-btn a:hover span{
	width: 100%;

}
.banner-btn a:hover{
	color: #fd4a47;
	border: .5px solid #000;
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
@media screen and(max-width: 770px){
	.banner-text h1{
		font-size: 44px;
		color: #fd4a47;
	}
	.banner-btn a{
		display: block;
	}
}
/*--featur--*/

#feature{
	width: 100%;
	padding: 70px 0;
}
.title-text{
	text-align: center;
	padding-bottom: 70px;
}
.title-text p{
	margin: auto;
	font-size: 20px;
	color: #009688;
	font-weight: bold;
	position: relative;
	z-index: 1;
	display: inline-block;
	font-family: 'Kaushan Script', cursive;

}
.title-text p::after{
	content: '';
	width: 50px;
	height: 35px;
	background: linear-gradient(#019587,#fff);
	position: absolute;
	top: -20px;
	left: 0;
	z-index: -1;
	transform: rotate(10deg);
	border-top-left-radius: 35px;
	border-bottom-right-radius: 35px;
}
.title-text h1{
	font-size: 50px;

}
.future-box{
	width: 80%;
	margin: auto;
	display: flex;
	flex-wrap: wrap;
	align-items: center;
	text-align: center;	
}
.features{
	flex-basis: 50%;
}

.features-img{
	flex-basis: 50%;
	margin top: 00px;
	margin-left: 500px;
	margin-bottom: 00px;
}
.features-img img{
	width: 40%;
	border-radius: 50%;
	margin-left: 0px;
	margin-top: 10px;
}
.features h1{
	margin-left: 30px;
	margin-bottom: 10px;
	font-weight: 100;
	color: #009688;
	font-family: 'Kaushan Script', cursive;
}
.features-desc{
	display: flex;
	align-items: center;
	margin-bottom: 40px;

}
	
.feature-icon i{
	margin-left: 10px;

}
.feature-icon img{
	width: 50px;
	height: 50x;
	font-size: 30px;
	margin-left: 30px;
	line-height: 50px;
	border-radius: 8px;
	color: #009688;
	border: 1px solid #009688;
}
.features h1{
	margin-bottom: 10px;
	font-weight: 100;
	color: #009688;
	margin-left: 30px;
}
.features-desc{
	display: flex;
	align-items: center;
	margin-bottom: 40px;
}
@media screen and (max-width:770px){
	.title-text h1{
		font-size: 35px;
	}
	.features{
		flex-basis: 100%;
	}
	.features-img{
		flex-basis: 100%;
		margin-left: 250px;
		margin-bottom: 100px;
	}
	.features-img img{
		width: 100%;
	}
}
.feature-text p{
	margin-left: 0px;
	padding: 0 20px;
	margin-right: 700px;
	margin-top: 0px;
	margin-bottom: 0px;
	text-align: initial;
}
#service{
	width: 100%;
	padding: 70px 0;
	background: #efefef;
}
.service-box{
	width: 80%;
	display: flex;
	flex-wrap: wrap;
	justify-content: 	space-around;
	margin: auto;
}
.single-service{
	flex-basis: 48%;
	text-align: center;
	border-radius: 7px;
	margin-bottom: 20px;
	color: #fff;
	position: relative;
}
.single-service img{
	width: 100%;
	border-radius: 7px;
	height: 350px;
}
.overlay{
	width: 100%;
	height: 100%;
	position: absolute;
	top: 0;
	border-radius: 7px;
	background: linear-gradient(rgba(0, 0, 0, 0.5),#009688);
	opacity: 0;
	transition: 1s;
}
.single-service:hover .overlay{
	opacity: 1;
}

.service-desc{
	width: 80%;
	position: absolute;
	bottom: 40%;
	left: 50%;
	opacity: 0;
	transform: translateX(-50%);
	transition: 1s;
}
hr{
	background: #fff;
	height: 2px;
	border: 0;
	margin: 15px auto;
	width: 60%;
}
.service-desc p{
	font-size: 14px;
}
.single-service:hover .service-desc{
	bottom: 40%;
	opacity: 1;
}
@media screen and (max-width:770px){
	.single-service{
		flex-basis: 100%;
		margin-bottom: 30px;
	}
	.service-desc p{
		font-size: 12px;
	}
	hr{
		margin: 5px auto;
	}
	.single-service:hover .service-desc{
		bottom: 40% !important;
	}
}
#testimonial{
	width: 100%;
	padding: 70px 0;
}
.testimonial-row{
	width: 80%;
	margin: auto;
	display: flex;
	justify-content: space-between;
	align-items: flex-start;
	flex-wrap: wrap;
}
.testimonial-col{
	flex-basis: 28%;
	padding: 10px;
	margin-bottom: 30px;
	border-radius: 5px;
	border: solid #27c0ff 1px;
	cursor: pointer;
	transition: transform .5s;
}
.testimonial-col p{
	font-size: 14px;	
}
.user{
	display: flex;
	align-items: center;
	margin: 20px 0;
}
.user img{
	width: 40px;
	margin-right: 20px;
	border-radius: 3px;	
}
.user-info img{
	width: 13px;
	height: 13px;
}
.testimonial-col:hover{
	transform: translateY(7px);

}
@media screen and (max-width:770px){
	.testimonial-col{
		flex-basis: 100%;
	}
}

#footer{
	padding: 100px 0 20px;
	background: #efefef;
	position: relative;
}
.footer-row{
	width: 80%;
	margin: 0 auto;
	display: flex;
	justify-content: space-between;
	flex-wrap: wrap;

}
.footer-left,.footer-right{
	flex-basis: 45%;
	padding: 10px;
	margin-bottom: 20px;
}
.footer-right{
	text-align: right;	
}
.footer-row h1{
	margin: 10px 0;
}
.footer-row p{
	line-height: 35px;

}
.footer-left img{
	width: 15px;
	height: 15px;
}
.footer-right img{
	width: 15px;
	height: 15px;
	border-radius: 50%;
}
.footer-right p{
	margin-left: 200px;	
}
.footer-img{
	max-width: 370px;
	opacity: 0.1;
	position: absolute;
	left: 50%;
	top: 35%;
	transform: translate(-50%,-50%);

}
.social-links img{
	width: 40px;
	height: 40px;
	font-size: 20px;
	line-height: 40px;
	border: 2px solid #fd4a47;
	border-radius: 50%;
	margin: 40px 5px 0;
	cursor: pointer;
	transition: .5s;
}
.social-links{
	text-align: center;

}
.social-links img:hover{
	background: #009688;
	color: #fff;
	transform: translateY(-7px);
}
@media screen and (max-width:770px){
	.footer-left,.footer-right{
		flex-basis: 100%;
		font-size: 14px;
	}
	.footer-img{
		top: 25%;

	}	
}
#exam{
	width: 100%;
	padding: 70px 0;
}
.title-text{
	text-align: center;
	padding-bottom: 70px;
}
.title-text p{
	margin: auto;
	font-size: 20px;
	color: #009688;
	font-weight: bold;
	position: relative;
	z-index: 1;
	display: inline-block;
	font-family: 'Kaushan Script', cursive;

}
.title-text p::after{
	content: '';
	width: 50px;
	height: 35px;
	background: linear-gradient(#019587,#fff);
	position: absolute;
	top: -20px;
	left: 0;
	z-index: -1;
	transform: rotate(10deg);
	border-top-left-radius: 35px;
	border-bottom-right-radius: 35px;
}
.title-text h1{
	font-size: 50px;

}
.future-box{
	width: 80%;
	margin: auto;
	display: flex;
	flex-wrap: wrap;
	align-items: center;
	text-align: center;	
}
.exams{
	flex-basis: 50%;
}

.exams-img{
	flex-basis: 50%;
	margin top: 00px;
	margin-left: 500px;
	margin-bottom: 00px;
}
.exams-img img{
	width: 40%;
	border-radius: 50%;
	margin-left: 0px;
	margin-top: 10px;
}
.exams h1{
	margin-left: 30px;
	margin-bottom: 10px;
	font-weight: 100;
	color: #009688;
	font-family: 'Kaushan Script', cursive;
}
.exams-desc{
	display: flex;
	align-items: center;
	margin-bottom: 40px;

}
	
.exam-icon i{
	margin-left: 10px;

}
.exam-icon img{
	width: 50px;
	height: 50x;
	font-size: 30px;
	margin-left: 30px;
	line-height: 50px;
	border-radius: 8px;
	color: #009688;
	border: 1px solid #009688;
}
.exams h1{
	margin-bottom: 10px;
	font-weight: 100;
	color: #009688;
	margin-left: 30px;
}
.exams-desc{
	display: flex;
	align-items: center;
	margin-bottom: 40px;
}
@media screen and (max-width:770px){
	.title-text h1{
		font-size: 35px;
	}
	.exams{
		flex-basis: 100%;
	}
	.exams-img{
		flex-basis: 100%;
		margin-left: 250px;
		margin-bottom: 100px;
	}
	.exams-img img{
		width: 100%;
	}
}
.exam-text p{
	margin-left: 0px;
	padding: 0 20px;
	margin-right: 700px;
	margin-top: 0px;
	margin-bottom: 0px;
	text-align: initial;
}
	</style>
</head>
<body>
<section id="banner">
	<img src="logo.png" class="logo">
	<div class="banner-text">
		<h1><b>NPS</b></h1>
		<p>Turning your dreams into reality.</p>
		<div class="banner-btn">
			<a href="#"><span></span>Find Out</a>
			<a href="#"><span></span>Read More</a>
		</div>
	</div>
</section>

<div id="sideNav">
	<nav>
	<ul>
		<li><a href="#banner">Home</a></li>
		<li><a href="#feature">About Me!</a></li>
		<li><a href="#service">About Teachers!</a></li>
		<li><a href="#testimonial">International Teachers.</a></li>
		<li><a href="#footer">About School.</a></li>
		<li><a href="#exam">About Exams.</a></li>
	</ul>
	</nav>
</div>
<div id="menuBtn">
	<img src="menu.png" id="menu">
</div>

<!--Features-->

<section id="feature">
<div class="title-text">
<p>About Me!</p>
<h1>Student</h1>
</div>
<div class="feature-box">
	<div class="features">
		<h1>When I was Born?</h1>
		<div class="features-desc">
			<div class="feature-icon">
				<img src="shield.png">
			</div>
			<div class="feature-text">
				<p>I was Born in 26.04.2011 and I am 11 year old.</p>
			</div>
		</div>
		<h1>Where I was Born?</h1>
		<div class="features-desc">
			<div class="feature-icon">
				<img src="check.png">
			</div>
			<div class="feature-text">
				<p>I am from Uzbekistan and I was Born in Zarafshan.</p>
			</div>
		</div>
		<h1>Where I study?</h1>
		<div class="features-desc">
			<div class="feature-icon">
				<img src="inr.png">
			</div>
			<div class="feature-text">
				<p>I am from Zarafshan but, I study in Presidental School in <b>Navai<b>.</p>
			</div>
		</div>
	</div>
</div>
</section>

<!--Service-->

<section id="service">
<div class="title-text">
<p>About Teachers!</p>
<h1>Our Teachers.</h1>
</div>
<div class="service-box">
	<div class="single-service">
		<img src="pic-1.jpg">
		<div class="overlay"></div>
		<div class="service-desc">
			<h3>Our Teachers</h3>
			<hr>
			<p>Our techers are very smart.</p>
		</div>
	</div>
	<div class="single-service">
		<img src="pic-2.jpg">
		<div class="overlay"></div>
		<div class="service-desc">
			<h3>Our Teachers</h3>
			<hr>
			<p>Our Teachers Are very positive.</p>
		</div>
	</div>
	<div class="single-service">
		<img src="pic-3.jpg">
		<div class="overlay"></div>
		<div class="service-desc">
			<h3>Our Teachers</h3>
			<hr>
			<p>Our techers are very Strong.</p>
		</div>
	</div>
	<div class="single-service">
		<img src="pic-4.jpg">
		<div class="overlay"></div>
		<div class="service-desc">
			<h3>Our Teachers</h3>
			<hr>
			<p>Our techers are The best.</p>
		</div>
	</div>
</div>
</section>
<section id="testimonial">
<div class="title-text">
<p>International Teachers.</p>
<h1>What International Teachers says.</h1>
</div>
<div class="testimonial-row">
	<div class="testimonial-col">
		<div class="user">
			<img src="img-1.jpg">
			<div class="user-info">
				<h4>Ms Christa<img src="t.png"></h4>
				<small>@MsChrista</small>
			</div>
		</div>
		<h3>I'm the computer Science's teacher.This is the best school I see ever.This shool's Studentds are too smart but, the smartest is Temurbek from 6Blue.</h3>
	</div>
	<div class="testimonial-col">
		<div class="user">
			<img src="img-2.jpg">
			<div class="user-info">
				<h4>Mr Bagdan<img src="t.png"></h4>
				<small>@MrBagdan</small>
			</div>
		</div>
		<h3>I'm Science's teacher.Yeah this is very great school. There are many smart pupil and I was Shocked when saw The samrtest pupil(Temurbek 6Blue).I don't work so hard.</h3>
	</div>
	<div class="testimonial-col">
		<div class="user">
			<img src="img-2.jpg">
			<div class="user-info">
				<h4>Ms Thabang.<img src="t.png"></h4>
				<small>@MsThabang</small>
			</div>
		</div>
		<h3>I'm Mathematic's teacher.This school is very Beautiful and great And There are all pupils are sorted from another many pupils.There is the smartest pupil is Temurbek from 6Blue</h3>
	</div>
</div>


</section>
<section id="footer">
<img src="footer-img.jpg" class="footer-img">
<div class="title-text">
<p>About School.</p>
<h1>NPS</h1>
</div>
<div class="footer-row">
	<div class="footer-left">
		<h1>Study days</h1>
		<p><img src="clock.png">Monday to Friday - 8:30-15:35</p>
	</div>
	<div class="footer-right">
		<h1>Get in Touch</h1>
		<p><img src="check.png">Uzbekistan Respublic,Navai region,Navai city, Near Park.</p>
		<p><img src="t.jpg">Telegram Channel>>><a href = "https://t.me/maqsad_kamolot_sari" class="l" target="_blank">Click Me</a></p>
	</div>
</div>
<div class="social-links">
	<a href = "https://www.facebook.com/prezident.maktablar/" class="l" target="_blank"><img src="f.jpg" ></a>
	<a href = "https://www.instagram.com/nps_press/" class="l" target="_blank"><img src="i.jpg" ></a>
	<a href = "https://t.me/maqsad_kamolot_sari" class="l" target="_blank"><img src="t.jpg" ></a>
	<a href = "https://www.youtube.com/@PIIMArasmiysahifasi" class="l" target="_blank"><img src="y.png" ></a>
</div>
</section>
<section id="exam">
<div class="title-text">
<p>About Exams!</p>
<h1>Exams</h1>
</div>
<div class="exam-box">
	<div class="exams">
		<h1>When Exam was?</h1>
		<div class="exams-desc">
			<div class="exam-icon">
				<img src="shield.png">
			</div>
			<div class="exam-text">
				<p>I think 1st stage was in 1July in 2022 and 2nd stage was in 2nd August in 2022.</p>
			</div>
		</div>
		<h1>Where Exam was.</h1>
		<div class="exams-desc">
			<div class="exam-icon">
				<img src="check.png">
			</div>
			<div class="exam-text">
				<p>It was in Navai street: Alisher Navai.</p>
			</div>
		</div>
		<h1>What you feel after 2nd stage.</h1>
		<div class="exams-desc">
			<div class="exam-icon">
				<img src="feel.png">
			</div>
			<div class="exam-text">
				<p>I think I pass the exam and was so happy and my family also.</p>
			</div>
		</div>
	</div>
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
