<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Travelmate - Discover amazing trips, reviews, pricing, hotels, and more.">
    <meta name="keywords" content="travel, trips, reviews, pricing, hotels, restaurants, flights">
    <title>Travelmate</title>
    <link rel="stylesheet" href="./styles.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<body>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Travelmate</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavDropdown">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Discover</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Trips</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Review</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  More
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Pricing</a></li>
                  <li><a class="dropdown-item" href="#">Hotels</a></li>
                  <li><a class="dropdown-item" href="#">Restaurants</a></li>
                  <li><a class="dropdown-item" href="#">Flights</a></li>
                </ul>
              </li>
            </ul>
          </div>
        </div>
      </nav>
      <hr>
      <div id="carouselExample" class="carousel slide">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="https://images.squarespace-cdn.com/content/v1/6776fb052b2d52105bdde525/bc40edfc-e4d4-4f6e-a81a-762a528e2c1f/Trends_HeroV2.gif" class="d-block w-100" alt="Travel Trends 2025">
          </div>
          <div class="carousel-item">
            <img src="https://images.squarespace-cdn.com/content/v1/6776fb052b2d52105bdde525/bc40edfc-e4d4-4f6e-a81a-762a528e2c1f/Trends_HeroV2.gif" class="d-block w-100" alt="Travel Trends 2025">
          </div>
          <div class="carousel-item">
            <img src="https://images.squarespace-cdn.com/content/v1/6776fb052b2d52105bdde525/bc40edfc-e4d4-4f6e-a81a-762a528e2c1f/Trends_HeroV2.gif" class="d-block w-100" alt="Travel Trends 2025">
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
      <hr>
      <div class="card" style="width: 18rem;">
        <img src="https://s7ap1.scene7.com/is/image/incredibleindia/1-palolem-beach-goa-goa-city-hero?qlt=82&ts=1726735654599" class="card-img-top" alt="Palolem Beach, Goa">
        <div class="card-body">
          <h5 class="card-title">Discover Palolem Beach</h5>
          <p class="card-text">Experience the serene beauty of Palolem Beach, located in the heart of Goa.</p>
          <a href="#" class="btn btn-primary">Explore</a>
        </div>
      </div>
      <div class="card" style="width: 18rem;">
        <img src="https://media-cdn.tripadvisor.com/media/attractions-splice-spp-674x446/09/94/28/eb.jpg" class="card-img-top" alt="Attraction Image">
        <div class="card-body">
          <h5 class="card-title">Amazing Attractions</h5>
          <p class="card-text">Find out more about the top attractions in your travel destination.</p>
          <a href="#" class="btn btn-primary">Learn More</a>
        </div>
      </div>
      <div class="card" style="width: 18rem;">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRS56OgMF-IOm8Cwfvgb9ESmmZjxpxqHdlpmA&s" class="card-img-top" alt="Restaurant Image">
        <div class="card-body">
          <h5 class="card-title">Best Restaurants</h5>
          <p class="card-text">Explore the best dining options in your travel destination.</p>
          <a href="#" class="btn btn-primary">Find Out</a>
        </div>
      </div>
      <hr>
      <div class="form">
        <h3>Contact Us</h3>
        <input type="text" placeholder="Enter your name" required>&nbsp;
        <input type="email" placeholder="Enter email address" required>
        <p>From</p>
        <input type="date" required>
        <p>To</p>
        <input type="date" required>&nbsp;
        <input type="tel" placeholder="Enter your contact number" required>
        <button type="submit">Submit</button>
      </div>
      <div class="footer">
        <p>&copy; 2025 Travelmate. All rights reserved. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore laudantium nam deserunt impedit nobis blanditiis provident fuga praesentium, vel rem minus dolorum modi, suscipit assumenda quae amet cupiditate ab odit.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore laudantium nam deserunt impedit nobis blanditiis provident fuga praesentium, vel rem minus dolorum modi, suscipit assumenda quae amet cupiditate ab odit.</p>
      </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>
