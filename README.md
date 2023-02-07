<!DOCTYPE>
<!DOCTYPE html>
<html>

<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title> profile </title>

	<!---Bootstrp Icons--->
	<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.3/font/bootstrap-icons.css">


	<link rel="stylesheet" href="profile.css">
	<link rel="stylesheet" href="bootstrap.css">
	<link rel="stylesheet" href="boxicons.min.css">
	<link rel="stylesheet" href="owl.carousel.min.css">
	<link rel="stylesheet" href="owl.theme.default.min.css">
	<link rel="stylesheet" href="assets/vendor/aos/aos.css">
	<script src="bootstrap.js"></script>





	<style>
		.hero-image {
			background-image: url(sami4.jpeg);
			background-color: #cccccc;
			height: 1200px;
			background-position: center;
			background-repeat: no-repeat;
			background-size: cover;
			position: relative;

		}

		/*----------------------------------------------
		#Navbar 
		-----------------------------------------------*/

		.navbar {
			box-shadow: 0px 6px 30px rgba(0, 0, 0, 0.08)
		}

		.navbar-brand {
			padding-right: 50px;
			font-weight: 700;
			font-size: 26px;
			color: #092032;
		}

		.navbar-brand span {
			color: #ff4d29;
		}

		.navbar ul li {
			padding-right: 40px;
			color: rgb(142, 130, 151);
			font-size: 20px;
			font-weight: bold;
			font-family: 'Courier New', Courier, monospace;
		}


		li a.active {
			background-color: bisque;
			color: #ff4d29;
		}

		li a:hover:not(.active) {
			background-color: rgb(222, 238, 251);
			color: #ff4d29;
		}

		.display-2 {
			margin-top: 250px;
			margin-left: 150px;
			font-weight: 400;
			line-height: 2cm;
		}

		/*-------------------------------------------
		#About
		--------------------------------------------*/

		.info-box {
			text-align: center;
			display: flex;
		}

		.info-box img {
			width: unset;
			margin-right: 18px;

		}

		#image3 {
			height: 450px;
			max-width: 100%;
			border-radius: 4pc;
			margin-bottom: 10%;
			margin-top: 8%;
			padding-left: 300px;
		}

		#image3:hover {
			transform: scaleX(-1);
		}

		.about .content ul i {
			cursor: pointer;
			font-size: 25px;
			margin-right: 20px;
			margin-top: 20px;
			color: #1ccacd;
		}

		.about .content ul strong {
			margin-right: 10px;
		}

		/*-------------------------------
		#Resume
		---------------------------------*/
		.resume {
			margin-top: 40px;
			margin-bottom: 40px;
			color: #173b6c;
		}

		.resume .resume-title {
			font-size: 26px;
			font-weight: 700;
			margin-top: 20px;
			margin-bottom: 20px;
			color: black;
		}

		.resume .resume-items {
			padding: 0 0 20px 20px;
			margin-top: -2px;
			border-left: 2px solid #1ccacd;
			position: relative;
		}

		.resume .resume-items h4 {
			margin-bottom: 10px;
			font-size: 18px;
			font-weight: 600;
			text-transform: uppercase;
			font-family: "poppins", sans-serif;
			color: #050d18;


		}

		.resume .resume-items h5 {
			background-color: #ceebec;
			display: inline-block;
			margin-bottom: 10px;
			font-size: 16px;
			font-weight: 600px;
			padding: 7px 7px;
		}

		.resume .resume-items ul {
			padding-left: 20px;
		}

		.resume .resume-items ul li {
			padding-bottom: 10px;
		}

		.resume .resume-item:last-child {
			padding-bottom: 0;
		}

		/*-------------------------
		#Contact
		--------------------------*/
		.contact .section-title {
			padding-bottom: 80px;
			font-size: 32px;
			font-weight: bold;
			color: #173b6c;
			position: relative;
			
		}

		.contact .addres i {
			font-size: 20px;
			color: #149ddd;
			float: left;
			width: 44px;
			height: 44px;
			background: #dff3fc;
			display: flex;
			justify-content: center;
			align-items: center;
			border-radius: 50px;
			transition: all 0.3s ease-in-out;

		}

		.addres h4 {
			padding: 0 0 0 60px;
			font-size: 22px;
			font-weight: 600;
			margin-bottom: 5px;
			color: #050d18;
		}

		.addres p {
			padding: 0 0 10px 60px;
			font-size: 14px;
			margin-bottom: 20px;
			color: #173b6c;
		}
		.addres .location{
			margin-top: 40px;
		}
		.addres .phone{
			margin-bottom: 300px;
		}
	</style>







