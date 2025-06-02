<template>
  <section>

<!-- NAVIGATION -->
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top" id="mainNav">
            <div class="container">
                <a class="navbar-brand" href="#"><img src="../assets/logo.png" alt="Toksmail"> Toksmail</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
                    Menu
                    <i class="fas fa-bars ms-1"></i>
                </button>
                <div class="collapse navbar-collapse" id="navbarResponsive">
                    <ul class="navbar-nav text-uppercase ms-auto py-4 py-lg-0">
                        <li class="nav-item"><a href="#" class="nav-link">Home</a></li>
                        <li class="nav-item"><a href="#guide" class="nav-link" >Guide</a></li>
                        <li class="nav-item"><a href="#testimonials" class="nav-link" >Testimonials</a></li>
                        <!-- <li class="nav-item"><a href="" class="nav-link" >About</a></li> -->
                        <li class="nav-item"><a href="#subscription" class="nav-link" >Contact</a></li>
                    </ul>
                </div>
            </div>
    </nav>
<!-- NAVIGATION ENDS -->

<!-- MASTHEAD BEGINS -->
      <!-- <button class="bg-blue-600 text-white px-6 py-2 rounded-lg shadow hover:bg-blue-700 transition">Get Started</button> -->
    <header class="masthead">

      <div class="container">

        <div class="row animate-fade-in-up">

          <div class="col-lg-6 col-md-4">

            <div class="masthead-subheading text-uppercase">Toksmail Travel and Tours</div>
            <div class="masthead-heading">Travel, enjoy and live a new full life</div>
            <p class="text-lg slogan">Book unforgettable journeys to breathtaking destinations.</p>
            <a href="#subscription" class="btn btn-warning btn-xl"> Find out more</a>
          
          </div>

          <div class="col-lg-2"></div>

        </div>
              
      </div>

    </header>
<!-- MASTHEAD ENDS -->


<!-- POPULAR DESTINATIONS -->
    <div id="destinations" class=" destinations p-10 container gap-6">

      <h6 class="text-center text-uppercase py-4 px-3"> popular destinations </h6>

      <div class="row align-items-center justify-content-evenly">

        <div class="card col-lg-3 col-md-3">
          <img src="../assets/london.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h6 class="text-xl font-bold">London, UK</h6>
            <p class="card-text"> <i class="fa fa-location-arrow"></i> 12 days trip </p>
          </div>
        </div>

        <div class="card dest col-lg-3 col-md-3">
          <img src="../assets/rome.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h6 class="text-xl font-bold">Rome, Italy</h6>
            <p class="card-text"> <i class="fa fa-location-arrow"></i> 10 days trip</p>
          </div>
        </div>

        <div class="card col-lg-3 col-md-3">
          <img src="../assets/europe.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h6 class="text-xl font-bold">European Tour</h6>
            <p class="card-text"> <i class="fa fa-location-arrow"></i> 28 days trip </p>
          </div>
        </div>

      </div>
          
    </div>


<!-- PARTNERS -->
    <div class="container partners">

      <div class="row px-3 py-3">

        <div class="col-2">
          <img src="../assets/delta.jpg" alt="">
        </div>

        <div class="col-2">
          <img src="../assets/airCanada.jpg" alt="">
        </div>

        <div class="col-2">
          <img src="../assets/haiwaiin.jpg" alt="">
        </div>

        <div class="col-2">
          <img src="../assets/airfrance.jpg" alt="">
        </div>

        <div class="col-2">
          <img src="../assets/southwest.jpg" alt="">
        </div>

        <div class="col-2">
          <img src="../assets/lufthansa.jpg" alt="">
        </div>

      </div>

    </div>


