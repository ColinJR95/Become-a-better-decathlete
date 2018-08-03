# Become-a-better-decathlete
#Practice using resposive image and design techniques

<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Track and Field</title>
    <link href="https://fonts.googleapis.com/css?family=Roboto:300,400,500" rel="stylesheet" type="text/css">
    <link rel="stylesheet" type="text/css" href="main.css">
    <link rel="stylesheet" type="text/css" href="responsive.css">
    <link rel="stylesheet" type="text/css" href="final.css">
  </head>
  <body>

    <header class="header">
      <div class="header__inner">
        <img class="header__logo" src="images/city.png" alt="iconic view of a cityscape">
        <h1 class="header__title">
          Become a better decathlete
        </h1>
        <a id="menu" class="header__menu">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
            <path d="M2 6h20v3H2zm0 5h20v3H2zm0 5h20v3H2z"/>
          </svg>
        </a>
      </div>
    </header>

    <nav id="drawer" class="nav">
      <ul class="nav__list">
        <li class="nav__item"><a href="#">News</a></li>
        <li class="nav__item"><a href="#">Events</a></li>
        <li class="nav__item"><a href="#">Culture</a></li>
        <li class="nav__item"><a href="#">Videos</a></li>
      </ul>
    </nav>

    <main>
      <section class="content">
        <section class="hero">
          <article class="description">
            <h2>Ashton Eaton</h2>
            <p>One of the best athletes that has every stepped on the track and field.</p>
          </article>
        </section>

        <section class="news top-news">
          <h2 class="news__title">Click on the events below to learn more <a href="#" class="news__more">+ more</a></h2>
          <ul>
            <li class="top-news__item">
              <a href="#">100m, 200m, 400m event</a>
            </li>
            <li class="top-news__item">
              <a href="#">Hurdle events.</a>
            </li>
            <li class="top-news__item">
              <a href="#">Throwing events.</a>
            </li>
            <li class="top-news__item">
              <a href="#">Jump events.</a>
            </li>
          </ul>
        </section>

        <section class="scores">
          <table class="scores__table">
            <thead>
              <tr>
                <th>date</th>
                <th class="scores__location">location</th>
                <th>team</th>
                <th colspan="2">score</th>
                <th>team</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>Friday</td>
                <td class="scores__location">Brighton</td>
                <td>Bears</td>
                <td>95</td>
                <td class="winner">109</td>
                <td class="winner">Cubs</td>
              </tr>
              <tr>
                <td>Friday</td>
                <td class="scores__location">Worthington</td>
                <td class="winner">Otters</td>
                <td class="winner">3</td>
                <td>1</td>
                <td>Cubs</td>
              </tr>
              <tr>
                <td>Saturday</td>
                <td class="scores__location">Littlehampton</td>
                <td class="winner">Wolves</td>
                <td class="winner">7</td>
                <td>0</td>
                <td>Panthers</td>
              </tr>
              <tr>
                <td>Sunday</td>
                <td class="scores__location">Portslade</td>
                <td>Hawks</td>
                <td>11</td>
                <td class="winner">12</td>
                <td class="winner">Capons</td>
              </tr>
              <tr>
                <td>Sunday</td>
                <td class="scores__location">Hove</td>
                <td class="winner">Stags</td>
                <td class="winner">6</td>
                <td>2</td>
                <td>Foxes</td>
              </tr>
              
            </tbody>
          </table>
        </section>

        <section class="weather">
          <span class="weather__location">Los Angeles, CA</span>
          <span class="weather__desc">Sunny</span>
          <span class="weather__today">
          <img class="weather__today__image" src="images/weather.png" alt="icon of a partially cloudy day"><span class="weather__today__temp">100</span><span class="weather__today__deg">&deg;F</span>
          </span>
          <ul class="weather__next">
            <li class="weather__next__item">
              <span>Mon</span>
              <img class="weather__next__image" src="images/sunny.png" alt="icon of a sunny day">
              <span>100 &deg;F</span>
            </li><li class="weather__next__item">
              <span>Tues</span>
              <img class="weather__next__image" src="images/cloudy.png" alt="icon of a cloudy day">
              <span>100 &deg;F</span>
            </li><li class="weather__next__item">
              <span>Wed</span>
              <img class="weather__next__image" src="images/cloudy.png" alt="icon of a cloudy day">
              <span>100 &deg; F</span>
            </li><li class="weather__next__item">
              <span>Thu</span>
              <img class="weather__next__image" src="images/rain.png" alt="icon of a rainy day">
              <span>100 &deg;F</span>
            </li><li class="weather__next__item">
              <span>Fri</span>
              <img class="weather__next__image" src="images/sunny.png" alt="icon of a sunny day">
              <span>109 &deg;F</span>
            </li>
          </ul>
        </section>

        <section class="news recent-news">
          <h2 class="news__title">Latest news <a href="#" class="news__more">+ more</a></h2>
          <ul>
            <li class="snippet">
              <h3 class="snippet__title"><a href="#">Best runs in history!</a></h3>
              <div class="snippet__thumbnail">
                <img src='http://www.bendbulletin.com/csp/mediapool/sites/dt.common.streams.StreamServer.cls?STREAMOID=QNHs7ytG2VFxyZAeSC_J1M$daE2N3K4ZzOUsqbU5sYt_bBLmBHj3xL5lkOJblrrOWCsjLu883Ygn4B49Lvm9bPe2QeMKQdVeZmXF$9l$4uCZ8QDXhaHEp3rvzXRJFdy0KqPHLoMevcTLo3h8xh70Y6N_U_CryOsw6FTOdKL_jpQ-&CONTENTTYPE=image/jpeg' alt="picture of a girl with a large, stuffed dog toy">
              </div>
              <p class="snippet__description">Enjoy this video of the best runners in history.
              </p>
            </li>
            <li class="snippet">
              <div class="snippet__thumbnail">
                <img src='https://media.aws.iaaf.org/media/LargeL/fecc703b-8ed7-490c-889f-ba8e17b35d69.jpg?v=-1420779244' alt="picture of a girl with a large, stuffed dog toy">
              </div>
              <h3 class="snippet__title"><a href="#">Best hurdle races in history.</a></h3>
              <p class="snippet__description">This is a playlist of the most memorable hurdle races in history.
              </p>
            </li>
            <li class="snippet">
              <div class="snippet__thumbnail">
                <img src='https://media.aws.iaaf.org/media/LargeL/a204e06d-0f39-4ff1-82ab-43f234dbf5b2.jpg?v=307771568' alt="picture of a girl with a large, stuffed dog toy">
              </div>
              <h3 class="snippet__title"><a href="#">World record throws!</a></h3>
              <p class="snippet__description">Watch the speed of this amazing throw with the discus, shotput hammer and javelin.
              </p>
            </li>
            <li class="snippet">
              <div class="snippet__thumbnail">
                <img src= "https://media.aws.iaaf.org/media/Original/f6f60135-04a2-4276-b070-c96ef25ff96f.png?v=472050767" alt="picture of a girl with a large, stuffed dog toy">
              </div>
              <h3 class="snippet__title"><a href="#">The most intense jumps in history! </a></h3>
              <p class="snippet__description">Sit back and prepared to be mindblown by these record breaking jumps!
              </p>
            </li>
          </ul>
        </section>
      </section>
      <footer>
        <ul>
          <li><a href="#">Contact us</a></li>
          <li><a href="#">Follow us on Twitter</a></li>
          <li><a href="#">RSS</a></li>
        </ul>
      </footer>
    </main>
    <script>
      /*
       * Open the drawer when the menu icon is clicked.
       */
      var menu = document.querySelector('#menu');
      var main = document.querySelector('main');
      var drawer = document.querySelector('.nav');

      menu.addEventListener('click', function(e) {
        drawer.classList.toggle('open');
        e.stopPropagation();
      });
      main.addEventListener('click', function() {
        drawer.classList.remove('open');
      });

    </script>
  </body>
</html>
