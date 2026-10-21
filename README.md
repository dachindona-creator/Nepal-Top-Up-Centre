# Nepal-Top-Up-Centre
Nepal Top Up Centre - Free Fire Diamonds, Level Up and Gaming Top Up Website 🇳🇵

<!DOCTYPE html>
<html lang="ne">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#071426">
<title>Nepal Top Up Centre</title>
<style>
*{box-sizing:border-box}
body{margin:0;background:#071426;color:white;font-family:Arial,sans-serif}
header{text-align:center;padding:25px 12px;background:linear-gradient(135deg,#073b78,#071426)}
header h1{color:#42d9ff;margin:8px 0}
header p{color:#ddd}
main{max-width:600px;margin:auto;padding:16px}
.card{background:#12243b;border:1px solid #294766;border-radius:14px;padding:16px;margin:14px 0}
h2{color:#42d9ff}
.item{display:flex;justify-content:space-between;gap:10px;padding:11px 0;border-bottom:1px solid #304259}
.price{color:#7cffaa;font-weight:bold}
button{width:100%;border:0;border-radius:10px;padding:14px;background:#16c768;color:#04180b;font-size:16px;font-weight:bold}
.note{color:#ccc;font-size:13px;line-height:1.5}
footer{text-align:center;padding:20px;color:#aaa}
</style>
</head>
<body>
<header>
  <div style="font-size:42px">💎🎮🇳🇵</div>
  <h1>Nepal Top Up Centre</h1>
  <p>Fast • Easy • Gaming Top Up</p>
</header>
<main>
  <section class="card">
    <h2>🔥 Free Fire Diamonds</h2>
    <div class="item"><span>25 Diamonds</span><span class="price">Rs. 40</span></div>
    <div class="item"><span>50 Diamonds</span><span class="price">Rs. 60</span></div>
    <div class="item"><span>115 Diamonds</span><span class="price">Rs. 160</span></div>
    <div class="item"><span>240 Diamonds</span><span class="price">Rs. 270</span></div>
    <div class="item"><span>610 Diamonds</span><span class="price">Rs. 529</span></div>
    <div class="item"><span>1240 Diamonds</span><span class="price">Rs. 1,058</span></div>
  </section>

  <section class="card">
    <h2>🚀 Level Up</h2>
    <div class="item"><span>Level UP-6</span><span class="price">Rs. 80</span></div>
    <div class="item"><span>Level UP-10</span><span class="price">Rs. 110</span></div>
    <div class="item"><span>Level UP-15</span><span class="price">Rs. 110</span></div>
    <div class="item"><span>Level UP-20</span><span class="price">Rs. 115</span></div>
    <div class="item"><span>Level UP-25</span><span class="price">Rs. 115</span></div>
    <div class="item"><span>Level UP-30</span><span class="price">Rs. 170</span></div>
  </section>

  <section class="card">
    <h2>💳 Payment & Order</h2>
    <p>Payment method: TFS Wallet / उपलब्ध भुक्तानी विधि पुष्टि गर्नुहोस्।</p>
    <p class="note">अर्डर गर्दा Game UID र छानेको package लेख्नुहोस्। भुक्तानी गर्नुअघि मूल्य र प्राप्तकर्ता विवरण पुष्टि गर्नुहोस्।</p>
    <button onclick="orderNow()">Order on WhatsApp</button>
  </section>
</main>
<footer>© 2026 Nepal Top Up Centre 🇳🇵</footer>
<script>
function orderNow(){
  const message = "Namaste Nepal Top Up Centre! I want to place a top-up order. Please send package details.";
  window.open("https://wa.me/qr/S7TIJEDPBDHCP1?text="+encodeURIComponent(message),"_blank");
}
</script>
</body>
</html>
