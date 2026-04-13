<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CHHABRA REAL ESTATES</title>

<style>
body {margin:0;font-family:Arial;}
header {background:#0d6efd;color:white;text-align:center;padding:15px;}
nav {display:flex;justify-content:center;background:#222;position:sticky;top:0;}
nav a {color:white;padding:14px;text-decoration:none;}
nav a:hover {background:#444;}
.hero {
background:url('https://images.unsplash.com/photo-1560518883-ce09059eeffa') no-repeat center/cover;
height:300px;color:white;display:flex;align-items:center;justify-content:center;text-align:center;font-size:28px;
}
section {padding:20px;}
.property-container {display:flex;flex-wrap:wrap;justify-content:center;}
.property {
width:280px;margin:10px;border-radius:10px;overflow:hidden;
box-shadow:0 0 10px rgba(0,0,0,0.1);
}
.property img {width:100%;height:180px;}
.property h3,.property p {margin:10px;}
.services ul {max-width:800px;margin:auto;}
.review {background:#f4f4f4;margin:10px;padding:15px;border-radius:8px;}
.contact {background:#eee;text-align:center;}
input,textarea {width:80%;padding:10px;margin:5px;}
button {padding:10px 20px;background:#0d6efd;color:white;border:none;}
footer {background:#222;color:white;text-align:center;padding:10px;}
.float-btn {position:fixed;right:15px;}
.call {bottom:80px;background:#0d6efd;}
.whatsapp {bottom:20px;background:#25D366;}
.float-btn a {
display:block;padding:12px;color:white;border-radius:50%;
text-align:center;text-decoration:none;font-size:18px;
}
iframe {width:100%;height:300px;border:none;}
</style>

</head>

<body>

<header>
<h1>CHHABRA REAL ESTATES</h1>
<p>⭐ 4.8 Rating (46 Reviews)</p>
<p>📞 <a href="tel:9599485663" style="color:white;">+91 95994 85663</a></p>
</header>

<nav>
<a href="#home">Home</a>
<a href="#properties">Properties</a>
<a href="#services">Services</a>
<a href="#reviews">Reviews</a>
<a href="#contact">Contact</a>
</nav>

<div class="hero" id="home">
Trusted Property Experts in Delhi – Honest Deals, Best Prices
</div>

<!-- Floating Buttons -->
<div class="float-btn call">
<a href="tel:9599485663">📞</a>
</div>

<div class="float-btn whatsapp">
<a href="https://wa.me/919599485663">💬</a>
</div>

<section id="properties">
<h2 style="text-align:center;">Featured Properties</h2>

<div class="property-container">

<div class="property">
<img src="https://images.unsplash.com/photo-1570129477492-45c003edd2be">
<h3>Luxury Villa</h3>
<p>₹1.2 Crore - Delhi</p>
</div>

<div class="property">
<img src="https://images.unsplash.com/photo-1560185127-6ed189bf02f4">
<h3>Modern Apartment</h3>
<p>₹75 Lakh - Gurgaon</p>
</div>

<div class="property">
<img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c">
<h3>Independent House</h3>
<p>₹90 Lakh - Noida</p>
</div>

</div>
</section>

<section id="services" class="services">
<h2 style="text-align:center;">Our Services</h2>
<ul>
<li>✔ Property Buying & Selling</li>
<li>✔ Commercial Property Consulting</li>
<li>✔ Property Investment Consulting</li>
<li>✔ Rental & Leasing</li>
<li>✔ Luxury Property Deals</li>
<li>✔ Property Management</li>
<li>✔ Relocation Assistance</li>
</ul>
</section>

<section id="reviews">
<h2 style="text-align:center;">Customer Reviews</h2>

<div class="review">⭐ Excellent property options within budget</div>
<div class="review">⭐ Highly recommend for hassle-free home search</div>
<div class="review">⭐ Honest, hardworking and trustworthy broker</div>

</section>

<section id="contact" class="contact">
<h2>Contact Us</h2>

<p>📍 Mehrauli, New Delhi</p>
<p>📞 +91 95994 85663</p>

<input type="text" placeholder="Your Name"><br>
<input type="text" placeholder="Phone"><br>
<textarea placeholder="Your Message"></textarea><br>
<button onclick="submitForm()">Send Message</button>

</section>

<iframe src="https://maps.google.com/maps?q=Mehrauli%20Delhi&t=&z=13&ie=UTF8&iwloc=&output=embed"></iframe>

<footer>
<p>© 2026 CHHABRA REAL ESTATES</p>
</footer>

<script>
function submitForm(){
alert("Thank you! We will contact you soon.");
}
</script>

</body>
</html>