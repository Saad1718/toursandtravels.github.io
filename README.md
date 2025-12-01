# toursandtravels.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tours & Travels</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f0f0f0;
    }
    header {
      background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e')
        center/cover no-repeat;
      height: 90vh;
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
    }
    header h1 {
      font-size: 3rem;
      margin: 0;
    }
    header p {
      font-size: 1.2rem;
      max-width: 600px;
    }
    .btn {
      margin-top: 20px;
      padding: 12px 24px;
      background: #ff9800;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      font-size: 1.1rem;
    }
    .section {
      padding: 50px 20px;
      text-align: center;
      background: white;
      margin-top: -40px;
      border-radius: 20px 20px 0 0;
    }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }
    .card {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    .card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 10px;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #222;
      color: #fff;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Explore The World With Us</h1>
    <p>Your dream destinations, unforgettable experiences, and hassle-free trips— all in one place.</p>
    <a class="btn" href="#packages">View Packages</a>
  </header>

  <section class="section" id="packages">
    <h2>Popular Tour Packages</h2>
    <div class="cards">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1493558103817-58b2924bce98" />
        <h3>Beach Paradise</h3>
        <p>Enjoy the most beautiful beaches with clear blue waters.</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee" />
        <h3>Mountain Adventure</h3>
        <p>Perfect for trekkers and nature lovers.</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1469474968028-56623f02e42e" />
        <h3>City Tours</h3>
        <p>Experience the best urban destinations around the world.</p>
      </div>
    </div>
  </section>

  <footer>
    © 2025 Tours & Travels | All Rights Reserved
  </footer>
</body>
</html>
