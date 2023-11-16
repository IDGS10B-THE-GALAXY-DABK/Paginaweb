<!doctype html>
<html lang="es">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>El Enigma de la Universidad repuesto</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.7.2/font/bootstrap-icons.css">
  <link rel="stylesheet" href="css/estilos.css">
</head>

<style>
  *{
    font-family: Arial, Helvetica, sans-serif;

}

body{
    background-color: rgb(14, 12, 12);
}
body{
    background-color: rgb(14, 12, 12);
}
.section-padding{
    padding: 70px;

}

.nosotros{
    text-align: justify;
    line-height: 2em;
}

.img{
    width: 350px;
    height: 350px;
}

.carrousel-item{
    height: 80vh;
    min-height: 300px;
}
.carrousel-caption{
    bottom: 200px;
    z-index: 2;
}
.carrousel-caption h5{
    font: 45px;
    text-transform: uppercase;
    letter-spacing: 2px;
    margin-bottom: 25px;
}
.carrousel-caption h5{
    font: 45px;
    text-transform: uppercase;
    letter-spacing: 2px;
    margin-bottom: 25px;
}
.carrousel-caption p{
   width: 60px;
   margin: auto;
   font-size: 18px;
   line-height: 1.9;
}
.carrousel-inner::before {
    content: '';
    position: absolute;
    width: 100%;
    height: 100%;
    top:  0;
    left: 0;
    background: rgba(0, 30, 82, 0.327);
    z-index: 1;
}
.discord {
   display: block;
   width: 130px;
   font-family: Arial, Helvetica, sans-serif;
   text-align: center;
   font-weight: 130;
   background-color: rgb(39, 114, 255);
   border-radius: 10px;
   margin: 10px 20px;
   color: white;
   text-decoration: none;
}
.whatsapp {
   display: block;
   width: 130px;
   font-family: Arial, Helvetica, sans-serif;
   text-align: center;
   font-weight: 130;
   background-color: rgb(39, 114, 255);
   border-radius: 10px;
   margin: 10px 20px;
   color: white;
   text-decoration: none;
}
.instagram {
   display: block;
   width: 130px;
   font-family: Arial, Helvetica, sans-serif;
   text-align: center;
   font-weight: 130;
   background-color: rgb(39, 114, 255);
   border-radius: 10px;
   margin: 10px 20px;
   color: white;
   text-decoration: none;
}
</style>
<body>
  <header>
    <div class="container">
      <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top " data-bs-theme="dark">
        <div class="container-fluid">
          <a href="#" class="navbar-brand"> <span class="text-primary">The</span>Galaxy</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
            data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
            aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
  
              </li>
              <li class="nav-item">
                <a href="#aboutus" class="nav-link">About us</a>
              </li>
              <li class="nav-item">
                <a href="#ournetworks" class="nav-link">Our Networks</a>
              </li>
             
              </li>
              <li class="nav-item">
                <a href="#creators" class="nav-link">Creators and Roles</a>
              </li>
             
            </ul>

          </div>
        </div>
      </nav>
      <div id></div>
    </div>
  </header>

  <div id="carouselExampleCaptions" class="carousel slide">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselE" data-bs-slide-to="0" class="active" aria-current="true" 
      aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselE" data-bs-slide-to="1" aria-current="true"
        aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselE" data-bs-slide-to="2" aria-current="true"
        aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner">

      <div class="carousel-item active">
        <img src="Img/Pantalla.png" class="d-block w-100" alt="...">
        <div class="carousel-caption">
          <h5>The enigma of the University</h5>
          <p>Would you dare to investigate?</p>
          <a href="#information" class="btn btn-primary mt-3 bg-dark">More information</a>
        </div>
      </div>
      <div class="carousel-item">
        <img src="Img/Escenario 1.jpeg" class="d-block w-100" alt="...">
        <div class="carousel-caption ">


        </div>
      </div>
      <div class="carousel-item">
        <img src="Img/Escritrio.png" class="d-block w-100" alt="...">
        <div class="carousel-caption">

        </div>
      </div>
    </div>
    <button class="carousel-control-prev" type="button"
    data-bs-target="#carouselE"
    data-bs-slide="prev"
    >
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>

  </div>

  </section>
  <section class="Nosotros my-5" id="aboutus">
    <h2 class="text-center text-white my-5">About us</h2>
    <div class="container">
      <div class="row">
        <div class="col-6 text-white justify">
          <p>We are a small group of people from a University in the municipality</p>
          <p> from Santa Catarina, in the state of Monterrey Nuevo León</p>
          <p>We are looking to promote our Demo of a video game themed to the University where we are studying</p>
          <p>The name of our game is "The Enigma of the University", and it is related to a story that has been
            circulating for some time that
            at the university at a certain time of day a girl usually appears.</p>
        </div>
        <div class="col-6">
          <img src="Img/logo.png" class="img" alt="">
        </div>
      </div>
    </div>
    <section class="Nosotros my-5" id="information">
      <h2 class="text-center text-white my-5">Game Related</h2>
      <div class="container">
        <div class="row">
          <div class="col-6 text-white justify">
            <p>Daniela, a young security guard struggling with financial problems, delves into her new night job at the Technological University. The university, 
              far from being abandoned, is silent at night, making it the perfect place for Daniela.</p>
              <br>
              <p>Everything changes when he discovers a ghost girl in one of the hallways. Initially, the girl 
                seems harmless and in need of help. Daniela feels compassion and decides to investigate further.</p>
              <br>
            <p>Players take on the role of Daniela and must explore the university in search of answers.
               As they progress, they discover dark secrets about the history of the college and the ghost girl. They must make 
              important decisions that will affect the course of history and Daniela's destiny.</p>
              <br>
              <p>"Night's Watch" combines RPG elements, such as skill upgrading and item collecting, 
                with a growing sense of tension and mystery. Players must face supernatural challenges 
                and solve puzzles to unravel the riddle of the university.</p>
          </div>
          <div class="col-6">
            <img src="Img/Estacionamiento.jpeg" class="img" alt="">
          </div>
        </div>
      </div>
    </section>
  </section>
  <section class="services section pading  " id="ournetworks">

    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <div class="section-header text-center text-white pb-5">
            <h2>Our Networks</h2>
            <p>
              In this section you will find some of our platforms <br> 
              where you can find out about new updates
            </p>

          </div>

        </div>
      </div>
      <div class="row">
        <div class="col-12 col-md-12 col-lg-4">
          <div class="card text-white text center bg-dark pb-2">
            <div class="card-body">
              <i class="bi bi-discord"></i>
              <h3 class="card-title">Discord</h3>
              <p class="lead">
                Join the Discord Community more information or questions
              </p>
              <a class="discord" href="https://discord.gg/4wGxfYrE">More information </a>
            </div>
          </div>

        </div>
        <div class="col-12 col-md-12 col-lg-4">
          <div class="card text-white text center bg-dark pb-2">
            <div class="card-body">
              <i class="bi bi-whatsapp"></i>
              <h3 class="card-title">Whatsapp</h3>
              <p class="lead">
                Join the WhatsApp Group for more information or questions
              </p>
              <a class="whatsapp" href="https://chat.whatsapp.com/L8TPEpwkwDuCRei1uLRAqz">More information </a>
            </div>
          </div>

        </div>
        <div class="col-12 col-md-12 col-lg-4">
          <div class="card text-white text center bg-dark pb-2">
            <div class="card-body">
              <i class="bi bi-instagram"></i>
              <h3 class="card-title">instagram</h3>
              <p class="lead">
                Join the WhatsApp Group for more information or questions and new characters
              </p>
              <a class="instagram" href="https://instagram.com/thegalaxy_of?igshid=MWlsenJvaWQ3bThoMA==">More information </a>
            </div>
          </div>

        </div>
      </div>
    </div>

  </section>

  <section class="team section-padding" id="creators">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <div class="section-header text-center text-white pb-5">
            <h2>Creators and Roles</h2>

            <p>Meet those responsible for the creation of this game idea</p>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-11 col-md-11 col-lg-3">
          <div class="card text-center bg-dark">
            <div class="card-body text-white">
              <img src="Img/Foto.jpg" class="img-fluid rounded-circle" alt="">
              <h3 class="card-title py-2">Brayan Alejandro Castillo Alanis </h3>
              <p class="card-text">
                <i class="bi bi-send"></i>Design <br>
                <i class="bi bi-send"></i>Page creation <br>
                <i class="bi bi-send"></i>mobile design<br>
                <i class="bi bi-send"></i>Mobile app creation<br>
                <i class="bi bi-send"></i>Video game creation
              </p>



            </div>

          </div>
        </div>
        <div class="col-11 col-md-11 col-lg-3">
          <div class="card text-center bg-dark">
            <div class="card-body text-white">
              <img src="Img/Foto.jpg" class="img-fluid rounded-circle" alt="">
              <h3 class="card-title py-2">Alan Joaquin Flores Diaz </h3>
              <p class="card-text">
                <i class="bi bi-send"></i>Design <br>
                <i class="bi bi-send"></i>Page creation <br>
                <i class="bi bi-send"></i>mobile design<br>
                <i class="bi bi-send"></i>Mobile app creation<br>
                <i class="bi bi-send"></i>Video game creation
              </p>



            </div>

          </div>
        </div>
        <div class="col-11 col-md-11 col-lg-3">
          <div class="card text-center bg-dark">
            <div class="card-body text-white">
              <img src="Img/Foto.jpg" class="img-fluid rounded-circle" alt="">
              <h3 class="card-title py-2">Kevin Orlando Guzman Reyes </h3>
              <p class="card-text">
                <i class="bi bi-send"></i>Design <br>
                <i class="bi bi-send"></i>Page creation <br>
                <i class="bi bi-send"></i>mobile design<br>
                <i class="bi bi-send"></i>Mobile app creation<br>
                <i class="bi bi-send"></i>Video game creation
              </p>



            </div>

          </div>
        </div>
        <div class="col-11 col-md-11 col-lg-3">
          <div class="card text-center bg-dark">
            <div class="card-body text-white">
              <img src="Img/Foto.jpg" class="img-fluid rounded-circle" alt="">
              <h3 class="card-title py-2">Sergio Daniel de la Cruz </h3>
              <p class="card-text">
                <i class="bi bi-send"></i>Design <br>
                <i class="bi bi-send"></i>Page creation <br>
                <i class="bi bi-send"></i>mobile design<br>
                <i class="bi bi-send"></i>Mobile app creation<br>
                <i class="bi bi-send"></i>Video game creation
              </p>



            </div>

          </div>
        </div>
      </div>
    </div>
    </div>

  </section>

  <footer class="text-center text-white py-3">
    &copy; The Galaxy - All rights reserved
  </footer>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL"
    crossorigin="anonymous"></script>
</body>

</html>
