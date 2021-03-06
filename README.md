<!DOCTYPE html>
<html lang="fr">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Portfolie épreuve E6</title>
  <!-- <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css"> -->
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.3.1/css/all.css"
    integrity="sha384-mzrmE5qonljUremFsqc01SB46JvROS7bZs3IO2EmfFsd15uHvIt+Y8vEf7N7fWAU" crossorigin="anonymous">
  <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,400,700" rel="stylesheet">
  <!-- Bulma Version 0.7.1-->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bulma/0.7.1/css/bulma.min.css" />
  <!-- <link href="https://unpkg.com/bulma-fluent@0.3.13/css/bulma.min.css" rel="stylesheet"> -->
  <link rel="stylesheet" type="text/css" href="css/personal.css">
  <script async type="text/javascript" src="js/bulma.js"></script>
</head>

<body>
  <!-- Navigation bar -->
  <nav class="navbar is-link is-fixed-top">
    <div class="navbar-brand">
      <div class="navbar-burger burger" data-target="navbarExampleTransparentExample">
        <span></span>
        <span></span>
        <span></span>
      </div>
    </div>

    <div id="navbarExampleTransparentExample" class="navbar-menu">
      <div class="navbar-end">
        <a class="navbar-item" href="#about">
          <span class="icon">
            <i class="fas fa-info"></i>
          </span>
          <span>Moi</span>
        </a>
        <a class="navbar-item" href="#portfolio">
          <span class="icon">
            <i class="fas fa-th-list"></i>
          </span>
          <span>Mes projets</span>
        </a>
        <a class="navbar-item" href="#services">
          <span class="icon">
            <i class="fas fa-bars"></i>
          </span>
          <span>Veille technologique</span>
        </a>
      </div>
    </div>
  </nav>

  <!-- Header -->
  <section class="hero is-link is-fullheight is-fullheight-with-navbar">
    <div class="hero-body">
      <div class="container">
        <h1 class="title is-1">
          Portfolio de l'épreuve E6
        </h1>
      </div>
    </div>
  </section>

  <!-- About -->
  <section class="section" id="about">
    <!-- Title -->
    <div class="section-heading">
      <h3 class="title is-2">À propos de Moi</h3>
      <h4 class="subtitle is-5">David De Oliveira</h4>
      <div class="container">
        <p>Etudiant en deuxiéme années de BTS SIO option SLAM.<br>
          Je présente aujourd'hui mon parcours professionnel vécu durant ma formation.
        </p>
      </div>
    </div>

    <div class="columns has-same-height is-gapless">
      <div class="column">
        <!-- Profile picture -->
        <div class="card">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="images/arton105455.png" alt="Placeholder image">
            </figure>
          </div>
        </div>
      </div>

      <div class="column">
        <!-- Skills -->
        <div class="card">
          <div class="card-content skills-content">
            <h3 class="title is-4">Mes compétances</h3>
            <div class="content">

              <article class="media">
                <div class="media-content">
                  <div class="content">
                    <p>
                      <strong>PHP:</strong>
                      <br>
                      <progress class="progress is-primary" value="80" max="100"></progress>
                    </p>
                  </div>
                </div>
              </article>

              <article class="media">
                <div class="media-content">
                  <div class="content">
                    <p>
                      <strong>JavaScript:</strong>
                      <br>
                      <progress class="progress is-primary" value="80" max="100"></progress>
                    </p>
                  </div>
                </div>
              </article>

              <article class="media">
                <div class="media-content">
                  <div class="content">
                    <p>
                      <strong>HTML5/CSS3:</strong>
                      <br>
                      <progress class="progress is-primary" value="75" max="100"></progress>
                    </p>
                  </div>
                </div>
              </article>

              <article class="media">
                <div class="media-content">
                  <div class="content">
                    <p>
                      <strong>Databases:</strong>
                      <br>
                      <progress class="progress is-primary" value="66" max="100"></progress>
                    </p>
                  </div>
                </div>
              </article>

              <article class="media">
                <div class="media-content">
                  <div class="content">
                    <p>
                      <strong>Android:</strong>
                      <br>
                      <progress class="progress is-primary" value="65" max="100"></progress>
                    </p>
                  </div>
                </div>
              </article>
            </div>
          </div>
        </div>
      </div>
    </div>
    </div>
  </section>

  <!-- Portfolio -->
  <section class="section" id="portfolio">
    <div class="container">
      <div class="section-heading">
        <h3 class="title is-2">Mes projets</h3>
      </div>
      <br>

      <div class="container portfolio-container">
        <div class="columns">
          <div class="column is-4">

            <div class="card">
              <header class="card-header">
                <p class="card-header-title">
                  <span>GuessWhat</span>
                </p>
              </header>
              <div class="card-content">
                <figure class="image">
                  <img src="images/guesswhat.png">
                </figure>
              </div>
              <footer class="card-footer">
                <a href="" class="card-footer-item">Aperçu</a>
                <a href="https://gitlab.com/david.deoliveira77190/guesswhat" class="card-footer-item">Code Source</a>
              </footer>
            </div>

            <div class="card">
              <header class="card-header">
                <p class="card-header-title">
                  <span>Sparkline</span>
                </p>
              </header>
              <div class="card-content">
                <figure class="image">
                  <img src="images/Spark-line.png">
                </figure>
              </div>
              <footer class="card-footer">
                <a href="" class="card-footer-item">Aperçu</a>
                <a href="https://gitlab.com/david.deoliveira77190/spark-line" class="card-footer-item">Code Source</a>
              </footer>
            </div>

            <div class="card">
              <header class="card-header">
                <p class="card-header-title">
                  <span>Multiplication</span>
                </p>
              </header>
              <div class="card-content">
                <figure class="image">
                  <img src="images/multi^lication.png">
                </figure>
              </div>
              <footer class="card-footer">
                <a href="" class="card-footer-item">Aperçu</a>
                <a href="https://gitlab.com/david.deoliveira77190/table-multiplication" class="card-footer-item">Code
                  Source</a>
              </footer>
            </div>

            <div class="card">
              <header class="card-header">
                <p class="card-header-title">
                  <span>Filmotec</span>
                </p>
              </header>
              <div class="card-content">
                <figure class="image">
                  <img src="images/filmotec.png">
                </figure>
              </div>
              <footer class="card-footer">
                <a href="" class="card-footer-item">Aperçu</a>
                <a href="https://gitlab.com/david.deoliveira77190/filmotec" class="card-footer-item">Code Source</a>
              </footer>
            </div>

            <div class="card">
              <header class="card-header">
                <p class="card-header-title">
                  <span>Le masquede BonoBoh</span>
                </p>
              </header>
              <div class="card-content">
                <figure class="image">
                  <img src="images/LeMasqueDeBonoboh.PNG">
                </figure>
              </div>
              <footer class="card-footer">
                <a href="" class="card-footer-item">Aperçu</a>
                <a href="https://gitlab.com/david.deoliveira77190/masque"
                  class="card-footer-item">Code Source</a>
              </footer>
            </div>
          </div>

          <div class="column is-4">

            <div class="card">
              <header class="card-header">
                <p class="card-header-title">
                  <span>Découvert Android</span>
                </p>
              </header>
              <div class="card-content">
                <figure class="image">
                  <img src="images/Sans titre.png" alt="">
                </figure>
              </div>
              <footer class="card-footer">
                <a href="" class="card-footer-item">Aperçu</a>
                <a href="https://gitlab.com/david.deoliveira77190/decouvert-android" class="card-footer-item">Code
                  Source</a>
              </footer>
            </div>

            <div class="card">
              <header class="card-header">
                <p class="card-header-title">
                  <span>JsonGit</span>
                </p>
              </header>
              <div class="card-content">
                <figure class="image">
                  <img src="images/JsonGit.png">
                </figure>
              </div>
              <footer class="card-footer">
                <a href="" class="card-footer-item">Aperçu</a>
                <a href="https://gitlab.com/david.deoliveira77190/jsongit" class="card-footer-item">Code Source</a>
              </footer>
            </div>

            <div class="card">
              <header class="card-header">
                <p class="card-header-title">
                  <span>FluxRSS</span>
                </p>
              </header>
              <div class="card-content">
                <figure class="image">
                  <img src="images/FluxRSS.png">
                </figure>
              </div>
              <footer class="card-footer">
                <a href="" class="card-footer-item">Aperçu</a>
                <a href="https://gitlab.com/david.deoliveira77190/fluxrss" class="card-footer-item">Code Source</a>
              </footer>
            </div>

            <div class="card">
              <header class="card-header">
                <p class="card-header-title">
                  <span>Pokemon</span>
                </p>
              </header>
              <div class="card-content">
                <figure class="image">
                  <img src="images/Pokemon.png">
                </figure>
              </div>
              <footer class="card-footer">
                <a href="" class="card-footer-item">Aperçu</a>
                <a href="https://gitlab.com/david.deoliveira77190/pokemon" class="card-footer-item">Code Source</a>
              </footer>
            </div>

            <div class="card">
              <header class="card-header">
                <p class="card-header-title">
                  <span>MeteoRest</span>
                </p>
              </header>
              <div class="card-content">
                <figure class="image">
                  <img src="images/MeteoRest.png">
                </figure>
              </div>
              <footer class="card-footer">
                <a href="" class="card-footer-item">Aperçu</a>
                <a href="https://gitlab.com/david.deoliveira77190/meteorest" class="card-footer-item">Code Source</a>
              </footer>
            </div>
          </div>
          <div class="column is-4">

            <div class="card">
              <header class="card-header">
                <p class="card-header-title">
                  <span>WarcraftVoice</span>
                </p>
              </header>
              <div class="card-content">
                <figure class="image">
                  <img src="images/WarcraftVoice.png">
                </figure>
              </div>
              <footer class="card-footer">
                <a href="" class="card-footer-item">Aperçu</a>
                <a href="https://gitlab.com/david.deoliveira77190/warcraftvoice" class="card-footer-item">Code
                  Source</a>
              </footer>
            </div>

            <div class="card">
              <header class="card-header">
                <p class="card-header-title">
                  <span>FilmQuiz</span>
                </p>
              </header>
              <div class="card-content">
                <figure class="image">
                  <img src="images/FilmQuiz.png">
                </figure>
              </div>
              <footer class="card-footer">
                <a href="" class="card-footer-item">Aperçu</a>
                <a href="https://gitlab.com/david.deoliveira77190/filmquiz" class="card-footer-item">Code Source</a>
              </footer>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>


  <section class="section" id="services">
    <div class="section-heading">
      <h3 class="title is-2">Veille technologique</h3>
    </div>
    <div class="container">
      <div class="columns">
        <div class="column">
          <div class="box">
            <div class="content">
              <h4 class="title is-5">Documentation du framework</h4>
              Sur le site officiel j'ai recherche des méthode dans la documentation pour met projets et stages.
            </div>
          </div>
        </div>
        <div class="column">
          <div class="box">
            <div class="content">
              <h4 class="title is-5">Forums</h4>
              Je me suis inscript à plussieurs forums notament pour mon stages de premiers années (forums sur laravel et
              OSM France).
              Un mail m'envoie les nouveaux sujets de discusion tout les vendredi.
            </div>
          </div>
        </div>
      </div>

      <div class="columns">
        <div class="column">
          <div class="box">
            <div class="content">
              <h4 class="title is-5">Formation</h4>
              J'ai suis des formations sur laravel avant mon stage de premier années pour apprendre a utilisé ce
              framework
              aussi qu'une formation openclassroom sur mongoDB et robo 3T pendant mon stage.
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

</body>

</html>
