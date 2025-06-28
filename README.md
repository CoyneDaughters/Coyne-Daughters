<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Coyne Daughters Hauling & Removal Services</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
      color: #333;
    }
    .slideshow {
      position: relative;
      width: 100%;
      height: 400px;
      overflow: hidden;
    }
    .slideshow img {
      position: absolute;
      width: 100%;
      height: 100%;
      object-fit: cover;
      opacity: 0;
      transition: opacity 1s ease-in-out;
    }
    .slideshow img.active {
      opacity: 1;
    }
    header {
      color: #fff;
      text-align: center;
      padding: 20px;
      background-color: #000;
    }
    header img {
      max-width: 200px;
      margin-bottom: 20px;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    header p {
      font-size: 1.2rem;
      margin-top: 10px;
    }
    nav {
      background: #2f855a;
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: 600;
      font-size: 1rem;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      max-width: 1100px;
      margin: 40px auto;
      background: #fff;
      padding: 40px;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    }
    section h2 {
      color: #2f855a;
      margin-bottom: 20px;
    }
    ul {
      padding-left: 20px;
      line-height: 1.8;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }
    .gallery img {
      width: 100%;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    }
    .contact p {
      margin: 10px 0;
    }
    footer {
      text-align: center;
      background: #1a202c;
      color: #aaa;
      padding: 30px 20px;
      font-size: 0.9rem;
    }
    .popup {
      display: none;
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.7);
      justify-content: center;
      align-items: center;
      z-index: 1000;
    }
    .popup-content {
      background: #fff;
      padding: 30px;
      border-radius: 10px;
      text-align: center;
      max-width: 400px;
      width: 90%;
      position: relative;
    }
    .popup-content input,
    .popup-content textarea {
      width: 100%;
      margin: 10px 0;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .popup-content button {
      background: #2f855a;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .close-btn {
      position: absolute;
      top: 10px;
      right: 15px;
      background: none;
      border: none;
      font-size: 20px;
      cursor: pointer;
      color: #333;
    }
  </style>
</head>
<body onload="document.getElementById('popup').style.display='flex'">
  <div class="popup" id="popup">
    <div class="popup-content">
      <button class="close-btn" onclick="document.getElementById('popup').style.display='none'">&times;</button>
      <h2>Request a Free Quote</h2>
      <form action="mailto:removemyjunk@coynedaughters.com" method="post" enctype="text/plain">
        <input type="text" name="Name" placeholder="Your Name" required>
        <input type="email" name="Email" placeholder="Your Email" required>
        <textarea name="Message" placeholder="Tell us what you need..." required></textarea>
        <button type="submit">Submit</button>
      </form>
    </div>
  </div>

  <div class="slideshow">
    <img src="IMG_2209.jpeg" class="active" alt="Landscaping Work 1">
    <img src="F26E15FC-01F1-4B94-9A8F-56BFE91A3D85.jpeg" alt="Landscaping Work 2">
    <img src="IMG_7829.jpeg" alt="Landscaping Work 3">
  </div>

  <header>
    <img src="coyne-logo.png" alt="Coyne Daughters Logo">
    <h1>Coyne Daughters Hauling & Removal Services</h1>
    <p>"We Lift It, Load It, Cut It & You Get It...We Do It All!"</p>
  </header>

  <nav>
    <a href="#junk">Junk Removal</a>
    <a href="#landscaping">Landscaping</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="junk">
    <h2>Junk Removal Division</h2>
    <ul>
      <li>Furniture Removal</li>
      <li>Appliance Pickup</li>
      <li>Property Cleanouts</li>
      <li>Yard Debris Removal</li>
      <li>Garage Cleanouts</li>
      <li>Construction Debris</li>
    </ul>
  </section>

  <section id="landscaping">
    <h2>Landscaping Division</h2>
    <ul>
      <li>Lawn Maintenance</li>
      <li>Mulching & Edging</li>
      <li>Seasonal Cleanup</li>
      <li>Snowplowing</li>
      <li>Sod Installation & Removal</li>
      <li>Weed Removal</li>
      <li>Shrub Planting</li>
      <li>Landscape Design</li>
      <li>Pavers & Hardscaping</li>
      <li>Excavation & Grading</li>
      <li>Trimming & Planting</li>
    </ul>
  </section>

  <section id="gallery">
    <h2>Project Gallery</h2>
    <div class="gallery">
      <img src="gallery1.jpg" alt="Lawn Maintenance">
      <img src="gallery2.jpg" alt="Yard Clean-up">
      <img src="gallery3.jpg" alt="Mulching Project">
    </div>
  </section>

  <section id="contact">
    <h2>Contact & Estimates</h2>
    <div class="contact">
      <p><strong>Phone:</strong> 845-208-5997</p>
      <p><strong>Email:</strong> <a href="mailto:removemyjunk@coynedaughters.com">removemyjunk@coynedaughters.com</a></p>
      <p><strong>Facebook:</strong> <a href="https://www.facebook.com/people/Coyne-Daughters-Hauling-Removal-Services/61575155865544/">Click Here</a></p>
      <p><strong>Yelp:</strong> <a href="https://www.yelp.com/biz/coyne-daughters-hauling-and-removal-services-garnerville">Click Here</a></p>
      <p><strong>Service Area:</strong> Rockland County & Surrounding Areas</p>
    </div>
  </section>

  <footer>
    &copy; 2025 Coyne Daughters Hauling & Removal Services. All rights reserved.
  </footer>

  <script>
    const slides = document.querySelectorAll('.slideshow img');
    let index = 0;

    setInterval(() => {
      slides[index].classList.remove('active');
      index = (index + 1) % slides.length;
      slides[index].classList.add('active');
    }, 4000);
  </script>
</body>
</html>
