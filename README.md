<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>REF2k24</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.7/dist/umd/popper.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">


  
  <style>

    .offcanvas-dark {
      background-color: #343a40;
      color: white;
    }
    .carousel-item img {
      width: 100%;
      height: 400px; 
      object-fit: cover; 
    }

    .card.borderless {
      border: none;
      box-shadow: none;
    }
  </style>
</head>

<body class="text-bg-dark ">
    <div class="offcanvas offcanvas-start offcanvas-dark" id="demo">
        <div class="offcanvas-header ">
          <h1 class="offcanvas-title">Heading</h1>
          <button type="button" class="btn-close" data-bs-dismiss="offcanvas"></button>
        </div>
    </div>        
  <nav class="navbar navbar-expand-lg bg-body-tertiary"  data-bs-theme="dark">
    <div class="container-fluid">
        <button type="button" class="btn" data-bs-toggle="offcanvas" data-bs-target="#demo">
            Menu
        </button>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
              aria-expanded="false">
              Dropdown
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">Action</a></li>
              <li><a class="dropdown-item" href="#">Another action</a></li>
              <li><hr class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="#">Something else here</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled" aria-disabled="true">Disabled</a>
          </li>
        </ul>
        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-success" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>

  <div class="container-fluid">
    <div id="myCarousel" class="carousel slide" data-bs-ride="carousel">
      <ul class="carousel-indicators">
        <li  data-bs-slide-to="0" class="active"></li>
        <li  data-bs-slide-to="1"></li>
        <li  data-bs-slide-to="2"></li>
      </ul>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="verse1.png" class="d-block w-100" alt="Break the Chords">
        </div>
        <div class="carousel-item">
          <img src="verse2.png" class="d-block w-100" alt="In your steps">
        </div>
        <div class="carousel-item">
          <img src="verse3.png" class="d-block w-100" alt="Decode">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#myCarousel" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#myCarousel" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </div>

  <div class="container px-4 text-center" >
    <div class="row p-2 gx-4 gy-4">
      <div class="card col-xl-4 col-sm-12 p-4 text-bg-dark borderless">
        <img src="pic1.jpg" class="card-img-top">
        <div class="card-body">
          <h5 class="card-title">Break the Chords</h5>
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
            content.</p>
          <a href="#" class="btn btn-outline-success">Go somewhere</a>
        </div>
      </div>
      <div class="card col-xl-4 col-sm-12 p-4 text-bg-dark borderless">
        <img src="pic2.jpg" class="card-img-top">
        <div class="card-body">
          <h5 class="card-title">In your steps</h5>
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
            content.</p>
          <a href="#" class="btn btn-outline-success">Go somewhere</a>
        </div>
      </div>
      <div class="card col-xl-4 col-sm-12 p-4 text-bg-dark borderless">
        <img src="pic3.jpg" class="card-img-top">
        <div class="card-body">
          <h5 class="card-title">Decode</h5>
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
            content.</p>
          <a href="#" class="btn btn-outline-success">Go somewhere</a>
        </div>
      </div>
      <div class="card col-xl-4 col-sm-12 p-4 text-bg-dark borderless">
        <img src="pic4.jpg" class="card-img-top">
        <div class="card-body">
          <h5 class="card-title">Jokes-a-Part</h5>
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
            content.</p>
          <a href="#" class="btn btn-outline-success">Go somewhere</a>
        </div>
      </div>
      <div class="card col-xl-4 col-sm-12 p-4 text-bg-dark borderless">
        <img src="pic5.jpg" class="card-img-top">
        <div class="card-body">
          <h5 class="card-title">Punch-Ayath</h5>
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
            content.</p>
          <a href="#" class="btn btn-outline-success">Go somewhere</a>
        </div>
      </div>
      <div class="card col-xl-4 col-sm-12 p-4 text-bg-dark borderless">
        <img src="pic6.jpg" class="card-img-top">
        <div class="card-body">
          <h5 class="card-title">Rap the Theme</h5>
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
            content.</p>
          <a href="#" class="btn btn-outline-success">Go somewhere</a>
        </div>
      </div>
    </div>
  </div>

  
  

</body>

</html>
