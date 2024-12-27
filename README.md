<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Welcome to Tech Club, your hub for technology enthusiasts.">
  <title>Tech Club</title>
  <style>
    /* General Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      line-height: 1.6;
    }

    /* Header */
    header {
      background: #1e1e2f;
      color: #fff;
      padding: 20px 10%;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
    }

    header p {
      margin-top: 10px;
      font-size: 1rem;
    }

    nav {
      margin-top: 15px;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 20px;
    }

    nav ul li a {
      text-decoration: none;
      color: #ff5c58;
      font-weight: bold;
    }

    nav ul li a:hover {
      color: #fff;
    }

    /* Hero Section */
    .hero {
      background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('https://source.unsplash.com/1600x900/?technology');
      background-size: cover;
      background-position: center;
      color: white;
      padding: 100px 10%;
      text-align: center;
    }

    .hero h2 {
      font-size: 3rem;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 20px;
    }

    .hero a {
      text-decoration: none;
      background: #ff5c58;
      padding: 10px 20px;
      color: white;
      border-radius: 5px;
      font-weight: bold;
    }

    .hero a:hover {
      background: #d9443b;
    }

    /* Sections */
    .container {
      padding: 50px 10%;
    }

    .section {
      margin-bottom: 50px;
    }

    .section h3 {
      font-size: 2rem;
      margin-bottom: 20px;
      text-align: center;
      color: #333;
    }

    .cards {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      justify-content: center;
    }

    .card {
      background: #f5f5f5;
      border: 1px solid #ddd;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      padding: 20px;
      width: 300px;
      text-align: center;
    }

    .card img {
      max-width: 100%;
      height: auto;
      border-radius: 5px;
      margin-bottom: 15px;
    }

    .card h4 {
      margin-bottom: 10px;
      color: #333;
    }

    .card p {
      font-size: 0.9rem;
      color: #666;
    }

    /* Footer */
    footer {
      background: #1e1e2f;
      color: #fff;
      padding: 20px 10%;
      text-align: center;
    }

    footer p {
      font-size: 0.9rem;
    }

    footer a {
      color: #ff5c58;
      text-decoration: none;
    }

    footer a:hover {
      color: #fff;
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <h2>Techsquad Club</h2>
    <p>Your Gateway to Innovation and Technology</p>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#events">Events</a></li>
        <li><a href="#members">Members</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h2>Welcome to Techsquad Club</h2>
    <p>Explore, Innovate, and Build the Future</p>
    <a href="#about">Learn More</a>
  </section>

  <!-- About Section -->
  <section id="about" class="container section">
    <h3>About Us</h3>
    <p>Welcome to Tech Squad Club, a dynamic community of innovators and tech enthusiasts proudly operated by the Computer Science Engineering (CSE) students of the 2023-26 session at Government Polytechnic Siwan.</p><br>

<p><strong>Who We Are</strong>
Tech Squad Club is more than just a name; it’s a passion-driven initiative dedicated to fostering technical knowledge, creativity, and collaboration. Founded by aspiring technologists, we aim to create a space where ideas thrive, projects come to life, and learning knows no bounds.
</p><br>

<p>
 <strong>
  <!--Tab to edit-->
Our Mission</strong>
At Tech Squad Club, our mission is to empower students by providing them with opportunities to explore, learn, and excel in the ever-evolving world of technology. We strive to bridge the gap between academics and industry, nurturing innovation and preparing our members for real-world challenges.</p>
<br>
<p><strong>What We Do</strong>
Our activities include:

Workshops and Seminars: Hands-on learning experiences led by experts and industry professionals.

Tech Projects: Collaborative projects that bring ideas from concept to reality.

Competitions: Encouraging creativity and innovation through coding challenges, hackathons, and technical events.

Community Outreach: Sharing knowledge and giving back to the community through tech-based solutions..</p><br>
  </section>

  <!-- Events Section -->
  <section id="events" class="container section">
    <h3>Upcoming Events</h3>
    <div class="cards">
      <div class="card">
        <img src="https://source.unsplash.com/300x200/?coding" alt="Event">
        <h4>Hackathon 2024</h4>
        <p>Join us for a 48-hour coding marathon to create innovative solutions.</p>
      </div>
      <div class="card">
        <img src="https://source.unsplash.com/300x200/?robotics" alt="Event">
        <h4>Robotics Workshop</h4>
        <p>Learn the basics of robotics and build your own bot!</p>
      </div>
      <div class="card">
        <img src="https://source.unsplash.com/300x200/?cloud" alt="Event">
        <h4>Cloud Computing Seminar</h4>
        <p>Discover the power of cloud computing and its applications.</p>
      </div>
    </div>
  </section>

  <!-- Members Section -->
  <section id="members" class="container section">
  <h3>Our Team</h3>
  <div class="cards">
    <div class="card">
      <img src="https://source.unsplash.com/300x200/?person1" alt="President">
      <h4>Munna Kumar</h4>
      <p>President</p>
    </div>
    <div class="card">
      <img src="https://source.unsplash.com/300x200/?person2" alt="Vice President">
      <h4>Shivangi Jaiswal</h4>
      <p>Vice President</p>
    </div>
    <div class="card">
      <img src="https://source.unsplash.com/300x200/?person3" alt="Secretary">
      <h4>Aman Kumar</h4>
      <p>Secretary</p>
    </div>
    <div class="card">
      <img src="https://source.unsplash.com/300x200/?person4" alt="Vice Secretary">
      <h4>Namrata Pal</h4>
      <p>Vice Secretary</p>
    </div>
    <!-- Other Members -->
    <div class="card">
      <img src="https://source.unsplash.com/300x200/?person5" alt="Member">
      <h4>Rahul Nayak Diwakar</h4>
      <p>Treasurer</p>
    </div>
    <div class="card">
      <img src="https://source.unsplash.com/300x200/?person6" alt="Member">
      <h4>Prince Kumar</h4>
      <p>Tech Expert</p>
    </div>
    <div class="card">
      <img src="https://source.unsplash.com/300x200/?person7" alt="Member">
      <h4>Emily Davis</h4>
      <p>Member</p>
    </div>
    <div class="card">
      <img src="https://source.unsplash.com/300x200/?person8" alt="Member">
      <h4>Michael White</h4>
      <p>Member</p>
    </div>
    <div class="card">
      <img src="https://source.unsplash.com/300x200/?person9" alt="Member">
      <h4>Laura Green</h4>
      <p>Member</p>
    </div>
    <div class="card">
      <img src="https://source.unsplash.com/300x200/?person10" alt="Member">
      <h4>James Taylor</h4>
      <p>Member</p>
    </div>
    <!-- New Members -->
    <div class="card">
      <img src="https://source.unsplash.com/300x200/?person11" alt="Member">
      <h4>Sophia Carter</h4>
      <p>Member</p>
    </div>
    <div class="card">
      <img src="https://source.unsplash.com/300x200/?person12" alt="Member">
      <h4>Daniel Harris</h4>
      <p>Member</p>
    </div>
  </div>
</section>

  <!-- Contact Section -->
  <section id="contact" class="container section">
    <h3>Contact Us</h3>
    <p>Email: amansinhaonline@gmail.com</p>
    <p>Phone: +91 9973355620</p>
    
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Techsquad Club | Designed By Aman Kumar</p>
    <p><a href="#top">Back to Top</a></p>
  </footer>
</body>
</html>
