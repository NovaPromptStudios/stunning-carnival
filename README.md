<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Simple Product Landing — Your Product Name</title>
  <style>
    body{font-family:system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial; margin:0; color:#111}
    .wrap{max-width:900px;margin:40px auto;padding:24px}
    .hero{display:flex;flex-direction:column;gap:16px;align-items:flex-start}
    h1{margin:0;font-size:clamp(24px,4vw,36px)}
    p.lead{font-size:16px;color:#444}
    .cta{display:inline-block;background:#0b78d1;color:#fff;padding:12px 20px;border-radius:8px;text-decoration:none;font-weight:600}
    .features{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px;margin-top:24px}
    .card{border:1px solid #eee;padding:16px;border-radius:10px;background:#fff}
    footer{margin-top:30px;color:#666;font-size:13px}
    .badge{display:inline-block;padding:6px 10px;border-radius:999px;background:#eef9ff;color:#0b78d1;font-weight:600;font-size:13px}
    @media(min-width:900px){ .hero{flex-direction:row;justify-content:space-between;align-items:center} }
  </style>
</head>
<body>
  <div class="wrap">
    <div class="hero">
      <div>
        <div class="badge">Instant Download</div>
        <h1>Your Product Name — one-sentence benefit</h1>
        <p class="lead">Short, punchy description: what it does, who it's for, and the big benefit. Example: "A done-for-you Instagram template bundle that saves you 5+ hours/week and gets you consistent posts."</p>
        <a class="cta" href="PAYMENT_LINK" target="_blank" rel="noopener noreferrer">Buy now — $19</a>
        <p style="margin-top:12px;color:#666;font-size:14px">Delivered instantly via Gumroad. Secure checkout.</p>
      </div>
      <div style="max-width:320px">
        <img src="https://placehold.co/600x400?text=Product+Preview" alt="product preview" style="width:100%;border-radius:10px;box-shadow:0 6px 18px rgba(0,0,0,.06)">
      </div>
    </div>

    <div class="features">
      <div class="card">
        <h3>What's included</h3>
        <ul>
          <li>✔ Downloadable files (PDF, PNG, ZIP)</li>
          <li>✔ Commercial use license</li>
          <li>✔ Bonus checklist</li>
        </ul>
      </div>
      <div class="card">
        <h3>Who it's for</h3>
        <p>Solopreneurs, side-hustlers, small shops — anyone who wants professional results with no design skill.</p>
      </div>
      <div class="card">
        <h3>FAQ</h3>
        <p><strong>Delivery:</strong> Instant after payment. <strong>Refunds:</strong> Handled by seller platform.</p>
      </div>
    </div>

    <footer>
      <p>Tip: replace the payment link with your Gumroad URL (create product → copy share link). Host this file on Netlify or GitHub Pages and you’re live.</p>
    </footer>
  </div>
</body>
</html>
