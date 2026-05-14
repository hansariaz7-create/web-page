<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hansa Jasmine Bloom</title>
  <style>
    body {
      font-family: 'Georgia', serif;
      margin: 0;
      background: linear-gradient(135deg, #fffbea, #fdf6f0); /* soft jasmine cream */
      color: #3a3a3a;
    }

    /* Header */
    header {
      background: #f8f0c6; /* jasmine yellow */
      padding: 25px;
      text-align: center;
      border-bottom: 3px solid #d4a373; /* soft golden brown */
    }
    header h1 {
      margin: 0;
      font-size: 2.6rem;
      color: #124d12;
      letter-spacing: 2px;
      font-style: italic;
    }

    /* Navbar */
    nav {
      background-color: #fff0f5; /* jasmine pink */
      display: flex;
      justify-content: center;
      padding: 14px;
      border-bottom: 2px solid #d4a373;
    }
    nav a {
      margin: 0 20px;
      text-decoration: none;
      color: #7a4b2f; /* brownish gold */
      font-weight: bold;
      transition: 0.3s;
    }
    nav a:hover {
      color: #d4a373; /* soft gold */
    }

    /* Hero Section */
    .hero {
      text-align: center;
      padding: 100px 20px;
      background: url('https://images.unsplash.com/photo-1501004318641-b39e6451bec6?auto=format&fit=crop&w=1400&q=80') no-repeat center/cover;
      color: #fff;
      position: relative;
    }
    .hero::after {
      content: "";
      position: absolute;
      inset: 0;
      background: rgba(240, 220, 180, 0.5); /* soft golden overlay */
    }
    .hero h2 {
      position: relative;
      font-size: 3rem;
      margin-bottom: 15px;
      text-shadow: 2px 2px 6px rgba(0,0,0,0.5);
      color: #318563;
    }
    .hero p {
      position: relative;
      font-size: 1.3rem;
      color: #fff0f5;
    }

    /* About Section */
    .about {
      padding: 60px;
      text-align: center;
      background: #fffdf5;
      border-top: 2px solid #d4a373;
      border-bottom: 2px solid #d4a373;
    }
    .about h2 {
      color: #7a4b2f;
      margin-bottom: 20px;
      font-size: 2rem;
      font-style: italic;
    }
    .about p {
      font-size: 1.1rem;
      line-height: 1.7;
      max-width: 750px;
      margin: auto;
      color: #555;
    }

    /* Products Section */
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 30px;
      padding: 60px;
      background: #fffbea;
    }
    .product {
      background: #fff0f5;
      border-radius: 12px;
      padding: 25px;
      text-align: center;
      box-shadow: 0 6px 14px rgba(0,0,0,0.1);
      border: 1px solid #f8d7da;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .product:hover {
      transform: translateY(-8px);
      box-shadow: 0 10px 22px rgba(0,0,0,0.2);
      border-color: #d4a373;
    }
    .product img {
      width: 140px;
      height: 180px;
      object-fit: cover;
      margin-bottom: 14px;
      border-radius: 10px;
      border: 2px solid #d4a373;
    }
    .product h3 {
      color: #7a4b2f;
      margin-bottom: 8px;
    }
    .product p {
      color: #555;
    }

    /* Footer */
    footer {
      text-align: center;
      background: #f8f0c6;
      padding: 20px;
      margin-top: 20px;
      border-top: 3px solid #d4a373;
      color: #7a4b2f;
      font-weight: bold;
      letter-spacing: 1px;
      font-style: italic;
    }
  </style>
</head>
<body>
  <header>
    <h1>Hansa Jasmine Bloom</h1>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Collections</a>
    <a href="#">Contact</a>
  </nav>

  <section class="hero">
    <h2>The Essence of Jasmine, with Hansa’s fragrance</h2>
    <p>Pure. Elegant. Timeless Bloom.</p>



  </section>

  <section class="about">
    <h2>About Us</h2>
    <p>
      At <b>Hansa Jasmine Bloom</b>, we believe every fragrance tells a story.  
      Our perfumes are inspired by the natural beauty of jasmine flowers, blended  
      with timeless elegance and a touch of golden warmth. A fragrance that feels  
      like love at first bloom. 
    </p>
  </section>

  <section class="products">
    <div class="product">
      <img src="https://cdn2.parfumdreams.de/image/product/138118-223863-8-8.webp?box=528" alt="Perfume 1">
      <h3>Golden Jasmine</h3>
      <p>Warm jasmine notes with golden undertones.</p>
    </div>
    <div class="product">
      <img src="https://unicoscents.com/cdn/shop/files/pink-bloom-inspired-by-ysl-1128880.webp?v=1755175176" alt="Perfume 2">
      <h3>Pink Bloom</h3>
      <p>Fresh jasmine with a soft pink floral finish.</p>
    </div>
    <div class="product">
      <img src="https://m.media-amazon.com/images/I/51lkmmpYv9L._UF894,1000_QL80_.jpg" alt="Perfume 3">
      <h3>Classic Essence</h3>
      <p>A timeless jasmine blend for elegant souls.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Hansa Jasmine Bloom | Pure Elegance in Every Drop</p>
  </footer>
</body>
</html>
