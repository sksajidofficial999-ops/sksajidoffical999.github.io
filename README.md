<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Farmer Help Portal with crop advice, weather alerts, schemes, market prices, and support in English and Telugu." />
  <title>Farmer Help Portal</title>
  <link rel="stylesheet" href="css/styles.css" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Telugu:wght@400;600;700&display=swap" rel="stylesheet">
</head>
<body>
  <a class="skip-link" href="#main-content">Skip to main content</a>

  <header class="site-header">
    <div class="container header-inner">
      <div>
        <p class="brand" id="brand-text">Farmer Help Portal</p>
        <p class="tagline" id="tagline-text">Support, alerts, and services for farmers</p>
      </div>

      <div class="topbar" aria-label="Language switcher">
        <button class="lang-btn" id="enBtn" aria-pressed="true" type="button">English</button>
        <button class="lang-btn" id="teBtn" aria-pressed="false" type="button">తెలుగు</button>
      </div>

      <nav aria-label="Primary navigation">
        <ul class="nav-list">
          <li><a href="#services" id="nav-services">Services</a></li>
          <li><a href="#alerts" id="nav-alerts">Alerts</a></li>
          <li><a href="#support" id="nav-support">Support</a></li>
          <li><a href="#contact" id="nav-contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main id="main-content">
    <section class="hero" aria-labelledby="hero-title">
      <div class="container hero-inner">
        <div class="hero-text">
          <h1 id="hero-title">One place for farming help, weather updates, and government schemes</h1>
          <p id="hero-desc">Find crop guidance, report issues, check market prices, and get help quickly in a simple, accessible way.</p>
          <div class="hero-actions">
            <a class="button primary" href="#services" id="hero-primary">Explore Services</a>
            <a class="button secondary" href="#support" id="hero-secondary">Get Support</a>
          </div>
        </div>

        <aside class="hero-card" aria-labelledby="quick-help-title">
          <h2 id="quick-help-title">Quick Help</h2>
          <ul class="quick-list">
            <li><a href="#alerts" id="quick-1">Weather alerts</a></li>
            <li><a href="#services" id="quick-2">Crop advisory</a></li>
            <li><a href="#contact" id="quick-3">Talk to support</a></li>
          </ul>
        </aside>
      </div>
    </section>

    <section class="section" id="services" aria-labelledby="services-title">
      <div class="container">
        <h2 id="services-title">Main services</h2>
        <div class="card-grid">
          <article class="card">
            <h3 id="service-1-title">Crop Advisory</h3>
            <p id="service-1-desc">Get guidance on sowing, irrigation, fertilization, and pest control.</p>
          </article>

          <article class="card">
            <h3 id="service-2-title">Weather Alerts</h3>
            <p id="service-2-desc">Receive timely weather updates to plan farm work safely.</p>
          </article>

          <article class="card">
            <h3 id="service-3-title">Market Prices</h3>
            <p id="service-3-desc">Check daily market rates for crops and local produce.</p>
          </article>

          <article class="card">
            <h3 id="service-4-title">Government Schemes</h3>
            <p id="service-4-desc">Find eligible schemes, subsidies, and application details.</p>
          </article>
        </div>
      </div>
    </section>

    <section class="section alt" id="alerts" aria-labelledby="alerts-title">
      <div class="container">
        <h2 id="alerts-title">Latest alerts</h2>
        <div class="alert-box" role="status" aria-live="polite">
          <p id="alert-1"><strong>Weather:</strong> Light rain expected in the next 24 hours.</p>
          <p id="alert-2"><strong>Advisory:</strong> Check drainage before irrigation.</p>
        </div>
      </div>
    </section>

    <section class="section" id="support" aria-labelledby="support-title">
      <div class="container">
        <h2 id="support-title">Report a problem</h2>
        <form class="support-form" action="#" method="post">
          <div class="form-group">
            <label for="name" id="label-name">Your name</label>
            <input type="text" id="name" name="name" autocomplete="name" />
          </div>

          <div class="form-group">
            <label for="phone" id="label-phone">Phone number</label>
            <input type="tel" id="phone" name="phone" autocomplete="tel" />
          </div>

          <div class="form-group">
            <label for="issue" id="label-issue">Issue type</label>
            <select id="issue" name="issue">
              <option value="" id="issue-opt-default">Select an issue</option>
              <option value="crop" id="issue-opt-crop">Crop problem</option>
              <option value="weather" id="issue-opt-weather">Weather concern</option>
              <option value="scheme" id="issue-opt-scheme">Scheme help</option>
              <option value="market" id="issue-opt-market">Market information</option>
            </select>
          </div>

          <div class="form-group">
            <label for="message" id="label-message">Describe your issue</label>
            <textarea id="message" name="message" rows="5"></textarea>
          </div>

          <button type="submit" class="button primary" id="submit-btn">Submit request</button>
        </form>
      </div>
    </section>
  </main>

  <footer class="site-footer" id="contact">
    <div class="container footer-inner">
      <div>
        <h2 class="footer-title" id="contact-title">Contact support</h2>
        <p id="contact-email">Email: support@farmerhelpportal.com</p>
        <p id="contact-phone">Phone: +91 9989919779</p>
      </div>
      <p class="footer-note" id="footer-note">Accessible, simple, and mobile-friendly for every farmer.</p>
    </div>
  </footer>

  <script src="js/app.js"></script>
</body>
</html>
