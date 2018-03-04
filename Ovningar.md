# ÖVNINGAR: 

1. Skapa en sida som är så lik exemplet här:

![IMG](Bootstrap-presentation/IMG/o1.jpg)

# Tips:

	Använda Bootstrap "https://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_gs_container-fluid&stacked=h".

# Lösningsförslag:
	
	´´´html
	<div class="container-fluid">
	  <h1>My First Bootstrap Page</h1>
	  <ul>
	  	<li>???</li>
		<li>???</li>
		<li>???</li>
	  </ul>
	  <h1>???????</h1>
	  <p>This is some text.</p>
	  <p>This is some text.</p>
	</div>
	´´´
	
	
2. Skapa en sida som är så lik exemplet här:

![IMG](Bootstrap-presentation/IMG/o2.png)

# Tips:

	Använda Bootstrap grid classes "https://getbootstrap.com/docs/3.3/css/#grid"

# Lösningsförslag:
	
	´´´html
	
	<div class="row">
	  <div class="col-md-3">.col-md-3</div>
	  <div class="col-md-3">.col-md-3</div>
	  <div class="col-md-3">.col-md-3</div>
	  <div class="col-md-3">.col-md-3</div>
	</div>
	
	<div class="row">
	  <div class="col-md-4">.col-md-4</div>
	  <div class="col-md-4">.col-md-4</div>
	  <div class="col-md-4">.col-md-4</div>
	</div>
	
	<div class="row">
	  <div class="col-md-6">.col-md-6</div>
	  <div class="col-md-6">.col-md-6</div>
	</div>
	
	<div class="row">
	  <div class="col-md-2">.col-md-2</div>
	  <div class="col-md-2">.col-md-2</div>
	  <div class="col-md-2">.col-md-2</div>
	  <div class="col-md-2">.col-md-2</div>
	  <div class="col-md-2">.col-md-2</div>
	  <div class="col-md-2">.col-md-2</div>
	</div>
	
	<div class="row">
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	  <div class="col-md-1">.col-md-1</div>
	</div>
	
	´´´


3. Skapa en sida som är så lik exempel här:

![IMG](Bootstrap-presentation/IMG/o3.jpg)

# Tips:

	Använda Bootstrap content CSS classes för att lägga in table och image thumbnails till sidan:
	 * http://v4-alpha.getbootstrap.com/content/reboot/.
	 * http://v4-alpha.getbootstrap.com/content/tables/.
	 * http://v4-alpha.getbootstrap.com/content/images/.
	 * https://www.w3schools.com/bootstrap/bootstrap_images.asp.


# Lösningsförslag:

	´´´html
	<div class="container-fluid">
	  <h1>My First Bootstrap Page</h1>
	  <p>??????????????</p>
	  
	  <!-- Table -->
	  <h2>???????</h2>
	  <table class="table">
	  <thead>
		<tr>
		  <th>#</th>
		  <th>First Name</th>
		  <th>Last Name</th>
		  <th>Username</th>
		</tr>
	  </thead>
	  <tbody>
	  	<tr>
		  <th scope="row">1</th>
		  <td>???</td>
		  <td>???</td>
		  <td>???</td>
		</tr>
		<tr>
		  <th scope="row">2</th>
		  <td>???</td>
		  <td>???</td>
		  <td>???</td>
		</tr>
		<tr>
	 </tbody>
	 </table>
	 
	 <!-- Image thumbnails --> 
	 <div class="row">
	  <div class="col-md-4">
		<div class="thumbnail">
		  <a href="???.jpg">
			<img src="???.jpg" alt="Lights" style="width:100%">
		  </a>
		</div>
	  </div>
	  <div class="col-md-4">
		<div class="thumbnail">
		  <a href="???.jpg">
			<img src="???.jpg" alt="Nature" style="width:100%">
		  </a>
		</div>
	  </div>
	  <div class="col-md-4">
		<div class="thumbnail">
		  <a href="???.jpg">
			<img src="???.jpg" alt="Fjords" style="width:100%">
		  </a>
		</div>
	  </div>
	</div>
	</div>
	
	´´´


4.  Skapa en navbar som är så lik exempel här:

![IMG](Bootstrap-presentation/IMG/o4.jpg)
	
# Tips:

	Använda BS Navbar “https://www.w3schools.com/bootstrap/bootstrap_navbar.asp” 

# Lösningsförslag:

	´´´html
	<nav class="navbar navbar-inverse">
	  <div class="container-fluid">
		<div class="navbar-header">
		  <a class="navbar-brand" href="#">WebSiteName</a>
		</div>
		<ul class="nav navbar-nav">
		  <li class="active"><a href="#">Home</a></li>
		  <li><a href="#">Page 1</a></li>
		  <li><a href="#">Page 2</a></li>
		</ul>
		<form class="navbar-form navbar-left" action="/action_page.php">
		  <div class="form-group">
			<input type="text" class="form-control" placeholder="Search">
		  </div>
		  <button type="submit" class="btn btn-default">Submit</button>
		</form>
	  </div>
	 </nav>
	
	´´´
	

