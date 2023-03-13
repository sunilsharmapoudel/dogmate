# DogMate - Platform to find best friends for your dog.

This is a bootstrap based project named "DogMate" which focuses in code readability, modularity and efficiency.

## Table of contents

- [Overview](#overview)
  - [Screenshots](#screenshots)
  - [Links](#links)

- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)
## Overview
### Screenshots

Desktop Screenshot

![Desktop](/images/DogMate-Desktop.png)
Moile Screenshot

![Mobile](/images/Mobile-design.png)

### Links

- Live Site URL: [https://sunilsharmapoudel.github.io/dogmate/](https://sunilsharmapoudel.github.io/qrcomponent/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Bootstrap 5

### What I learned

From this project I learned to combine bootstrap and custom CSS for best result. This project taught me code resualbility and readibility.

```html
    <section id="title">
      <div class="container-fluid">
        <!-- Nav Bar -->
        <nav class="navbar navbar-dark navbar-expand-lg">
          <a class="navbar-brand" href="">tindog</a>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>

          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ms-auto">
              <li class="nav-item">
                <a class="nav-link" href="#footer">Contact</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#pricing">Pricing</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#cta">Download</a>
              </li>
            </ul>
          </div>
        </nav>

        <!-- Title -->
        <div class="row">
          <div class="col-lg-6">
            <h1 class="big-heading">Meet new and interesting dogs nearby.</h1>
            <button
              id="download"
              class="download-button btn btn-lg btn-dark"
              type="button"
            >
              <i class="fa-brands fa-apple"></i> Download
            </button>
            <button
              class="download-button btn btn-lg btn-outline-light"
              type="button"
            >
              <i class="fa-brands fa-google-play"></i> Download
            </button>
          </div>
          <div class="col-lg-6">
            <img
              class="title-img"
              src="images/iphone6.png"
              alt="iphone-mockup"
            />
          </div>
        </div>
      </div>
    </section>

    <!-- Features -->

    <section id="features">
      <div class="features row">
        <div class="col-lg-4">
          <i class="icons fa-solid fa-circle-check"></i>
          <h3 class="feature-title">Easy to use.</h3>
          <p class="feature-subtitle">
            So easy to use, even your dog could do it.
          </p>
        </div>
        <div class="col-lg-4">
          <i class="icons fa-solid fa-bullseye"></i>
          <h3 class="feature-title">Elite Clientele</h3>
          <p class="feature-subtitle">
            We have all the dogs, the greatest dogs.
          </p>
        </div>
        <div class="col-lg-4">
          <i class="icons fa-solid fa-heart"></i>
          <h3 class="feature-title">Guaranteed to work.</h3>
          <p class="feature-subtitle">
            Find the love of your dog's life or your money back.
          </p>
        </div>
      </div>
    </section>

    <!-- Testimonials -->

    <section id="testimonials">
      <div id="testimonials-carousel" class="carousel slide" data-ride="false">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <h2 class="testimonial-text">
              I no longer have to sniff other dogs for love. I've found the
              hottest Corgi on TinDog. Woof.
            </h2>
            <img
              class="testimonials-img"
              src="images/dog-img.jpg"
              alt="dog-profile"
            />
            <em>Pebbles, New York</em>
          </div>
          <div class="carousel-item">
            <h2 class="testimonial-text">
              My dog used to be so lonely, but with TinDog's help, they've found
              the love of their life.
            </h2>
            <img
              class="testimonials-img"
              src="images/lady-img.jpg"
              alt="lady-profile"
            />
            <em>Beverly, Illinois</em>
          </div>
        </div>

        <button
          class="carousel-control-prev"
          type="button"
          data-bs-target="#testimonials-carousel"
          data-bs-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button
          class="carousel-control-next"
          type="button"
          data-bs-target="#testimonials-carousel"
          data-bs-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </section>

    <!-- Press -->

    <section id="press">
      <img class="press-logo" src="images/techcrunch.png" alt="tc-logo" />
      <img class="press-logo" src="images/tnw.png" alt="tnw-logo" />
      <img
        class="press-logo"
        src="images/bizinsider.png"
        alt="biz-insider-logo"
      />
      <img class="press-logo" src="images/mashable.png" alt="mashable-logo" />
    </section>

    <!-- Pricing -->

    <section id="pricing">
      <h2 class="pricing-heading">A Plan for Every Dog's Needs</h2>
      <p>Simple and affordable price plans for your and your dog.</p>

      <div class="row">
        <div class="pricing-col col-lg-4 col-md-6">
          <div class="card">
            <div class="card-header">
              <h3 class="pricing-category">Chihuahua</h3>
            </div>

            <div class="card-body">
              <h2 class="pricingtab-heading">Free</h2>
              <p>5 Matches Per Day</p>
              <p>10 Messages Per Day</p>
              <p>Unlimited App Usage</p>
              <button class="btn btn-lg col-12 btn-outline-dark" type="button">
                Sign Up
              </button>
            </div>
          </div>
        </div>

        <div class="col-lg-4 pricing-col col-md-6">
          <div class="card">
            <div class="card-header">
              <h3 class="pricing-category">Labrador</h3>
            </div>

            <div class="card-body">
              <h2 class="pricingtab-heading">$49 / mo</h2>
              <p>Unlimited Matches</p>
              <p>Unlimited Messages</p>
              <p>Unlimited App Usage</p>
              <button class="btn btn-lg col-12 btn-dark" type="button">
                Sign Up
              </button>
            </div>
          </div>
        </div>

        <div class="col-lg-4 pricing-col">
          <div class="card">
            <div class="card-header">
              <h3 class="pricing-category">Mastiff</h3>
            </div>

            <div class="card-body">
              <h2 class="pricingtab-heading">$99 / mo</h2>
              <p>Pirority Listing</p>
              <p>Unlimited Matches</p>
              <p>Unlimited Messages</p>
              <p>Unlimited App Usage</p>
              <button class="btn btn-lg col-12 btn-dark" type="button">
                Sign Up
              </button>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Call to Action -->

    <section id="cta">
      <h3 class="ct-heading">Find the True Love of Your Dog's Life Today.</h3>
      <button class="ct-btn btn btn-dark btn-lg" type="button">
        <i class="fa-brands fa-apple"></i> Download
      </button>
      <button class="btn btn-light btn-lg" type="button">
        <i class="fa-brands fa-google-play"></i> Download
      </button>
    </section>

    <!-- Footer -->

    <footer id="footer">
      <div class="social">
        <span><i class="fa-brands fa-twitter"></i></span>
        <span><i class="fa-brands fa-facebook"></i></span>
        <span><i class="fa-brands fa-instagram"></i></span>
        <span><i class="fa-solid fa-envelope"></i></span>
      </div>
      <p>© Copyright TinDog</p>
    </footer>

```
```css
body {
    font-family: 'Montserrat', sans-serif;
    text-align: center;
}

h1,h2,h3,h4{
    font-family: 'Montserrat', sans-serif;
}

.big-heading {
    font-weight: 900;
    line-height: 1.5;
} 
 .testimonial-text {
    font-weight: 900;
    font-size: 3rem;
    line-height: 1.5;
 }
 .pricing-heading {
    font-weight: 900;
    font-size: 3rem;
    line-height: 1.5;
 }

 .pricing-category {
    font-weight: 900;
    font-size: 2rem;
 }

 .pricingtab-heading {
    font-weight: 900;
    font-size: 1.5rem;
 }

#title {
    background-color: #ff4c68;
    color: #fff;
    text-align: left;
}

.nav-item {
    text-align: left;
}

.container-fluid {
    padding: 3% 15% 7%;
}

.navbar {
    padding:0 0 6rem;
}

.navbar-brand {
    font-family: 'Ubuntu', sans-serif;
    font-size: 2.5rem;
    font-weight: bold;
}

.nav-item {
    padding: 0 18px;
}

.nav-link {
    font-family: 'Montserrat', sans-serif;;
    font-size: 1.2rem;
    font-weight: lighter;
}

.download-button {
    margin: 5% 3% 5% 0 ;
}

.title-img {
    width: 20%;
    transform: rotate(25deg);
    position: absolute;
    right: 25%;
}

.icons {
    color: #ff4c68;
    font-size: 2.5rem;
}
.icons:hover {
    color: #ff4d90;
}
.features{
    width: 65%;
    margin:2rem auto 2rem auto;
}

.feature-title {
    font-family: 'Montserrat', sans-serif;
    margin: 2rem 0;
}

.feature-subtitle {
    color: #8f8f8f;
}

#features {
    position: relative;
    padding: 5%;
    background-color: #fff;
}

@media (max-width: 1028px) {
    #title {
        text-align: center;
    }
    .title-img {
        position: static;
        transform: rotate(0);
        width: 60%;

    }
}


/* Testimonials*/

#testimonials {
    background-color: #ff4c68;
    color: white;
}
.carousel-item {
    padding: 7% 15%;
}
.testimonials-img {
    width: 10%;
    border-radius: 100%;
    margin: 20px;
}

/* Press Section*/
#press {
    background-color: #ff4c68;
    padding-bottom: 3%;
}

.press-logo {
    width: 15%;
    margin: 20px 20px 50px;
}

/* Pricing */

#pricing {
    padding: 100px;
}

.pricing-col{
    padding: 3% 2%;
}

#cta {
    background-color: #ff4c68;
    padding: 5%;
}

.ct-btn {
    margin-right: 5%;
}

#footer {
    padding: 10% 0 5%;
}

.social > span {
    margin: 0 2% 0% 2%;
}

.ct-heading {
    font-family: 'Montserrat', sans-serif;
    font-weight: 900;
    font-size: 2rem;
    line-height: 1.5;
    padding: 5% 20%;
    color: #fff;
}

#footer > p {
    margin-top: 20px;
}
```

## Author

- Website - [Sunil Sharma](https://github.com/sunilsharmapoudel)
- Facebook - [@mesunilsharmapoudel](https://www.facebook.com/mesunilsharmapoudel)
- Twitter - [@techsunilsharma](https://www.twitter.com/techsunilsharma)

## Acknowledgments
Thanks to Dr. Angela Yu, my instructor who instructed me during her course. She guided me during the course and I followed her approach.