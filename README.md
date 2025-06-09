<!DOCTYPE html>
<html lang="en">
<head>
<meta charset= "UTF-8">
<meta name= "viewport" content= "width=device-width , initial-scale=1.0">
<title>To my Love</title>
<link href="https://fonts.googleapis.com/css2?family=Dancing+Script&family=Playfair+Display&family=Pacifico&display=swap" rel="stylesheet">
<style>

	body {
		background-image: url('https://i.ibb.co/b51Yb1vr/image-2025-05-31-171636179.png');
		background-size: cover;
		background-repeat: no-repeat;
		background-position: center;
		text-align: center;
		font-family: 'Dancing Script', cursive;
	}
	.link-title  {
		font-family: 'Playfair Display' , serif;
		overflow: hidden;
	}
		
		.message-box {
			background: rgba(255,255,255,0.1);
			border: 2px solid white;
			border-radius:15px;
			padding: 20px;
			width: 60%;
			margin: 40px auto;
			box-shadow: 0 0 15px white;
	}	
		
		.song-link {
			font-family:'Playfair Display' , serif;
			font-size: 24px;
			color: white;
			text-decoration: none; 
	}
			
		.song-link:hover {
			text-shadow: 0 0 10px white;
	}
	
		.love-message {
		color:white;
		font-size: 30px;
		text-shadow: 0 0 10px white;
	}
			
		.mine-title {
			color:white;
			font-size:90px;
			font-family: 'pacifico' , cursive;
			margin-top: 200px;
	}
			
		@keyframes float{
			0% {transform: translateY(0); opacity: 1;}
			100% {transform: translateY(-100vh); opacity: 0;}
		}
		
		.heart {
			position: absolute;
			width: 20px;
			height: 20px;
			background: red;
			transform: rotate(45deg);
			animation: float 2s infinite;
	}
		
		.heart::before,
		.heart::after {
			content: "";
			position: absolute;
			width: 20px;
			height: 20px;
			background: red;
			border-radius: 50%;
	}	
			
		.heart::before {
			top: -10px;
			left: 0;
	}

		.heart::after {
			top: 0;
			left: -10px;
	}		
		@media	(max-width: 600px) {
		.message-box {
			width: 90%;
			padding: 15px;
	}

		.mine-title { 
			font-size: 50px;
			margin-top: 100px;
	}
	
		.button	{
		font-size: 30px;
		padding: 8px 15px;
		
	}

		img {
			width: 90%;
			height: auto;
	}
	
	}
</style>
</head>
<body>
<div class= "message-box">
<h1 class="love-message"> To my Beautiful girl</h1>
<p class= "love-message"> SHALEV THE LOVE OF MY LIFE, THANK YOU FOR YOU</p>
</div>

<img src= "https://i.ibb.co/ZRC0HQGF/image-2025-05-31-162753177.png" width= "500" height= "500" alt= "beautiful image of love">
<br>
<h2 class="link-title">
	<a href="https://www.youtube.com/watch?v=ZZjnfWx0cvw" class="song-link"> 
			<em> A song that reminds me of you 💜</em>
		</a>
	</h2>
<div style ="margin-top: 200px; text-align: center;">
<h1 class= "mine-title"> MINE.</h1>
<img src= "https://i.ibb.co/pBvt1tf7/image-2025-05-31-173916558.png" alt= "centered image" style="display: block; margin: 0 auto;">
<div class= "heart" style="left: 10%; animation-delay: 0.2s;"></div>
<div class= "heart" style="left: 15%; animation-delay: 0.3s;"></div>
<div class= "heart" style="left: 20%; animation-delay: 0.4s;"></div>
<div class= "heart" style="left: 30%; animation-delay: 0.7s;"></div>
<div class= "heart" style="left: 45%; animation-delay: 1.2s;"></div>
<div class= "heart" style="left: 50%; animation-delay: 1.5s;"></div>
<div class= "heart" style="left: 75%; animation-delay: 2s;"></div>

<button onclick="document.getElementById('loveSong').play()"style=
margin-top: 100px;
font-size: 50px;
background-color: transparent;
color: white;
border: 2px solid white;
border-radius: 12px;
padding: 10px 20px;
cursor: pointer;
font-family: 'Playfair Display',serif;
box-shadow: 0 0 10px white;
">
	💜 Click to Play the Song 💜
</button>	

<audio id="loveSong" loop style="display: none;">
	<source src="https://www.dropbox.com/scl/fi/sw5rozlh0njtksuijwal6/Calum-Scott-You-Are-The-Reason-Official-Video.mp3?rlkey=6ldt1hckxsxgzfhrx0j991x82&st=3pzpcfi7&raw=1" type="audio/mpeg"></audio>
</body>
</html>	


