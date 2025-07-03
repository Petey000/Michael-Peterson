# Michael-Peterson
/* Reset and base */

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #333;
}

/* Header and navigation */

header {
  background: #f8f8f8;
  padding: 20px 0;
}

nav ul {
  display: flex;
  justify-content: center;
  list-style: none;
}

nav li + li {
  margin-left: 30px;
}

nav a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
}

.hero {
  text-align: center;
  margin-top: 20px;
}

.hero h1 {
  font-size: 3rem;
}

.hero p {
  font-size: 1.2rem;
  color: #666;
}

/* Sections */

main {
  max-width: 900px;
  margin: 40px auto;
  padding: 0 20px;
}

section {
  margin-bottom: 60px;
}

section h2 {
  margin-bottom: 15px;
  border-bottom: 2px solid #ddd;
  padding-bottom: 5px;
}

/* Stats table */

table {
  width: 100%;
  border-collapse: collapse;
}

th, td {
  padding: 10px;
  border: 1px solid #ddd;
  text-align: left;
}

/* Gallery grid */

.gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 15px;
}

.gallery-grid img {
  width: 100%;
  height: auto;
  display: block;
}

/* Footer */

footer {
  text-align: center;
  padding: 20px 0;
  background: #f0f0f0;
  font-size: 0.9rem;
}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Your Name | Model Portfolio</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>

  <header>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#stats">Stats</a></li>
        <li><a href="#hobbies">Hobbies</a></li>
        <li><a href="#gallery">Gallery</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
    <div class="hero">
      <h1>Your Name</h1>
      <p>Professional Model</p>
    </div>
  </header>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>Write a short bio here. Talk about your background, experience, and what makes you unique.</p>
    </section>

    <section id="stats">
      <h2>Stats</h2>
      <table>
        <tr>
          <th>Height</th>
          <td>6 ft 1 in / 185 cm</td>
        </tr>
        <tr>
          <th>Weight</th>
          <td>170 lbs / 77 kg</td>
        </tr>
        <tr>
          <th>Eyes</th>
          <td>Blue</td>
        </tr>
        <tr>
          <th>Hair</th>
          <td>Brown</td>
        </tr>
      </table>
    </section>

    <section id="hobbies">
      <h2>Hobbies & Interests</h2>
      <ul>
        <li>Photography</li>
        <li>Traveling</li>
        <li>Fitness & Yoga</li>
        <li>Cooking</li>
      </ul>
    </section>

    <section id="gallery">
      <h2>Portfolio</h2>
      <div class="gallery-grid">
        <img src="images/photo1.jpg" alt="Photo 1">
        <img src="images/photo2.jpg" alt="Photo 2">
        <img src="images/photo3.jpg" alt="Photo 3">
        <img src="images/photo4.jpg" alt="Photo 4">
      </div>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Email: your.email@example.com</p>
      <p>Phone: (123) 456-7890</p>
      <p>Instagram: @yourhandle</p>
    </section>
  </main>

  <footer>
    <p>© 2025 Your Name. All rights reserved.</p>
  </footer>

</body>
</html>
