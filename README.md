# page
primer page
/* Write some CSS below */

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Le Wagon - Web </title>

  <link href="https://fonts.googleapis.com/css2?family=Lora:700|Overpass:400,700&ital@1&display=swap" rel="stylesheet">
 
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <!-- Banner section -->
  <div class="banner-wrap">
    <h1>Change your life, learn to code</h1>
    <p>Le Wagon brings technical skills to creative people</p>
    <a href="https://www.lewagon.com"> Apply now </a>  
  </div>
   
   <!-- Cards section --> 
  <div class="cards-wrap">
     <h2>Discover our campuses</h2>
    <!-- Cards container -->
    <div class="cards-container">

      <!-- Shanghai card -->
      <div class="card">
         <img src="https://source.unsplash.com/collection/1964125/200x200">
         <h3>Shanghai</h3>
         <p>Learn to code with us in Shanghai</p>
      </div>

      <!-- London card -->
      <div class="card">
         <img src="https://source.unsplash.com/collection/9469068/200x200">
         <h3>London</h3>
         <p>Learn to code with us in London</p>
      </div>

      <!-- Paris card -->
      <div class="card">
         <img src="https://source.unsplash.com/collection/2005064/200x200">
         <h3>Paris</h3>
         <p>Learn to code with us in Paris</p>
      </div>
    </div>
  </div>

  <!-- Footer section -->
  <footer>
    <p>Website made by DaniBus with the ❤️ for Le Wagon</p>    
  </footer>
      
    
    </div>

</body>
</html>

body {
	font-family: "LORA", sans-serif;
	margin: 0;
}
.banner-wrap{
	background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url("https://source.unsplash.com/collection/81223"); 
	background-size: cover;
	background-position: center;
	padding: 150px 0;
	text-align: center;
}
h1{
	color: white ;
	font-size: 45px;
	margin: 0;
	font-weight: bold;
}
p{
	color: rgba(255,255,255,.6);
	font-size: 22px;
}
a{
    background-color: #1A48E3;	
    color: white;
    padding: 14px 30px;
    border-radius:4px;
    text-decoration:underline;	
    transition: .3s;
    font-size:16px;
    font-weight:bold;
    border:none;
}
.cards-wrap{
	width: 860px;
	margin: 60px auto;
}
.cards-container{
	display: flex;
	flex-direction: row;
	align-items: center;
	justify-content: space-between;
}
.card{
	background: white;
	box-shadow: 0 0 10px rgba(0,0,0,0.2);
	border-radius: 4px;
	padding: 24px;
	margin: 8px;
	}

.card img{
	align-items: center;
	width: 200px;
	height: 200px;
}
.card p{
	color: #393939;
	font-size: 15px;
}	
footer{
	background: gray;
	color: white;
	padding: 30px 60px;
	bottom: 0;
	left: 0;
	right: 0;
}
footer p{
	color:white;
	margin: 0;
	font-size: 18px;
	text-align: center;
}






