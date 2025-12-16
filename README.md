<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Kade's Music Hub</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; }
    nav { background: #333; padding: 10px; }
    nav a { color: white; margin: 0 15px; text-decoration: none; }
    nav a:hover { text-decoration: underline; }
    section { padding: 20px; }
    .product { border: 1px solid #ccc; padding: 10px; margin: 10px 0; }
    iframe { width: 560px; height: 315px; }
  </style>
</head>
<body>
  <nav>
    <a href="#shop">Shop</a>
    <a href="#videos">Videos</a>
  </nav>

  <section id="shop">
    <h2>Shop Tabs</h2>
    <div class="product">
      <h3>Guitar Tab 1</h3>
      <p>Price: $5</p>
      <button>Buy Now</button>
    </div>
    <div class="product">
      <h3>Guitar Tab 2</h3>
      <p>Price: $7</p>
      <button>Buy Now</button>
    </div>
  </section>

  <section id="videos">
    <h2>Performance Videos</h2>
    <!-- Replace the src with your actual YouTube video link -->
    <iframe src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>
    <iframe src="https://www.youtube.com/embed/ANOTHER_VIDEO_ID" frameborder="0" allowfullscreen></iframe>
  </section>
</body>
</html>
