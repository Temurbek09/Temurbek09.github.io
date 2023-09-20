<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Random Password Generator</title>
	<style>
		*{
	padding: 0;
	margin: 0;
	font-family: 'Poppins', sans-serif;
	box-sizing: border-box;
}
body{
	background: #002339;
	color: #fff;
}
.container{
	margin: 12%;
	width: 90%;
	max-width: 700px;
}
.display{
	width: 100%;
	margin-top: 50px;
	margin-bottom: 30px;
	background: #fff;
	color: #333;
	display: flex;
	align-items: center;
	justify-content: space-between;
	padding: 26px 20px;
	border-radius: 5px;
}
.container h1{
	font-weight: 500;
	font-size: 45px;
}
.container h1 span{
	color: #019f55;
	border-bottom: 4px solid #019f55;
	padding-bottom: 7px;
}
.display img{
	width: 30px;
	cursor: pointer;
}
.display input{
	border: 0;
	outline: 0;
	font-size: 24px;
}
.container button img{
	width: 28px;
	margin-right: 10px;
}
.container button{
	border: 0;
	outline: 0;
	background: #019f55;
	color: #fff;
	font-size: 22px;
	font-weight: 300;
	display: flex;
	cursor: pointer;
	align-items: center;
	justify-content: center;
	padding: 16px 26px;
	border-radius: 5px;
}
	</style>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<div class="container">
		<h1>Generate a <br><span>Random Password</span></h1>
		<div class="display">
			<input type="text" id="password" placeholder="Password">
			<img src="copy.png" onclick="copyPassword()">
		</div>
		<button onclick="createPassword()">Generate Password</button>
	</div>
	<script>
		
	const passwordBox = document.getElementById("password");
	const length = 12;

	const upperCase = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
	const lowerCase = "abcdefghijklmnopqrstuvwxyz";
	const number = "0123456789";
	const symbol = "@#$%^&*()_+~|}{[]></-=";

	const allChars = upperCase + lowerCase + number +symbol;

function createPassword(){
	let password = "";
	password += upperCase[Math.floor(Math.random() * upperCase.length)];
	password += lowerCase[Math.floor(Math.random() * lowerCase.length)];
	password += number[Math.floor(Math.random() * number.length)];
	password += symbol[Math.floor(Math.random() * symbol.length)];

	while(length > password.length){
		password += allChars[Math.floor(Math.random() * allChars.length)];

	}
	passwordBox.value = password;

}

function copyPassword(){
	passwordBox.select();
	document.execCommand("copy");

}

	</script>
</body>
</html>
