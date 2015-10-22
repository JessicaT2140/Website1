# Website1
Centered
<!DOCTYPE html>
 <html>
    <head>
	 <meta charset="utf-8"/>
	 <title> Fit Healthy </title>
	 <style type="text/css">
	 body {
     background-image: url(#6F9ED0);
	 font-family: verdana, Arial, sans-serif;
	 font-size: small;
	 margin: 0;
	 padding: 0;
	 }
	
#container {
     background: #96999c;
	 text-align: center;
     width: 768px;
	 margin: auto;
	 border-right: 1px solid #000000;
	 border-left: 1px solid #000000;
	 border-top: 1px solid #000000;
	 border-bottom: 1px solid #000000;
	 padding: 0;
	 }
	 
ul {
	list-style-type: none;
     margin: 0;
     padding: 0;
	 text-decoration: none;
}
	 
 #content {
     height: 580px;
	 width: 400px;
	 background: #787a7d;
	 margin: 0;
	 padding: 10px 38px 10px 20px;
	 width: 508px;
	 float: left;
	 border-right: 2px solid #000000;
	 border-top: 2px solid #000000;
	 }
	 
 #navigation {
     height: 550px;
	 width: 150px;
     background: #666666;
	 margin: 0;
	 padding: 10px 10px 10px 10px;
	 float: right;
	 width: 180px;
	 height: 100%;
	 list-style: none;
	 border-top: 2px solid #000000;
	 }	 
	 
#navbar {
    list-style: none;
	height: 553px;
	}

#navbar li {
	padding-bottom: 2px;
	}	
	
#navbar li a {
	display: block;
	background: #000000;
	color: #ffffff;
	text-decoration: none;
	}
	
#navbar li a:hover {
	background: #000000;
	}
	 
 #footer {
     border-top: 2px solid #000000;
     height: 30px;
	 clear: both;
	 padding: 10px 20px;
	 margin: 0;
	 color: #000000;
	 font-size: 85%;
	 font-weight: bold;
	 background-color: #616161;
	 }
	
h1 {
    background: url(#F8EAEA) no-repeat top left; 
    }
	
h2 {
	border-bottom: 1px solid #000000;
	background-color: #AAFFA7;
	font-family: alike;
	font-style: normal;
	font-weight: 400;
	}
	
#bigpic {
	height: 300px;
	width: 500px;
	}
	 </style>
  <link rel="stylesheet" href="layout.css" title="style1" media="screen" />  
	</head>
	
	<body>
	
	  <div id="container">
	  
	  <img src="Images/header-home.png" width="600px" height="200px" align="center">
	
	  <div id="content">
	    <h2 style="text-align:center;font:bold 12px">Introduction</h2>
	     
		 <p id="textcolor" onclick="myFunction()">The mission of Fit Healthy is to educate people about how to change their unhealthy
		 lifestyle to lead a healthy one by eating clean, exercising regularly, and getting 
		 enough sleep. From people who do not know where to start to people who have hit a
		 plateau in their regiment, this organization can use a website to spread knowledge on 
		 how to get to the results that they want. </p>

         <script>
             function myFunction() {
             document.getElementById("textcolor").style.color = "white";
             }
         </script>
		 <!--This makes the paragraph change the text color from black to white onclick.-->
		 
		 <img src="Images/home-image.jpg" alt="Weight Lifting" height="200px" width="400px" id="normalpic" onmouseover=changePic("Images/home-image.jpg" id="bigpic")>
		
		<!--<script>
			function bigImg(x) {
			x.style.height = "300px";
			x.style.width = "500px";
			}

			function normalImg(x) {
			x.style.height = "200px";
			x.style.width = "400px";
			}
		</script>
		
		<img onmouseover="bigImg()" onmouseout="normalImg()" border="0" src="Images/home-image.jpg" alt="Weight Lifting" width="400" height="200">
		-->
		<!-- Why did this mouseover event not work on the image?-->


		
		<h2>Contact Us</h2>
		 <ul>
		  <li style="text-align:left;padding:0;margin:left;40px;">Phone: (555) 555-4321</li> 
		  <li style="text-align:left;padding:0;margin:left;40px;">E-mail: Jessicat2140@gmail.com</li>
		  <li style="text-align:left;padding:0;margin:left;40px;">Address: </li>
		 </ul>
		 
	  </div>
	  
	  <div id="navigation">
	  <ul id="navbar">
	    <li onclick=confirm("Continue?");><a href="index.html">Home</a></li>
		<li onclick=confirm("Continue?");><a href="burner.html">Burner</a></li>
		<li onclick=confirm("Continue?");><a href="toned.html">Toned</a></li>
		<li onclick=confirm("Continue?");><a href="build.html">Build</a></li>
		<li onclick=confirm("Continue?");><a href="aboutus.html">About Us</a></li>
	  </div>
	  <!-- Nav has an on mouseover and on click event-->
	  
	  <div id="footer">
	    <center>
		<p>©JessicaThompson</p>
	    </center>
	  </div>
	  
	  </div>
	  
	</body>
  </html>
