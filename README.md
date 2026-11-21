# Chila-website

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>CHILA Digital | Web Design Zambia</title>

  <meta name="description" content="CHILA Digital creates modern, affordable and professional websites for businesses in Zambia.">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: white;
      line-height: 1.6;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 18px 7%;
      background: #111c30;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    .logo {
      font-size: 25px;
      font-weight: bold;
      color: #a78bfa;
    }

    nav {
      display: flex;
      gap: 20px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-size: 14px;
    }

    nav a:hover {
      color: #a78bfa;
    }

    .hero {
      padding: 95px 20px;
      text-align: center;
      background: linear-gradient(
        135deg,
        #0f172a,
        #25204a,
        #0f172a
      );
    }

    .tag {
      color: #a78bfa;
      font-weight: bold;
      font-size: 13px;
      letter-spacing: 2px;
    }

    .hero h1 {
      font-size: clamp(36px, 8vw, 58px);
      line-height: 1.15;
      margin: 22px auto;
      max-width: 750px;
    }

    .hero h1 span {
      color: #a78bfa;
    }

    .hero p {
      color: #cbd5e1;
      max-width: 550px;
      margin: 0 auto 30px;
    }

    .btn {
      display: inline-block;
      background: #8b5cf6;
      color: white;
      padding: 14px 25px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn:hover {
      background: #7c3aed;
      transform: translateY(-2px);
    }

    section {
      padding: 65px 7%;
    }

    .section-title {
      text-align: center;
      margin-bottom: 35px;
    }

    .section-title h2 {
      font-size: 32px;
      margin-bottom: 10px;
    }

    .section-title p {
      color: #94a3b8;
    }

    .services {
      background: #172033;
    }

    .service-grid {
      display: grid;
      grid-template-columns: repeat(
        auto-fit,
        minmax(220px, 1fr)
      );
      gap: 20px;
    }

    .service {
      background: #1e293b;
      padding: 27px;
      border-radius: 12px;
      border: 1px solid #334155;
    }

    .service h3 {
      color: #a78bfa;
      margin-bottom: 12px;
    }

    .service p {
      color: #cbd5e1;
      font-size: 14px;
    }

    .pricing-grid {
      display: grid;
      grid-template-columns: repeat(
        auto-fit,
        minmax(230px, 1fr)
      );
      gap: 20px;
    }

    .price-card {
      background: #1e293b;
      padding: 27px;
      border: 1px solid #334155;
      border-radius: 12px;
    }

    .price-card h3 {
      color: #a78bfa;
    }

    .price {
      font-size: 26px;
      font-weight: bold;
      margin: 15px 0;
    }

    .price-card ul {
      padding-left: 20px;
      color: #cbd5e1;
      font-size: 14px;
      margin-bottom: 22px;
    }

    .price-card li {
      margin-bottom: 8px;
    }

    .about {
      background: #172033;
      text-align: center;
    }

    .about p {
      color: #cbd5e1;
      max-width: 650px;
      margin: auto;
    }

    .contact {
      text-align: center;
    }

    .contact p {
      color: #cbd5e1;
      margin: 15px 0 25px;
    }

    .note {
      color: #94a3b8;
      font-size: 12px;
      margin-top: 20px;
    }

    footer {
      text-align: center;
      padding: 25px;
      background: #080e1b;
      color: #94a3b8;
      font-size: 13px;
    }

    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #16a34a;
      color: white;
      text-decoration: none;
      padding: 14px 18px;
      border-radius: 30px;
      font-weight: bold;
      z-index: 200;
      box-shadow: 0 5px 20px #0005;
    }

    @media (max-width: 600px) {
      header {
        flex-direction: column;
        gap: 12px;
      }

      nav {
        gap: 13px;
        flex-wrap: wrap;
        justify-content: center;
      }

      nav a {
        font-size: 12px;
      }

      .hero {
        padding: 75px 20px;
      }

      section {
        padding: 55px 20px;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">CHILA.</div>

    <nav>
      <a href="#home">Home</a>
      <a href="#services">Services</a>
      <a href="#pricing">Pricing</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">

    <div class="tag">CREATIVE DIGITAL SOLUTIONS</div>

    <h1>
      Build Your <span>Digital Future.</span>
    </h1>

    <p>
      We design and develop modern, affordable
      and professional websites that help
      businesses establish their online presence.
    </p>

    <a href="#contact" class="btn">
      Start Your Project
    </a>

  </section>

  <section class="services" id="services">

    <div class="section-title">
      <h2>Our Services</h2>
      <p>Everything your business needs online.</p>
    </div>

    <div class="service-grid">

      <div class="service">
        <h3>Website Design</h3>
        <p>
          Beautiful, modern and professional
          website designs for your business.
        </p>
      </div>

      <div class="service">
        <h3>Website Development</h3>
        <p>
          Responsive websites designed to work
          on phones, tablets and computers.
        </p>
      </div>

      <div class="service">
        <h3>Online Stores</h3>
        <p>
          Product catalogues and online shopping
          experiences for growing businesses.
        </p>
      </div>

      <div class="service">
        <h3>Website Maintenance</h3>
        <p>
          Regular website updates and technical
          support to keep your site running.
        </p>
      </div>

    </div>
  </section>

  <section id="pricing">

    <div class="section-title">
      <h2>Our Pricing</h2>
      <p>Affordable website solutions in Zambia.</p>
    </div>

    <div class="pricing-grid">

      <div class="price-card">
        <h3>Starter Website</h3>
        <div class="price">K800–K1,500</div>

        <ul>
          <li>One-page website</li>
          <li>Mobile-friendly design</li>
          <li>About and services sections</li>
          <li>WhatsApp contact button</li>
          <li>Business contact information</li>
        </ul>

        <a href="#contact" class="btn">
          Get Started
        </a>
      </div>

      <div class="price-card">
        <h3>Business Website</h3>
        <div class="price">K2,000–K3,500</div>

        <ul>
          <li>Up to 5 pages</li>
          <li>Professional design</li>
          <li>Mobile responsiveness</li>
          <li>Contact form</li>
          <li>WhatsApp integration</li>
          <li>Basic SEO setup</li>
        </ul>

        <a href="#contact" class="btn">
          Get Started
        </a>
      </div>

      <div class="price-card">
        <h3>Business Plus</h3>
        <div class="price">K5,000–K8,000</div>

        <ul>
          <li>Up to 8 pages</li>
          <li>Customised design</li>
          <li>Image gallery</li>
          <li>Contact forms</li>
          <li>Basic SEO</li>
          <li>Google Analytics setup</li>
        </ul>

        <a href="#contact" class="btn">
          Get Started
        </a>
      </div>

    </div>

    <p class="note">
      Domain registration, hosting and additional
      features are quoted separately.
    </p>

  </section>

  <section class="about" id="about">

    <div class="section-title">
      <h2>About CHILA</h2>
    </div>

    <p>
      CHILA Digital is a growing website design
      and development brand based in Zambia.

      Our mission is to help businesses build
      a professional online presence through
      creative, accessible and modern websites.
    </p>

  </section>

  <section class="contact" id="contact">

    <h2>Ready to Grow Your Business?</h2>

    <p>
      Let's create a website that brings your
      business closer to its customers.
    </p>

    <!-- Replace with your actual WhatsApp number -->
    <a
      href="https://wa.me/260976828833"
      class="btn"
      target="_blank"
      rel="noopener"
    >
      Contact Us on WhatsApp
    </a>

  </section>

  <footer>
    © 2026 CHILA Digital. All Rights Reserved.
    <br>
    Creative Websites. Real Business Growth.
  </footer>

  <a
    href="https://wa.me/260976828833"
    class="whatsapp"
    target="_blank"
    rel="noopener"
  >
    WhatsApp Us
  </a>

</body>
</html>
