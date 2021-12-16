<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1.0">
  <!-- Latest compiled and minified CSS -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.10.0/css/all.min.css" integrity="sha512-PgQMlq+nqFLV4ylk1gwUOgm6CtIIXkKwaIHp/PAIWHzig/lKZSEGKEysh0TCVbHJXCLN7WetD8TFecIky75ZfQ==" crossorigin="anonymous"
    referrerpolicy="no-referrer" />
  <!-- jQuery library -->
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

  <!-- Popper JS -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>

  <!-- Latest compiled JavaScript -->
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
  <title>Weather Daily</title>
  <link rel="stylesheet" href="style.css">
  <link rel="shortcut icon" href="images/logo.jpeg" type="image/jpeg">

</head>

<body>
    <div class="container-fluid main_menu">
    <div class="row">
      <div class="col-md-10 col-12 mx-auto">
        <nav class="navbar navbar-expand-lg">
          <a class="navbar-brand" href="index.html"><i class="fas fa-cloud-sun"></i> Weather Daily</a>
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>

          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ml-auto">
              <li class="nav-item active">
                <a class="nav-link" href="index.html">Home <span class="sr-only">(current)</span></a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="weather.html">Weather</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="about.html">About</a>
              </li>


            </ul>

          </div>
        </nav>
      </div>
    </div>
  </div>
  <!-- main header-->
  <div class="container-fluid main_header">
    <div class="row">
      <div class="col-md-10 col-12 mx-auto">
        <div class="row">
          <!-- left side div-->
          <div class="col-md-6 col-12 main_header_left">
            <p> Welcome to Weather Daily </p>
            <h1>Get the latest <span style="color: blue" > Weather </span> Updates!</h1>
            <a href="weather.html"><button> Check now </button></a>
          </div>
          <!--right side div-->
          <div class="col-md-6 col-12 main_header_right">
            <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
              <div class="carousel-inner">
                <div class="carousel-item active">
                  <img class="w-100" src="images/img_1.png" alt="First slide">
                </div>
                <div class="carousel-item">
                  <img class="w-100" src="images/img_2.png" alt="Second slide">
                </div>
                <div class="carousel-item">
                  <img class="w-100" src="images/img_3.png" alt="Third slide">
                </div>
              </div>
              <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
              </a>
              <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  </div>
  <!--Footer code-->
  <footer>
    <p> Created by Simran Joon </p>
  </footer>
</body>

</html>
