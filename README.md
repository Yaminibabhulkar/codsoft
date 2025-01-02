# codsoft
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sweet Delights Cake Shop</title>
  <style>
    /* General Styles */
    body {
      margin: 0;
      font-family: 'lora', sans-serif;
      color: #333;
      line-height: 1.6;
    }

    h1, h2 {
        font-family: 'Playfair Display', serif;
      margin: 0;
    }

    ul {
      list-style: none;
      margin: 0;
      padding: 0;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    img {
      max-width: 100%;
      border-radius: 5px;
    }

    /* Header */
    .header {
      background: #f89774;
      padding: 10px 10%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      color: rgb(15, 15, 15);
    }

    .header .navbar ul {
      display: flex;
      gap: 20px;
    }

    .header .navbar ul li a {
      font-weight: bold;
      padding: 5px 10px;
      transition: background 0.3s;
    }

    .header .navbar ul li a:hover {
      background: white;
      color: #e8a0a0;
      border-radius: 5px;
    }

    /* Hero Section */
    .hero {
      background: url('landing2.jpg') no-repeat center center/cover;
      color: rgb(7, 7, 7);
      text-align: center;
      padding: 100px 10%;
    }

    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 30px;
    }

    .cta-btn {
      background-color: #98300b;
      padding: 10px 20px;
      color: white;
      font-weight: bold;
      border-radius: 5px;
      transition: background 0.3s;
    }

    .cta-btn:hover {
      background: #91321c;
    }

    /* About Section */
    .about {
      padding: 50px 10%;
      text-align: center;
      background-color: #ffe4b5;
    }

    .about h2 {
      font-size: 2rem;
      margin-bottom: 20px;
    }

    /* Menu Section */
    .menu {
      padding: 50px 10%;
      text-align: center;
      background-color: #f9f9f9;
    }

    .menu h2 {
      font-size: 2rem;
      margin-bottom: 30px;
    }

    .menu-grid {
      display: flex;
      gap: 20px;
      justify-content: center;
      flex-wrap: wrap;
    }

    .menu-item {
      width: 200px;
      background: white;
      border: 1px solid #ddd;
      border-radius: 5px;
      text-align: center;
      padding: 15px;
    }

    .menu-item h3 {
      margin: 15px 0;
    }

    /* Contact Section */
    .contact {
      padding: 50px 10%;
      text-align: center;
      background-color: #4b0303;
      color: white;
    }

    .contact .social-icons a {
      margin: 0 10px;
      font-size: 1.5rem;
      transition: transform 0.3s;
    }

    .contact .social-icons a:hover {
      transform: scale(1.2);
    }

    /* Footer */
    .footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 10px 0;
    }

    /* Responsive Design */
    @media (max-width: 768px) {
      .header {
        flex-direction: column;
        text-align: center;
      }

      .header .navbar ul {
        flex-direction: column;
        gap: 10px;
      }

      .menu-grid {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
  <!-- Header Section -->
  <header class="header">
    <div class="logo">
      <h1>Sweet Delights</h1>
    </div>
    <nav class="navbar">
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#menu">Menu</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero" id="home">
    <div class="hero-text">
      <h1>Welcome to Sweet Delights</h1>
      <p>Delicious, fresh, and beautifully crafted cakes for every occasion.</p>
      <a href="#menu" class="cta-btn">Explore Our Cakes</a>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="about">
    <h2>About Us</h2>
    <p>
      At Sweet Delights, every cake tells a story. From weddings to birthdays, we create edible masterpieces tailored to your taste and style.
      Made with the finest ingredients, our cakes bring joy to every celebration.
    </p>
  </section>

  <!-- Menu Section -->
  <section id="menu" class="menu">
    <h2>Our Menu</h2>
    <div class="menu-grid">
      <div class="menu-item">
        <img src="chocolate cake.jpeg" alt="Chocolate Cake">
        <h3>Chocolate Cake</h3>
        <p>Rich, moist, and decadent.</p>
      </div>
      <div class="menu-item">
        <img src="redvelvet.jpg" alt="Red Velvet Cake">
        <h3>Redvelvet cake</h3>
        <p>Elegant, smooth, and irresistible.</p>
      </div>
      <div class="menu-item">
        <img src="landingpage.jpg" alt="Cheesecake">
        <h3>Cheesecake</h3>
        <p>Creamy and utterly delightful.</p>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>We'd love to hear from you! Whether you have questions or want to place a custom order, reach out to us:</p>
    <p><i class="fa-solid fa-phone"></i> +123 456 7890</p>
    <p><i class="fa-solid fa-envelope"></i> ymini@sweetdelights.com</p>
    <div class="social-icons">
      <a href="#"><i class="fa-brands fa-facebook"></i></a>
      <a href="#"><i class="fa-brands fa-instagram"></i></a>
      <a href="#"><i class="fa-brands fa-twitter"></i></a>
    </div>
  </section>

  <!-- Footer Section -->
  <footer class="footer">
    <p>&copy; 2024 Sweet Delights. All rights reserved.</p>
  </footer>
</body>
</html>
