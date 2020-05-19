<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./css/style.css" />
    <link
      href="https://fonts.googleapis.com/css2?family=Lato:wght@400;700;900&display=swap"
      rel="stylesheet"
    />
    <title>Document</title>
  </head>
  <body>
    <header id="header" class="header">
      <div class="emblem">
        <img
          class="emblem-img"
          id="header-img"
          src="https://s3.amazonaws.com/freecodecamp/original_trombones.png"
          alt="original trombones emblem"
        />
      </div>

      <nav class="navigation" id="nav-bar">
        <ul>
          <li><a class="nav-link" href="#features">Features</a></li>
          <li><a class="nav-link" href="#video">How it works</a></li>
          <li><a class="nav-link" href="#pricing">Pricing</a></li>
        </ul>
      </nav>
    </header>
    <div class="container">
      <!--find section-->
      <section class="section-find">
        <h2 class="find-title">Handcrafted, home-made masterpieces</h2>
        <form id="form" class="form" action="https://www.freecodecamp.com/email-submit">
          <input
            class="email-block"
            type="email"
            name="email"
            id="email"
            placeholder="Enter your email adress"
          />
          <input id="submit" type="submit" class="button" value="GET STARTED" />
        </form>
      </section>
      <!--/find section-->

      <!--features section-->
      <section id="features" class="features">
        <div class="features-items">
          <div class="icon">
            <i class="fa fa-3x fa-fire"></i>
          </div>
          <div class="features-text">
            <h2>Premium Materials</h2>
            <p>
              Our trombones use the shiniest brass which is sourced locally. This will increase the
              longevity of your purchase.
            </p>
          </div>
        </div>

        <div class="features-items">
          <div class="icon">
            <i class="fa fa-3x fa-truck"></i>
          </div>
          <div class="features-text">
            <h2>Fast Shipping</h2>
            <p>
              We make sure you recieve your trombone as soon as we have finished making it. We also
              provide free returns if you are not satisfied.
            </p>
          </div>
        </div>
        <div class="features-items">
          <div class="icon">
            <i class="fa fa-3x fa-battery-full"></i>
          </div>
          <div class="features-text">
            <h2>Quality Assurance</h2>
            <p>
              For every purchase you make, we will ensure there are no damages or faults and we will
              check and test the pitch of your instrument.
            </p>
          </div>
        </div>
      </section>
      <!--/features section-->

      <!--video section-->
      <section class="video">
        <iframe
          id="video"
          width="560"
          height="315"
          src="https://www.youtube.com/embed/EaPmysTfVFI"
          frameborder="0"
          allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </section>
      <!--/video section-->

      <!--Price section-->
      <section id="pricing" class="pricing">
        <div class="card">
          <div class="card-footer">
            <h3>TENOR TROMBONE</h3>
          </div>
          <div class="card-body">
            <div class="card-price"><span>$600</span></div>
            <ol class="car-list">
              <li>Lorem ipsum.</li>
              <li>Lorem ipsum.</li>
              <li>Lorem ipsum dolor.</li>
              <li>Lorem ipsum.</li>
            </ol>
            <button class="card-button">SELECT</button>
          </div>
        </div>
        <div class="card">
          <div class="card-footer">
            <h3>BASS TROMBONE</h3>
          </div>
          <div class="card-body">
            <div class="card-price"><span>$900</span></div>
            <ol class="car-list">
              <li>Lorem ipsum.</li>
              <li>Lorem ipsum.</li>
              <li>Lorem ipsum dolor.</li>
              <li>Lorem ipsum.</li>
            </ol>
            <button class="card-button">SELECT</button>
          </div>
        </div>
        <div class="card">
          <div class="card-footer">
            <h3>VALVE TROMBONE</h3>
          </div>
          <div class="card-body">
            <div class="card-price"><span>$1200</span></div>
            <ol class="car-list">
              <li>Lorem ipsum.</li>
              <li>Lorem ipsum.</li>
              <li>Lorem ipsum dolor.</li>
              <li>Lorem ipsum.</li>
            </ol>
            <button class="card-button">SELECT</button>
          </div>
        </div>
      </section>
      <!--/Price section end-->
    </div>
    <footer class="footer">
      <div class="footer-info">
        <ul class="footer-list">
          <li><a href="#">Privacy</a></li>
          <li><a href="#">Terms</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
        <span class="copyright">Copyright 2016, Original Trombones</span>
      </div>
    </footer>
  </body>
  <script src="https://kit.fontawesome.com/e8a22e890f.js" crossorigin="anonymous"></script>
</html>
