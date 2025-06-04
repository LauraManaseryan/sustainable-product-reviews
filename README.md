<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sustainable Product Reviews</title>
  <link rel="stylesheet" href="css/style.css">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

  <header class="hero">
    <h1>Welcome to Sustainable Product Reviews</h1>
    <p>We highlight eco-conscious brands and products—from clothing and food to tech and home goods—that help protect the planet while enhancing your lifestyle.</p>
    <a href="#categories" class="button">Explore Top Picks</a>
  </header>

  <section class="cards" id="categories">
    <div class="card">
      <img src="images/clothing.png" alt="Clothing">
      <h3>Eco-Friendly Clothing</h3>
      <p>Explore brands using organic cotton, recycled fabrics, and fair-trade production.</p>
    </div>

    <div class="card">
      <img src="images/food.png" alt="Food">
      <h3>Conscious Food Products</h3>
      <p>From plant-based snacks to regenerative farming goods—see what's truly sustainable.</p>
    </div>

    <div class="card">
      <img src="images/tech.png" alt="Tech">
      <h3>Green Tech</h3>
      <p>Discover solar-powered gadgets, e-waste-conscious devices, and energy-saving tools.</p>
    </div>
  </section>

  <section class="comparison">
    <h2>Traditional vs. Green Brands</h2>
    <table>
      <tr>
        <th>Aspect</th>
        <th>Traditional Products</th>
        <th>Sustainable Products</th>
      </tr>
      <tr>
        <td>Packaging</td>
        <td>Single-use plastic</td>
        <td>Recycled or biodegradable</td>
      </tr>
      <tr>
        <td>Materials</td>
        <td>Non-renewable/synthetic</td>
        <td>Organic, upcycled, or compostable</td>
      </tr>
      <tr>
        <td>Carbon Footprint</td>
        <td>High emissions</td>
        <td>Low to neutral</td>
      </tr>
    </table>
  </section>

  <section class="explore">
    <h2>Explore Our Reviews</h2>
    <div class="explore-cards">
      <div class="explore-card">
        <h3>User Stories</h3>
        <p>Real people. Real reviews. See how eco-products changed their habits.</p>
      </div>
      <div class="explore-card">
        <h3>Product Spotlights</h3>
        <p>We highlight the top-performing sustainable products monthly.</p>
      </div>
      <div class="explore-card">
        <h3>News & Trends</h3>
        <p>Stay updated on green tech innovations and conscious living tips.</p>
      </div>
    </div>
  </section>

  <footer>
    <p>© 2025 Laura Manaseryan | Designed for a Greener Future</p>
  </footer>

</body>
</html>
/* style.css */
body {
  margin: 0;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: #f5fdf5;
  color: #2e4d2e;
  line-height: 1.6;
}

.hero {
  background: linear-gradient(to right, #46c67f, #34aadc);
  color: white;
  text-align: center;
  padding: 60px 20px;
}

.hero h1 {
  font-size: 2.8em;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.2em;
  margin-bottom: 20px;
}

.button {
  background-color: #ff6600;
  color: white;
  padding: 12px 24px;
  text-decoration: none;
  font-weight: bold;
  border-radius: 8px;
  display: inline-block;
  transition: background 0.3s ease;
}

.button:hover {
  background-color: #e65c00;
}

.cards {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  padding: 40px 20px;
  gap: 20px;
  background-color: #fff;
}

.card {
  background-color: #ffffff;
  border-radius: 10px;
  padding: 20px;
  width: 300px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  text-align: center;
}

.card img {
  width: 60px;
  margin-bottom: 10px;
}

.card h3 {
  color: #216e21;
  margin-bottom: 10px;
}

.comparison {
  padding: 40px 20px;
  background-color: #e9f5e9;
  text-align: center;
}

.comparison h2 {
  margin-bottom: 20px;
}

table {
  width: 90%;
  max-width: 800px;
  margin: auto;
  border-collapse: collapse;
  background-color: #fff;
}

table, th, td {
  border: 1px solid #cdeac0;
}

th, td {
  padding: 12px;
  text-align: left;
}

th {
  background-color: #b2e4b2;
}

.explore {
  background-color: #f4fff4;
  padding: 40px 20px;
  text-align: center;
}

.explore-cards {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
}

.explore-card {
  background-color: #fff;
  width: 280px;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.1);
}

.explore-card h3 {
  color: #2c7a2c;
  margin-bottom: 10px;
}

footer {
  background-color: #216e21;
  color: white;
  text-align: center;
  padding: 20px;
  font-size: 0.9em;
  margin-top: 40px;
}
