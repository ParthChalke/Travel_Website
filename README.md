# Travel_Website
I have developed this website using Html,CSS,JavaScript.
<!doctype html>
<html lang="en">
  <head>
 
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" 
    integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">

    <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js"
    integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js" 
integrity="sha384-Fy6S3B9q64WdZWQUiU+q4/2Lc9npb8tCaSX9FK7E8HnRr0Jz8D6OP9dO5Vg3Q9ct" crossorigin="anonymous"></script>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" 
integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" 
crossorigin="anonymous" referrerpolicy="no-referrer" />

    <title>travel website</title>

    <style>
        *{
margin: 0;
padding: 0;
box-sizing: border-box;
text-decoration: none;
list-style: none;
scroll-behavior: smooth;
}

.navbar{
background-color: #f9f9f9;
}

#logo{
font-size: 36px;
font-weight: 700;
color: black;
text-shadow: 0px 1px 1px black;
margin-bottom: 5px;
}

#logo span{
color: #ffa500;
}
.navbar-toggler span{
color: #ffa500;
}
.navbar-nav{
    margin-left: 20px;
}
.nav-item .nav-link{
font-size: 16px;
font-weight: 550;
color: black;
letter-spacing: 1px;
border-radius: 3px;
transition: 0.5s ease;
}
.nav-item .nav-link:hover{
background-color: #ffa500;
color: white;
}
.navbar form button{
    background: orange;
    color: white;
    border: none;
}

.home{
    width: 100%;
    height: 100vh;
    background-image:url(mount.jpeg);
    background-repeat: no-repeat;
    background-size: cover;
}
.home .content{
text-align: center;
padding-top: 200px;
}
.home .content h5{
color: white;
font-size: 38px;
font-weight: 500;
text-shadow: 0px 1px 1px black;
}
.home .content h1{
    color: white;
    font-size: 70px;
    font-weight: 550;
    text-shadow: 0px 1px 1px black;
    margin-top: 5px;
}
.changecontent::after{
    content: " ";
    color: #ffa500;
    text-shadow:0px 1px 1px black ;
    animation: changetext 10s infinite linear;
}
    @keyframes changetext {
        0%{content:  "India";}
        10%{content:  "Spain";}
        20%{content:  "United States";}
        30%{content:  "China";}
        40%{content:  "France";}
        50%{content:  "Italy";}
        60%{content:  "Germany";}
        70%{content:  "Turkey";}
        80%{content:  "Mexico";}
        90%{content:  "United Kingdom";}
    }

.home .content p{
color: white;
font-size: 15px;
font-weight: 600;
text-shadow: 0px 1px 1px black;
    margin-bottom: 30px;
    margin-top: 5px;
}
.home .content a{
padding: 10px;
background: white;
color: black;
letter-spacing: 2px;
font-weight: 550;
border-radius: 5px;
transition: 0.5s;
text-decoration: none;
}
.home .content a:hover{
background: #ffa500;
color: white;
}

.book{
    background: #f9f9f9;
    padding: 50px;
}
.main-text h1{
    text-align: center;
    text-shadow: 0px 1px 1px black;
    font-weight: 600;
}
.main-text h1 span{
    color: #ffa500;

}
.book .card{
    border-radius: 50px;
    box-shadow: 0px 5px 5px -6px black;
}
.book .row{
    margin-top: 20px;
}
.book form input{
padding: 10px;
color: black;
border: none;
outline: none;
font-size: 15px;
border-radius: 10px;
box-shadow: 0px 5px 5px -6px black;
}
.book form textarea{
  border: none;
  border-radius: 10px;
  resize: none;
  box-shadow: 0px 5px 5px -6px black;
  height: 200px;
}
.book .submit{
  width: 160px;
  font-size: 16px;
  font-weight: 550;
  background: #ffa500;
  color: white;
  margin: top 10px; 
  transition: 0.5s;
}
.book .submit:hover{
  width: 170px;
}

@media (max-width:765px;) {
  .book{
    padding: 0%;
  }
  .main-text h1{
    margin-top: 20px;
  }
}

