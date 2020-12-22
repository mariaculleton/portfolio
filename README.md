<!DOCTYPE html>
<html lang="en" >
<head>
  <meta charset="UTF-8">
  <title>Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1"><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/5.0.0/normalize.min.css">
<link rel='stylesheet' href='https://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/css/bootstrap.min.css'>
<link rel='stylesheet' href='https://fonts.googleapis.com/css?family=Open+Sans:400,300,700'>
<link rel='stylesheet' href='https://maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css'><link rel="stylesheet" href="./style.css">

</head>
<body>
<!-- partial:index.partial.html -->
<div class="wrapper">
  <header role="header">
    <nav class="navbar navbar-default navbar-fixed-top" role="navigation">
      <div class="container">
        <div class="navbar-header">
          <button class="navbar-toggle collapsed" type="button" data-toggle="collapse" data-target=".navbar-collapse" role="button">
            <span class="sr-only">Toggle Navigation</span>
            
            <span class="icon-bar"></span>
            
            <span class="icon-bar"></span>
            
            <span class="icon-bar"></span>
          </button>

          <a href="#" class="navbar-brand">Maria</a>
        </div>

        <div class="collapse navbar-collapse">
          <ul class="nav navbar-nav navbar-right js-nav">
            <li><a href="#home">Home</a></li>

            <li><a href="#about">About</a></li>

            <li><a href="#services">Services</a></li>

            <li><a href="#folio">Gallery</a></li>

            <li><a href="#testimonials">Testimonials</a></li>

            <li><a href="#contact">Contact</a></li>

            <li><a href="https://mariaculleton.tumblr.com/" target="_blank">Blog</a></li>
          </ul>
        </div>
      </div>
    </nav>
  </header>

  <section id="home" class="sec-main">
    <h1 class="main-heading">Maria Culleton.</h1>
  </section>

  <section id="about" class="sec-about">
    <div class="container">
      <h1>About me</h1>

      <hr />

      <div class="row">
        <div class="col-sm-6 col-sm-offset-3">
          <p>Hi, my name is Maria Culleton and I am an artist based in Leek, Staffordshire. I love painting animals in a realistic style using acrylics. If you want to hire me or just to talk, <a class="js-connect" href="#footer">connect</a> with me.</p>
        </div>
      </div>
    </div>
  </section>
  <section id="services" class="sec-services">
    <div class="container">
      <h1>Services</h1>

      <hr />

      <div class="row">
        <div class="col-sm-4">
          <i class="fa fa-4x fa-paint-brush"></i>

          <h2 class="h3">Detailed brush strokes</h2>

          <p>Every animal and painting has unique fur textures and directions, which can be customised to a particular environment you would like your subject to be in.</p>
        </div>

        <div class="col-sm-4">
          <i class="fa fa-4x fa-code"></i>

          <h2 class="h3">Clean Code</h2>

          <p>All websites are written in valid and clean HTML5 / CSS3 &amp; JavaScript (jQuery).</p>
        </div>

        <div class="col-sm-4">
          <i class="fa fa-4x fa-tablet"></i>

          <h2 class="h3">Quick response</h2>

          <p>All messages and emails will be responded to ASAP</p>
        </div>
      </div>
    </div>
  </section>

  <section id="folio" class="sec-folio">
    <div class="container">
      <h1>Previous Work</h1>

      <hr />

      <div class="row">
        <div class="col-md-4">
          <img class="center-block" src="Cockatoo.jpeg" alt="Cockatoo" />
        </div>

        <div class="col-md-4">
          <img class="center-block" src="Edward.jpeg" alt="Winter Stag" />
        </div>

        <div class="col-md-4">
          <img class="center-block" src="Ernie.jpg" alt="Ernie" />
        </div>
      </div>

      <div class="row">
        <div class="col-md-4">
          <img class="center-block" src="Cat.jpeg" alt="Cat" />
        </div>

        <div class="col-md-4">
          <img class="center-block" src="Ray.jpg" alt="Winstone" />
        </div>

        <div class="col-md-4">
          <img class="center-block" src="Romeo.jpg" alt="Romeo" />
        </div>
      </div>
    </div>
  </section>

  <section id="testimonials" class="sec-testimonials">
    <div class="container">
      <h1>Clients said</h1>

      <hr />

      <div class="row">
        <div class="col-sm-4">
          <p class="text-center">"Shes such a bully"</p>

          <p class="text-right">&mdash; Sian Jones</p>
        </div>

        <div class="col-sm-4">
          <p class="text-center">"She put her bag down in a mean way"</p>

          <p class="text-right">&mdash; Emilia Good</p>
        </div>

        <div class="col-sm-4">
          <p class="text-center">"um....im going to turn everyone against her"</p>

          <p class="text-right">&mdash; Alex Stanaway</p>
        </div>
      </div>
    </div>
  </section>

  <section id="contact" class="sec-contact">
    <div class="container">
      <h1>Hire me</h1>

      <hr />

      <div class="row">
        <div class="col-sm-4 col-sm-offset-4">
          <form class="center-block" action="#" method="post">
            <div class="form-group">
              <label class="sr-only" for="inputName">Full name</label>

              <input id="inputName" class="form-control" type="text" placeholder="Adam Smith" required />
            </div>

            <div class="form-group">
              <label for="inputMail" class="sr-only">Email Address</label>

              <input id="inputMail" class="form-control" type="email" placeholder="adam.smith@mail.com" required />
            </div>

            <div class="form-group">
              <label for="inputMessage" class="sr-only">Your Message</label>

              <textarea id="inputMessage" class="form-control" name="message" cols="30" rows="8" required></textarea>
            </div>

            <div class="form-group">
              <button class="btn btn-default center-block" type="submit" value="Hire me">Hire me</button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>

  <footer id="footer">
    <div class="container">
      <ul class="soc-media-ul">
        <li>
          <a href="https://twitter.com/mariaculleton" class="fa fa-twitter" target="_blank"></a>
        </li>

        <li>
          <a href="https://www.linkedin.com/in/maria-culleton-942271182/" class="fa fa-linkedin" target="_blank"></a>
        </li>

        <li>
          <a href="mariaculleton@me.com" class="fa fa-envelope"></a>
        </li>
      </ul>
    </div>
  </footer>
</div>
  <script src='https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js'></script>
<script src='https://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/js/bootstrap.min.js'></script><script  src="./script.js"></script>

</body>
</html>
