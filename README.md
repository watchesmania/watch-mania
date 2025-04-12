<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Watches Mania</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Roboto&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Roboto', sans-serif;
    }

    body {
      background-color: #000;
      color: #fff;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      background-color: #111;
      border-bottom: 1px solid #444;
    }

    .logo {
      font-family: 'Playfair Display', serif;
      font-size: 28px;
      font-weight: bold;
      color: #fff;
    }

    nav a {
      margin: 0 15px;
      color: #aaa;
      text-decoration: none;
      font-size: 16px;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #fff;
    }

    .search-bar {
      background: #222;
      border: none;
      border-radius: 5px;
      padding: 8px 12px;
      color: white;
      width: 200px;
      transition: width 0.3s;
    }

    .search-bar:focus {
      width: 250px;
      outline: none;
    }

    .tagline {
      text-align: center;
      padding: 40px 20px;
      font-size: 22px;
      font-style: italic;
      color: #ccc;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 40px;
      padding: 40px;
    }

    .product {
      background-color: #111;
      border: 1px solid #333;
      padding: 20px;
      text-align: center;
      border-radius: 10px;
      transition: transform 0.3s;
    }

    .product:hover {
      transform: scale(1.05);
    }

    .product img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
    }

    .product h3 {
      margin: 15px 0 5px;
      font-size: 18px;
      color: #eee;
    }

    .product p {
      color: #bbb;
      margin: 5px 0;
    }

    .product .price {
      color: #f00;
      font-weight: bold;
      margin-top: 10px;
    }

    footer {
      background-color: #111;
      color: #888;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }
  </style>
</head>

<body>
  <header>
    <div class="logo">Watches Mania</div>
    <nav>
      <a href="#">Home</a>
      <a href="#">Collection</a>
      <a href="#">Cart</a>
    </nav>
    <input type="text" class="search-bar" placeholder="Search watches...">
  </header>

  <div class="tagline">For 20 years, Watches Mania has defined its own path. Today, that story continues with five new releases.</div>

  <section class="products">
    <div class="product">
      <img src="https://i.imgur.com/OVQ2IjJ.png" alt="Titanium Ceramic" />
      <h3>20th Anniversary Titanium Ceramic 43 MM</h3>
      <p class="price">INR 1,890,000</p>
    </div>
    <div class="product">
      <img src="https://i.imgur.com/kMXqTcy.png" alt="King Gold Ceramic" />
      <h3>20th Anniversary King Gold Ceramic 43 MM</h3>
      <p class="price">INR 3,490,000</p>
    </div>
    <div class="product">
      <img src="https://i.imgur.com/GItlBcm.png" alt="All Black" />
      <h3>20th Anniversary All Black 43 MM</h3>
      <p class="price">INR 2,290,000</p>
    </div>
    <div class="product">
      <img src="https://i.imgur.com/qcL3LZ0.png" alt="Red Magic" />
      <h3>20th Anniversary Red Magic 43 MM</h3>
      <p class="price">INR 2,890,000</p>
    </div>
    <div class="product">
      <img src="https://i.imgur.com/1v2JuZn.png" alt="Full Magic Gold" />
      <h3>20th Anniversary Full Magic Gold 43 MM</h3>
      <p class="price">INR 3,690,000</p>
    </div>
  </section>

  <footer>
    Contact us: watchmania@gmail.com | +91 8800403563<br>
    &copy; 2025 Watches Mania. All rights reserved.
  </footer>
</body>

</html>