.main-text{
  text-align: center;
  margin-top: 30px;
  font-weight: 600;
  text-shadow: 0px 1px 1px black;
}
.main-text h1 span{
  color: #ffa500;
}
.packages .card{
  border-radius: 5px;
  border: none;
  box-shadow: rgba(0,0,0,0.1) 0px 4px 12px;
}
.packages .card img{
  border-radius: 5px;
}
.packages .card .card-body{
  background: transparent;
}
.packages .card .card-body h3{
  font-size: 25px;
  font-weight: 600;
}
.packages .card .card-body p{
  font-size: 15px;
}
.packages .card .card-body h6 {
 font-size: 20px;
}
.packages .card .card-body a{
padding: 10px;
text-decoration: none;
background: #ffa500;
color: white;
border-radius: 5px;
}

.services{
  background: #f9f9f9;
  margin-top: 50px;
}
.services .card{
  box-shadow: 0px 5px 5px -6px black;
  border: none;
  cursor: pointer;
}
.services .card{
  border-radius: 5px;
  border: none;
  box-shadow: rgba(0,0,0,0.1) 0px 4px 12px;
}
.services .card img{
  border-radius: 5px;
}
.services .card .card-body{
  background: transparent;
}
.services .card .card-body h3{
  font-size: 25px;
  font-weight: 600;
}
.services .card .card-body p{
  font-size: 15px;
}
.services .card .card-body h6 {
 font-size: 20px;
}
.services .card .card-body a{
padding: 10px;
text-decoration: none;
background: #ffa500;
color: white;
border-radius: 5px;
}

.about{
  padding: 50px;
  margin-top: 50px;
  background: #f9f9f9;
}
.about .card{
 border-radius: 10px;
}
.about .card img{
  border-radius: 10px;
}
.about h2{
  font-weight: 600;
  letter-spacing: 1px;
}
.about p{
  font-weight: 500;
}
#about-btn{
  width: 150px;
  height: 38px;
  border: none;
  border-radius: 5px;
  background: #ffa500;
  color: white;
  letter-spacing: 2px;
  font-weight: 550;
  transition: 0.5s ease;
  cursor: pointer;
}
#about-btn:hover{
  width: 170px;
}
        </style>
  </head>
  <body>

 <!--navbar starts-->
 <nav class="navbar navbar-expand-lg  id="navbar">
    <a class="navbar-brand" href="index.html" id="logo"><span>T</span>ravel</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
  
    <div class="collapse navbar-collapse" id="mynavbar">

      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="#home">Home <span class="sr-only">(current)</span></a>
        </li>

        <li class="nav-item">
          <a class="nav-link" href="#book">Book</a>
        </li>

        <li class="nav-item">
            <a class="nav-link" href="#packages">Packages</a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#services">Services</a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#about">About</a>
          </li>

       
      <form class="form-inline my-2 my-lg-0" style="margin-left: 400px;">
        <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-sucess my-2 my-sm-0" type="submit">Search</button>
      </form>
    </div>
  </nav>
 <!---navbar ends-->

 <!--home section starts-->
<div class="home">
<div class="content">
<h5>Welcome to the World</h5><br>
<h1>Visit <span class="changecontent"></span></h1><br>
<p>The dream countries across the world</p>
<a href="#book">For Booking</a>
</div>
</div>
 <!--home section ends-->

 <!---section book starts-->
<section class="book" id="book">
<div class="container">

<div class="main-text">
<h1><span>B</span>ook<h1>
   

    <div class="row">

        <div class="col-md-6 py-3 py-md-0">
            <div class="card">
                <img src="trip.jpeg">
            </div>
        </div>

            <div class="col-md-6 py-3 py-md-0">
                <form action="#">
                      <input type="text" class="form-control" placeholder="Where to" required><br>
                      <input type="text" class="form-control" placeholder="How many" required><br>
                      <input type="date" class="form-control" placeholder="Arrivals" required><br>
                      <input type="date" class="form-control" placeholder="Leaving" required><br>
                      <textarea class="form-control" rows="5" name="text" placeholder="Enter you name & details"></textarea>
                      <input type="submit" value="Book Now" class="submit" required>
                </form>
            </div>
          
