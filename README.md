<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>Evolt Photographer</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {margin:0;font-family:Arial, sans-serif;line-height:1.6;}
    header, section {padding:60px 20px;text-align:center;}
    nav {background:#333;color:#fff;padding:15px;}
    nav ul {list-style:none;margin:0;padding:0;display:flex;justify-content:center;}
    nav ul li {margin:0 15px;}
    nav ul li a {color:white;text-decoration:none;}
    .hero {background:url('assets/images/hero.jpg') no-repeat center/cover;color:white;}
    .hero h1 {font-size:48px;}
    .btn {background:#ff4d4d;color:white;padding:10px 20px;text-decoration:none;border-radius:5px;}
    .gallery {display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:10px;}
    .gallery img {width:100%;height:auto;}
    .features {display:flex;flex-wrap:wrap;justify-content:center;}
    .features div {margin:10px;padding:20px;border:1px solid #ddd;border-radius:8px;}
    footer {background:#222;color:#fff;padding:20px;}
  </style>
</head>

<body>
<nav>
  <h2>Evolt Photographer</h2>
  <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">Portfolio</a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</nav>
<header class="hero">
  <h1>Vietnam Photographer</h1>
  <p>Capturing timeless moments</p>
  <a href="#" class="btn">Book a Shoot</a>
</header>

<!-- GALLERY -->
<section>
  <h2>My Portfolio</h2>
  <div class="gallery">
    <img src="assets/images/photo1.jpg">
    <img src="assets/images/photo2.jpg">
    <img src="assets/images/photo3.jpg">
    <img src="assets/images/photo4.jpg">
  </div>
</section>
<section>
  <h2>About Me</h2>
  <p>
    I am a photographer based in Vietnam,
    specializing in lifestyle photography.
  </p>
</section>
<section>
  <h2>Services</h2>
  <div class="features">
    <div>Wedding Photography</div>
    <div>Pre-wedding Shoots</div>
    <div>Travel Photography</div>
    <div>Event Coverage</div>
  </div>
</section>
<section>
  <h2>Get in Touch</h2>
  <p>Email: venerableevolt@email.com</p>
  <p>Phone: 09051234jpqka</p>
</section>

<footer>
  <p>©2026 Evolt Photographer</p>
</footer>

</body>
</html>
