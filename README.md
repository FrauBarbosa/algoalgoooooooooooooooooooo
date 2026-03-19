<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Embassy of Nepal in Brazil</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap" rel="stylesheet">

<style>
body {
  margin: 0;
  font-family: 'Inter', sans-serif;
  background: #f5f7fa;
  color: #1a1a1a;
}

/* HEADER */
header {
  background: linear-gradient(90deg, #b22222, #8b0000);
  color: white;
  padding: 20px 40px;
  display: flex;
  align-items: center;
  gap: 15px;
}

header img {
  width: 55px;
}

header h1 {
  margin: 0;
  font-weight: 600;
}

/* NAV */
nav {
  background: white;
  padding: 15px 40px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  position: sticky;
  top: 0;
}

nav a {
  margin-right: 25px;
  text-decoration: none;
  color: #003893;
  font-weight: 500;
}

/* HERO */
.hero {
  background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)),
  url('https://upload.wikimedia.org/wikipedia/commons/1/12/Mount_Everest_as_seen_from_Drukair2_PLW_edit.jpg');
  background-size: cover;
  color: white;
  text-align: center;
  padding: 120px 20px;
}

.hero h2 {
  font-size: 42px;
  margin-bottom: 10px;
}

.hero p {
  font-size: 18px;
}

/* SECTION */
.section {
  max-width: 1100px;
  margin: auto;
  padding: 60px 20px;
}

/* CARD */
.card {
  background: white;
  padding: 30px;
  border-radius: 18px;
  box-shadow: 0 8px 25px rgba(0,0,0,0.06);
  margin-bottom: 30px;
}

/* GRID */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 25px;
}

/* NEWS */
.news-card {
  padding: 20px;
  border-radius: 12px;
  background: #fafafa;
  transition: 0.3s;
}

.news-card:hover {
  transform: translateY(-6px);
  background: #ffffff;
}

/* BUTTON */
.btn {
  display: inline-block;
  margin-top: 15px;
  padding: 12px 18px;
  background: #003893;
  color: white;
  border-radius: 8px;
  text-decoration: none;
}

/* FOOTER */
footer {
  background: #0d0d0d;
  color: #bbb;
  text-align: center;
  padding: 30px;
}
</style>

</head>

<body>

<header>
  <img src="https://media.tenor.com/7cX2K7kQzJIAAAAd/nepal-flag.gif">
  <h1>Embassy of Nepal in Brazil</h1>
</header>

<nav>
  <a href="#services">Services</a>
  <a href="#mission">Mission</a>
  <a href="#news">News</a>
  <a href="#contact">Contact</a>
</nav>

<section class="hero">
  <h2>Embassy of Nepal</h2>
  <p>Strengthening Nepal–Brazil Relations</p>
</section>

<div class="section">

  <div class="card" id="services">
    <h2>Consular Services</h2>
    <div class="grid">
      <div class="news-card">
        <h3>Visa Application</h3>
        <p>Apply for travel authorization.</p>
      </div>
      <div class="news-card">
        <h3>Passport</h3>
        <p>Support for Nepali citizens.</p>
      </div>
      <div class="news-card">
        <h3>Authentication</h3>
        <p>Legal document services.</p>
      </div>
    </div>
  </div>

  <div class="card" id="mission">
    <h2>Diplomatic Mission</h2>
    <p>The Embassy promotes diplomacy, cooperation, and cultural exchange between Nepal and Brazil.</p>
  </div>

  <div class="card" id="news">
    <h2>Latest News</h2>
    <div class="grid">
      <div class="news-card">
        <h3>Embassy Event</h3>
        <p>Cultural diplomacy event in Brasília.</p>
      </div>
      <div class="news-card">
        <h3>Diplomatic Meeting</h3>
        <p>High-level meeting between officials.</p>
      </div>
      <div class="news-card">
        <h3>Public Notice</h3>
        <p>Updates on consular services.</p>
      </div>
    </div>
  </div>

  <div class="card" id="contact">
    <h2>Contact</h2>
    <p><strong>Ambassador:</strong> Nirmal Raj Kafle</p>
    <p>Email: info@nepalembassy.gov.np</p>
    <p>Brasília, Brazil</p>
    <a class="btn" href="#">Get in Touch</a>
  </div>

</div>

<footer>
  <p>© 2026 Embassy of Nepal in Brazil</p>
</footer>

</body>
</html>
