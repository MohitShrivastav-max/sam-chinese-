<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SAM Chinese Corner</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="logo">SAM Chinese Corner</div>
    <nav>
      <a href="#about">About</a>
      <a href="#menu">Menu</a>
      <a href="#gallery">Gallery</a>
      <a href="#reviews">Reviews</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>SAM Chinese Corner</h1>
    <p>Chinese, Fast Food, Rolls, Street Food, North Indian</p>
    <div class="ratings">
      <span>Dining ★ 3.0 (68)</span>
      <span>Delivery ★ 4.1 (856)</span>
    </div>
    <a href="#menu" class="cta">View Menu</a>
    <a href="#order" class="cta outline">Order Online</a>
  </section>

  <section id="about" class="about">
    <h2>Discover Our Story</h2>
    <p>
      Located at Plot 267, Munna Compound, Pimpri Pada, Gen.A.K.V Marg, Near Amar Chemist, Near Patanjali Mega Store, Malad East, Mumbai.
    </p>
    <ul>
      <li>Open: 11am – 12midnight daily</li>
      <li>Average Cost: ₹450 for two people (approx.)</li>
      <li>Payment Methods: Cash, Cards, Digital payments accepted</li>
      <li>Phone: +912228425454</li>
    </ul>
    <div class="features">
      <div>Customizations Available</div>
      <div>Plenty of Vegetarian Options</div>
      <div>Bang for the Buck</div>
      <div>Office Crowd</div>
      <div>Casual Seating Area</div>
      <div>Lip Smacking Food</div>
    </div>
  </section>

  <section id="menu" class="menu">
    <h2>Our Menu</h2>
    <div class="menu-categories">
      <details>
        <summary>Spring Rolls</summary>
        <ul>
          <li>Chicken Mixed Spring Roll</li>
          <li>Paneer Spring Roll</li>
          <li>Veg Mushroom Spring Roll</li>
          <li>Prawns Spring Roll</li>
          <li>Veg Spring Roll (8Pcs)</li>
        </ul>
      </details>
      <details>
        <summary>Shawarma</summary>
        <ul>
          <li>Chicken Arabic Shawarma</li>
          <li>Chicken Cheese Shawarma</li>
          <li>Paneer Shawarma</li>
          <li>Spicy Chicken Shawarma</li>
        </ul>
      </details>
      <details>
        <summary>Momos</summary>
        <ul>
          <li>Chicken Momos (Steamed/Fried)</li>
          <li>Veg Momos (Steamed/Fried)</li>
          <li>Paneer Momos (Steamed/Fried)</li>
        </ul>
      </details>
      <!-- Add more menu categories in the same way -->
      <details>
        <summary>Kathi Roll & Wraps</summary>
        <ul>
          <li>Chicken Kathi Roll</li>
          <li>Mutton Kathi Roll</li>
          <li>Veg Kathi Roll</li>
          <li>Cheese Bread Roll</li>
          <li>Chicken Schezwan Noodle Roll</li>
        </ul>
      </details>
      <details>
        <summary>Soups</summary>
        <ul>
          <li>Veg Manchow Soup</li>
          <li>Chicken Manchow Soup</li>
          <li>Chicken Lung Fung Soup</li>
          <li>Veg Hot & Sour Soup</li>
          <li>Prawns Soup</li>
        </ul>
      </details>
      <!-- ... (Continue adding all categories as needed) ... -->
    </div>
    <p><em>See our full menu in-restaurant or call for today's specials!</em></p>
  </section>

  <section id="gallery" class="gallery">
    <h2>Gallery</h2>
    <div class="gallery-images">
      <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?fit=crop&w=500&q=80" alt="Dish 1">
      <img src="https://images.unsplash.com/photo-1523987355523-c7b5b0723c71?fit=crop&w=500&q=80" alt="Dish 2">
      <img src="https://images.unsplash.com/photo-1464306076886-debca5e8a6b0?fit=crop&w=500&q=80" alt="Interiors">
      <!-- Replace with your actual restaurant images -->
    </div>
  </section>

  <section id="reviews" class="reviews">
    <h2>Customer Reviews</h2>
    <blockquote>
      "Lip-smacking food and great value for money!"
    </blockquote>
    <blockquote>
      "Love the variety for vegetarians!"
    </blockquote>
    <blockquote>
      "Best spot for office lunch."
    </blockquote>
    <div class="rating-summary">
      Dining: ★ 3.0 (68 ratings) &nbsp;|&nbsp; Delivery: ★ 4.1 (856 ratings)
    </div>
  </section>

  <section id="order" class="order-online">
    <h2>Order Online</h2>
    <p>Online ordering is currently closed.<br>
       Please use our mobile app to order.</p>
    <a class="cta" href="#">Download the App</a>
  </section>

  <footer>
    <div>
      <strong>SAM Chinese Corner</strong> <br>
      Plot 267, Munna Compound, Pimpri Pada, Gen.A.K.V Marg, Near Amar Chemist, Near Patanjali Mega Store, Malad East, Mumbai <br>
      Open: 11am – 12midnight | Phone: +912228425454
    </div>
    <div class="footer-links">
      <span>Follow us:</span>
      <a href="#">Instagram</a>
      <a href="#">Facebook</a>
      <a href="#">WhatsApp</a>
    </div>
    <div>
      © 2025 SAM Chinese Corner. All rights reserved.
    </div>
  </footer>
