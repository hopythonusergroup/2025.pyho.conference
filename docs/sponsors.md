---
# template: sponsors.html
hide:
  - toc
  - navigation
---

<title>Sponsors | PyHo 2025</title>

<style>
    section {
      /* padding: 60px 20px; */
      max-width: 1200px;
      margin: 0 auto;
    }

    h2 {
      /* font-size: 2.5em; */
      text-align: center;
      margin-bottom: 40px;
      /* color: #1e1e1e; */
    }

    h3 {
      font-size: 1.8em;
      text-align: center;
      margin-bottom: 20px;
      position: relative;
      display: inline-block;
    }

    h3::after {
      content: "";
      position: absolute;
      width: 80px;
      height: 3px;
      bottom: -8px;
      left: 50%;
      transform: translateX(-50%);
      background-color: #facc15;
      border-radius: 3px;
    }

    .sponsor-category {
      text-align: center;
      margin-bottom: 60px;
    }

    .sponsor-grid {
      /* display: grid; */
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 30px;
      justify-items: center;
      margin-top: 30px;
    }

    .sponsor-card {
      background-color: white;
      border-radius: 15px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.08);
      width: 180px;
      height: 180px;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 15px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .sponsor-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 14px rgba(0, 0, 0, 0.1);
    }

    .sponsor-card img {
      max-width: 120px;
      max-height: 80px;
      margin-bottom: 10px;
      filter: grayscale(100%);
      transition: filter 0.3s ease;
    }

    .sponsor-card:hover img {
      filter: grayscale(0%);
    }

    .sponsor-card p {
      font-size: 0.9em;
      color: #444;
      font-weight: 500;
      text-align: center;
      margin: 0;
    }

    /* Category Color Variations */
    .grant h3::after {
      background-color: #facc15; /* yellow */
    }

    .community h3::after {
      background-color: #22c55e; /* green */
    }

    @media (max-width: 600px) {
      h2 {
        font-size: 2em;
      }
      h3 {
        font-size: 1.4em;
      }
      .sponsor-card {
        width: 150px;
        height: 150px;
      }
    }
  </style>

# Sponsors

<section>
    <div class="space-text">
        <p>
            PyHo 2025 was made possible the generosity of the organizations below.
            We are grateful for the support to provide and make the entire event free to attend and the activities that help us grow 
            the Python User Group community and the PyHo events respectively.
        </p>
        <p data-block-key="3b82b">
            If you would like to sponsor PyHo 2025, please <!--review our <a href="static/prospectus.pdf" download>Sponsorship Prospectus</a> 
            or--> send us an email <a href="mailto:ho@pythonghana.org">ho@pythonghana.org</a>
        </p>
    </div>

  <!-- Grant Sponsors -->
  <!-- <div class="sponsor-category grant">
    <h3>Grant</h3>
    <div class="sponsor-grid">
      <div class="sponsor-card">
        <img src="../static/images/sponsors/psf-logo.png" alt="PSF Logo">
      </div>
    </div>
  </div> -->

  <!-- Community Sponsors -->
  <!-- <div class="sponsor-category community">
    <h3>Community</h3>
    <div class="sponsor-grid">
      <div class="sponsor-card">
        <img src="../static/images/sponsors/django-community.svg" alt="BPD Logo">
      </div>
      <br>
      <div class="sponsor-card">
        <img src="../static/images/sponsors/pylady_geek-removebg-preview.png" alt="Pre Logo">
      </div>
      <br>
      <div class="sponsor-card">
        <img src="../static/images/sponsors/caktus-logo.png" alt="Pre Logo">
      </div>
      <br>
      <div class="sponsor-card">
        <img src="../static/images/sponsors/143823894.png" alt="Pre Logo">
      </div>
      <br>
      <div class="sponsor-card">
        <img src="../static/images/sponsors/pretix.png" alt="Pre Logo">
      </div>
    </div>
  </div> -->
</section>