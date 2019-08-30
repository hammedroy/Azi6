# Azi6 contact page
<html lang="en">
<head>
  <link rel="icon" href="https://res.cloudinary.com/dhtwv1cwv/image/upload/v1567120562/azi6/trippleA_logo1_ebnu29.png" type="image/gif" sizes="16x16">
  <title>Azi6 | Contact Us</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>
</head>
<body>
<img class="img-responsive" img src="https://res.cloudinary.com/dhtwv1cwv/image/upload/v1567120562/azi6/trippleA_logo1_ebnu29.png" alt="TrippleA" style="height:30%;width:100%">
<div class="container">
<nav class="navbar navbar-inverse">
  <div class="container-fluid">
    <div class="navbar-header">
      <a class="navbar-brand" href="#">AZI6 INTERIORS</a>
    </div>
    <ul class="nav navbar-nav">
      <li><a href="file:///C:/Users/Hammed/Documents/TRIPPLEA/look_good_naija.html">Home</a></li>
      <li><a href="file:///C:/Users/Hammed/Documents/TRIPPLEA/Azi6_Beddings.html">Beddings</a></li>
      <li><a href="#">Clothings</a></li>
      <li><a href="#">Cosmetics</a></li>
	  <li class="active"><a href="file:///C:/Users/Hammed/Documents/TRIPPLEA/contact_Us.html">Contact Us</a></li>
    </ul>
  </div>
  
<h2>Tell us what you want</h2>
<div class="container">
	<div class="row">
		<div class="col-sm-8">
			<form class="form-horizontal" action="contact.php" method="post" role="form" id="contact">
				<div class="form-group">
				 <label class="control-label col-sm-2" for="email">Email Address:</label>
				 <div class="col-sm-6">
					<input type="email" class="form-control" id="email" placeholder="Enter email" name="email">
				</div>
				</div>				
				<div class="form-group">
				  <label class="control-label col-sm-2" for="Fstnm">First Name:</label>
				  <div class="col-sm-6">          
					<input type="Firstname" class="form-control" id="Fstnm" placeholder="First name" name="Fstnm">
				  </div>
				</div>
				<div class="form-group">
				  <label class="control-label col-sm-2" for="Lstnm">Last Name:</label>
				  <div class="col-sm-6">
					<input type="Last name" class="form-control" id="Lstnm" placeholder="Last name" name="Lstnm">
				  </div>
				</div>
				<div class="form-group">
				<label class="control-label col-sm-2" for="phn">Phone Number</label>
					<div class="col-sm-6">          
						<input type="phone number" class="form-control" id="phn" placeholder="Phone number" name="phn">
					</div>
				</div>
				<div class="form-group">
				<label class="control-label col-sm-2" for="qty">Message</label>
				    <div class="col-sm-6">
						<textarea class="form-control" rows="5" id="message"></textarea>
					</div>
				</div>
				<div class="form-group">
					<div class="col-sm-offset-2 col-sm-10">
						<button type="send" class="btn btn-primary btn-md">Send</button>
					</div>
				</div>
		  </form>
		</div>
		<div class="col-sm-4">
			<div id="myCarousel" class="carousel slide" data-ride="carousel">
				<!-- Indicators -->
				<ol class="carousel-indicators">
					  <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
					  <li data-target="#myCarousel" data-slide-to="1"></li>
					  <li data-target="#myCarousel" data-slide-to="2"></li>
				</ol>

					<!-- Wrapper for slides -->
					<div class="carousel-inner">
					  <div class="item active">
						<img src="IMG-20190618-WA0005.jpg" alt="Hermes" style="height:50%;width:100%">
					  </div>

					  <div class="item">
						<img src="IMG-20190618-WA0006.jpg" alt="versace" style="height:50%;width:100%">
					  </div>
					
					  <div class="item">
						<img src="IMG-20190618-WA0012.jpg" alt="night sky" style="height:50%;width:100%">
					  </div>
					</div>

					<!-- Left and right controls -->
					<a class="left carousel-control" href="#myCarousel" data-slide="prev">
					  <span class="glyphicon glyphicon-chevron-left"></span>
					  <span class="sr-only">Previous</span>
					</a>
					<a class="right carousel-control" href="#myCarousel" data-slide="next">
					  <span class="glyphicon glyphicon-chevron-right"></span>
					  <span class="sr-only">Next</span>
					</a>
			</div>
		</div>
	</div>
</div>
</body>
</html>
