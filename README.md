<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kundan Art | Kundan & Jadau Jewellery</title>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

  <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@500;700&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:'Poppins',sans-serif;
    }

    body{
      background:#fffaf5;
      color:#333;
    }

    h1,h2,h3{
      font-family:'Cinzel',serif;
    }

    .hero{
      height:100vh;
      background:linear-gradient(rgba(0,0,0,0.6),rgba(0,0,0,0.6)),
      url('https://images.unsplash.com/photo-1617038220319-276d3cfab638?auto=format&fit=crop&w=1600&q=80');
      background-size:cover;
      background-position:center;
      display:flex;
      align-items:center;
      justify-content:center;
      text-align:center;
      color:#fff;
      padding:20px;
    }

    .hero-content{
      max-width:800px;
    }

    .hero h1{
      font-size:4rem;
      margin-bottom:20px;
    }

    .hero p{
      font-size:1.1rem;
      line-height:1.8;
      margin-bottom:30px;
    }

    .btn{
      display:inline-block;
      background:#c79a2d;
      color:#fff;
      text-decoration:none;
      padding:14px 32px;
      border-radius:30px;
      font-weight:600;
    }

    section{
      padding:80px 10%;
    }

    .about{
      display:grid;
      grid-template-columns:1fr 1fr;
      gap:50px;
      align-items:center;
    }

    .about img{
      width:100%;
      border-radius:20px;
    }

    .about p{
      line-height:1.9;
      margin-top:20px;
      color:#555;
    }

    .collection{
      background:#f7efe5;
      text-align:center;
    }

    .cards{
      margin-top:40px;
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:25px;
    }

    .card{
      background:#fff;
      border-radius:18px;
      overflow:hidden;
      box-shadow:0 10px 25px rgba(0,0,0,0.08);
    }

    .card img{
      width:100%;
      height:250px;
      object-fit:cover;
    }

    .card h3{
      padding:20px 20px 10px;
    }

    .card p{
      padding:0 20px 25px;
      color:#666;
    }

    footer{
      background:#2c1c0c;
      color:#fff;
      text-align:center;
      padding:30px 20px;
    }

    @media(max-width:768px){

      .hero h1{
        font-size:2.8rem;
      }

      .about{
        grid-template-columns:1fr;
      }
    }
  </style>
</head>

<body>

  <section class="hero">
    <div class="hero-content">
      <h1>Kundan Art</h1>
      <p>
        Discover the timeless beauty of handcrafted Kundan and Jadau jewellery inspired by India's royal heritage.
        Every piece reflects elegance, tradition, and exquisite craftsmanship.
      </p>

      <a href="#collections" class="btn">Explore Collection</a>
    </div>
  </section>

  <section class="about">
    <div>
      <img src="https://images.unsplash.com/photo-1611652022419-a9419f74343d?auto=format&fit=crop&w=1000&q=80" alt="Kundan Jewellery">
    </div>

    <div>
      <h2>About Kundan & Jadau Jewellery</h2>

      <p>
        Kundan jewellery is one of India's oldest and most celebrated jewellery styles, known for its intricate designs and use of highly refined gold foil to set precious stones.
      </p>

      <p>
        Jadau jewellery is a traditional art form that originated in the royal courts of Rajasthan and Gujarat. Skilled artisans handcraft each piece by embedding gemstones into gold without adhesives, creating magnificent heirloom jewellery.
      </p>

      <p>
        At Kundan Art, we preserve these timeless techniques while creating designs for modern celebrations and special occasions.
      </p>
    </div>
  </section>

  <section class="collection" id="collections">
    <h2>Our Signature Collections</h2>

    <div class="cards">

      <div class="card">
        <img src="https://images.unsplash.com/photo-1627293509201-cd0c78004317?auto=format&fit=crop&w=800&q=80" alt="Bridal Collection">
        <h3>Bridal Collection</h3>
        <p>Luxurious handcrafted sets designed for weddings and grand celebrations.</p>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1617038260897-41a1f14a8ca6?auto=format&fit=crop&w=800&q=80" alt="Necklaces">
        <h3>Necklaces</h3>
        <p>Elegant Kundan and Jadau necklaces crafted with intricate detailing.</p>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1603974372039-adc49044b6bd?auto=format&fit=crop&w=800&q=80" alt="Earrings">
        <h3>Earrings</h3>
        <p>Traditional earrings designed to complement every festive occasion.</p>
      </div>

    </div>
  </section>

  <footer>
    <p>© 2026 Kundan Art | Celebrating the Heritage of Kundan & Jadau Jewellery</p>
  </footer>

</body>
</html>
