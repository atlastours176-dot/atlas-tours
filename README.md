# atlas-tours
Atlas Tours – Where Every Trip Tells a Story.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Atlas Tours - Where Every Trip Tells a Story</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(90deg, #0077cc, #ff6600);
      color: white;
      padding: 20px;
      text-align: center;
    }
    header img {
      max-height: 80px;
    }
    nav {
      background: #333;
      color: white;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      color: #ff6600;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=1600&q=80') no-repeat center center/cover;
      color: white;
      padding: 100px 20px;
      text-align: center;
    }
    .hero h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }
    .section {
      padding: 40px 20px;
      text-align: center;
    }
    .section h2 {
      color: #0077cc;
      margin-bottom: 20px;
    }
    .packages {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      width: 280px;
      padding: 20px;
      transition: 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card h3 {
      color: #ff6600;
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    footer a {
      color: #ff6600;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <header>
    <img src="YOUR-LOGO.png" alt="Atlas Tours Logo">
    <h1>Atlas Tours</h1>
    <p><em>Where Every Trip Tells a Story</em></p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#packages">Packages</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h1>Explore South Africa with Us</h1>
    <p>Affordable trips, unforgettable memories 🌍✨</p>
  </section>

  <section class="section" id="packages">
    <h2>Our Packages</h2>
    <div class="packages">
      <div class="card">
        <h3>Gold Reef City</h3>
        <p>Thrills, rides & history. Perfect for families and friends.</p>
        <p><strong>From R650 pp</strong></p>
      </div>
      <div class="card">
        <h3>Magaliesburg</h3>
        <p>Peaceful getaway in nature’s heart.</p>
        <p><strong>From R500 pp</strong></p>
      </div>
      <div class="card">
        <h3>God’s Window</h3>
        <p>Breathtaking views that you’ll never forget.</p>
        <p><strong>From R1200 pp</strong></p>
      </div>
    </div>
  </section>

  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <p>📞 Call: 072 579 0544</p>
    <p>📱 WhatsApp: 081 544 5981</p>
    <p>📧 Email: atlastours156@gmail.com</p>
  </section>

  <footer>
    <p>&copy; 2025 Atlas Tours | Designed with ❤️</p>
    <p><a href="https://github.com">Hosted Free on GitHub Pages</a></p>
  </footer>

</body>
</html>
