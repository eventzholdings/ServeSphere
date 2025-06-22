<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ServeSphere Canteen</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #fff8e1;
      color: #333;
    }

    header {
      background-color: #00796b;
      color: white;
      padding: 1rem 2rem;
      text-align: center;
    }

    nav {
      background-color: #004d40;
      text-align: center;
      padding: 0.5rem;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      color: #00796b;
      margin-top: 0;
    }

    .gallery img {
      width: 100%;
      max-width: 300px;
      border-radius: 12px;
      margin: 1rem;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    footer {
      background-color: #f57c00;
      color: white;
      text-align: center;
      padding: 1rem;
    }

    .logo {
      height: 40px;
      vertical-align: middle;
    }

    .flex {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
  </style>
</head>
<body>

  <header>
    <h1>ServeSphere Canteen</h1>
    <p>Wholesome, Fresh, Delicious</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Us</h2>
    <p>ServeSphere Canteen is your trusted in-house dining destination dedicated to providing wholesome, freshly prepared meals with a focus on nutrition, taste, and convenience.</p>
  </section>

  <section>
    <h2>Mission & Vision</h2>
    <p><strong>Mission:</strong> To serve healthy, delicious, and affordable meals in a welcoming environment while ensuring the highest standards of hygiene, sustainability, and service excellence.</p>
    <p><strong>Vision:</strong> To become the most trusted and innovative canteen service in the region, setting benchmarks in taste, nutrition, and customer satisfaction.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li>Daily meals (breakfast, lunch, snacks)</li>
      <li>Customizable meal plans</li>
      <li>Catering for events</li>
      <li>Vegetarian & allergy-conscious menus</li>
      <li>Takeaway and dine-in options</li>
    </ul>
  </section>

  <section id="gallery">
    <h2>Gallery</h2>
    <div class="flex gallery">
      <img src="https://source.unsplash.com/300x200/?healthy-food" alt="Healthy Dish">
      <img src="https://source.unsplash.com/300x200/?canteen-lunch" alt="Lunch Plate">
      <img src="https://source.unsplash.com/300x200/?vegan-food" alt="Vegan Meal">
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p><strong>Location:</strong> Home, 8th Road, Rynfield AH, Benoni</p>
    <p><strong>Email:</strong> <a href="mailto:servesphere@gmail.com">servesphere@gmail.com</a></p>
    <p><strong>Phone:</strong> <a href="tel:+27780613117">078 061 3117</a></p>
    <p><strong>Website:</strong> www.servesphere/canteen.com</p>
  </section>

  <footer>
    <img src="logo.png" alt="ServeSphere Logo" class="logo" /> <br/>
    &copy; 2025 ServeSphere Canteen. All rights reserved.
  </footer>

</body>
</html>
