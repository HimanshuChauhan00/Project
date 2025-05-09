<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Coffee Haven</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="container">
      <h1 class="logo">☕ Coffee Haven</h1>
      <nav>
        <a href="#home">Home</a>
        <a href="#menu">Menu</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <section id="home" class="hero">
    <div class="container">
      <h2>Freshly Brewed Happiness</h2>
      <p>Come for the coffee, stay for the atmosphere.</p>
      <a href="#menu" class="btn">View Menu</a>
    </div>
  </section>

  <section id="menu" class="menu container">
    <h2>Our Menu</h2>
    <div class="grid">
      <div class="card">
        <img src="images/Expresso.jpeg" alt="Espresso">
        <h3>Espresso</h3>
        <p>Strong and bold, perfect for true coffee lovers.</p>
      </div>
      <div class="card">
        <img src="images/latte.jpg" alt="Latte">
        <h3>Latte</h3>
        <p>Velvety steamed milk with smooth espresso.</p>
      </div>
      <div class="card">
        <img src="images/Cappuccino.jpg" alt="Cappuccino">
        <h3>Cappuccino</h3>
        <p>Classic frothy perfection, topped with cocoa.</p>
      </div>
      <div class="card">
        <img src="images/Mocha.jpg" alt="Mocha">
        <h3>Mocha</h3>
        <p>Espresso meets chocolate in this rich, smooth drink.</p>
      </div>
      <div class="card">
        <img src="images/coldbrew.jpeg" alt="Cold Brew">
        <h3>Cold Brew</h3>
        <p>Slow-steeped for 12 hours, smooth and refreshing.</p>
      </div>
      <div class="card">
        <img src="images/Macchiato.png" alt="Macchiato">
        <h3>Macchiato</h3>
        <p>Espresso topped with a dollop of milk foam.</p>
      </div>
    </div>
  </section>
  

  <section id="about" class="about container">
    <h2>About Us</h2>
    <div class="about-content">
      <img src="images/Coffeeshopinterior.jpg" alt="Coffee Shop Interior">
      <div class="about-text">
        <p>
          Coffee Haven is a cozy spot in the heart of the city, offering premium coffee, fresh pastries, and a relaxing atmosphere.
          Whether you're grabbing a cup on the go or catching up with friends, we're here to serve you comfort in every cup.
        </p>
      </div>
    </div>
  </section>
  

  <section id="contact" class="contact container">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Coffee Haven. Crafted with ☕ + ❤️.</p>
  </footer>
</body>
</html>