</head>

<body data-bs-spy="scroll" data-bs-target=".navbar">

	<div class="container-fluid">
		<div class="hero-image">

			<!---Navbar-->

			<nav class="navbar navbar-expand-lg navbar-light bg-white sticky-top" id="custom-nav">
				<div class="container">
					<a class="navbar-brand" href="#">Zadran<span>.</span></a>
					<ul class="navbar-nav ms-auto">
						<li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
						<li class="nav-item"><a class="nav-link " href="#about">About</a></li>
						<li class="nav-item"><a class="nav-link" href="#resume">WorkExperience</a></li>
						<li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
					</ul>
				</div>
				<a href="#" class="btn btn-info ms-lg-3">Contact Us</a>
			</nav>
			<!---Navbar End-->

			<!---Page Header-->

			<div class="row">
				<div class="col-6 ml-auto">
					<h1 class="display-2 text-uppercase text-black"> Samiullah <br> Zadran </h1>
					<p
						style=" margin-left: 150px; margin-top: 0px; font-size: 20px; font-family: Franklin Gothic Medium;">
						Software Developer in MCIT
					</p>
				</div>
			</div>
		</div>

		<!---About--->
		<section id="about">
			<div class="row mt-5 about">
				<div class="col-6" style="padding-left: 100px; float: right;">
					<img src="sami3 (1).jpeg" id="image3">
				</div>
				<div class="col-6 content">
					<h3
						style="color: #173b6c; line-height: 1; font-weight: 600; margin-top: 10%;font-size: 40px; font-family: 'Ubuntu', sans-serif;">
						<span class="mb-2" style="color:#1ccacd; display: block; font-size: 20px;">Some info</span>
						About Me
					</h3>
					<p style="font-style: italic;"> I Am a Front-End developer with using HTML, CSS and Bootstrap, As I
						am new in this field
						and this is my first website to develop for myself and it was the great experience for me to
						developing a website,
						and I am gratful to doing web development.
					</p>
					<div class="row" style="margin-top: 30px;">
						<div class="col-8">
							<ul>
								<i class="bi bi-envelope" id="bticon"></i> <strong>Website:</strong>
								<span>alisina.sadet@gmail.com</span><br>
								<i class="bi bi-telephone"></i> <strong>Phone:</strong> <span>+93764296855</span><br>
								<i class="bi bi-layers-fill"></i> <strong> Degree</strong><span>Bachelor of
									Technology</span><br>
								<i class="bi bi-briefcase-fill"></i> <strong> Job</strong> <span>Software
									developer</span><br>
								<i class="bi bi-house"></i> <strong> City</strong><Span> Kabul, Afghanistan</Span><br>
							</ul>
						</div>
					</div>
				</div>
			</div>
		</section>
		<!---End about section--->

		<!---Resume--->
		<section id="resume" class="resume">
			<div class="container" style="margin: right 100px;;">
				<div class="section-title">
					<h2> Resume </h2>
					<p> Front end Developere and also Standards developing expert with high level of experience in
						web/Software
						Development Here are a few technologies I’ve been working with recently: JavaScript, HTML, CSS,
						Python, Django.</p>
				</div>
				<div class="row">
					<div class="col-lg-6" data-aos="dade-up">
						<h1 class="resume-title"> Professional Experience</h1>
						<div class="resume-items">
							<h4> Front End Developer</h4>
							<h5> April 2022 - Present</h5>
							<p>
								<i>Ministry of Communication & Information Technology (MCIT), Afghanisan</i>
							</p>
							<ul>
								<li> Here I am responsible to develop front end for Data Warehouse System and also iam
									working as ICT
									Standards developer and had many researches in MCIT for imoroving my skills in
									Standards development.
								</li>
								<p> Skills: HTML, CSS, Java Script, Python, Django</p>
							</ul>
						</div>
						<div class="resume-items">
							<h4> IT Technical Support</h4>
							<h5> Jan 2022 - sep 2022</h5>
							<p>
								<i>Micro Asan Technology center (MSTC), Afghanistan</i>
							</p>
							<ul>
								<li>Here I worked as an IT Technical support and I did alot of tasks my main task was to
									arrange online meetings amd also supporting IT seniors for further Problems occur in
									Provincial branches and I was responsive for Email ansewring.
								</li>
								<p> Skills: HTML, CSS, Java Script, Python, Django</p>
							</ul>
						</div>
					</div>


					<div class="col-lg-6" data-aos="dade-up" data-aos-delay="100" style="flex: auto; width: 50%;">
						<h1 class="resume-title"> Professional Experience</h1>
						<div class="resume-items">
							<h4> IT Assistant</h4>
							<h5> Feb 2017 - Dec 2017</h5>
							<p>
								<i>Afghanistan Telecommunication Regularity Authority(ATRA)</i>
							</p>
							<ul>
								<li> Here I am responsible to develop front end for Data Warehouse System and also iam
									working as ICT
									Standards developer and had many researches in MCIT for imoroving my skills in
									Standards
									development.
								</li>
								<p> Skills: HTML, CSS, Java Script, Python, Django</p>
							</ul>
						</div>
						<div class="resume-items">
							<h4> IT Technical Support</h4>
							<h5> Jan 2022 - sep 2022</h5>
							<p>
								<i>Micro Asan Technology center (MSTC), Afghanistan</i>
							</p>
							<ul>
								<li> Here I am responsible to develop front end for Data Warehouse System and also iam
									working as ICT
									Standards developer and had many researches in MCIT for imoroving my skills in
									Standards
									development.
								</li>
								<p> Skills: HTML, CSS, Java Script, Python, Django</p>
							</ul>
						</div>
					</div>
				</div>


			</div>

		</section>
		<!--End of Resume section-->

		<!-------Contact Section------->
		<section id="contact" class="contact">
			<div class="container contact" style="margin-top: 80px;">
				<div class="section-title">
					<h2> Contact</h2>
				</div>
				<div class="row" data-aos="fade-in">
					<div class="col-lg-5 d-flex align-items-stretch" style="box-shadow: 0 0 24px 0 rgb(0 0 0 / 12%); padding-right: 20px; margin-bottom: 100px;">
						<div class="addres">
							<div class="location">
								<i class="bi bi-geo-alt" id="bticon"></i>
								<h4>Location</h4>
								<p>Kabul, Afghanistan</p>
							</div>

							<div class="Email">
								<i class="bi bi-envelope" id="bticon"></i>
								<h4> Email</h4>
								<p>Kabul, Afghanistan</p>
							</div>

							<div class="phone">
								<i class="bi bi-phone" id="bticon"></i>
								<h4>Phone</h4>
								<p>Kabul, Afghanistan</p>
							</div>
						</div>
					</div>
					<div class="col-lg-7 mt-5 mt-lg-0 d-flex align-items-stretch">
						<form action="forms/contact.php" method="post" role="form" class="php-email-form">
						  <div class="row">
							<div class="form-group col-md-6">
							  <label for="name">Your Name</label>
							  <input type="text" name="name" class="form-control" id="name" required>
							</div>
							<div class="form-group col-md-6">
							  <label for="name">Your Email</label>
							  <input type="email" class="form-control" name="email" id="email" required>
							</div>
						  </div>
						  <div class="form-group">
							<label for="name">Subject</label>
							<input type="text" class="form-control" name="subject" id="subject" required>
						  </div>
						  <div class="form-group">
							<label for="name">Message</label>
							<textarea class="form-control" name="message" rows="10" required></textarea>
						  </div>
						  <div class="my-3">
							<div class="loading">Loading</div>
							<div class="error-message"></div>
							<div class="sent-message">Your message has been sent. Thank you!</div>
						  </div>
						  <div class="text-center"><button type="submit">Send Message</button></div>
						</form>
					  </div>
			
				</div>
			</div>

		</section>

	</div>

	
</body>

</html>