</div>
</div>
</section>

  <!---section book ends-->
 


  <!---section packages starts-->
<section class="packages" id="packages">
                    <div class="container">


          <div class="main-text">
<h1><span>P</span>ackages</h1>
                </div>

    <div class="row" style="margin-top: 30px;">



  <div class="col-md-4 py-3 py-md-0">
    <div class="card">
<img src="uk.jpeg">
<div class="card-body">
<h3>United Kingdom</h3>
<p>The U.K. is known all over the world for its sports and literature. 
  Soccer, rugby, cricket, boxing, and golf were all invented in the United Kingdom</p>

<h3><strike>*****</strike></h3>
<h6><strike>Price: <strong>50,000rs</strong>
</strike></h6>
<a href="#book">Book Now</a>

</div>
</div>
</div>




<div class="col-md-4 py-3 py-md-0">
  <div class="card">
<img src="mahal.jpeg">
<div class="card-body">
<h3>India</h3>
<p>India is amongst the top 10 countries in the world in terms of the number of World Heritage Sites. 
  There are 38 UNESCO World Heritage Sites in India.

<h3><strike>*****</strike></h3>
<h6><strike>Price: <strong>70,000rs</strong>
</strike></h6>
<a href="#book">Book Now</a>

</div>
</div>
</div>



<div class="col-md-4 py-3 py-md-0">
  <div class="card">
<img src="italy.jpeg">
<div class="card-body">
<h3>Italy</h3>
<p>Italy is a country famous not only for its glorious landscapes, rich history and vibrant culture, 
  but also for the Italian divine food that is a perfect fit for everyone.
  </p>

<h3><strike>*****</strike></h3>
<h6><strike>Price: <strong>50,000rs</strong>
</strike></h6>
<a href="#book">Book Now</a>

</div>
</div>
</div>
</div>  






<div class="row" style="margin-top: 30px;">

  <div class="col-md-4 py-3 py-md-0">
    <div class="card">
<img src="france.jpeg">
<div class="card-body">
<h3>France</h3>
<p>France is the symbol of romance and love worldwide. 
    The Eiffel tower, the iconic symbol of love, is the heart of Paris.France France is the symbol of worldwide. </p>

<h3><strike>*****</strike></h3>
<h6><strike>Price: <strong>50,000rs</strong>
</strike></h6>
<a href="#book">Book Now</a>

</div>
</div>
</div>


<div class="col-md-4 py-3 py-md-0">
  <div class="card">
<img src="mexico.jpeg">
<div class="card-body">
<h3>Mexico</h3>
<p> vibrant culture, beautiful beaches, and rich ancient history. Mexico is 
  also known for its delicious Mexican dishes and food, with some of its most popular expeppers.</p>

<h3><strike>*****</strike></h3>
<h6><strike>Price: <strong>60,000rs</strong>
</strike></h6>
<a href="#book">Book Now</a>

</div>
</div>
</div>


<div class="col-md-4 py-3 py-md-0">
  <div class="card">
<img src="germany.jpeg">
<div class="card-body">
<h3>Germany</h3>
<p>Germany is a country famous not only for its glorious landscapes, rich history and vibrant culture, 
  but also for the Italian divine food that is a perfect fit for everyone.
  </p>

<h3><strike>*****</strike></h3>
<h6><strike>Price: <strong>70,000rs</strong>
</strike></h6>
<a href="#book">Book Now</a>

</div>
</div>
</div>
</div> 

</div>
</section>

  <!---section packages ends-->
 

  <!---section services starts-->

<section class="services" id="services">
  <div class="container">

<div class="main-text">
<h1><span>S</span>ervices</h1>
</div>


<div class="row" style="margin-top: 30px;">

  <div class="col-md-4 py-3 py-md-0">
    <div class="card">
      
<div class="card-body">
 <center> <i class="fa-solid fa-hotel fa-beat fa-2xl" style="color: #ffd43b;"></i></center>
<h3 style="margin-top: 10px;">Affordable Hotels</h3>
<p>provides flawless guest services in a state-of-the-art facility. 
  As a five-star property, such as premium dining options. </p>
</div>
</div>
</div>


