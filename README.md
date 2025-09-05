,<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Digital Portfolio - Book Collection</title>
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f5f7fa;
      color: #333;
      line-height: 1.6;
    }

    /* Navigation */
    nav {
      background: #333;
      padding: 15px 20px;
      display: flex;
      justify-content: center;
      gap: 30px;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-size: 1rem;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ff9a9e;
    }

    header {
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      color: white;
      text-align: center;
      padding: 60px 20px;
    }

    header h1 {
      font-size: 2.8rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
    }

    /* About Me */
    .about {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 20px;
      padding: 50px 20px;
      background: white;
      margin: 30px auto;
      border-radius: 15px;
      max-width: 1000px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    .about img {
      width: 160px;
      height: 160px;
      border-radius: 50%;
      object-fit: cover;
      border: 5px solid #ff9a9e;
    }

    .about-text {
      max-width: 650px;
    }

    .about-text h2 {
      margin-bottom: 12px;
      font-size: 2rem;
      color: #444;
    }

    .about-text p {
      margin-bottom: 15px;
      color: #555;
    }

    .contact {
      margin-top: 10px;
    }

    .contact p {
      margin: 5px 0;
      font-size: 1rem;
    }

    /* Projects / Gallery */
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 40px;
    }

    .card {
      background: white;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card img {
      width: 100%;
      height: 220px;
      object-fit: cover;
    }

    .card h3 {
      font-size: 1.4rem;
      padding: 12px;
      color: #444;
    }

    .card p {
      padding: 0 12px 15px;
      font-size: 1rem;
      color: #555;
    }

    /* Skills Section */
    .skills {
      padding: 50px 20px;
      text-align: center;
      background: white;
      margin: 30px;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    .skills h2 {
      margin-bottom: 20px;
      font-size: 2rem;
      color: #444;
    }

    .skills ul {
      list-style: none;
    }

    .skills ul li {
      font-size: 1.1rem;
      margin: 10px 0;
      color: #555;
    }

    /* Hire Me Section */
    .hire {
      text-align: center;
      padding: 60px 20px;
      background: linear-gradient(135deg, #fad0c4, #ffdde1);
      margin: 30px;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    .hire h2 {
      font-size: 2.2rem;
      margin-bottom: 15px;
      color: #333;
    }

    .hire p {
      font-size: 1.1rem;
      margin-bottom: 20px;
      color: #444;
    }

    /* Contact Form */
    .hire form {
      max-width: 500px;
      margin: 0 auto;
      text-align: left;
    }

    .hire label {
      display: block;
      margin: 10px 0 5px;
      font-weight: bold;
      color: #333;
    }

    .hire textarea {
      width: 100%;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 8px;
      margin-bottom: 15px;
      font-size: 1rem;
    }

    .hire button {
      display: block;
      width: 100%;
      padding: 12px;
      font-size: 1rem;
      font-weight: bold;
      background: #ff9a9e;
      color: white;
      border: none;
      border-radius: 30px;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    .hire button:hover {
      background: #ff6a6a;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 25px;
      background: #333;
      color: white;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <!-- Navigation -->
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#skills">Skills</a>
    <a href="#hire">Hire Me</a>
  </nav>

  <!-- Header -->
  <header id="home">
    <h1>📚 Digital Portfolio</h1>
    <p>Book Collection Showcase</p>
  </header>

  <!-- About Me Section -->
  <section class="about" id="about">
    <img src="https://via.placeholder.com/160" alt="Profile Picture">
    <div class="about-text">
<h1>Sivaranjani</span></h1>

      <h2>About Me</h2>
      <p>Hello! I am a book enthusiast who loves exploring knowledge through reading. Through this portfolio, I share some of my favorite books and the lessons they teach.</p>
      <div class="contact">
        <p><strong>Location:</strong> India</p>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section class="gallery" id="projects">
    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/6/62/First_folio_shakespeare.jpg" alt="Shakespeare">
      <h3>Shakespeare’s Works</h3>
      <p>A timeless collection of plays and poetry that shaped English literature.</p>
    </div>

    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/8/88/Don_Quixote_1st.jpg" alt="Don Quixote">
      <h3>Don Quixote</h3>
      <p>One of the greatest novels ever written, exploring imagination and reality.</p>
    </div>

    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/0/0c/The_Holy_Bible_title_page_1611.jpg" alt="Bible">
      <h3>The Holy Bible</h3>
      <p>A spiritual text influencing millions across centuries.</p>
    </div>

    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/6/62/PrideAndPrejudiceTitlePage.jpg" alt="Pride and Prejudice">
      <h3>Pride and Prejudice</h3>
      <p>Jane Austen’s classic novel about love, society, and human nature.</p>
    </div>
  </section>

  <!-- Skills Section -->
  <section class="skills" id="skills">
    <h2>My Skills</h2>
    <ul>
      <li>HTML, CSS, JavaScript</li>
      <li>Web Design & UI/UX</li>
      <li>Creative Writing & Reviewing</li>
      <li>Research & Presentation</li>
    </ul>
  </section>

  <!-- Hire Me Section -->
  <section class="hire" id="hire">
    <h2>Hire Me</h2>
    <p>If you like my work and would like to collaborate, please send me a message below:</p>

    <form action="mailto:yourname@example.com" method="post" enctype="text/plain">
      <label for="message">Message</label>
      <textarea id="message" name="message" rows="5" placeholder="Write your message..." required></textarea>

      <button type="submit">Submit</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Digital Portfolio | Book Collection</p>
  </footer>

</body>
</html>
