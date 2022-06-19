<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="Css/style.css" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    
    <title>Collegenius</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous">
  </head>
  <body>
      
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary shadow fixed-top">
        <div class="container">
          <a class="navbar-brand" href="#" style="font-size: 30px; font-weight: bolder;">Collegenius</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavDropdown">
            <ul class="navbar-nav ms-auto">
              <li class="nav-login">
                <a class="nav-link active" aria-current="page" href="html/login.html">Log In</a>
              </li>
              <li class="nav-daftar">
                <a class="nav-link" href="html/signup.html">Sign Up</a>
              </li>
              <li class="nav-tanya">
                <a class="nav-link" href="html/forum.html">Tanya Ke Forum</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    <!-- Navbar End-->
    
    <!-- Hero section -->
    <div class="banner py-5">
        <div class="container">
            <div class="row">
            <div class="col order-last text-end pt-2">
                <h1>Collegenius Make Your Task Easier</h1>
                <p>Collegenius merupakan sebuah forum diskusi yang dibuat oleh kelompk kami untuk memenuhi tugas akhir mata kuliah interaksi manusia dan komputer</p>
                <a class="buttons" href="html/forum.html">
                  <button type="button" class="btn btn-outline-light">Get Started</button>
                </a>
                <from class="d-flex pt-3" role="search">
                    <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                    <button class="btn btn-outline-light" type="submit">Search</button>
                </form>
            </div>
            <div class="col"></div>
            <div class="col order-first">
                <img src="Image/image3-removebg-preview.png" class="d-block w-70" alt="">
            </div>
            </div>
        </div>
    </div>
    <!-- Hero section End-->

    <!-- carousel --> <!-- belum jadi -->
    <div class="prodi pt-3 text-white text-center">
      <div class="row">
        <div class="col-lg-2 col-md-4 col-sm-6 col-xs-12">
          <a href="html/listProdi.html"><i class="fas fa-bars"> Lihat Semua</i></a>
        </div>
        <div class="col-lg-2 col-md-4 col-sm-6 col-xs-12">
          <a href="html/listMatkul.html"><i class="fas fa-laptop">Teknologi Informasi</i></a>
        </div>
        <div class="col-lg-2 col-md-4 col-sm-6 col-xs-12">
          <a href="html/listProdi.html"><i class="fas fa-cog"> Teknik Mesin</i></a>
        </div>
        <div class="col-lg-2 col-md-4 col-sm-6 col-xs-12">
          <a href="html/listProdi.html"><i class="far fa-building"> Teknik Sipil</i></a>
        </div>
        <div class="col-lg-2 col-md-4 col-sm-6 col-xs-12">
          <a href="html/listProdi.html"><i class="fas fa-heartbeat"> Kedokteran</i></a>
        </div>
        <div class="col-lg-2 col-md-4 col-sm-6 col-xs-12">
          <a href="html/listProdi.html"><i class="far fa-money-bill-alt"> Manajemen</i></a>
        </div>
      </div>
    </div>
    <!-- carousel -->

    <!-- Review section -->
    <div id="carouselExampleControls" class="carousel slide carousel-dark pt-5" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="Image/Group 373.png" class="mx-auto d-block w-50" alt="...">
        </div>
        <div class="carousel-item">
          <img src="Image/Group 372.png" class="mx-auto d-block w-50" alt="...">
        </div>
        <div class="carousel-item">
          <img src="Image/Group 372(1).png" class="mx-auto d-block w-50" alt="...">
        </div>
        <div class="carousel-item">
          <img src="Image/Group 372(2).png" class="mx-auto d-block w-50" alt="...">
        </div>
        <div class="carousel-item">
          <img src="Image/Group 372(3).png" class="mx-auto d-block w-50" alt="...">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
    <svg class="wave pt-1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#49ACFF" fill-opacity="1" d="M0,128L40,144C80,160,160,192,240,170.7C320,149,400,75,480,53.3C560,32,640,64,720,112C800,160,880,224,960,218.7C1040,213,1120,139,1200,117.3C1280,96,1360,128,1400,144L1440,160L1440,320L1400,320C1360,320,1280,320,1200,320C1120,320,1040,320,960,320C880,320,800,320,720,320C640,320,560,320,480,320C400,320,320,320,240,320C160,320,80,320,40,320L0,320Z"></path></svg>

    <!-- Review section end -->

    <!-- leaderboards -->
    <div class="leaderboard">
      <h1 class="title text-center text-white pt-3" style="font-weight: bold;">Meet Our Top Tier On Last Year</h1>
      <img src="Image/Group 368.png" class="rounded mx-auto d-block" alt="...">
      <div class="row ps-5 pe-5 justify-content-center">
        <div class="col-sm-2 order-last">
          <img src="Image/Group 369.png" class="rounded float-end" alt="...">
        </div>
        <div class="col-sm-2">
          <h5 class="leaderboard_content text-center text-white pt-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat voluptas quidem repellat ipsam temporibus soluta in quasi totam, consectetur ex dolore, aliquam, ipsa error eius exercitationem unde sunt iste placeat?</h5>
        </div>
        <div class="col-sm-2 order-first">
          <img src="Image/Group 370.png" class="rounded float-start" alt="...">
        </div>
      </div>
    </div>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#4a00ab" fill-opacity="1" d="M0,160L34.3,170.7C68.6,181,137,203,206,192C274.3,181,343,139,411,106.7C480,75,549,53,617,64C685.7,75,754,117,823,160C891.4,203,960,245,1029,218.7C1097.1,192,1166,96,1234,53.3C1302.9,11,1371,21,1406,26.7L1440,32L1440,0L1405.7,0C1371.4,0,1303,0,1234,0C1165.7,0,1097,0,1029,0C960,0,891,0,823,0C754.3,0,686,0,617,0C548.6,0,480,0,411,0C342.9,0,274,0,206,0C137.1,0,69,0,34,0L0,0Z"></path></svg>
    <!-- leaderboards end -->

    <!-- Anouncement -->
    <h1 class="title-footer text-center px-5 pb-3" style="font-weight: bold; font-family: Arial, Helvetica, sans-serif;">Berdiskusi dengan jutaan pakar dan tenaga ahli di bidangnya, selesaikan tugasmumu dan bantu yang lain disini</h1>
    <div class="announcement py-5 px-5">
      <div class="row ps-5 pe-5 justify-content-center">
        <div class="col order-last">
          <img src="Image/Group 309.png" class="image-content w-50 float-end" alt="">
        </div>
        <div class="col order-first">
          <h1 class="title">TANYAKAN</h1>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident aliquam eveniet molestias est distinctio vero delectus fugit adipisci assumenda repellat.</p>
          <h1 class="title">DAPATKAN</h1>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta libero harum tenetur, quis architecto quas! Veniam dolor esse sint cumque!</p>
          <h1 class="title">BANTU YANG LAIN</h1>
          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Omnis, neque rem. Sequi recusandae facere nobis, dolorum vel repudiandae reprehenderit beatae.</p>
        </div>
      </div>
    </div>
    <!-- Anouncement end -->

  <!-- Footer -->
    <footer
            class="text-center text-lg-start text-white w-100"
            style="background-image: linear-gradient(to right, rgb(0, 10, 126), rgb(89, 0, 111));"
            >
      <!-- Section: Social media -->
      <section
              class="d-flex justify-content-between"
              style="background-image: linear-gradient(to right, rgb(0, 7, 82), rgb(63, 0, 79));"
              >
        <!-- Left -->
        <div class="me-5 px-2">
          <span>Get connected with us on social networks:</span>
        </div>
        <!-- Left -->

        <!-- Right -->
        <div class="icon pt-1">
          <a href="" class="text-white me-4">
            <i class="fa-brands fa-facebook-f"></i>
          </a>
          <a href="" class="text-white me-4">
            <i class="fab fa-twitter"></i>
          </a>
          <a href="" class="text-white me-4">
            <i class="fab fa-google"></i>
          </a>
          <a href="" class="text-white me-4">
            <i class="fab fa-instagram"></i>
          </a>
          <a href="" class="text-white me-4">
            <i class="fab fa-linkedin"></i>
          </a>
          <a href="" class="text-white me-4">
            <i class="fab fa-github"></i>
          </a>
        </div>
        <!-- Right -->
      </section>
      <!-- Section: Social media -->

      <!-- Section: Links  -->
      <section class="footer-class">
        <div class="container text-center text-md-start mt-5">
          <!-- Grid row -->
          <div class="row mt-3">
            <!-- Grid column -->
            <div class="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4">
              <!-- Content -->
              <h6 class="text-uppercase fw-bold">Collegenius</h6>
              <hr
                  class="mb-4 mt-0 d-inline-block mx-auto"
                  style="width: 60px; background-color: #7c4dff; height: 2px" /> 
              <p style="text-align:justify ;">
                Dengan platform ini, kami selaku pengembang berharap produk yang kami ciptakan dapat membantu banyak orang sekaligus memberi manfaat bagi kita sebagai amal jariyah
              </p>
            </div>
            <!-- Grid column -->

            <!-- Grid column -->
            <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
              <!-- Links -->
              <h6 class="text-uppercase fw-bold">Features</h6>
              <hr
                  class="mb-4 mt-0 d-inline-block mx-auto"
                  style="width: 60px; background-color: #7c4dff; height: 2px"
                  />
              <p>
                <a href="#!" class="text-white">Discussion Forum</a>
              </p>
              <p>
                <a href="#!" class="text-white">Profile Page</a>
              </p>
              <p>
                <a href="#!" class="text-white">Leaderboard Page</a>
              </p>
              <p>
                <a href="#!" class="text-white">Acievement</a>
              </p>
            </div>
            <!-- Grid column -->

            <!-- Grid column -->
            <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">
              <!-- Links -->
              <h6 class="text-uppercase fw-bold">Useful links</h6>
              <hr
                  class="mb-4 mt-0 d-inline-block mx-auto"
                  style="width: 60px; background-color: #7c4dff; height: 2px"
                  />
              <p>
                <a href="#!" class="text-white">Your Account</a>
              </p>
              <p>
                <a href="#!" class="text-white">Become an Affiliate</a>
              </p>
              <p>
                <a href="#!" class="text-white">Shipping Rates</a>
              </p>
              <p>
                <a href="#!" class="text-white">Help</a>
              </p>
            </div>
            <!-- Grid column -->

            <!-- Grid column -->
            <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mb-md-0 mb-4">
              <!-- Links -->
              <h6 class="text-uppercase fw-bold">Contact</h6>
              <hr
                  class="mb-4 mt-0 d-inline-block mx-auto"
                  style="width: 60px; background-color: #7c4dff; height: 2px"
                  />
              <p><i class="fas fa-home mr-3"></i> New York, NY 10012, US</p>
              <p><i class="fas fa-envelope mr-3"></i> info@example.com</p>
              <p><i class="fas fa-phone mr-3"></i> + 01 234 567 88</p>
              <p><i class="fas fa-print mr-3"></i> + 01 234 567 89</p>
            </div>
            <!-- Grid column -->
          </div>
          <!-- Grid row -->
        </div>
      </section>
      <!-- Section: Links  -->

      <!-- Copyright -->
      <div
          class="text-center p-3"
          style="background-color: rgba(0, 0, 0, 0.2)"
          >
        © 2020 Copyright:
        <a class="text-white" href="https://mdbootstrap.com/"
          >MDBootstrap.com</a
          >
      </div>
      <!-- Copyright -->
    </footer>
    <!-- footer end -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js" integrity="sha384-pprn3073KE6tl6bjs2QrFaJGz5/SUsLqktiwsUTF55Jfv3qYSDhgCecCxMW52nD2" crossorigin="anonymous"></script>
  </body>
</html>
