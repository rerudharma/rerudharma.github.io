
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

    <!-- My Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Viga" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Akaya+Telivigala&family=Viga" rel="stylesheet">

    <!-- My CSS -->
    <link rel="stylesheet" href="style.css">

    <title>Gauri Janaki</title>
    <link rel="icon" href="img/kidungutama.jpg" type="image/x-icon">

  </head>
  <style>
    /* Navbar */
.navbar {
    position: relative;
    z-index: 1;
}
.navbar-brand {
    font-family: Viga;
    font-size: 32px;
}

/* Jumbotron */
.jumbotron{
    background-image: url(img/jumbot.jpg);
    background-size: cover;
    text-align: center;
    height: 575px;
    position: relative;
}

.jumbotron .container {
    z-index: 1;
    position: relative;
}

.jumbotron::after {
    content: '';
    display: block;
    width: 100%;
    height: 100%;
    background-image: linear-gradient(to top, rgba(0, 0, 0, 1), rgba(0, 0, 0, 0));
    position: absolute;
    bottom: 0;
}

.jumbotron .display-4 {
    font-family: Akaya;
    color: rgb(197, 197, 197);
    margin-top: 150px;
    font-weight: 200;
    text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.7);
    font-size: 35px;
}

.jumbotron .display-4 span {
    font-weight: 700;
}

.jumbotron .lead {
    color: white;
    text-align: center;
    text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.7);
    margin-bottom: 30px;
}

/* Info Panel */
.info-panel {
    box-shadow: 0 3px 20px rgba(0, 0, 0, 0.5);
    border-radius: 12px;
    margin-top: -100px;
    background-color: white;
    padding: 30px;
}

.info-panel img {
    width: 80px;
    height: 80px;
    margin-right: 20px;
    margin-bottom: 20px;
}

.info-panel h4 {
    font-size: 16px;
    text-transform: uppercase;
    font-weight: bold;
    margin-top: 5px;
}

.info-panel p {
    font-size: 14px;
    color: #ACACAC;
    margin-top: -5px;
    font-weight: 200;
}

/* Workingspace */
.workingspace {
    margin-top: 30px;
    text-align: center;
    margin-right: -20px;
}

.workingspace h3 {
    font-size: 52px;
    font-weight: 200;
    text-transform: uppercase;
    margin-top: 100px;
}

.workingspace h3 span {
    font-weight: 500;
}

.workingspace p {
    font-size: 18px;
    color: #ACACAC;
    font-weight: 200;
    margin: 30px 0;
}

/* footer */
.footer {
    margin-top: 100px;
}
.footer p {
    color: #ACACAC;
    font-size: 18px;
}

/* Utility */
.btn-primary {
    background-color: #996900;
    border-bottom: #996900;
    border-color: #996900;
}
.tombol {
    text-transform: uppercase;
    border-radius: 40px;
}
.tombol-1 {
    text-transform: uppercase;
    border-radius: 40px;
    font-family: Viga;
}



/* DEKSTOP VERSION */
@media (min-width: 992px) { 
    .navbar-brand, .nav-link {
        color: white !important;
        text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.7);
    }
    .nav-link {
        text-transform: uppercase;
        margin-right: 30px;
    }

    .nav-link:hover::after{
        content: '';
        display: block;
        border-bottom: 3px solid #0b63dc;
        width: 50%;
        margin: auto;
        padding-bottom: 5px;
        margin-bottom: -8px;

    }

    .jumbotron {
        margin-top: -75px;
        height: 640px;
    }

    .jumbotron .display-4 {
        font-size: 62px;
    }

    .workingspace {
        text-align: left;
    }
 }
  </style>
  <body>
   
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light">
      <div class="container">
        <a class="navbar-brand" href="#">BangLipur</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
          <div class="navbar-nav ml-auto">
            <a class="nav-item nav-link active" href="#">Home <span class="sr-only">(current)</span></a>
            <a class="nav-item nav-link" href="#">Features</a>
            <a class="nav-item nav-link" href="#">About Us</a>
            <a class="nav-item nav-link" href="#">Contact Us</a>
            <a class="nav-item btn btn-primary tombol font-weight-bold" href="#">Login</a>
          </div>
        </div>
      </div>
    </nav>
    <!-- Akhir Navbar -->

    <!-- Jumbotron -->
    <div class="jumbotron jumbotron-fluid">
      <div class="container">
        <h1 class="display-4"><span>Culture</span> of the <span>Mind</span> must be <br>subservient to the <span>Heart</span></h1>
        <p class="lead">“People without the knowledge of their past history, origin and culture is like a tree without roots.”</p>
        <a href="" class="btn btn-primary tombol-1">Bang Lipur</a>
      </div>
    </div>
    <!-- akhir Jumbotron -->

    <!-- Container -->
    <div class="container">

        <!-- Info Panel -->
        <div class="row justify-content-center">
          <div class="col-10 info-panel">
            <div class="row">
              <div class="col-lg">
                <img src="img/book1.png" alt="logo" class="float-left">
                <h4>Buku Cerita</h4>
                <p>Lorem ipsum dolor sit amet.</p>
              </div>
                <div class="col-lg">
                  <img src="img/tempur.jpg" alt="logo" class="float-left">
                  <h4>kartu Tempur</h4>
                  <p>Lorem ipsum dolor sit amet.</p>
                </div>
                  <div class="col-lg">
                    <img src="img/barcode.png" alt="logo" class="float-left">
                    <h4>Barcode</h4>
                    <p>Lorem ipsum dolor sit amet.</p>
                  </div>
              </div>
            </div>
          </div>
        </div>
        <!-- akhir Info Panel -->

        <!-- Workingspace -->
        <div class="row workingspace">
          <div class="col-lg-6">
            <img src="img/logo.png" alt="Workingspace" class="img-fluid">
          </div>
          
          <div class="col-lg-5">
            <h3> Cintai <span>Budaya</span> Nusantara</h3>
            <p> “Culture is the widening of the mind and of the spirit.” </p>
            <a href="" class="btn btn-primary tombol">Gallery</a>
          </div>
        </div>
        <!-- akhir Workingspace -->

        <!-- Footer -->
          <div class="row footer">
            <div class="col text-center">
              <p>2021 All Rights Reserved by Gauri Janaki ft Kemah Budaya</p>
            </div>
          </div>
        <!-- akhir Footer -->


    </div>
    <!-- akhir Container -->








    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
  </body>

