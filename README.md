<!DOCTYPE HTML>
<html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    .parent {
display: flex;
}
 header{
    position: fixed;
  }
  @media (max-width: 600px) {
  body {
    background-color: lightblue;
  }
}
</style>
  <script src="https://kit.fontawesome.com/9650a62e47.js" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="css/style.css">
  <title>Product Landing Page - freecodecamp</title>
</head>
<body>
  <header id="header">
   <img id="header-img" src="https://s3.amazonaws.com/freecodecamp/original_trombones.png" alt="logo" class="logo">
   <nav id="nav-bar">
     <ul>
        <a class="nav-link" href="#features">Features</a>
        <a class="nav-link" href="#how-it-work">How It Works</a>
        <a class="nav-link" href="#pricing">Pricing</a>
    </nav>
  </header>

  <div id="container">
    <section class="message-box">
      <h1>Handcrafted, home-made masterpieces</h1>
      <form id="form" action="https://www.freecodecamp.com/email-submit">
      <input id="email" type="email" name="email" placeholder="example@mail.com">
      <input id="submit" type="submit" value="Get Started" class="btn"></input>
      </form>
    </section>

    <section id="features">
      <div class="feature">
        <i class="fab fa-free-code-camp fa-3x"></i>
        <div>
          <h2>Premium Materials</h2>
          <p>Our trombones use the shiniest brass which is sourced locally. This will increase the longevity of your
            purchase.</p>
        </div>
      </div>
      <div class="feature">
        <i class="fas fa-shipping-fast fa-3x"></i>
        <div>
          <h2>Fast Shipping</h2>
          <p>We make sure you receive your trombone as soon as we have finished making it. We also provide free returns
            if you are not satisfied.</p>
        </div>
      </div>
      <div class="feature">
        <i class="fas fa-battery-full fa-3x"></i>
        <div>
          <h2>Quality Assurance</h2>
          <p>For every purchase you make, we will ensure there are no damages or faults and we will check and test the
            pitch of your instrument.</p>
        </div>
      </div>
    </section>
    <section id="how-it-work">
      <iframe id="video" src="https://youtu.be/y8Yv4pnO7qc"></iframe>
    </section>
    <section id="pricing">
      <div class="price-box">
        <h3>TENOR TROMBONE</h3>
        <h2>$600</h2>
        <p>Lorem ipsum.
          Lorem ipsum.
          Lorem ipsum dolor.
          Lorem ipsum.</p>
        <a href="#" class="btn">SELECT</a>
      </div>
      <div class="price-box">
        <h3>BASS TROMBONE</h3>
        <h2>$900</h2>
        <p>Lorem ipsum.
          Lorem ipsum.
          Lorem ipsum dolor.
          Lorem ipsum.</p>
        <a href="#" class="btn">SELECT</a>
      </div>
      <div class="price-box">
        <h3>VALVE TROMBONE</h3>
        <h2>$1200</h2>
        <p>Lorem ipsum.
          Lorem ipsum.
          Lorem ipsum dolor.
          Lorem ipsum.</p>
        <a href="#" class="btn">SELECT</a>
      </div>
    </section>
  </div>
  <footer id="main-footer">
    <div>
      <a href="#">Privacy</a>
      <a href="#">Terms</a>
      <a href="#">Contact</a>
    </div>
    <p class="my-name">This Page recreated by AHMARI FERREIRA<a target="_blank" id="fcs" href="https://product-landing-page.freecodecamp.rocks/"></a></p>
    <p>&copy;Copyright 2016, Original Trombones</p>
  </footer>
</body>
<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
</html>
