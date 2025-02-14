<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        img{
            width: 80%  ;
        }

        p{
            text-align: justify;
        }
    </style>
  </head>
  <body>
        <div>
            <div>
                <nav class="navbar navbar-dark bg-dark fixed-top">
                    <div class="container-fluid">
                      <a class="navbar-brand" href="#">Welcome!</a>
                      <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasDarkNavbar" aria-controls="offcanvasDarkNavbar" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                      </button>
                      <div class="offcanvas offcanvas-end text-bg-dark" tabindex="-1" id="offcanvasDarkNavbar" aria-labelledby="offcanvasDarkNavbarLabel">
                        <div class="offcanvas-header">
                          <h5 class="offcanvas-title" id="offcanvasDarkNavbarLabel">Dark offcanvas</h5>
                          <button type="button" class="btn-close btn-close-white" data-bs-dismiss="offcanvas" aria-label="Close"></button>
                        </div>
                        <div class="offcanvas-body">
                          <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
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
                              <ul class="dropdown-menu dropdown-menu-dark">
                                <li><a class="dropdown-item" href="#">Action</a></li>
                                <li><a class="dropdown-item" href="#">Another action</a></li>
                                <li>
                                  <hr class="dropdown-divider">
                                </li>
                                <li><a class="dropdown-item" href="#">Something else here</a></li>
                              </ul>
                            </li>
                          </ul>
                          <form class="d-flex mt-3" role="search">
                            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                            <button class="btn btn-success" type="submit">Search</button>
                          </form>
                        </div>
                      </div>
                    </div>
                  </nav>
            </div> <br><br><br>

            <div class="row">
          
                    <div class=" col-12 col-lg-6">
                        <h1>Indie Horror Games of 2025</h1>
            
                                        
                            <p> <b> Directive 8020</b> is the latest entry in The Dark Pictures Anthology and introduces a terrifying sci-fi horror setting. Set aboard the spaceship Cassiopeia, the game follows a crew sent to explore planet Tau Ceti F, only to encounter an unknown alien organism that begins to take control. As paranoia spreads among the crew, players must make critical choices that determine who survives and who falls victim to the extraterrestrial threat. With Supermassive Games’ signature cinematic approach, branching narratives, and immersive horror elements, Directive 8020 offers a chilling deep-space experience reminiscent of films like Alien and Event Horizon.</p>
            
                            <button><a href="https://store.steampowered.com/app/2255370/Directive_8020/">Buy Now on Steam!</a></button>

                            <br><br>
                    </div >
                    <div class="col-12 col-lg-6">
                        <img src="D80201.jpg" alt="">
                    </div> 
                    <div> <br><br>
                        <form class="row g-3">
                            <div class="col-md-6">
                              <label for="inputEmail4" class="form-label">Email</label>
                              <input type="email" class="form-control" id="inputEmail4">
                            </div>
                            <div class="col-md-6">
                              <label for="inputPassword4" class="form-label">Password</label>
                              <input type="password" class="form-control" id="inputPassword4">
                            </div>
                            <div class="col-12">
                              <label for="inputAddress" class="form-label">Address</label>
                              <input type="text" class="form-control" id="inputAddress" placeholder="1234 Main St">
                            </div>
                            <div class="col-12">
                              <label for="inputAddress2" class="form-label">Address 2</label>
                              <input type="text" class="form-control" id="inputAddress2" placeholder="Apartment, studio, or floor">
                            </div>
                            <div class="col-md-6">
                              <label for="inputCity" class="form-label">City</label>
                              <input type="text" class="form-control" id="inputCity">
                            </div>
                            <div class="col-md-4">
                              <label for="inputState" class="form-label">State</label>
                              <select id="inputState" class="form-select">
                                <option selected>Choose...</option>
                                <option>...</option>
                              </select>
                            </div>
                            <div class="col-md-2">
                              <label for="inputZip" class="form-label">Zip</label>
                              <input type="text" class="form-control" id="inputZip">
                            </div>
                            <div class="col-12">
                              <div class="form-check">
                                <input class="form-check-input" type="checkbox" id="gridCheck">
                                <label class="form-check-label" for="gridCheck">
                                  Check me out
                                </label>
                              </div>
                            </div>
                            <div class="col-12">
                              <button type="submit" class="btn btn-primary">Sign in</button>
                            </div>
                          </form>
                    </div>
                
            </div>
        </div>


    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
  </body>
</html>
