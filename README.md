<!-- HELLO
-
DevFolio is a minimal, clean, lightweight and fully responsive template for Devlopers!
Created by Anil Seervi.
-
GitHub repo: https://github.com/AnilSeervi/DevFolio
README: https://github.com/AnilSeervi/DevFolio/blob/master/README.md
-
Have fun creating your portfolio on this template!!! -->

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <!-- Title: add your Portfolio websites's title here -->
    <title>Alessandro de Almeida | Developer</title>

    <!-- Add some coding keywords below, Ex: (javascript, yourusername, etc) -->
    <meta name="meuPortifolio" content="AlessandrodeAlmeida, Alessandro, skill" />

    <!-- Improve your SEO by adding a small descrption of you -->
    <meta name="description" content="Alessandro de Almeida | Developer" />

    <!-- Add a your png Logo to the assets folder and change the href attr accordingly  -->
    <link rel="icon" type="image/png" href="./assets/devfolio-logo.png" />

    <!-- Add your primary-theme color for the value of content -->
    <meta name="theme-color" content="#36d1dc" />

    <!-- Open Graph / Facebook -->
    <meta property="og:type" content="https://www.linkedin.com/in/valter-alessandro-de-alameida-d-alvia-agostini-b140a51a7/" />
    <!-- Fill content with the URL of this portfolio you'll host -->
    <meta property="og:url" content="https://devfolio.js.org/" />
    <!-- Fill content with the title of your portfolio(Recommended to use what you put in <title> tag) -->
    <meta property="og:title" content="Alessandro de Almeida | Developer" />
    <!-- Give a short description that'll show up when you/someone shares your portfolio on different platform -->
    <meta property="og:description" content="Made using DevFolio Template" />
    <!-- Add a thumbnail image in assets folder and fill the content attr with URL to that thumbnail 
      so that a thumbnail image of your portfolio is shown while shared on other platform -->
    <meta
      property="og:image"
      content="https://devfolio.js.org/assets/devfolio.png"
    />

    <!-- Twitter -->
    <meta property="twitter:card" content="summary_large_image" />
    <!-- Again fill content attr with the URL of this portfolio you'll host -->
    <meta property="twitter:url" content="https://devfolio.js.org" />
    <!-- Recommended to use the same text used within <title> element -->
    <meta property="twitter:title" content="Alessandro de Almeida | Developer" />
    <!-- short description that shows up while your portfolio is shared -->
    <meta
      property="twitter:description"
      content="Made using DevFolio Template"
    />
    <!-- Fill content with the URL to the thumbnail image that you'll put in the assets folder -->
    <meta
      property="twitter:image"
      content="https://anilseervi.vercel.app/assets/devfolio.png"
    />

    <!-- link tags -->
    <link rel="stylesheet" href="./css/main.css" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
    />
    <script src="./javascript/scrollreveal.min.js"></script>
    <script
      defer
      type="text/javascript"
      src="./javascript/scrollveal.js"
    ></script>

    <!-- Remove Google Analytics once you have your portfolio website set-up -->
    <!-- Global site tag (gtag.js) - Google Analytics -->
    <script
      async
      src="https://www.googletagmanager.com/gtag/js?id=UA-122228201-4"
    ></script>
    <script>
      window.dataLayer = window.dataLayer || [];
      function gtag() {
        dataLayer.push(arguments);
      }
      gtag("js", new Date());

      gtag("config", "UA-122228201-4");
    </script>
    <!-- End of Google Analytics -->
  </head>
  <body>
    <!-- Hero Section -->
    <div id="hero">
      <section class="container">
        <h1 class="hero-title">
          Hi, my name is <span class="text-color-main name">Valter Alessandro de Almeida D'Alvia Agostini</span>
          <br />
          I'm the Developer you need.
        </h1>
        <p class="hero-cta">
          <a class="cta-btn cta-btn--hero" href="#about">Get in touch</a>
        </p>
      </section>
      <a href="#about" class="scroll-down-link" aria-label="scroll-down">
        <div class="scroll-down"></div
      ></a>
    </div>
    <!-- /END Hero Section -->

    <!-- About Section -->
    <section id="about">
      <div class="container">
        <h2 class="section-title">About Me</h2>
        <div class="row about-wrapper">
          <div class="about-wrapper__image">
            <img
              class="img-fluid"
              src="img/myp.jpg"
              alt="Profile Image"
            />
          </div>
          <div class="about-wrapper__info">
            <p class="about-wrapper__info-text">
              Estudo ciência de dados na Univesp e também faço cursos de front-end e back-end. Sou apaixonado por programação e estou muito ancioso pra colocar em prática tudo o que eu aprendi até aqui.
            </p>
            <p class="about-wrapper__info-text">
              I study data science at Univesp and I also take front-end and back-end clases. I love programming and I'm very excited to put into practice everything I've learned so far.
            </p>
            <span class="about-wrapper__cta">
              <a href="#" class="cta-btn cta-btn--resume">View Resume</a>
            </span>
          </div>
        </div>
      </div>
    </section>
    <!-- /END About Section -->

    <!--Projects Section-->
    <section id="projects">
      <div class="container">
        <div class="project-wrapper">
          <h2 class="section-title dark-blue-text">Projects</h2>

          <!-- Each .row is a project -->
          <article class="row">
            <div class="project-wrapper__text">
              <h3 class="project-wrapper__text-title">Finans website</h3>
              <p class="project-wrapper__text-info">
                finance website template made with html5 and bootstrap
              </p>
              <div class="project-wrapper__text-btns">
                <a
                  href="https://github.com/AlessandrodeAlmeida2/finans"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="cta-btn cta-btn--hero cta-btn--projects"
                  >See Live</a
                >
                <a href="https://github.com/AlessandrodeAlmeida2/finans/blob/main/index.html" target="_blank" class="cta-btn text-color-main"
                  >Source Code</a
                >
              </div>
            </div>

            <div class="project-wrapper__image">
              <a href="#" target="_blank" rel="noopener noreferrer">
                <div class="thumbnail rounded">
                  <img
                    src="img/finans.jpg"
                    class="img-fluid"
                    alt="Project Image"
                  />
                </div>
              </a>
            </div>
          </article>
          <!-- /END Project -->

          <!-- Each .row is a project -->
          <article class="row">
            <div class="project-wrapper__text">
              <h3 class="project-wrapper__text-title">Chalé Hotel website</h3>
              <p class="project-wrapper__text-info">
                Hotel website template made with html5 and CSS3.
              </p>
              <div class="project-wrapper__text-btns">
                <a
                  href="https://github.com/AlessandrodeAlmeida2/hotel"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="cta-btn cta-btn--hero cta-btn--projects"
                  >See Live</a
                >
                <a href="https://github.com/AlessandrodeAlmeida2/hotel/blob/main/index.html" target="_blank" class="cta-btn text-color-main"
                  >Source Code</a
                >
              </div>
            </div>

            <div class="project-wrapper__image">
              <a href="#" target="_blank" rel="noopener noreferrer">
                <div class="thumbnail rounded">
                  <img
                    src="img/chale-hotel.jpg"
                    class="img-fluid"
                    alt="Project Image"
                  />
                </div>
              </a>
            </div>
          </article>
          <!-- /END Project -->

          <!-- Each .row is a project -->
          <article class="row">
            <div class="project-wrapper__text">
              <h3 class="project-wrapper__text-title">Museu Nacional website</h3>
              <p class="project-wrapper__text-info">
                Website template made with html and CSS3.
              </p>
              <div class="project-wrapper__text-btns">
                <a
                  href="https://github.com/AlessandrodeAlmeida2/museu"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="cta-btn cta-btn--hero cta-btn--projects"
                  >See Live</a
                >
                <a href="https://github.com/AlessandrodeAlmeida2/museu/blob/main/index.html" target="_blank" class="cta-btn text-color-main"
                  >Source Code</a
                >
              </div>
            </div>

            <div class="project-wrapper__image">
              <a href="#" target="_blank" rel="noopener noreferrer">
                <div class="thumbnail rounded">
                  <img
                    src="img/museu.jpg"
                    class="img-fluid"
                    alt="Project Image"
                  />
                </div>
              </a>
            </div>
          </article>
          <!-- /END Project -->
        </div>
      </div>
    </section>
    <!-- End Projects Section -->

    <!-- Contact Section -->
    <section id="contact">
      <div class="container">
        <h2 class="section-title">Contact</h2>
        <div class="contact-wrapper">
          <p class="contact-wrapper__text">*55 (19) 993000487</p>
          <a href="#" class="cta-btn cta-btn--resume">Call to Action</a>
        </div>
      </div>
    </section>
    <!-- END Contact Section -->

    <!-- Footer Section -->
    <footer class="footer">
      <div class="container">
        <a href="#hero" class="back-to-top" aria-label="go back to top">
          <i class="fa fa-angle-up fa-2x" aria-hidden="true"></i>
        </a>
        <div class="social-links">
          <a
            href="#!"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="twitter"
          >
            <i class="fa fa-twitter"></i>
          </a>
          <a
            href="#!"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="instagram"
          >
            <i class="fa fa-instagram"></i>
          </a>
          <a
            href="https://codepen.io/AlessandrodeAlmeida2"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="codepen"
          >
            <i class="fa fa-codepen"></i>
          </a>
          <a
            href="https://www.linkedin.com/in/valter-alessandro-de-alameida-d-alvia-agostini-b140a51a7/"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="linkedin"
          >
            <i class="fa fa-linkedin"></i>
          </a>
          <a
            href="https://github.com/AlessandrodeAlmeida2"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="github"
          >
            <i class="fa fa-github"></i>
          </a>
        </div>
        <hr />
        <p class="footer__text">
          &copy; <span id="year"></span> - Template by
          <a
            href="https://github.com/AnilSeervi"
            target="_blank"
            rel="noopener noreferrer"
            >Anil Seervi</a
          >. <br />Made with &hearts;
        </p>
      </div>
    </footer>
    <!-- END Footer Section -->

    <script>
      document.getElementById("year").textContent = new Date().getFullYear();
    </script>
    <script src="./javascript/vanilla-tilt.min.js"></script>
    <script type="text/javascript" src="./javascript/valtilt.js"></script>
  </body>
</html>
