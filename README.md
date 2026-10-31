# haniffrozenfoods.github.io
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hanif Frozen Foods</title>
<style>
  :root{--blue:#0a4a8a;--green:#16a34a;--dark:#0b2a4a}
  *{margin:0;padding:0;box-sizing:border-box;font-family:'Segoe UI',Arial,sans-serif}
  body{background:var(--blue);color:#fff}
  #welcome{height:100vh;background:linear-gradient(135deg,#0a4a8a,#1e88e5 60%,#90caf9);display:flex;flex-direction:column;justify-content:center;align-items:center;text-align:center;padding:25px}
  #welcome h1{font-size:3.2rem;text-shadow:0 4px 12px rgba(0,0,0,.3)}
  .explore{background:var(--green);color:#fff;border:none;padding:18px 55px;font-size:1.4rem;border-radius:50px;cursor:pointer;font-weight:bold;margin-top:20px}
  #shop{display:none;background:#f4f8ff;color:var(--dark);min-height:100vh;padding:18px}
  .topbar{background:var(--blue);color:#fff;padding:16px;border-radius:14px;display:flex;justify-content:space-between}
  .goods{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:18px;margin-top:20px}
  .card{background:#fff;border-radius:16px;overflow:hidden;box-shadow:0 6px 18px rgba(0,0,0,.08)}
  .card img{width:100%;height:210px;object-fit:cover}
  .card-body{padding:14px;text-align:center}
  .card-body h3{color:var(--blue)}
  .contact{background:#fff;border-radius:16px;padding:22px;margin-top:30px}
  .phone-btn{display:inline-block;margin:6px;background:var(--blue);color:#fff;text-decoration:none;padding:12px 20px;border-radius:10px;font-weight:bold}
  .phone-btn.green{background:var(--green)}
</style>
</head>
<body>
<div id="welcome">
  <div style="font-size:65px">❄️</div>
  <h1>Welcome to Hanif<br>Frozen Foods</h1>
  <p>Fresh • Clean • Frozen Foods in Ota</p>
  <button class="explore" onclick="document.getElementById('welcome').style.display='none';document.getElementById('shop').style.display='block'">Explore</button>
</div>
<div id="shop">
  <div class="topbar"><b>❄️ Hanif Frozen Foods</b><button onclick="location.reload()" style="background:#fff;color:var(--blue);border:none;padding:8px 16px;border-radius:20px;cursor:pointer">Home</button></div>
  <div class="goods">
    <div class="card"><img src="chicken-lap.jpg"><div class="card-body"><h3>Chicken Laps</h3></div></div>
    <div class="card"><img src="chicken-wings.jpg"><div class="card-body"><h3>Chicken Wings</h3></div></div>
    <div class="card"><img src="turkey-wings.jpg"><div class="card-body"><h3>Turkey Wings</h3></div></div>
    <div class="card"><img src="titus.jpg"><div class="card-body"><h3>Titus Fish</h3></div></div>
    <div class="card"><img src="https://images.unsplash.com/photo-1585937421612-70a008356c36?w=500" alt="Gizzard"><div class="card-body"><h3>Chicken Gizzards</h3></div></div>
    <div class="card"><img src="https://images.unsplash.com/photo-1603360946369-dc9bb6258143?w=500" alt="Turkey Fingers"><div class="card-body"><h3>Turkey Fingers</h3></div></div>
  </div>
  <div class="contact">
    <h2 style="color:var(--blue)">📍 Contact Us</h2>
    <p style="margin:10px 0"><b>Location:</b> Sango-Ota, Ogun State - Delivery ONLY around Ota</p>
    <p><b>How to Order:</b> Call for enquiries. Pay after goods are bought.</p>
    <a class="phone-btn" href="tel:+2348028031430">📞 08028031430</a>
    <a class="phone-btn" href="tel:+2347061241289">📞 07061241289</a>
    <a class="phone-btn green" href="https://wa.me/2348028031430">💬 WhatsApp</a>
  </div>
</div>
</body>
</html>