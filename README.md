<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href= 
    "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"
        rel="stylesheet"> 
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <style> 
		body { 
			color: white; 
		} 

		.footer { 
			 
		} 

		.footer-content h2 { 
			color: #fff; 
		} 

		.footer-content h5, 
		.footer-content p, 
		.footer-links a { 
			color: #fff; 
		} 

		.footer-links a:hover { 
			text-decoration: underline; 
		} 

		.footer hr { 
			background-color: #fff; 
		} 
	</style> 

</head>
<body>
    <nav class="navbar navbar-expand-lg bg-dark navbar-dark fixed-top" >
        <div class="container px-4">
          <a class="navbar-brand ms-4 ps-4 text-light" href="">
            <img src="netflix.gif" alt="" class="rounded-pill" style="width: 250px; height: 80px;">
            
          </a>
          <a class="text-title" href="#"></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#collapsibleNavbar" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse me-4 pe-4" id="collapsibleNavbar">
            <ul class="navbar-nav  ms-auto mb-1 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link" href="https://www.netflix.com/in/browse/genre/6057">scary movies</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="https://www.netflix.com/in/browse/genre/5505">thriller</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="https://www.netflix.com/in/browse/genre/6548">comedy</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="https://www.netflix.com/in/browse/genre/9584">action</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="https://www.netflix.com/in/browse/genre/3276033">sci-fi</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="https://www.netflix.com/in/browse/genre/3063">anime</a>
              </li>
              
              
              </ul>
              
            
            
          </div>
        </div>
      </nav>
      
      <section class="home">
        <div class="container pt-md-0 pt-5">
          <div class="row text-center text-md-start pt-md-0 pt-5 justify-content-center align-items-center" style="height: 850px;">
          <div class="col-md-5">
            <h1 class="display-1 text-capitalize text-light">
               Some trending movies and series.
            </h1>
            <p class="lead text-light">
              get premium subscription in just 149/-per month
            </p>
          </div>
          <div class="col-md-4">
            <div id="demo" class="carousel slide" data-bs-ride="carousel">
                <div class="carousel-indicators">
                    <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
                    <button type="button" data-bs-target="#demo" data-bs-slide-to="1" ></button>
                    <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
                    <button type="button" data-bs-target="#demo" data-bs-slide-to="3"></button>
                    <button type="button" data-bs-target="#demo" data-bs-slide-to="4"></button>
                    <button type="button" data-bs-target="#demo" data-bs-slide-to="5"></button>
                </div>
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="stranger-things-3840-x-2160-sbuyy2j8ldllkhsj.jpg" alt="" class="d-block " style="width: 100%; height: 400px;">
                    </div>
                    <div class="carousel-item ">
                        <img src="got.jpg" alt="" class="d-block"  style="width: 100%;height: 400px;">
                    </div>
                    <div class="carousel-item ">
                        <img src="money.jpg" alt="" class="d-block " style="width: 100%;height: 400px;">
                    </div>
                    <div class="carousel-item ">
                      <img src="haunting.jpg" alt="" class="d-block " style="width: 100%;height: 400px;">
                  </div>
                  <div class="carousel-item ">
                    <img src="breaking bad.jpeg" alt="" class="d-block " style="width: 100%;height: 400px;">
                </div>
                <div class="carousel-item ">
                  <img src="asur.jpg" alt="" class="d-block " style="width: 100%;height: 400px;">
              </div>
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
                    <span class="carousel-control-prev-icon"></span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
                    <span class="carousel-control-next-icon"></span>
                </button>
            </div>
          </div>
          </div>
        </div>
      </section>
      <section class="features my-5">
        <div class="container">
          <div class="row gx-4 px-5 my-3 text-center justify-content-center ">
            <div class="col-lg-6 border border-5 border-danger text-light bg-secondary p-3">
      <h4> phone</h4>
      <p>Unlimited ad-free movies, TV shows, and mobile games

        Watch on 1 phone or tablet at a time
        
        Download on 1 phone or tablet at a time</p>
      
            </div>
            <div class="col-lg-6 border border-5 text-light border-danger  bg-secondary  p-3">
              <h4>
                basic
              </h4>
              <p>
                Unlimited ad-free movies, TV shows, and mobile games

