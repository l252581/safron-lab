<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Saffron Labs</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <div class="logo">
      <img src="assets/saffron-logo.svg" alt="Saffron Labs Logo" />
      <h1>Saffron Labs</h1>
    </div>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#join">Join Us</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>Welcome to Saffron Labs</h2>
      <p>Your partner in innovative saffron research and development.</p>
    </section>

    <section id="services">
      <h2>Our Services</h2>
      <article>
        <h3>Research & Development</h3>
        <p>We offer cutting-edge saffron cultivation technologies.</p>
      </article>
      <article>
        <h3>Consulting</h3>
        <p>Expert advice for optimizing saffron yield.</p>
      </article>
    </section>

    <section id="join">
      <h2>Join Us</h2>
      
    </section>
  </main>

  <footer>
    <p>Contact us at <a href="mailto:info@saffronlabs.com">info@saffronlabs.com</a></p>
    <p>&copy; 2025 Saffron Labs. All rights reserved.</p>
  </footer>
</body>
<form action="#" method="post" aria-label="Join Saffron Labs form">
  <div class="form-group">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required aria-required="true" />
  </div>

  <div class="form-group">
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required aria-required="true" />
  </div>

  <fieldset>
    <legend>Subscribe to our newsletters:</legend>
    <div class="form-group">
      <input type="checkbox" id="news" name="newsletter" value="news" />
      <label for="news">Newsletters</label>
    </div>
    <div class="form-group">
      <input type="checkbox" id="updates" name="newsletter" value="updates" />
      <label for="updates">Product Updates</label>
    </div>
    <div class="form-group">
      <input type="checkbox" id="alerts" name="newsletter" value="alerts" />
      <label for="alerts">Research Alerts</label>
    </div>
  </fieldset>
  <fieldset>
    <legend>Select your subscription plan:</legend>
    <div class="form-group">
      <input type="radio" id="basic" name="plan" value="basic" required />
      <label for="basic">Basic</label>
    </div>
    <div class="form-group">
      <input type="radio" id="premium" name="plan" value="premium" />
      <label for="premium">Premium</label>
    </div>
  </fieldset>


  <div class="form-group">
    <label for="country">Country:</label>
    <select id="country" name="country" required>
      <option value="">--Please choose an option--</option>
      <option value="us">United States</option>
      <option value="pak">pakistan</option>
      <option value="uk">United Kingdom</option>
      <option value="ca">Canada</option>
      <option value="au">Australia</option>
    </select>
  </div>

  <div class="form-group">
    <label for="comments">Additional Comments:</label>
    <textarea id="comments" name="comments" rows="4" placeholder="Your message"></textarea>
  </div>

  
  <div class="form-group">
    <button type="submit">Join Now</button>
  </div>
</form>
<section class="faq">
  <h2>FAQ</h2>

  <div class="faq-item">
    <input type="checkbox" id="faq1" class="toggle" />
    <label for="faq1" class="faq-question">What is Saffron Labs?</label>
    <div class="faq-answer">
      <p>Saffron Labs is an innovative saffron research and development initiative.Tests include analyzing moisture, ash, and coloring strength, and can use methods like high-pressure liquid chromatography (HPLC).</p>
    </div>
  </div>

  <div class="faq-item">
    <input type="checkbox" id="faq2" class="toggle" />
    <label for="faq2" class="faq-question">How can I join?</label>
    <div class="faq-answer">
      <p>You can join by filling out our Join Us form with your details and subscription plan.</p>
    </div>
  </div>
</section>
<section class="tabs">
  <input type="radio" name="tabset" id="tab1" checked />
  <label for="tab1">Overview</label>

  <input type="radio" name="tabset" id="tab2" />
  <label for="tab2">Products</label>

  <input type="radio" name="tabset" id="tab3" />
  <label for="tab3">Contact</label>

  <div class="tab-content" id="content1">
    <p>Welcome to Saffron Labs overview section.</p>
  </div>
  <div class="tab-content" id="content2">
    <p>Check out our innovative saffron products.</p>
  </div>
  <div class="tab-content" id="content3">
    <p>Contact us for queries and support.</p>
  </div>
</section>
<label for="modal-toggle" class="btn-open-modal">Open Modal</label>

<input type="checkbox" id="modal-toggle" class="modal-toggle" />

<div class="modal">
  <div class="modal-content">
    <label for="modal-toggle" class="modal-close">&times;</label>
    <h2>Modal Title</h2>
    <p>This is a CSS-only modal popup triggered via checkbox toggle.</p>
  </div>
</div>
</html>