<!-- GUIDING STEPS -->
  <div class="container guide" id="guide">
  
    <div class="row justify-content-around align-items-center px-2 py-2">

      <div class="col-lg-6 col-md-6">

      <h5> Easy and fast </h5>
      <h3>Book your next trip in 3 easy steps
      </h3><br>
      <div class="col-lg-6 col-md-6 py-3">
        <h6> <i class="fa fa-check-square fa-xl"></i> Choose Destination </h6>
        <p class="text-center "> Choose your prefererred destination. This could be anywhere in the world. </p>
      </div>
      <div class="py-3">
        <h6><i class="bi bi-credit-card-2-front-fill fa-xl"></i> Make Payment </h6>
        <p class="text-center"> Make payment for that travel plan to the designated bank account provided by your travel agent. </p>
      </div>
      <div class="py-3">
        <h6> <i class="bi bi-airplane-engines-fill fa-xl"></i> Reach Airport on Selected Date </h6>
        <p class="text-center"> Be sure to arrive at the airport early on the selected date for your trip</p>
      </div>  
    </div>
    <div class="col-lg-4 col-md-4">
      <img src="../assets/guide.jpg" alt="guide">
    </div>
  </div>
 </div>


<!-- TESTIMONIALS -->
  <div id="testimonials" class="container p-10 animate-fade-in-up">

    <div class="row align-items-center">

      <h6 class="text-uppercase py-4 px-3"> testimonials </h6>

      <div class="col-lg-5 col-md-5">
        <h1> What people say about Us</h1>
      </div>

      <div id="carouselExampleInterval" class="col-lg-6 col-md-6 carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active" data-bs-interval="3000">
            <img src="https://cdn.mos.cms.futurecdn.net/THCiUmVZcgxHodGCK3EyYo-970-80.jpg.webp" class="d-block thumbnail" alt="...">
            <p>"Our trip to Bali was magical! Everything was perfectly organized. Highly recommended!"</p>
            <p>Amanda L.</p>
          </div>
          <div class="carousel-item transition-transform duration-700 ease-in-out" data-bs-interval="2000">
            <img src="https://asamnews.com/wp-content/uploads/2019/02/thispersondoesnotexist.com_.jpg" class="d-block" alt="...">
            <p>"Professional service, amazing destinations. I will definitely travel with them again."</p>
            <p>Hailey</p>
          </div>
          <div class="carousel-item">
            <img src="https://mymodernmet.com/wp/wp-content/uploads/2019/09/100k-ai-faces-7.jpg" class="d-block" alt="...">
            <p>"Thanks to Toksmail Tavels and Tour, my honeymoon in Paris was unforgettable!"</p>
            <p> Ademide </p>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </div>
  </div>


<!-- EMAIL SUBSCRIPTION -->
    <div class="subs py-5 my-5">
      <div class="container">
        <div id="subscription" class="subscription p-10 text-center animate-fade-in-up py-3 ">

          <p class="py-4"> Subscribe to get information, latest news and other interesting offers about Toksmail</p>

          <form class="row g-3 justify-content-center">
            <div class="col-10 px-3">
              <label for="inputEmail" class="visually-hidden">Email</label>
              <input type="email" class="form-control" id="inputEmail" placeholder="Your Email">
            </div>
            <div class="col-auto">
              <button type="submit" class="btn btn-danger mb-3">Subscribe</button>
            </div>
          </form>
        </div>
      </div>
    </div>

<!-- FOOTER -->
    <footer class="container text-center p-4">

      <div class="row align-items-center justify-content-around">

        <div class="col-4">
          <h5>Toksmail Travels and tours</h5>
        </div>

        <div class="col-8">
            <h6> Contact Us</h6>
            <a href="#" class="btn" target="blank"> <h6><i class="bi bi-whatsapp"></i> Whatsapp</h6> </a>
            <a href="#" class="btn" target="blank"> <h6><i class="bi bi-envelope"></i> Gmail</h6> </a>
            <a href="#" class="btn" target="blank"> <h6><i class="bi bi-envelope"></i> Whatsapp</h6> </a>
            <!-- <h6><i class="bi bi-whatsapp"></i> Whatsapp</h6> -->
            <!-- <h6><i class="bi bi-envelope"></i> Gmail</h6> -->
            <!-- <h6><i class="bi bi-envelope"></i> Yahoo</h6> -->
            <!-- <span>Company</span> -->
        </div>

        <div class="col">
          <!-- <h5>Toksmail Travels and tours</h5> -->
        </div>

      </div>

        <p>&copy; 2025 Toksmail Travels and Tour. All rights reserved.</p>

    </footer>


  </section>
</template>

<script>
export default {
  name: 'LandingPage',
  props: {
    msg: String
  },
}
</script>