Watch on 1 supported device at a time

Watch in HD

Download on 1 supported device at a time
              </p>
      </div>
      
              
          </div>
        </div>
      </section>
    <div class="container-fluid text-center mt-4">
        <div class="row pt-5 d-flex justify-content-center p-3">
          <div class="col-sm-2 d-flex justify-content-center p-5" style="margin: top 5%">
            <div class="card text-center   " style="width: 300px; height:90% ;">
                <img src="shutterisland.jpg" alt="" height="50%" width="25%" class="card-img-top">

                <div class="card-body">
                    <div class="card-title">shutter island</div>
                    
                    <a href="#" class="btn btn-primary">watch now</a>

                </div>
                
            </div>
        </div>
            <div class="col-sm-2 d-flex justify-content-center p-5" style="margin: top 5%">
                <div class="card text-center   " style="width: 300px; height:90% ;">
                    <img src="godzilla.jpeg" alt="" height="50%" width="25%" class="card-img-top">

                    <div class="card-body">
                        <div class="card-title">godzilla x kong</div>
                        
                        <a href="#" class="btn btn-primary">watch now</a>

                    </div>
                    
                </div>
            </div>
            <div class="col-sm-2 d-flex justify-content-center p-5" style="margin: top 5%">
              <div class="card text-center   " style="width: 300px; height:90% ;">
                  <img src="transformers.jpg" alt="" height="50%" width="25%" class="card-img-top">

                  <div class="card-body">
                      <div class="card-title">tranformers</div>
                      
                      <a href="#" class="btn btn-primary">watch now</a>

                  </div>
                  
              </div>
           </div>
           <div class="col-sm-2 d-flex justify-content-center p-5" style="margin: top 5%">
            <div class="card text-center   " style="width: 300px; height:90% ;">
                <img src="conjuring.jpeg" alt="" height="50%" width="25%" class="card-img-top">

                <div class="card-body">
                    <div class="card-title">conjuring</div>
                    
                    <a href="#" class="btn btn-primary">watch now</a>

                </div>
                
            </div>
           </div>
           <div class="col-sm-2 d-flex justify-content-center p-5" style="margin: top 5%">
            <div class="card text-center   " style="width: 300px; height:90% ;">
              <img src="titanic.jpg" alt="" height="50%" width="25%" class="card-img-top">

              <div class="card-body">
                  <div class="card-title">titanic</div>
                  
                  <a href="#" class="btn btn-primary">watch now</a>

              </div>
              
          </div>
           </div>
          <div class="col-sm-2 d-flex justify-content-center p-5" style="margin: top 5%">
        <div class="card text-center   " style="width: 300px; height:90% ;">
            <img src="inception.jpg" alt="" height="50%" width="25%" class="card-img-top">

            <div class="card-body">
                <div class="card-title">inception</div>
                
                <a href="#" class="btn btn-primary">watch now</a>

            </div>
            
        </div>
        
    </div>
        </div>
        <div class="row pt-5 d-flex justify-content-center p-3">
          <div class="col-sm-2 d-flex justify-content-center p-5" style="margin: top 5%">
            <div class="card text-center   " style="width: 300px; height:90% ;">
                <img src="triangle.jpeg" alt="" height="50%" width="25%" class="card-img-top">

                <div class="card-body">
                    <div class="card-title">triangle</div>
                    
                    <a href="#" class="btn btn-primary">watch now</a>

                </div>
                
            </div>
        </div>
            <div class="col-sm-2 d-flex justify-content-center p-5" style="margin: top 5%">
                <div class="card text-center   " style="width: 300px; height:90% ;">
                    <img src="intersteller.jpg" alt="" height="50%" width="25%" class="card-img-top">

                    <div class="card-body">
                        <div class="card-title">intersteller </div>
                        
                        <a href="#" class="btn btn-primary">watch now</a>

                    </div>
                    
                </div>
            </div>
            <div class="col-sm-2 d-flex justify-content-center p-5" style="margin: top 5%">
              <div class="card text-center   " style="width: 300px; height:90% ;">
                  <img src="Memento.jpg" alt="" height="50%" width="25%" class="card-img-top">

                  <div class="card-body">
                      <div class="card-title">momento movie</div>
                      
                      <a href="#" class="btn btn-primary">watch now</a>

                  </div>
                  
              </div>
           </div>
           <div class="col-sm-2 d-flex justify-content-center p-5" style="margin: top 5%">
            <div class="card text-center   " style="width: 300px; height:90% ;">
                <img src="martian.jpg" alt="" height="50%" width="25%" class="card-img-top">

                <div class="card-body">
                    <div class="card-title">martian movie</div>
                    
                    <a href="#" class="btn btn-primary">watch now</a>

                </div>
                
            </div>
           </div>
           <div class="col-sm-2 d-flex justify-content-center p-5" style="margin: top 5%">
            <div class="card text-center   " style="width: 300px; height:90% ;">
              <img src="joker.jpeg" alt="" height="50%" width="25%" class="card-img-top">

              <div class="card-body">
                  <div class="card-title">joker movie</div>
                  
                  <a href="#" class="btn btn-primary">watch now</a>

              </div>
              
          </div>
           </div>
          <div class="col-sm-2 d-flex justify-content-center p-5" style="margin: top 5%">
        <div class="card text-center   " style="width: 300px; height:90% ;">
            <img src="fightclub.jpg" alt="" height="50%" width="25%" class="card-img-top">

            <div class="card-body">
                <div class="card-title">fight club</div>
                
                <a href="#" class="btn btn-primary">watch now</a>

            </div>
            
        </div>
    </div>
    <footer class="footer p-5"> 
      <div class="container"> 
        <div class="row"> 
          <div class="col-md-3"> 
            <h2 class="text-danger">NETFLIX</h2> 
          </div> 
          <div class="col-md-3"> 
            <h5>About Us</h5> 
            <p> 
              Netflix is a subscription-based streaming service that allows our members to watch TV shows and movies on an internet-connected device. 
            </p> 
          </div> 
          <div class="col-md-3 justify-content-center d-flex"> 
            <h5>Contact Us</h5> 
            <ul class="list-unstyled"> 
              <li>Email: info@example.com</li> 
              <li>Phone: +1233567890</li> 
              <li>Address: 123 Street, City, Country</li> 
            </ul> 
          </div> 
          <div class="col-md-3"> 
            <h5>Follow Us</h5> 
            <ul class="list-inline footer-links"> 
                <li class="list-inline-item"> 
                  <a href="#"> 
                        <i class="fab fa-facebook"></i> 
                  </a> 
                  </li> 
                <li class="list-inline-item"> 
                  <a href="#"> 
                        <i class="fab fa-twitter"></i> 
                  </a> 
                </li> 
                <li class="list-inline-item"> 
                  <a href="#"> 
                        <i class="fab fa-instagram"></i> 
                  </a> 
                </li> 
                <li class="list-inline-item"> 
                  <a href="#"> 
                        <i class="fab fa-linkedin"></i> 
                  </a> 
                </li> 
            </ul> 
        </div> 
          
        </div>
         
        <hr> 
        <div class="row"> 
          <div class="col-md-6 justify-content-center d-flex"> 
            <p>© 2024 Your Website. All rights reserved.</p> 
          </div> 
           
        </div> 
      </div> 
    </footer> 


</body>
</html>