</body>
</html>
body {
  font-family: 'Segoe UI', Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #fff;
  color: #262626;
}

header {
  background: #c62828;
  color: #fff;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 18px 8%;
}

.logo {
  font-size: 1.5em;
  font-weight: bold;
}

nav a {
  color: #fff;
  text-decoration: none;
  margin: 0 20px;
  font-weight: bold;
  letter-spacing: 1px;
}

nav a:hover {
  color: #ffc107;
}

.hero {
  background: url('https://images.unsplash.com/photo-1504674900247-0877df9cc836?fit=crop&w=1000&q=80') center/cover no-repeat;
  color: #fff;
  text-align: center;
  padding: 80px 15px 60px 15px;
  position: relative;
}

.hero::before {
  content: "";
  background: rgba(198, 40, 40, 0.7);
  position: absolute;
  top: 0; left: 0; right: 0; bottom: 0;
}

.hero > * {
  position: relative;
  z-index: 1;
}

.hero h1 {
  font-size: 3em;
}

.hero .ratings span {
  margin: 0 14px;
  font-size: 1.1em;
}

.cta {
  display: inline-block;
  margin: 18px 10px 0 10px;
  padding: 12px 25px;
  background: #ffc107;
  color: #a62828;
  border-radius: 24px;
  text-decoration: none;
  font-weight: bold;
  transition: background 0.2s;
}
.cta.outline {
  background: transparent;
  color: #fff;
  border: 2px solid #ffc107;
}

.cta:hover {
  background: #fff8e1;
}

section {
  padding: 64px 8%;
  max-width: 1200px;
  margin: 0 auto;
}

.about ul {
  list-style: none;
  padding: 0;
}

.about .features {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: 16px;
}

.about .features div {
  background: #ffe0b2;
  color: #a62828;
  padding: 7px 18px;
  border-radius: 12px;
  font-size: 1em;
}

.menu {
  background: #f9f9f9;
}

.menu-categories details {
  margin-bottom: 14px;
  border-radius: 8px;
  padding: 6px 0;
  background: #fff;
  box-shadow: 0 2px 6px #0001;
}

.menu-categories summary {
  cursor: pointer;
  font-weight: bold;
  font-size: 1.1em;
  color: #c62828;
  padding: 10px 14px;
  outline: none;
}

.menu-categories ul {
  padding-left: 32px;
}

.gallery {
  background: #fff8e1;
}

.gallery-images {
  display: flex;
  flex-wrap: wrap;
  gap: 16px;
}

.gallery-images img {
  border-radius: 14px;
  width: 300px;
  height: 200px;
  object-fit: cover;
  box-shadow: 0 2px 8px #fa6a6a33;
}

.reviews blockquote {
  font-style: italic;
  background: #fde0dc;
  margin: 20px 0;
  border-left: 4px solid #c62828;
  padding: 18px 24px;
  border-radius: 8px;
}

.rating-summary {
  margin-top: 18px;
  font-weight: bold;
}

.order-online {
  text-align: center;
  background: #fff3e0;
  border-radius: 12px;
}

footer {
  background: #c62828;
  color: #fff8e1;
  padding: 24px 8%;
  text-align: center;
  font-size: 1em;
}

.footer-links {
  margin: 12px 0;
}

.footer-links a {
  color: #fff8e1;
  margin: 0 6px;
  text-decoration: underline;
}

@media (max-width: 800px) {
  .gallery-images {
    flex-direction: column;
    align-items: center;
  }
  section {
    padding: 40px 4%;
  }
  header {
    flex-direction: column;
    gap: 10px;
  }
}

