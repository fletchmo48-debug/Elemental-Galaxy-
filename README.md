# Elemental-Galaxy-
Elemental Galaxy - Live Metal Dashboard 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Elemental Galaxy • LIVE Metals Palantir</title>
  <style>
    body { margin:0; font-family:Arial, sans-serif; background:#000; color:#fff; overflow:hidden; }
    .hero { height:100vh; background: linear-gradient(rgba(0,0,0,0.85), rgba(0,0,0,0.9)), url('https://picsum.photos/id/1015/1920/1080'); background-size:cover; display:flex; align-items:center; justify-content:center; text-align:center; position:relative; }
    .palantir { width:320px; height:320px; background: radial-gradient(circle at 40% 40%, #ffaa00, #440000); border-radius:50%; box-shadow:0 0 120px #ff5500, inset 0 0 80px #ffff88; animation: pulse 3s infinite; cursor:pointer; }
    @keyframes pulse { 0%,100% { transform:scale(1); } 50% { transform:scale(1.12); } }
    .content { max-width:1000px; }
    h1 { font-size:4rem; text-shadow:0 0 30px #ff0; }
    button { background:#c00; color:#fff; padding:18px 50px; font-size:1.3rem; margin:20px; border:none; border-radius:10px; cursor:pointer; }
    .subscribe { background:#ff0; color:#000; font-weight:bold; }
  </style>
</head>
<body>
  <section class="hero">
    <div class="content">
      <h1>🌌 ELEMENTAL GALAXY</h1>
      <p style="font-size:1.6rem;">Sauron’s Palantir for Physical Metals • Live Divergences • Vault Drains • Blackcat Squeezes</p>
      
      <div onclick="launchFullApp()" style="margin:50px auto; display:inline-block;">
        <div class="palantir"></div>
        <p style="margin-top:20px; font-size:1.2rem; color:#ff0;">Click the Palantir → Zoom into 42.1 φ Golden Ratio Harmony</p>
      </div>

      <div style="display:flex; justify-content:center; gap:40px; flex-wrap:wrap;">
        <div style="background:rgba(20,20,40,0.9); padding:25px; border:2px solid #ff0; border-radius:12px; width:380px;">
          <h2>Classic Periodic Grid</h2>
          <p>Money-weighted tiles (Copper dominates, Gold radiates, Li/U energize)</p>
        </div>
        <div style="background:rgba(20,20,40,0.9); padding:25px; border:2px solid #ff0; border-radius:12px; width:380px;">
          <h2>Spaceship Galaxy</h2>
          <p>Pilot through 3D spiderweb cosmos • Click orbs for live intel</p>
        </div>
      </div>

      <button class="subscribe" onclick="subscribeNow()">GET ACCESS — $29/mo Tier 1 (Free Trial Live Soon)</button>
      <p style="margin-top:30px;">Your $1M silver + these signals = Pure 42 funding engine. Data updates every 60s.</p>
    </div>
  </section>

  <script>
    function launchFullApp() {
      alert("Palantir activated! 42.1 φ spiral engaged → Loading LIVE dashboard...");
      window.location.href = "galaxy-live.html";
    }
    function subscribeNow() {
      alert("Redirecting to Stripe... Subscriptions launching soon. This funds the boat while exposing the paper market.");
    }
  </script>
</body>
</html>
