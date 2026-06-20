<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Neddy Shot It | Portfolio</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background: #0f0f0f;
  color: white;
}

/* NAVBAR */
nav {
  display: flex;
  justify-content: space-between;
  padding: 20px 60px;
  background: #111;
  position: sticky;
  top: 0;
}


nav a {
  color: gold;
  margin-left: 20px;
  text-decoration: none;
}

/* HERO */
.hero {
  height: 90vh;
  background: url('Screenshot_20260620_114830_Gallery.jpg') center/cover;
  display: flex;
  align-items: center;
  padding: 60px;
}

.hero-text {
  background: rgba(0,0,0,0.6);
  padding: 30px;
  max-width: 500px;
}

.hero-text h2 {
  font-size: 40px;
  color: gold;
}

.btn {
  display: inline-block;
  margin-top: 15px;
  padding: 10px 20px;
  background: gold;
  color: black;
  text-decoration: none;
  font-weight: bold;
}

/* SECTIONS */
section {
  padding: 60px;
}

h2.section-title {
  color: gold;
  margin-bottom: 20px;
}

/* SERVICES */
.services {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
}

.card {
  background: #1a1a1a;
  padding: 20px;
  border-radius: 10px;
}

/* GALLERY */
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 15px;
}

.gallery img {
  width: 100%;
  border-radius: 10px;
}

/* CONTACT */
.contact {
  background: #111;
  padding: 40px;
  text-align: center;
}

footer {
  text-align: center;
  padding: 20px;
  background: #000;
}

.logo {
  width: 150px;   /* adjust size */
  height: 100PX;
}
</style>
</head>

<body>

<nav>
 <img src="C:/Users/buabe/OneDrive/Documents/my html projects/ChatGPT Image Jun 20, 2026, 10_31_56 AM vvv.png" alt="NEDDY SHOT IT" class="logo">
  <div>
    <a href="#">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<!-- HERO -->
<div class="hero">
  <div class="hero-text">
    <h2>Visual Storyteller</h2>
    <p>I capture real moments and turn them into timeless visuals.</p>
    <a href="#portfolio" class="btn">View Portfolio</a>
  </div>
</div>

<!-- ABOUT -->
<section id="about">
  <h2 class="section-title">About Me</h2>
  <p>
    Behind the name neddy_shot_it is a young creative who believes every moment has a story worth capturing.

I’m passionate about photography because it allows me to freeze time and turn ordinary moments into something powerful and memorable. From smiles and emotions to light and atmosphere, I focus on the small details that bring a photo to life.

My work is all about storytelling capturing real people, real feelings, and real experiences. With every shot, I aim to create images that speak louder than words and stay in memory long after the moment has passed.
  </p>
</section>

<!-- SERVICES -->
<section id="services">
  <h2 class="section-title">Services</h2>
  <div class="services">
    <div class="card">Portrait Photography</div>
    <div class="card">Event Coverage</div>
    <div class="card">Street Photography</div>
    <div class="card">Photo Editing</div>
  </div>
</section>

<!-- PORTFOLIO -->
<section id="portfolio">
  <h2 class="section-title">Portfolio</h2>
  <div class="gallery">
    <img src="C:/Users/buabe/OneDrive/Documents/my html projects/Screenshot_20260620_114858_Gallery.jpg" />
    <img src="C:/Users/buabe/OneDrive/Documents/my html projects/Screenshot_20260620_114931_Gallery.jpg" />
    <img src="C:/Users/buabe/OneDrive/Documents/my html projects/Screenshot_20260620_114954_Gallery.jpg" />
    <img src="C:/Users/buabe/OneDrive/Documents/my html projects/Screenshot_20260620_115117_Gallery.jpg" />
    <img src="C:/Users/buabe/OneDrive/Documents/my html projects/Screenshot_20260620_115046_Gallery.jpg" />
    <img src="C:/Users/buabe/OneDrive/Documents/my html projects/Screenshot_20260620_115018_Gallery.jpg" />
  </div>
</section>

<!-- CONTACT -->
<section id="contact" class="contact">
  <h2 class="section-title">Contact Me</h2>
  <p>Email: buabengkonaduedward80@gmail.com</p>
  <p>WhatsApp: +233 530 76 8943</p>
  <p>Instagram: @neddy_shot_it</p>
</section>

<footer>
  © 2026 Neddy_Shot_It. All Rights Reserved.
</footer>

</body>
</html>