<div class="col-md-4 py-3 py-md-0">
  <div class="card">

<div class="card-body">
 <center> <i class="fa-solid fa-utensils fa-beat fa-2xl" style="color: #ffd43b;"></i></center>
<h3 style="margin-top: 10px;">Food & Drinks</h3>
<p>Remove the food cover using your right hand to place the food in front of guest and serve from the
   right hand side of the guest.</p>
</div>
</div>
</div>


<div class="col-md-4 py-3 py-md-0">
  <div class="card">

<div class="card-body">
  <center><i class="fa-solid fa-couch fa-beat fa-2xl" style="color: #ffd43b;"></i></center>
<h3 style="margin-top: 10px;">Relaxing Area</h3>
<p>offer not just lavish accommodation but a large number of different amenities gyms, spas, gourmet restaurants, and more. 
  </p>
</div>
</div>
</div>
</div>



<div class="row" style="margin-top: 30px;">

  <div class="col-md-4 py-3 py-md-0">
    <div class="card">

<div class="card-body">
  <center><i class="fa-solid fa-plane fa-beat fa-2xl" style="color: #ffd43b;"></i> </center>
<h3 style="margin-top: 10px;">Fastest Travel</h3>
<p>provides flawless guest services in a state-of-the-art facility. 
  As a five-star property, such as premium dining options. </p>
</div>
</div>
</div>


<div class="col-md-4 py-3 py-md-0">
  <div class="card">

<div class="card-body">
  <center><i class="fa-solid fa-shield-halved fa-beat fa-2xl" style="color: #ffd43b;"></i></center>
<h3 style="margin-top: 10px;">Saftey Guide</h3>
<p>Remove the food cover using your right hand to place the food in front of guest and serve from the
   right hand side of the guest.</p>
</div>
</div>
</div>


<div class="col-md-4 py-3 py-md-0">
  <div class="card">

<div class="card-body">
  <center><i class="fa-solid fa-person-swimming fa-beat fa-2xl" style="color: #ffd43b;"></i></center>
<h3 style="margin-top: 10px;">Adventures</h3>
<p>offer not just lavish accommodation but a large number of different amenities gyms, spas, gourmet restaurants, and more. 
  </p>
</div>
</div>
</div>
</div>


</div>
</section>

  <!---section services ends-->
 
<!----section about starts--->

<section class="about" id="about">
  <div class="container">

<div class="main-text">
  <h1>About <span>Us</span></h1>
</div>

<div class="row" style="margin-top: 50px;">
<div class="col-md-6 py-3 py-md-0">
  <div class="card">
    <img src="a1.jpeg">
  </div>
</div>

<div class="col-md-6 py-3 py-md-0">
  <h2>How Travel Agency Works </h2>
  <p>A travel agency is a private retailer or public service that provides travel and tourism-related services to the general
     public on behalf of accommodation or travel suppliers to offer different kinds of travelling packages for
      each destinationA travel agency is a private retailer or public service that provides travel and tourism-related  to the general 
     public on behalf of accommodation or travel suppliers to offer different kinds of travelling packages for each destination.</p>
     <button id="about-btn">Read More</button>
</div>


</div>

  </div>
</section>

<!----section about ends--->


<!---footer start-->

<footer id ="footer">
  <div class="card text-center bg-light" >
    <div class="card-header">
      <a class="navbar-brand" href="index.html" id="logo"><span>T</span>ravel.co.in</a>
    </div>
    <div class="card-body">
      <h5 class="card-title">
        <i class="fa-brands fa-facebook" style="color: #050505;"></i>
        <i class="fa-brands fa-instagram" style="color: #050505;"></i>
        <i class="fa-brands fa-twitter" style="color: #050505;"></i>
        <i class="fa-solid fa-envelope" style="color: #050505;"></i>
        <i class="fa-brands fa-youtube" style="color: #050505;"></i>
      </h5>
      <p class="card-text">We assure you the best you want.</p>
      <a href="#about" class="btn btn-primary">Know more</a>
    </div>
    <div class="card-footer text-muted">
     Thankyou for visiting us....!
    </div>
  </div>


</footer> 

<!---footer ends-->




  </body>
</html>
