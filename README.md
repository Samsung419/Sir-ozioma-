<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sir Ozioma Website Design</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", Arial, sans-serif;
    }

    body {
      background: #f8f9fc;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(90deg, #1a73e8, #0c47a1);
      color: #fff;
      padding: 20px 0;
      text-align: center;
      box-shadow: 0 2px 8px rgba(0,0,0,0.2);
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 5px;
    }

    nav {
      background: #0c47a1;
      display: flex;
      justify-content: center;
      gap: 25px;
      padding: 12px 0;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      position: relative;
    }

    nav a::after {
      content: "";
      display: block;
      width: 0;
      height: 2px;
      background: #ffd700;
      transition: width 0.3s;
      margin: auto;
    }

    nav a:hover::after {
      width: 100%;
    }

    .hero {
      background: url('https://picsum.photos/1200/500?webdesign') no-repeat center/cover;
      color: white;
      text-align: center;
      padding: 120px 20px;
    }

    .hero h2 {
      font-size: 2.8rem;
      margin-bottom: 15px;
      text-shadow: 2px 2px 6px rgba(0,0,0,0.5);
    }

    .btn {
      display: inline-block;
      background: #ffd700;
      color: #000;
      padding: 12px 25px;
      border-radius: 30px;
      font-weight: bold;
      text-decoration: none;
      transition: all 0.3s ease;
    }

    .btn:hover {
      background: #ffae00;
      transform: scale(1.05);
    }

    section {
      padding: 70px 20px;
      max-width: 1100px;
      margin: auto;
    }

    section h2 {
      text-align: center;
      margin-bottom: 20px;
      font-size: 2rem;
      color: #1a73e8;
    }

    /* Team Card */
    .team-container {
      display: flex;
      justify-content: center;
      margin-top: 40px;
    }

    .team-card {
      background: white;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      text-align: center;
      max-width: 300px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .team-card:hover {
      transform: translateY(-10px);
      box-shadow: 0 6px 20px rgba(0,0,0,0.15);
    }

    .team-card img {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.15);
    }

    .team-card h3 {
      margin: 10px 0 5px;
      color: #1a73e8;
    }

    .team-card p {
      font-size: 14px;
      color: #666;
      margin-bottom: 15px;
    }

    .social-icons {
      display: flex;
      justify-content: center;
      gap: 15px;
    }

    .social-icons a {
      color: #1a73e8;
      font-size: 20px;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    .social-icons a:hover {
      color: #ffae00;
    }

    /* Services */
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
      margin-top: 30px;
    }

    .service-box {
      background: white;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      text-align: center;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .service-box:hover {
      transform: translateY(-10px);
      box-shadow: 0 6px 15px rgba(0,0,0,0.15);
    }

    /* Contact */
    .contact-form {
      max-width: 600px;
      margin: auto;
      background: white;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    }

    .contact-form label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
    }

    .contact-form input, 
    .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ddd;
      border-radius: 8px;
      outline: none;
      transition: border 0.3s ease;
    }

    .contact-form input:focus, 
    .contact-form textarea:focus {
      border: 1px solid #1a73e8;
    }

    .contact-form button {
      background: #1a73e8;
      color: white;
      border: none;
      padding: 12px 25px;
      border-radius: 8px;
      cursor: pointer;
      font-weight: bold;
      transition: background 0.3s ease;
    }

    .contact-form button:hover {
      background: #0c47a1;
    }

    footer {
      background: #1a73e8;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Sir Ozioma Website Design</h1>
    <p>Creative • Modern • Professional</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h2>We Build Stunning Websites</h2>
    <p>Professional website design tailored for your brand</p>
    <a href="#contact" class="btn">Get Started</a>
  </section>

  <section id="about">
    <h2>Meet Our Team</h2>
    <div class="team-container">
      <div class="team-card">
        <!-- Replace with your saved image -->
        <img src="your-image.jpg" alt="Sir Ozioma">
        <h3>Sir Ozioma</h3>
        <p>Lead Web Designer</p>
        <div class="social-icons">
          <a href="#"><ion-icon name="logo-facebook"></ion-icon></a>
          <a href="#"><ion-icon name="logo-twitter"></ion-icon></a>
          <a href="#"><ion-icon name="logo-linkedin"></ion-icon></a>
          <a href="#"><ion-icon name="logo-instagram"></ion-icon></a>
        </div>
      </div>
    </div>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="service-box">
        <h3>Website Design</h3>
        <p>Beautiful and responsive websites tailored to your needs.</p>
      </div>
      <div class="service-box">
        <h3>UI/UX Design</h3>
        <p>Clean and user-friendly designs that enhance experience.</p>
      </div>
      <div class="service-box">
        <h3>SEO Optimization</h3>
        <p>Boost your visibility on search engines with our services.</p>
      </div>
      <div class="service-box">
        <h3>Branding</h3>
        <p>We help you create a unique and professional online identity.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <div class="contact-form">
      <form>
        <label for="name">Full Name</label>
        <input type="text" id="name" placeholder="Your Name" required>

        <label for="email">Email Address</label>
        <input type="email" id="email" placeholder="Your Email" required>

        <label for="message">Message</label>
        <textarea id="message" rows="5" placeholder="Your Message" required></textarea>

        <button type="submit">Send Message</button>
      </form>
    </div>
  </section>

  <footer>
    <p>© 2025 Sir Ozioma Website Design. All Rights Reserved.</p>
  </footer>

  <!-- Ionicons for social icons -->
  <script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js"></script>

</body>
</html>
