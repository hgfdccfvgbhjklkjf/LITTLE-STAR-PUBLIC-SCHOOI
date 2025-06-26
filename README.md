<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Little Star Public School - Gadwa, Bahraich</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f0f8ff;
      color: #333;
    }

    header {
      background: #004080;
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    nav {
      background: #003366;
      padding: 10px 0;
      text-align: center;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1577896851231-70ef18881754?fit=crop&w=1050&q=80') no-repeat center center/cover;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 4px #000;
    }

    .hero h1 {
      font-size: 40px;
    }

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }

    .section-title {
      font-size: 28px;
      margin-bottom: 20px;
      color: #004080;
    }

    .facilities ul {
      list-style: square;
      padding-left: 20px;
    }

    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    form button {
      padding: 10px 20px;
      background-color: #004080;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    .gallery img {
      width: 100px;
      height: 100px;
      margin: 5px;
      border-radius: 8px;
    }

    footer {
      background: #004080;
      color: white;
      text-align: center;
      padding: 15px 0;
      margin-top: 30px;
    }

    @media (max-width: 600px) {
      .hero h1 {
        font-size: 28px;
        text-align: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Little Star Public School</h1>
    <p>Gadwa, Bahraich</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#facilities">Facilities</a>
    <a href="#gallery">Gallery</a>
    <a href="#announcements">Announcements</a>
    <a href="#calendar">Calendar</a>
    <a href="#admission">Admission</a>
    <a href="#contact">Contact</a>
    <a href="#admin">Admin</a>
  </nav>

  <div class="hero">
    <h1>Welcome to Little Star Public School</h1>
  </div>

  <section id="about">
    <h2 class="section-title">About Us</h2>
    <p>
      Little Star Public School, located in Gadwa, Bahraich, is a nurturing and progressive institution that focuses on holistic development of students. Our mission is to impart quality education, build character, and create responsible citizens of tomorrow.
    </p>
    <p>
      We blend modern teaching methods with traditional values, helping students to excel academically and socially.
    </p>
  </section>

  <section id="facilities" class="facilities">
    <h2 class="section-title">Our Facilities</h2>
    <ul>
      <li>Smart Classrooms</li>
      <li>Science and Computer Labs</li>
      <li>Library with Digital Resources</li>
      <li>Playground and Sports Activities</li>
      <li>Transport Services</li>
      <li>Experienced and Caring Teachers</li>
    </ul>
  </section>

  <section id="gallery">
    <h2 class="section-title">Photo Gallery</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/100" alt="School Photo 1">
      <img src="https://via.placeholder.com/100" alt="School Photo 2">
      <img src="https://via.placeholder.com/100" alt="School Photo 3">
    </div>
  </section>

  <section id="announcements">
    <h2 class="section-title">Latest Announcements</h2>
    <ul>
      <li>Admissions for 2025-26 session now open.</li>
      <li>Annual Sports Day to be held on 15th August.</li>
      <li>Mid-term exams begin from 10th October.</li>
    </ul>
  </section>

  <section id="calendar">
    <h2 class="section-title">Academic Calendar</h2>
    <p>📅 Coming Soon: A downloadable yearly calendar with holidays and exam dates.</p>
  </section>

  <section id="admission">
    <h2 class="section-title">Admission Form</h2>
    <form>
      <input type="text" placeholder="Full Name" required />
      <input type="email" placeholder="Email Address" required />
      <input type="tel" placeholder="Phone Number" required />
      <textarea placeholder="Why do you want to join our school?" rows="4" required></textarea>
      <button type="submit">Submit</button>
    </form>
  </section>

  <section id="contact">
    <h2 class="section-title">Contact Us</h2>
    <p><strong>Address:</strong> Little Star Public School, Gadwa, Bahraich, Uttar Pradesh, India</p>
    <p><strong>Email:</strong> ry1550433@gmail.com</p>
    <p><strong>Phone:</strong> +91-9415632527</p>
  </section>

  <section id="admin">
    <h2 class="section-title">Admin Login</h2>
    <form>
      <input type="text" placeholder="Username" required />
      <input type="password" placeholder="Password" required />
      <button type="submit">Login</button>
    </form>
  </section>

  <footer>
    &copy; 2025 Little Star Public School, Gadwa, Bahraich. All rights reserved.
  </footer>

</body>
</html>
