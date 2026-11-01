# haniffrozenfoods.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hanif Frozen Foods | Freshness Preserved, Quality Delivered</title>
  <style>
    /* Global Styles & Reset */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background: linear-gradient(135deg, #e0f7fa 0%, #b2ebf2 40%, #80deea 100%);
      color: #00363a;
      min-height: 100vh;
      line-height: 1.6;
    }

    /* Header / Navbar */
    header {
      background-color: rgba(0, 77, 96, 0.9);
      backdrop-filter: blur(8px);
      color: #ffffff;
      padding: 20px 10%;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.15);
    }

    header h1 {
      font-size: 2.2rem;
      letter-spacing: 1px;
      font-weight: 700;
      color: #e0f7fa;
      text-shadow: 0 2px 4px rgba(0,0,0,0.3);
    }

    /* Main Container */
    .container {
      max-width: 900px;
      margin: 30px auto;
      padding: 0 20px;
    }

    /* Glassmorphism Card Style */
    .card {
      background: rgba(255, 255, 255, 0.85);
      backdrop-filter: blur(10px);
      border-radius: 16px;
      padding: 30px;
      margin-bottom: 30px;
      box-shadow: 0 8px 25px rgba(0, 150, 136, 0.15);
      border: 1px solid rgba(255, 255, 255, 0.6);
    }

    /* Hero & Shortened Ad Section */
    .hero {
      text-align: center;
      padding: 40px 20px;
    }

    .hero h2 {
      font-size: 1.8rem;
      color: #006064;
      margin-bottom: 10px;
    }

    .hero .tagline {
      font-weight: 600;
      color: #00838f;
      font-size: 1.1rem;
      margin-bottom: 15px;
    }

    .hero p {
      font-size: 1.05rem;
      color: #004d40;
      max-width: 650px;
      margin: 0 auto 25px auto;
    }

    /* CTA Button */
    .btn-products {
      display: inline-block;
      background: linear-gradient(135deg, #00838f 0%, #00acc1 100%);
      color: #ffffff;
      padding: 14px 28px;
      font-size: 1.1rem;
      font-weight: bold;
      text-decoration: none;
      border-radius: 30px;
      box-shadow: 0 4px 12px rgba(0, 131, 143, 0.4);
      transition: all 0.3s ease;
    }

    .btn-products:hover {
      background: linear-gradient(135deg, #006064 0%, #00838f 100%);
      transform: translateY(-2px);
      box-shadow: 0 6px 16px rgba(0, 131, 143, 0.5);
    }

    /* Contact Details Section */
    .contact-info {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }

    .contact-item {
      background: rgba(224, 247, 250, 0.7);
      padding: 15px;
      border-radius: 10px;
      display: flex;
      align-items: center;
      gap: 12px;
      border: 1px solid #b2ebf2;
    }

    .contact-item span {
      font-size: 1.4rem;
    }

    .contact-item a {
      color: #006064;
      text-decoration: none;
      font-weight: 600;
    }

    .contact-item a:hover {
      text-decoration: underline;
    }

    /* Table Section */
    .section-title {
      font-size: 1.6rem;
      color: #006064;
      margin-bottom: 20px;
      text-align: center;
    }

    .table-wrapper {
      overflow-x: auto;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    }

    table {
      width: 100%;
      border-collapse: collapse;
      background-color: #ffffff;
      text-align: left;
    }

    th {
      background-color: #00838f;
      color: #ffffff;
      padding: 14px 18px;
      font-size: 1.05rem;
    }

    td {
      padding: 14px 18px;
      border-bottom: 1px solid #e0f7fa;
      color: #004d40;
      font-size: 1rem;
    }

    tr:nth-child(even) {
      background-color: #f4fbfb;
    }

    tr:hover {
      background-color: #e0f7fa;
    }

    .status-badge {
      display: inline-block;
      background-color: #e8f5e9;
      color: #2e7d32;
      padding: 4px 10px;
      border-radius: 12px;
      font-size: 0.85rem;
      font-weight: 600;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 25px;
      color: #004d40;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>❄️ Hanif Frozen Foods</h1>
  </header>

  <div class="container">

    <!-- Hero Card / Shortened Ad Note -->
    <div class="card hero">
      <h2>Welcome to Hanif Frozen Foods!</h2>
      <p class="tagline">Freshness Preserved, Quality Delivered.</p>
      <p>We supply premium, hygienically packaged frozen foods at affordable prices—perfect for your home or events.</p>
      <a href="#products" class="btn-products">❄️ Our Product List</a>
    </div>

    <!-- Contact Details Card -->
    <div class="card">
      <h3 class="section-title">Get in Touch / Place an Order</h3>
      <div class="contact-info">
        <div class="contact-item">
          <span>📱</span>
          <div>
            <strong>Phone / WhatsApp:</strong><br>
            <a href="tel:08028031430">08028031430</a>
          </div>
        </div>

        <div class="contact-item">
          <span>✉️</span>
          <div>
            <strong>Email:</strong><br>
            <a href="mailto:kuburatabiola6a@gmail.com">kuburatabiola6a@gmail.com</a>
          </div>
        </div>

        <div class="contact-item">
          <span>📍</span>
          <div>
            <strong>Address:</strong><br>
            10, Ile Eyo, Afobaje, Ota, Ogun State, Nigeria.
          </div>
        </div>
      </div>
    </div>

    <!-- Product List Table Card -->
    <div class="card" id="products">
      <h3 class="section-title">📦 Available Products</h3>
      <div class="table-wrapper">
        <table>
          <thead>
            <tr>
              <th>S/N</th>
              <th>Item Description</th>
              <th>Category</th>
              <th>Availability</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>1</td>
              <td><strong>Chicken Laps</strong></td>
              <td>Chicken</td>
              <td><span class="status-badge">In Stock</span></td>
            </tr>
            <tr>
              <td>2</td>
              <td><strong>Chicken Wings</strong></td>
              <td>Chicken</td>
              <td><span class="status-badge">In Stock</span></td>
            </tr>
            <tr>
              <td>3</td>
              <td><strong>Chicken Gizzards</strong></td>
              <td>Chicken</td>
              <td><span class="status-badge">In Stock</span></td>
            </tr>
            <tr>
              <td>4</td>
              <td><strong>Turkey Wings (Blanket)</strong></td>
              <td>Turkey</td>
              <td><span class="status-badge">In Stock</span></td>
            </tr>
            <tr>
              <td>5</td>
              <td><strong>Turkey Gizzards</strong></td>
              <td>Turkey</td>
              <td><span class="status-badge">In Stock</span></td>
            </tr>
            <tr>
              <td>6</td>
              <td><strong>Turkey Fingers</strong></td>
              <td>Turkey</td>
              <td><span class="status-badge">In Stock</span></td>
            </tr>
            <tr>
              <td>7</td>
              <td><strong>Normal Turkey</strong></td>
              <td>Turkey</td>
              <td><span class="status-badge">In Stock</span></td>
            </tr>
            <tr>
              <td>8</td>
              <td><strong>Croaker Fish</strong></td>
              <td>Fish</td>
              <td><span class="status-badge">In Stock</span></td>
            </tr>
            <tr>
              <td>9</td>
              <td><strong>Herrings (Sawa)</strong></td>
              <td>Fish</td>
              <td><span class="status-badge">In Stock</span></td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>

  </div>

  <!-- Footer -->
  <footer>
    <p>&copy; Hanif Frozen Foods. All Rights Reserved.</p>
  </footer>

</body>
</html>
