<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Business Connect Uganda - Connecting Businesses Across Uganda</title>
<style>
  :root{--black:#111;--yellow:#FFCC00;--red:#CE1126;--gray:#f5f5f7}
  *{margin:0;padding:0;box-sizing:border-box;font-family:Inter,Arial,sans-serif}
  body{background:white;color:var(--black)}
  header{display:flex;justify-content:space-between;align-items:center;padding:14px 20px;border-bottom:3px solid var(--yellow);position:sticky;top:0;background:white;z-index:10}
  .logo{display:flex;align-items:center;gap:10px;font-weight:900;font-size:22px}
  .logo-circle{width:44px;height:44px;border-radius:50%;background:linear-gradient(135deg,black 33%,#FFCC00 33%,#FFCC00 66%,#CE1126 66%);display:flex;align-items:center;justify-content:center;color:white}
  .btn{background:var(--red);color:white;padding:10px 18px;border-radius:8px;text-decoration:none;font-weight:700;border:none;cursor:pointer}
  .btn-yellow{background:var(--yellow);color:black}
  .hero{display:grid;padding:40px 20px;background:linear-gradient(120deg,#fff 60%,#FFF3B0 70%,#FFD6D6 100%)}
  .hero h1{font-size:32px;line-height:1.1;font-weight:900}
  .hero p{margin:14px 0;color:#444;font-size:16px}
  .hero-btns{display:flex;gap:12px;margin-top:10px;flex-wrap:wrap}
  .stats{display:flex;gap:16px;margin-top:20px;font-size:13px;font-weight:600;flex-wrap:wrap}
  section{padding:30px 20px}
  .section-title{font-size:26px;font-weight:900}
  .cards{display:grid;gap:16px;margin-top:18px}
  @media(min-width:700px){.hero{grid-template-columns:1.2fr .8fr;align-items:center;padding:60px 40px}.cards{grid-template-columns:repeat(3,1fr)}header{padding:16px 40px}}
  .card{border:1px solid #eee;border-radius:16px;padding:18px;background:white;box-shadow:0 4px 20px rgba(0,0,0,.06);border-top:4px solid var(--yellow)}
  .card h3{font-size:18px;margin:8px 0}
  .badge{display:inline-block;background:var(--black);color:var(--yellow);padding:3px 10px;border-radius:20px;font-size:12px;font-weight:700;margin:4px 0}
  .card p{font-size:14px;color:#555;margin:10px 0}
  .card-footer{display:flex;justify-content:space-between;align-items:center;margin-top:12px;font-size:13px}
  footer{background:var(--black);color:white;padding:24px 20px;text-align:center;font-size:13px;border-top:4px solid var(--yellow);border-bottom:4px solid var(--red)}
  /* EDIT LOGO HERE: replace emoji with <img src="logo.png"> */
</style>
</head>
<body>

<header>
  <div class="logo">
    <div class="logo-circle">BCU</div>
    <span>BCU<br><small style="font-size:10px;font-weight:600;letter-spacing:1px">BUSINESS CONNECT UGANDA</small></span>
  </div>
  <a class="btn" href="#list">List Your Business</a>
</header>

<div class="hero">
  <div>
    <!-- EDIT TEXT 1: Main Headline -->
    <h1>Business Connect Uganda - Connecting Businesses Across Uganda</h1>
    <!-- EDIT TEXT 2: Subheadline -->
    <p>Discover, connect, and grow with trusted local businesses across all 134 districts of Uganda. Verified • Reliable • Local • Professional.</p>
    <div class="hero-btns">
      <a class="btn btn-yellow" href="#businesses">Explore Businesses →</a>
      <a class="btn" style="background:white;color:var(--red);border:2px solid var(--red)" href="#list">Join the Network</a>
    </div>
    <div class="stats">
      <span>☕ 500+ Businesses Registered</span>
      <span>📍 34 Districts Covered</span>
      <span>✅ Verified & Trusted</span>
    </div>
  </div>
  <div style="background:var(--black);color:white;border-radius:16px;padding:20px;margin-top:20px">
    <h3 style="color:var(--yellow)">🇺🇬 Why BCU?</h3>
    <p style="margin-top:10px;font-size:14px;line-height:1.5">We help Ugandans find real businesses near them. No scams. Only verified businesses in Kampala, Gulu, Jinja, Mbarara and everywhere.</p>
    <!-- EDIT LOGO/PHOTO 1: Add your map or photo here: <img src="uganda-map.png" style="width:100%;border-radius:12px;margin-top:12px"> -->
  </div>
</div>

<section id="businesses" style="background:var(--gray)">
  <div class="section-title">Featured Businesses</div>
  <p style="color:#666">Discover top-rated local businesses verified on our platform</p>
  
  <div class="cards">
    <!-- BUSINESS CARD 1 - EDIT THIS -->
    <div class="card">
      <div style="font-size:28px">☕</div>
      <h3>Kampala Coffee Co.</h3>
      <span class="badge">Coffee & Roastery</span>
      <p>Specialty coffee, catering, and wholesale beans in Kampala. Rated 4.8 ⭐ (124 reviews)</p>
      <div class="card-footer">
        <span>📍 Kampala • 2.3km away</span>
        <a class="btn" style="padding:6px 12px;font-size:12px" href="#">View Profile</a>
      </div>
    </div>

    <!-- BUSINESS CARD 2 - EDIT THIS -->
    <div class="card" style="border-top-color:var(--red)">
      <div style="font-size:28px">🧺</div>
      <h3>Nile Crafts Ltd</h3>
      <span class="badge" style="background:var(--red);color:white">Handcrafts & Textiles</span>
      <p>Traditional crafts, textiles, baskets & souvenirs handmade locally. Rated 4.7 ⭐ (89 reviews)</p>
      <div class="card-footer">
        <span>📍 Jinja • 8.1km away</span>
        <a class="btn" style="padding:6px 12px;font-size:12px" href="#">View Profile</a>
      </div>
    </div>

    <!-- BUSINESS CARD 3 - EDIT THIS -->
    <div class="card" style="border-top-color:black">
      <div style="font-size:28px">💻</div>
      <h3>SafeTech Uganda</h3>
      <span class="badge">IT & Cybersecurity</span>
      <p>IT services, cybersecurity, and digital solutions for small businesses. Rated 4.9 ⭐ (56 reviews)</p>
      <div class="card-footer">
        <span>📍 Kampala • 1.1km away</span>
        <a class="btn" style="padding:6px 12px;font-size:12px" href="#">View Profile</a>
      </div>
    </div>
  </div>
</section>

<section id="list" style="text-align:center">
  <h2 style="font-size:24px;font-weight:900">Ready to grow your business?</h2>
  <p style="margin:12px 0;color:#555">Join 500+ Ugandan businesses already on Business Connect Uganda</p>
  <!-- EDIT TEXT 3: Change WhatsApp number -->
  <a class="btn btn-yellow" href="https://wa.me/256700000000">WhatsApp Us to List: 0700 000 000</a>
  <p style="margin-top:10px;font-size:12px;color:#888">Replace 256700000000 with your real WhatsApp number in the code</p>
</section>

<footer>
  <p>© 2025 Business Connect Uganda • Privacy • Terms • Support</p>
  <p style="color:var(--yellow);margin-top:8px">Made for Ugandan businesses • Mobile-friendly • 🇺🇬</p>
  <!-- EDIT LOGO/PHOTO 2: To add real logo, upload logo.png to repo, then replace BCU circle above with: <img src="logo.png" style="width:44px;height:44px;border-radius:50%"> -->
</footer>

</body>
</html>