5. Skapa ett forum som är så lik exempel här:

![IMG](Bootstrap-presentation/IMG/o5.jpg)

# Tips:

	Använda BS Forms “https://www.w3schools.com/bootstrap/bootstrap_forms.asp” .

# Lösningsförslag:

	´´´html
	
		<div class="container-fluid">
		  <h1>My First Bootstrap Page</h1>
		  <p>??????????????</p>
		  
		  <!-- Form -->
		  <form class="form-inline" action="/action_page.php">
			  <div class="form-group">
				<label for="email">Name:</label>
				<input type="email" class="form-control" id="email">
			  </div>
			  <div class="form-group">
				<label for="pwd">Email:</label>
				<input type="password" class="form-control" id="pwd">
			  </div>
			  <div class="form-group">
				<label for="pwd">Phone:</label>
				<input type="password" class="form-control" id="pwd">
			  </div>
			  <div class="form-group">
			  <label for="comment">Message:</label>
			  <textarea class="form-control" rows="5" id="Message"></textarea>
			  </div>
			  <button type="submit" class="btn btn-default">Send form</button>
		  </form>
		  
		</div>
	
	´´´
	
	
6. Skapa en Carousel.

# Tips:

	Använda BS Carousel “https://www.w3schools.com/bootstrap/bootstrap_carousel.asp”.

# Lösningsförslag:

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
		  <img src="la.jpg" alt="Los Angeles">
		</div>

		<div class="item">
		  <img src="chicago.jpg" alt="Chicago">
		</div>

		<div class="item">
		  <img src="ny.jpg" alt="New York">
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


7. Skapa en Scrollspy. 

# Tips:
	“https://www.w3schools.com/bootstrap/bootstrap_scrollspy.asp” .
	
# Lösningsförslag:

	<!-- The scrollable area -->
	<body data-spy="scroll" data-target=".navbar" data-offset="50">

	<!-- The navbar - The <a> elements are used to jump to a section in the scrollable area -->
	<nav class="navbar navbar-inverse navbar-fixed-top">
	...
	  <ul class="nav navbar-nav">
		<li><a href="#section1">Section 1</a></li>
		...
	</nav>

	<!-- Section 1 -->
	<div id="section1">
	  <h1>Section 1</h1>
	  <p>Try to scroll this page and look at the navigation bar while scrolling!</p>
	</div>
	...

	</body>


8.  Skapa en Tooltip.
	
# Tips:

	Använda BS Tooltip “https://www.w3schools.com/bootstrap/bootstrap_tooltip.asp” .
	
# Lösningsförslag:

	´´´ html
		<div class="container">
		  <h3>Tooltip Example</h3>
		  <p>The data-placement attribute specifies the tooltip position.</p>
		  <a href="#" data-toggle="tooltip" title="Hooray!">Hover over me</a>
		</div>

		<script>
		$(document).ready(function(){
			$('[data-toggle="tooltip"]').tooltip();   
		});
		</script>
	´´´
	
9. Skapa en Popover.
	
# Tips:

	Använda BS Popover https://www.w3schools.com/bootstrap/bootstrap_popover.asp.
	
# Lösningsförslag:

	´´´ html
	<div class="container">
	  <h3>Popover Example</h3>
	  <a href="#" data-toggle="popover" title="Popover Header" data-content="Some content inside the popover">Toggle popover</a>

	<script>
	$(document).ready(function(){
		$('[data-toggle="popover"]').popover();   
	});
	</script>
	´´´
	

10. Skapa Media Objects som är så lik exempel här:

![IMG](Bootstrap-presentation/IMG/o10.jpg)
	
# Tips:

	Använda BS Media Objects https://www.w3schools.com/bootstrap/bootstrap_media_objects.asp.
	
# Lösningsförslag:
	
	<!-- Left-aligned -->
	<div class="media">
	  <div class="media-left">
		<img src="img_avatar1.png" class="media-object" style="width:60px">
	  </div>
	  <div class="media-body">
	    <h1>DDDD</h1>
		<h4 class="media-heading">John Doe</h4>
		<p>Lorem ipsum...</p>
	  </div>
	</div>

	<!-- Right-aligned -->
	<div class="media">
	  <div class="media-body">
	  	<h1>DDDD</h1>
		<h4 class="media-heading">John Doe</h4>
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
	  </div>
	  <div class="media-right">
		<img src="img_avatar1.png" class="media-object" style="width:60px">
	  </div>
	</div>

--------

#### Under olika exempel finns färdig kod som du enkelt kopierar och klistrar in i din HTML-fil. Det du nu måste göra är att ändra vad som skall stå istället för det som bootstrap har skrivit in.

#### Här gäller det att ha tålamod och våga att testa sig fram! Lycka till!