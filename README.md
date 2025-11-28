<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Wes Arts & Tech | Creative & Technology Solutions</title>
<meta name="description" content="Wes Arts & Tech provides professional web development, branding, graphic design, and digital services in Kenya. M-Pesa payments accepted.">

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif}
html{scroll-behavior:smooth}
body{background:#0b0e17;color:#fff;line-height:1.6}
a{text-decoration:none;color:inherit}

/* HEADER */
header{
  background:#0f1324;
  position:sticky;
  top:0;
  z-index:1000;
  border-bottom:1px solid rgba(255,255,255,.1)
}
nav{
  max-width:1200px;
  margin:auto;
  padding:15px 25px;
  display:flex;
  justify-content:space-between;
  align-items:center;
}
.logo{font-size:1.4rem;font-weight:700;color:#6a8cff}
nav ul{list-style:none;display:flex;gap:20px}
nav a:hover{color:#ff4aa2}

/* HERO */
.hero{
  min-height:90vh;
  display:flex;
  justify-content:center;
  align-items:center;
  text-align:center;
  padding:40px 20px;
  background:
    radial-gradient(circle at 20% 20%,rgba(106,140,255,.25),transparent 40%),
    radial-gradient(circle at 80% 30%,rgba(255,74,162,.25),transparent 40%),
    #0b0e17;
}
.hero h1{font-size:3rem;max-width:900px}
.hero p{margin-top:15px;font-size:1.1rem;opacity:.9}

/* BUTTONS */
.btn{
  display:inline-block;
  margin-top:25px;
  padding:14px 36px;
  border-radius:30px;
  background:linear-gradient(90deg,#6a8cff,#ff4aa2);
  color:white;
  font-weight:500;
  transition:.3s;
}
.btn:hover{transform:scale(1.05)}
.btn.secondary{
  background:#141935;
  border:1px solid #6a8cff;
}

/* SECTIONS */
.section{
  max-width:1200px;
  margin:auto;
  padding:80px 25px;
}
.section h2{font-size:2.3rem;margin-bottom:20px}

/* GRID */
.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:25px;
  margin-top:40px;
}

/* CARD */
.card{
  background:#141935;
  padding:30px;
  border-radius:18px;
  transition:.3s;
}
.card:hover{
  transform:translateY(-8px);
  background:#181f45;
}
.price{
  font-size:2rem;
  margin:10px 0;
  color:#6a8cff;
}

/* PAYMENT */
.payment-box{
  background:#0f1324;
  padding:30px;
  border-radius:18px;
  margin-top:30px;
}

/* CONTACT */
.contact-grid{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:40px;
}
input,textarea{
  width:100%;
  padding:14px;
  border-radius:10px;
  border:none;
  background:#141935;
  color:white;
}
textarea{resize:none}

/* MAP */
.map iframe{
  width:100%;
  height:300px;
  border-radius:20px;
  border:none;
}

/* WHATSAPP FLOAT */
.whatsapp{
  position:fixed;
  bottom:20px;
  right:20px;
  background:#25D366;
  padding:16px;
  border-radius:50%;
  font-size:1.6rem;
  color:white;
  z-index:2000;
}

/* FOOTER */
footer{
  background:#070912;
  padding:40px 25px;
  font-size:.9rem;
  opacity:.9;
}

/* RESPONSIVE */
@media(max-width:850px){
  .hero h1{font-size:2.2rem}
  .contact-grid{grid-template-columns:1fr}
}
</style>
</head>

<body>

<header>
<nav>
<div class="logo">Wes Arts & Tech</div>
<ul>
<li><a href="#home">Home</a></li>
<li><a href="#services">Services</a></li>
<li><a href="#pricing">Pricing</a></li>
<li><a href="#payment">Payment</a></li>
<li><a href="#location">Location</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>
</header>

<section class="hero" id="home">
<div>
<h1>Professional Creative & Technology Solutions</h1>
<p>Web Development · Branding · Design · Digital Services</p>
<a href="#services" class="btn">View Services</a>
<a href="#contact" class="btn secondary">Make an Enquiry</a>
</div>
</section>

<section class="section" id="services">
<h2>Our Services</h2>
<div class="grid">
<div class="card">
<h3>Website Development</h3>
<p>Professional responsive business websites</p>
<p class="price">From KES 5,000</p>
<a class="btn secondary" href="https://wa.me/254794257039?text=How%20much%20is%20website%20development?">Ask on WhatsApp</a>
</div>

<div class="card">
<h3>Graphic & Brand Design</h3>
<p>Logos, posters, branding materials</p>
<p class="price">From KES 2,000</p>
<a class="btn secondary" href="mailto:mikeryan605@gmail.com?subject=Design Inquiry&body=Please tell me more about your services">Ask via Email</a>
</div>

<div class="card">
<h3>UI / UX Design</h3>
<p>Modern app & web interfaces</p>
<p class="price">From KES 3,000</p>
<a class="btn secondary" href="https://wa.me/254794257039?text=Please%20tell%20me%20more%20about%20UI/UX%20design">Ask on WhatsApp</a>
</div>

<div class="card">
<h3>Digital Marketing</h3>
<p>Online business promotion</p>
<p class="price">From KES 4,000</p>
<a class="btn secondary" href="mailto:mikeryan605@gmail.com?subject=Marketing Inquiry&body=Where is your business located?">Ask via Email</a>
</div>
</div>
</section>

<section class="section" id="pricing">
<h2>Pricing Packages</h2>
<div class="grid">
<div class="card"><h3>Starter</h3><p class="price">KES 5,000</p><p>Basic website or design</p></div>
<div class="card"><h3>Business</h3><p class="price">KES 15,000</p><p>Full business website</p></div>
<div class="card"><h3>Premium</h3><p class="price">KES 30,000+</p><p>Custom enterprise solutions</p></div>
</div>
</section>

<section class="section" id="payment">
<h2>M-Pesa Payments</h2>
<div class="payment-box">
<p><strong>Accepted Payment:</strong> M-Pesa</p>
<p><strong>Send Payment To:</strong></p>
<h3>📱 +254 794 257 039</h3>
<p>After payment, confirm using the button below.</p>

<a class="btn" href="https://wa.me/254794257039?text=I%20have%20made%20the%20payment%20via%20M-Pesa">Confirm Payment on WhatsApp</a>
<a class="btn secondary" href="mailto:mikeryan605@gmail.com?subject=Invoice Request&body=Please send me an invoice">Request Invoice</a>
</div>
</section>

<section class="section" id="location">
<h2>Business Location</h2>
<p>📍 Based in Kenya | Serving clients locally & internationally</p>
<div class="map">
<iframe src="https://www.google.com/maps?q=Kenya&output=embed"></iframe>
</div>
</section>

<section class="section" id="contact">
<h2>Contact Us</h2>
<div class="contact-grid">
<div>
<p><strong>Email:</strong><br><a href="mailto:mikeryan605@gmail.com">mikeryan605@gmail.com</a></p>
<p><strong>Phone / WhatsApp:</strong><br><a href="tel:+254794257039">+254 794 257 039</a></p>
<p><strong>Hours:</strong><br>Mon – Sat | 8:00 AM – 6:00 PM</p>
</div>

<form action="mailto:mikeryan605@gmail.com" method="post" enctype="text/plain">
<input name="name" placeholder="Full Name" required>
<input type="email" name="email" placeholder="Email Address" required>
<textarea name="message" rows="5" placeholder="Please tell me more about..."></textarea>
<button class="btn">Send Enquiry</button>
</form>
</div>
</section>

<footer>
<p>© 2025 Wes Arts & Tech</p>
<p>Email: mikeryan605@gmail.com | Phone: +254 794 257 039 | Kenya</p>
</footer>

<a class="whatsapp" href="https://wa.me/254794257039" target="_blank">💬</a>

</body>
</html>
