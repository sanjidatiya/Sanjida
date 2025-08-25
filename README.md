<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-LN+7fdVzj6u52u30Kp6M/trliBMCMKTyK833zpbD+pXdCLuTusPj697FH4R/5mcr" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.13.1/font/bootstrap-icons.min.css">
</head>
  <body>
    <nav class="navbar navbar-expand-lg bg-success">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
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
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
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
        <input class="form-control me-2" type="Resume" placeholder="Search" aria-label="Search"/>
        <button class="btn btn-outline-success" type="submit">Resume</button>
      </form>
    </div>
  </div>
</nav>
    
    
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/js/bootstrap.bundle.min.js" integrity="sha384-ndDqU0Gzau9qJ1lfW4pNLlhNTkCfHzAVBReH9diLvGRem5+R9g2FzA8ZGN954O5Q" crossorigin="anonymous"></script>
 <!-- intro section -->
    <section class="container d-lg-flex justify-content-around align-items-center w-100 mt-4">
        <div class="text-center">
            <h1>Sanjida Tiya</h1>
            <p>Web Developer</p>
            <button class="btn btn-outline-success">Hire Me</button>
        </div>
        <div class="">
            <img src="Image/Smart.png" style="height: 500px;" class="mx-auto" alt="intro-image">
        </div>
    </section>


    <!-- project -->

    <section class="container mt-4">
        <h1 class="text-center">Projects</h1>
        <div class="d-lg-flex justify-content-around ">
            <!-- card 01 -->
            <div class="card mx-auto my-4" style="width: 18rem;">
                <img src="Image/5073120.jpg" class="card-img-top"
                    alt="...">
                <div class="card-body">
                    <h5 class="card-title">Marketing Agency</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card’s content.</p>
                    <a href="#" class="btn btn-sm btn-success">READ MORE</a>
                </div>
            </div>
            <!-- card 01 -->
            <div class="card mx-auto my-4" style="width: 18rem;">
                <img src="Image/5073120.jpg" class="card-img-top"
                    alt="...">
                <div class="card-body">
                    <h5 class="card-title">Marketing Agency</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card’s content.</p>
                    <a href="#" class="btn btn-sm btn-success">READ MORE</a>
                </div>
            </div>
            <!-- card 01 -->
            <div class="card mx-auto my-4" style="width: 18rem;">
                <img src="Image/5073120.jpg" class="card-img-top"
                    alt="...">
                <div class="card-body">
                    <h5 class="card-title">Marketing Agency</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card’s content.</p>
                    <a href="#" class="btn btn-sm btn-success">READ MORE</a>
                </div>
            </div>
        </div>
    </section>

    <!-- gallery -->
    <section class="container mt-4 ">
        <h1 class="text-center">Gallery</h1>
        <div class="d-lg-flex flex-wrap justify-content-around mt-4">
            <!-- image 01  -->
            <div class="card" style="width: 18rem;">
                <img src="Image/5073120.jpg" class="card-img-top"
                    alt="...">
            </div>
            <!-- image 01  -->
            <div class="card" style="width: 18rem;">
                <img src="Image/5073120.jpg" class="card-img-top"
                    alt="...">
            </div>
            <!-- image 01  -->
            <div class="card" style="width: 18rem;">
                <img src="Image/5073120.jpg" class="card-img-top"
                    alt="...">
            </div>
            <!-- image 01  -->
            <div class="card" style="width: 18rem;">
                <img src="Image/5073120.jpg" class="card-img-top"
                    alt="...">
            </div>
            <!-- image 01  -->
            
        </div>
        <div class="container d-flex justify-content-around mt-4">

            <div class="card" style="width: 18rem;">
                <img src="Image/5073120.jpg" class="card-img-top"
                    alt="...">
            </div>
            <!-- image 01  -->
            <div class="card" style="width: 18rem;">
                <img src="Image/5073120.jpg" class="card-img-top"
                    alt="...">
            </div>
        </div>
    </section>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ndDqU0Gzau9qJ1lfW4pNLlhNTkCfHzAVBReH9diLvGRem5+R9g2FzA8ZGN954O5Q"
        crossorigin="anonymous"></script> 
</body>
</html>
