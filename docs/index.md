---
# template: home.html
hide:
  - navigation
  - toc
---

<title>PyHo 2025</title>

<style>
  .hero img.logo {
    width: 350px;
    height: 300px;
    /* margin-bottom: 20px; */
  }

  .button {
    background-color: #ffd343;
    color: #111;
    padding: 12px 25px;
    border-radius: 5px;
    text-decoration: none;
    margin: 10px;
    display: inline-block;
    font-weight: bold;
  }

  .button:hover {
    background-color: #ffec99;
  }

  /* Why PyHo section */
  .about-pyho {
    background-color: #f9fafb;
    padding: 80px 20px;
    /* text-align: center; */
  }

  .about-pyho h1 {
    text-align: center;
    font-size: 32px;
    /* color: #111; */
    margin-bottom: 20px;
  }

  .about-pyho p {
    max-width: 800px;
    margin: 0 auto;
    font-size: 18px;
    color: #333;
    /* line-height: 1.7; */
  }

  /* Photo section */
  .photo-section {
    background-color: #fff;
    text-align: center;
    /* padding: 60px 20px; */
    padding-top: 60px;
  }

  .photo-section img {
    width: 100%;
    /* max-width: 900px; */
    height: auto;
    border-radius: 10px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
  }

  /* Sponsors section */
  .sponsors {
    background-color: #f3f4f6;
    text-align: center;
    padding: 80px 20px;
  }

  .sponsors h1 {
    font-size: 28px;
    margin-bottom: 30px;
  }

  .sponsor-logos {
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    gap: 40px;
  }

  .sponsor-logos img {
    width: 150px;
    height: auto;
    filter: grayscale(100%);
    opacity: 0.8;
    transition: 0.3s ease;
  }

  .sponsor-logos img:hover {
    filter: grayscale(0%);
    opacity: 1;
  }
</style>

<header class="hero">
    <img src="static/assets/pyho-2025-logo-removebg.png" alt="PyHo 2025 Logo" class="logo">
    <p class="hero-date"><b>October 24–25, 2025</b></p>
    <p class="hero-paragraph">
        A two-day developer and community conference for Pythonistas and tech enthusiasts <br>
    </p>
    <p class="hero-paragraph">G.R.N.M.A Hotel, Ho</p>
    
    <!-- <div class="hero-buttons">
        <a href="https://www.papercall.io/cfps/6263/submissions/new" class="button cfp-button" target="_blank">📢 Submit a Talk Proposal</a>
        <a href="https://ti.to/pythonho/pyho-2025" class="button ticket-button" target="_blank">🎟️ Get Your Ticket</a>
    </div> -->
</header>

<section class="about-pyho">
  <h1>Why PyHo?</h1>
  <p>
    PyHo is more than just a Python conference — it’s where technology, innovation, and community meet in the heart of Ghana’s Oxygen City.  
    <br><br>
    Designed for everyone from curious beginners to seasoned developers, PyHo celebrates learning, collaboration, and open-source culture. Whether you’re looking to dive deep into Python, connect with local and global experts, or explore the future of tech innovation, PyHo is your place to be.  
    <br><br>
    Join us, learn something new, share your story, and build meaningful connections that last beyond the conference.
  </p>
</section>

<section class="photo-section">
  <h1>2024 Highlight</h1>
  <img src="static/images/attendees-pyho-24.jpg" alt="PyHo 2024 Collage">
</section>

<section class="sponsors">
  <div class="sponsor-logos">
    <img src="static/images/sponsors/psf-logo.png" alt="PSF Logo">
    <img src="static/images/sponsors/django-community.svg" alt="DSF Logo">
    <img src="static/images/sponsors/pylady_geek-removebg-preview.png" alt="PyLadies Logo">
    <img src="static/images/sponsors/caktus-logo.png" alt="CAK Logo">
    <img src="static/images/sponsors/143823894.png" alt="BPD Logo">
    <img src="static/images/sponsors/pretix.png" alt="PRE Logo">
  </div>
</section>