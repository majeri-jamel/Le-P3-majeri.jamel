<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <script
      src="https://kit.fontawesome.com/7d17636476.js"
      crossorigin="anonymous"
    ></script>
    <link rel="stylesheet" href="style/base.css" />
    <link rel="stylesheet" href="style/homepage.css" />
    <title>Home Page Restaurant</title>
  </head>
  <body>
    <header class="header">
      <h1 class="header__logo">ohmyfood</h1>
    </header>

    <main>
      <section class="local">
        <i class="fas fa-map-marker-alt local__icon"></i>
        <span class="local__text">Paris, Belleville</span>
      </section>

      <section class="hero">
        <h2 class="hero__title">Réservez le menu qui<br />vous convient</h2>
        <p class="hero__subtitle">
          Découvrez des restaurants d'exception, séléctionnés par nos soins
        </p>
        <a class="hero__btn"> Explorer nos restaurants </a>
      </section>

      <section class="tuto">
        <div class="container">
          <h2 class="tuto__title">Fonctionnement</h2>
          <ol class="tuto__steps">
            <li class="tuto__step">
              <i class="tuto__icon fas fa-mobile-alt"></i>
              <span class="text">Choisissez un restaurant</span>
            </li>
            <li class="tuto__step">
              <i class="tuto__icon fas fa-list-ul"></i>
              <span class="text">Composez votre menu</span>
            </li>
            <li class="tuto__step">
              <i class="tuto__icon fas fa-store"></i>
              <span class="text">Dégustez au restaurant</span>
            </li>
          </ol>
        </div>
      </section>

      <section class="restaurants" id="restaurants">
        <div class="container">
          <h2 class="restaurants__title">Restaurants</h2>

          <div class="cards">
            <a class="card" href="./lapalettedugout.html">
              <img
                src="./img/restaurants/jay-wennington-N_Y88TWmGwA-unsplash.jpg"
                alt=""
                class="card__img"
              />
              <span class="card__badge">Nouveau</span>
              <footer class="card__footer">
                <div class="card__content">
                  <h3 class="card__title">La palette du goût</h3>
                  <span class="card__subtitle">Ménilmontant</span>
                </div>
                <div class="menu__btn card__btn">
                  <i
                    class="
                      card__like
                      menu__like menu__like--noBg
                      far
                      fa-heart fa-2x
                    "
                  ></i>
                  <i
                    class="
                      card__like
                      menu__like menu__like--bg
                      fas
                      fa-heart fa-2x
                    "
                  ></i>
                </div>
              </footer>
            </a>

            <a class="card" href="./lanoteenchantee.html">
              <img
                src="./img/restaurants/stil-u2Lp8tXIcjw-unsplash.jpg"
                alt=""
                class="card__img"
              />
              <span class="card__badge">Nouveau</span>
              <footer class="card__footer">
                <div class="card__content">
                  <h3 class="card__title">La note enchantée</h3>
                  <span class="card__subtitle">Charonne</span>
                </div>
                <div class="menu__btn card__btn">
                  <i
                    class="
                      card__like
                      menu__like menu__like--noBg
                      far
                      fa-heart fa-2x
                    "
                  ></i>
                  <i
                    class="
                      card__like
                      menu__like menu__like--bg
                      fas
                      fa-heart fa-2x
                    "
                  ></i>
                </div>
              </footer>
            </a>

            <a class="card" href="./alafrancaise.html">
              <img
                src="./img/restaurants/toa-heftiba-DQKerTsQwi0-unsplash.jpg"
                alt=""
                class="card__img"
              />
              <!-- <span class="card__badge">Nouveau</span> -->
              <footer class="card__footer">
                <div class="card__content">
                  <h3 class="card__title">À la française</h3>
                  <span class="card__subtitle">Cité Rouge</span>
                </div>
                <div class="menu__btn card__btn">
                  <i
                    class="
                      card__like
                      menu__like menu__like--noBg
                      far
                      fa-heart fa-2x
                    "
                  ></i>
                  <i
                    class="
                      card__like
                      menu__like menu__like--bg
                      fas
                      fa-heart fa-2x
                    "
                  ></i>
                </div>
              </footer>
            </a>

            <a class="card" href="./ledelicedessens.html">
              <img
                src="./img/restaurants/louis-hansel-shotsoflouis-qNBGVyOCY8Q-unsplash.jpg"
                alt=""
                class="card__img"
              />
              <!-- <span class="card__badge">Nouveau</span> -->
              <footer class="card__footer">
                <div class="card__content">
                  <h3 class="card__title">Le délice des sens</h3>
                  <span class="card__subtitle">Folie-Méricourt</span>
                </div>
                <div class="menu__btn card__btn">
                  <i
                    class="
                      card__like
                      menu__like menu__like--noBg
                      far
                      fa-heart fa-2x
                    "
                  ></i>
                  <i
                    class="
                      card__like
                      menu__like menu__like--bg
                      fas
                      fa-heart fa-2x
                    "
                  ></i>
                </div>
              </footer>
            </a>
          </div>
        </div>
      </section>
    </main>

    <footer class="footer">
      <div class="container">
        <span class="footer__logo">ohmyfood</span>
        <ul class="footer__list">
          <li class="footer__listElt">
            <a class="footer__link" href="#"
              ><i class="footer__icon fas fa-utensils"></i>Proposer un
              restaurant</a
            >
          </li>
          <li class="footer__listElt">
            <a class="footer__link" href="#"
              ><i class="footer__icon fas fa-hands-helping"></i>Devenir
              partenaire</a
            >
          </li>
          <li class="footer__listElt">
            <a class="footer__link" href="#">Mentions légales</a>
          </li>
          <li class="footer__listElt">
            <a class="footer__link" href="mailto:contact@ohmyfood.com"
              >Contact</a
            >
          </li>
        </ul>
      </div>
    </footer>
  </body>
</html>
