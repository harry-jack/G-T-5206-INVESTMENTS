<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>G&T 5206 Investments — Truck Dispatch Services</title>
  <meta name="description" content="Professional truck dispatch services for Dry Van, Reefer, Power Only." />
  <style>
    :root {
      --primary: #0d4d92;
      --accent: #ff9800;
      --bg: #f5f7fa;
      --text: #1a1a1a;
    }
    *{box-sizing:border-box;margin:0;padding:0;}
    body{font-family:Arial, sans-serif;color:var(--text);background:var(--bg);line-height:1.6;}
    .container{max-width:1100px;margin:auto;padding:20px;}
    header{background:#fff;padding:20px 0;text-align:center;box-shadow:0 2px 4px rgba(0,0,0,0.1);}
    header h1{color:var(--primary);font-size:2rem;}
    .hero{position:relative;margin:20px 0;}
    .hero img{width:100%;border-radius:8px;object-fit:cover;height:280px;}
    .hero-overlay{position:absolute;top:0;left:0;width:100%;height:100%;background:rgba(0,0,0,0.4);border-radius:8px;display:flex;flex-direction:column;justify-content:center;align-items:center;color:white;text-align:center;padding:10px;}
    .hero-overlay h2{font-size:2rem;margin-bottom:10px;}
    .btn{display:inline-block;padding:12px 24px;border-radius:5px;text-decoration:none;font-weight:bold;margin:5px;}
    .btn-primary{background:var(--primary);color:white;}
    .btn-secondary{background:var(--accent);color:white;}
    .services{display:flex;flex-wrap:wrap;gap:20px;margin-top:20px;}
    .service{background:white;padding:20px;border-radius:5px;flex:1;min-width:200px;box-shadow:0 2px 6px rgba(0,0,0,0.05);}
    .service h3{margin-bottom:8px;color:var(--primary);}
    form{background:white;padding:20px;border-radius:8px;box-shadow:0 2px 6px rgba(0,0,0,0.05);margin-top:20px;}
    form label{display:block;margin:10px 0 5px;}
    form input, form textarea{width:100%;padding:10px;border:1px solid #ccc;border-radius:4px;}
    footer{text-align:center;padding:15px 0;margin-top:30px;background:#fff;color:#555;}
  </style>
</head>
<body>

  <header>
    <h1>G&T 5206 Investments</h1>
    <p>Dry Van • Reefer • Power Only Dispatch Services</p>
  </header>

  <div class="container">
    <div class="hero">
      <img src="https://via.placeholder.com/1100x280?text=Truck+Dispatching+on+Road" alt="Truck Dispatching Banner">
      <div class="hero-overlay">
        <h2>Expert Dispatch Nationwide</h2>
        <p>We secure high-paying loads, manage broker relations, and keep your trucks moving.</p>
        <div>
          <a href="mailto:hashmiumaiz@gmail.com" class="btn btn-primary">Request a Quote</a>
          <a href="tel:+12765005667" class="btn btn-secondary">Call (276) 500-5667</a>
        </div>
      </div>
    </div>

    <section class="services">
      <div class="service">
        <h3>Dry Van (53')</h3>
        <p>Regional and long-haul lanes with steady volume and optimized routing.</p>
      </div>
      <div class="service">
        <h3>Reefer</h3>
        <p>Temperature-sensitive freight handling with precise timing.</p>
      </div>
      <div class="service">
        <h3>Power Only</h3>
        <p>Flexible drop-and-hook arrangements and dedicated power-only solutions.</p>
      </div>
    </section>

    <section>
      <h2>Request a Quote</h2>
      <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
        <label for="name">Name</label>
        <input id="name" name="name" required />
        <label for="email">Email</label>
        <input id="email" type="email" name="email" required />
        <label for="phone">Phone</label>
        <input id="phone" name="phone" required />
        <label for="equipment">Equipment Type</label>
        <select id="equipment" name="equipment">
          <option>Dry Van (53')</option>
          <option>Reefer</option>
          <option>Power Only</option>
        </select>
        <label for="message">Details</label>
        <textarea id="message" name="message" rows="4"></textarea>
        <button type="submit" class="btn btn-primary">Submit</button>
      </form>
    </section>
  </div>

  <footer>
    <p>📍 191 PRESIDENTIAL BOULEVARD, SUITE 110, BALA CYNWYD, PA 19004 | (276) 500-5667 | hashmiumaiz@gmail.com</p>
    <p>© 2025 G&T 5206 Investments</p>
  </footer>

</body>
</html>
