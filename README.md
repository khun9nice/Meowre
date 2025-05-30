<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1.0">
  <title>MeowRé - The Cat’s Way to Fashion</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Roboto:wght@400&display=swap" rel="stylesheet">
  <style>
    body {
      background: #fff;
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      color: #222;
    }
    header {
      padding: 32px 0 16px 0;
      text-align: center;
    }
    .logo {
      width: 110px;
      margin-bottom: 12px;
    }
    nav {
      margin-bottom: 24px;
    }
    nav a {
      text-decoration: none;
      color: #222;
      font-weight: bold;
      margin: 0 18px;
      font-size: 17px;
      letter-spacing: 1px;
      font-family: 'Playfair Display', serif;
      transition: color 0.2s;
    }
    nav a:hover {
      color: #a0a0a0;
    }
    .banner {
      background: #111;
      color: #fff;
      font-family: 'Playfair Display', serif;
      padding: 38px 0 26px 0;
      text-align: center;
      font-size: 1.6em;
      letter-spacing: 2px;
    }
    .shop-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 38px;
      padding: 45px 7vw;
      max-width: 1020px;
      margin: auto;
    }
    .product-card {
      background: #f9f9f9;
      border-radius: 18px;
      box-shadow: 0 3px 16px rgba(0,0,0,0.06);
      text-align: center;
      padding: 26px 18px 20px 18px;
      transition: box-shadow 0.2s;
    }
    .product-card:hover {
      box-shadow: 0 7px 22px rgba(0,0,0,0.11);
    }
    .prod-img {
      width: 92px;
      height: 92px;
      background: #ddd;
      border-radius: 12px;
      margin-bottom: 16px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.6em;
      color: #bbb;
    }
    .prod-name {
      font-family: 'Playfair Display', serif;
      font-size: 1.13em;
      font-weight: bold;
      margin-bottom: 6px;
    }
    .prod-price {
      color: #292929;
      font-size: 1.07em;
      margin-bottom: 14px;
    }
    .buy-btn {
      background: #000;
      color: #fff;
      border: none;
      border-radius: 2em;
      padding: 8px 28px;
      font-size: 1em;
      cursor: pointer;
      letter-spacing: 1px;
      font-family: 'Roboto', sans-serif;
      transition: background 0.2s;
    }
    .buy-btn:hover {
      background: #333;
    }
    .contact-bar {
      margin: 50px 0 28px 0;
      text-align: center;
      font-size: 1.08em;
    }
    .contact-bar a {
      color: #111;
      text-decoration: none;
      margin: 0 12px;
      border-bottom: 1px solid #e0e0e0;
      transition: border-color 0.2s;
    }
    .contact-bar a:hover {
      border-bottom: 1px solid #000;
    }
    @media (max-width:600px) {
      .shop-grid {
        padding: 25px 3vw;
        gap: 18px;
      }
      header {
        padding: 22px 0 7px 0;
      }
      .banner {
        font-size: 1.1em;
        padding: 20px 0 13px 0;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="https://i.imgur.com/vgL4XfE.png" class="logo" alt="MeowRé Logo"><br>
    <nav>
      <a href="#">Home</a>
      <a href="#shop">Shop</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  <div class="banner">
    The Cat’s Way to Fashion – MeowRé
  </div>
  <div id="shop" class="shop-grid">
    <div class="product-card">
      <div class="prod-img">👕</div>
      <div class="prod-name">Meowré Classic Tee</div>
      <div class="prod-price">฿790</div>
      <button class="buy-btn" onclick="alert('โปรดแอดไลน์ @meowre เพื่อสั่งซื้อ')">สั่งซื้อ</button>
    </div>
    <div class="product-card">
      <div class="prod-img">👜</div>
      <div class="prod-name">Meowré Cat Bag</div>
      <div class="prod-price">฿1,390</div>
      <button class="buy-btn" onclick="alert('โปรดแอดไลน์ @meowre เพื่อสั่งซื้อ')">สั่งซื้อ</button>
    </div>
  </div>
  <div id="contact" class="contact-bar">
    Line: <a href="https://line.me/R/ti/p/@meowre" target="_blank">@meowre</a>
    | IG: <a href="https://instagram.com/meowre.official" target="_blank">@meowre.official</a>
    | FB: <a href="https://facebook.com/meowre.brand" target="_blank">meowre.brand</a>
  </div>
</body>
</html>
