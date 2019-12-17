</!DOCTYPE html>
<html>
<head>
	<title>Tejus | Homepage</title>
	<meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" type="text/css" href="style/style.css">
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>
</head>
<body>
	<header id="top">
		<div class="background">
			<div class="navbar">
				<a class="active" href="main page.html">Home</a>
				<a href="#education">Education</a>
				<a href="#myinterests">My Interests</a>
				<a href="#contactme">Contact Me</a>
			</div>
			<div class="content">
				<h1>Hi, I'm Tony Stark</h1>
				<p>
					Sometimes people call me Tejus Singla.<br>
				</p>
				<p id="profession">Philosopher | Space Enthusiast</p><br>
				<!-- <p>
					Bachelor of technology, Mathematics And Computing<br>
					Indian Institute of Technology Guwahati.  
				</p> -->
			</div>
		</div>
	</header>
	<div class="content1">
		<div id="me">
			<img src="C:\Users\tejus\Desktop\New folder\My portfolio\images\me.JPG" alt="Tejus's image">
		</div>
		<h1 id="education" class="underline">Education</h1>
		<p class="push"><strong>Indian Institute of Technology Guwahati</strong><br>
			Bachelor of Technology | Mathematics And Computing, 9.33<br>
			Course Structure: https://www.iitg.ac.in/maths/acads/btech_struct.php?new=<br>
			<strong>Doon Valley School</strong><br>
		</p>
		<h3>Courses: </h3>
		<p class="push">
			<strong>Mathematics: </strong>Linear Algebra, Single Variable and Multiple Variable Calculus, Discrete Mathematics, 	Probability Theory and Random Processes, Complex Analysis, Partial Differential Equations, Ordinary Differential Equations, Elementary Number Theory and Algebra.<br>
			<strong>Computer Science: </strong>Introduction to Computing, Computing Laboratory, Data Structures, Digital Design.  	
		</p>
		<div id="skills">
			<h3>Compute Languages: </h3>
			<p>C, C++, Python, HTML, CSS</p>
		</div>
	</div>
	<!--Done-->
	<div id="background2">
		<div class="content2">
			<h1 id="myinterests" class="underline">My Interests</h1>
			<ul class="list">
				<li>I like space</li>
				<li>Space does not begin at a specific altitude above the Earth, but the Kármán line at 100km is a commonly used definition.</li>	
				<li>The temperature in the void of space is about −270.45 °C.</li>
				<li>Space is a hard vacuum, meaning it is a void containing very little matter.</li>
				<li>The space between galaxies is not completely empty but has an average of one atom per cubic meter.</li>
				<li>There are an estimated 100-400 billion stars in our galaxy, the Milky Way.</li>
				<li>The universe is observed to be 13.8 billion years old has been expanding since its formation in the Big Bang.</li>
				<li>In the observable universe there are an estimated 2 trillion (2,000,0000,000,000) galaxies.</li>
			</ul>
		</div>
	</div>	
	<div class="content3">
		<h1 id="contactme" class="underline">Contact Me</h1>
		<div class="push">
			<form action="/action_page.php" method="post">
				<label for="name">YOUR NAME</label><br>
				<input type="text" name="name" id="name" required><br>
				<label for="email">YOUR EMAIL</label><br>
				<input type="text" name="email" id="email" required><br>
				<label for="message">YOUR MESSAGE</label><br>
				<textarea name="message" id="message" required rows="5" cols="40"></textarea><br><br>
				<input type="submit" value="Send" class="btn btn-dark">
			</form>
		</div>
	</div>
	<div class="last">
		<div class="push">
	  		<a href="#" class="fa fa-facebook"></a>
			<a href="#" class="fa fa-twitter"></a>
			<a href="#" class="fa fa-google"></a>
			<a href="#" class="fa fa-linkedin"></a>
			<a href="#" class="fa fa-youtube"></a>
			<a href="#" class="fa fa-instagram"></a>
			<a href="#" class="fa fa-snapchat-ghost"></a>
		</div>	
		<!-- Copyright -->
		<div class="footer-copyright text-center py-3">© 2019 Copyright:
		<a href="#top"> Tejus Singla</a>
		</div>
		<!-- Copyright -->

	</div>
</body>
</html>