<!DOCTYPE html>
<html>
	<head>
		<title> Recipe Book! </title>
		<style>
			#nav {
				position: fixed;
				top: 0px;
				left: 0px;
				padding: 10px;
				margin: 0px;
				width: 100%;
				background-color: #ffecc4;
			}
			
			#sidenav {
				position: fixed;
				top: 20%;
				left: 5%;
				padding: 5px;
				margin: 10px;
				width: 15%;
				background-color: #ffecc4;
				border: 3px solid #7c0000;
				padding-top: 20px;
				padding-bottom: 20px;
			}
			
			a:link {
				color: #000000;
			}
			
			a.navbar:link {
				color: #7c0000;
				text-decoration: none;
				padding: 10px;
				margin: 5px;
				font-size: 22px;
			}
			
			a.navbar:visited {
				color: #7c0000;
				text-decoration: none;
				padding: 10px;
				margin: 5px;
				font-size: 22px;
			}
			
			a.navbar:hover {
				color: #7c0000;
				text-decoration: none;
				padding: 10px;
				margin: 5px;
				font-size: 22px;
				background-color: #fffaef;
			}
			
			a.sidenavbar:link {
				color: #7c0000;
				text-decoration: none;
				padding: 10px;
				margin: 5px;
				font-size: 20px;
			}
			
			a.sidenavbar:visited {
				color: #7c0000;
				text-decoration: none;
				padding: 10px;
				margin: 5px;
				font-size: 20px;
			}
			
			body {
				background-color: #fffaef;
				text-align: center;
				width: 700px;
				margin-left: auto;
				margin-right: auto;
				color:  black;
			}
			
			#sidenav {
				text-align: center;
			}
			
			p {
				text-align: left;
				color: #420000;
			}
			
			h1, h2 {
				text-align: center;
				color: #7c0000;
			}
		</style>
	</head>
	<body>
		<div id="nav">
			<a class="navbar" href="index.html">Home</a>
			<a class="navbar" href="index.html">Sweet</a>
			<a class="navbar" href="index.html">Savory</a>
			<a class="navbar" href="index.html">Other</a>
		</div>
		<br>
		<br>
		<div id="sidenav">
			<a class="sidenavbar" href="#home">Home</a>
			<br>
			<br>
			<a class="sidenavbar" href="#about">About</a>
			<br>
			<br>
			<a class="sidenavbar" href="index.html">Recipe Spotlight: ???</a>
			<br>
			<br>
			<a class="sidenavbar" href="index.html">Recipe Spotlight: ???</a>
		</div>
		<h1 id="home">Hello, and welcome to the Recipe Book!</h1>
		<h2 id="about">About this Website</h2>
		<p>Hello! Do you need a quick meal? Perhaps something low-cost? An easy-to-follow 
		recipe? Well look no further! The Recipe Book has many simple, yet delicious, 
		recipes for you to make.</p>
		
	</body>
</html>
