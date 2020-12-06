<!DOCTYPE html>

<style>
body {
    margin: 30px;
    font-family: Arial, Helvetica, sans-serif;
    background: #333;
    color: #fff;
    font-size: 1.1em;
    line-height: 1.5;
    text-align: center;

}
header {
    display: block;
}

#top {
    min-height: 450px;
    text-align: center;
}
#top .headBg{
	position: absolute;
	background-image: url("bg.jpg");
	width: 100%;
	height: 450px;
	z-index: -1;
	background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    opacity: 0.5;
}
h1 {
	padding-top: 100px;
    display: block;
    font-size: 50px;
    font-weight: bold;
}
p {
    display: block;
}
#sec-a{
	display: block;
	background-color: rgb(47,79,79);
	padding-bottom: 15px;
	padding-top: 15px;
	text-align: center;
	min-height: 150px;
	}
h2{
	text-decoration: underline;
	font-weight: bold;
	display: block;
}
#sec-a .review_text {
	padding-left: 50px;
	padding-right: 50px;
    columns: 2;
    column-gap: 2em;
}
#sec-c ul{
	display: flex;
	justify-content: space-around;
}
ul {
	align-content: center;
	list-style: none;
    grid-column: 2/4;

}
li{
    padding: 0px;
}
img{
	display: block;
    width: 100%;
    height: auto;
}
h3{
	display: block;
}

#sec-d{
	display: block;
	background-color: rgb(47,79,79);
	padding-bottom: 10px;
	padding-top: 10px;
	text-align: center;
	min-height: 100px;
}
#sec-d .about_text{
	padding-left: 50px;
	padding-right: 50px;
	background-color: rgb(47,79,79);
}
.grid2{
	display: grid;
	grid-template-columns: 1fr repeat(2, minmax(auto, 25em)) 1fr;
}
.box{
	background-color: rgb(47,79,79);
	grid-column: span 2;
}
.contact-text{
	background-color: rgb(0,79,0);
}
.about-maker{
	background-color: rgb(0,0,79);
}
div{
	display: block;
}
.card-content {
    padding: 1.5em;
  }
#sec-c li{
	width: 31%;
}
.btn{
	display: inline-block;
    background: #333;
    color: #fff;
    text-decoration: none;
    padding: 1em 2em;
    border: 1px solid #666;
    margin: 0.5em 0;
}
</style>
<html>
	<head>
		<title>CSS Responsive</title>
		<link rel="stylesheet" href="views/style.css">
	</head>

	<body>
		<header id="top" class="grid">
			<div class="headBg"></div>
			<div class="headtext">
			<h1>Turbo (Ryan Reynolds)-2013</h1>
			<p>
				Turbo (Ryan Reynolds) is a speed-obsessed snail with an unusual dream: to become the world's greatest racer. This odd snail gets a chance to leave his slow-paced life behind when a freak accident gives him the power of superspeed.
			</p>
			<a href="#sec-c" class="btn">Gallery</a>
			
			</div>
		</header>
		<br>

		<section id="sec-a" class="grid">
			<div>
				<h2 class="review">Critic Reviews & Public Reactions</h2>
				<div>
					<p class="review_text">
						"This is one of the best movies of the decade, showing the emotion that comes with being a human, and the vulnerability of being a man. In this thriller, we meet our young hero, Tyson. As he walks the fields of his home, he encounters a blue snail. He decides to take him home, only to release him shortly after. As he awakes in the middle of the night, he sees that snails are entering his home, only to turn him into a snail."
					</p>
				</div>
			</div>

		</section>
		
		<br>
		<section id="sec-c" class="grid">
			<ul>
				<li>
					<div class="card">
						<img src="views/turbo1.jpg" alt="Turbo">
						<div class="card-content">
							<h3 class="card-title">Turbo</h3>
							<p>
								This is one of the best movies of the decade, showing the emotion that comes with being a human, and the vulnerability of being a man.
							</p>
							
						</div>
					</div>
				</li>
				<li>
					<div class="card">
						<img src="views/turbo2.jpg" alt="Turbo">
						<h3 class="card-title">Turbo</h3>
						<p>
							This is one of the best movies of the decade, showing the emotion that comes with being a human, and the vulnerability of being a man.
						</p>
						
					</div>
					
				</li>
				<li>
					<div class="card">
						<img src="views/turbo3.jpg" alt="Turbo">
						<h3 class="card-title">Turbo</h3>
						<p>
							This is one of the best movies of the decade, showing the emotion that comes with being a human, and the vulnerability of being a man.
						</p>
						
					</div>
					
				</li>
			</ul>
			
		</section>
		<br>
		<section id="sec-d" class="grid">
			<h2 class="about">About the movie</h2>
				<div>
					<p class="about_text">
						Along with his streetwise snail crew and new human friends, Turbo, an underdog snail, takes on the biggest challenge ever to make their dreams come true.
					</p>
		</section>
		<br>
		<section id="sec-e" class="grid2">
			<div class="box">
			<h2 class="contact-text">Contact Maker</h2>
			<p>
				Thanks to movies like Shrek, Trolls, Kung-Fu Panda, How to Train Your Dragon, Madagascar, and The Boss Baby, and television series like Trollhunters, Spirit Riding Free, and All Hail King Julien, DreamWorks Animation is recognized across the globe as a leader in quality family entertainment.
			</p>
			</div>
			<div class="box">
			<h2 class="about-maker">About Maker</h2>
			<p>
				Thanks to movies like Shrek, Trolls, Kung-Fu Panda, How to Train Your Dragon, Madagascar, and The Boss Baby, and television series like Trollhunters, Spirit Riding Free, and All Hail King Julien, DreamWorks Animation is recognized across the globe as a leader in quality family entertainment.
			</p>
			</div>
		</section>
		<br>
		<br>
		<div>
			<p style="background-color: black;">
				Project by Md Hasibur Rahman Tomal @copyright2020
			</p>
		</div>
	</body>
</html>
