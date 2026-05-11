# Ex02 Commercial Website
## Date:11.05.2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
## HTML code
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>UrbanWear Store</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header class="topbar">
<a href="#home" class="brand">UrbanWear</a>

<nav class="nav">
<a href="#home">Home</a>
<a href="#products">Products</a>
<a href="#about">About</a>
<a href="#services">Services</a>
<a href="#contact">Contact</a>
<a href="#account">Account</a>
</nav>
</header>

<main>

<section class="hero" id="home">

<div class="hero-copy">

<span class="eyebrow">Modern Fashion Collection</span>

<h1>Discover Your Perfect Style.</h1>

<p>Premium fashion products designed for comfort, confidence, and everyday elegance.</p>

<div class="hero-actions">
<a href="#products" class="button button-primary">Shop Now</a>
<a href="#about" class="button button-secondary">Learn More</a>
</div>

<div class="hero-stats">
<div>
<strong>50K+</strong>
<span>Customers</span>
</div>

<div>
<strong>24/7</strong>
<span>Support</span>
</div>

<div>
<strong>4.9★</strong>
<span>Ratings</span>
</div>
</div>

</div>

<div class="hero-visual">
<img src="images/banner.jpg" alt="Fashion Banner">

<div class="floating-card card-one">
<span>New Arrival</span>
<strong>Summer Collection</strong>
</div>

<div class="floating-card card-two">
<span>Special Offer</span>
<strong>Up to 40% Off</strong>
</div>

</div>

</section>

<section class="section products-section" id="products">

<div class="section-heading">
<span class="eyebrow">Trending Products</span>
<h2>Explore Our Featured Collection.</h2>
</div>

<div class="product-grid">

<article class="product-card">
<img src="images/product1.jpg" alt="Product 1">

<div>
<h3>Classic Hoodie</h3>
<p>Stylish and comfortable hoodie for daily wear.</p>
<button class="button button-primary">Buy Now</button>
</div>

</article>

<article class="product-card">

<img src="images/product2.jpg" alt="Product 2">

<div>
<h3>Premium Sneakers</h3>
<p>Lightweight sneakers designed for comfort and performance.</p>
<button class="button button-primary">Buy Now</button>
</div>

</article>

<article class="product-card">

<img src="images/product3.jpg" alt="Product 3">

<div>
<h3>Luxury Watch</h3>
<p>Elegant watch collection with premium craftsmanship.</p>
<button class="button button-primary">Buy Now</button>
</div>

</article>

</div>

</section>

<section class="section split-section" id="about">

<div class="section-heading">

<span class="eyebrow">About Us</span>

<h2>Fashion Built Around Quality and Style.</h2>

<p>UrbanWear combines modern trends with premium quality to deliver fashion products people truly love.</p>

</div>

<div class="about-panel">

<div class="feature-row">

<strong>01</strong>

<div>
<h3>Premium Quality</h3>
<p>Every product is designed using high-quality materials and craftsmanship.</p>
</div>

</div>

<div class="feature-row">

<strong>02</strong>

<div>
<h3>Fast Delivery</h3>
<p>Get your orders delivered quickly with reliable shipping services.</p>
</div>

</div>

<div class="feature-row">

<strong>03</strong>

<div>
<h3>Secure Payments</h3>
<p>Safe and secure payment methods for worry-free shopping.</p>
</div>

</div>

</div>

</section>

<section class="section services-section" id="services">

<div class="section-heading">
<span class="eyebrow">Services</span>
<h2>More Than Just Shopping.</h2>
</div>

<div class="product-grid">

<article class="product-card">

<img src="images/service1.jpg" alt="Service 1">

<div>
<h3>Free Shipping</h3>
<p>Enjoy free shipping on selected products and collections.</p>
</div>

</article>

<article class="product-card">

<img src="images/service2.jpg" alt="Service 2">

<div>
<h3>Gift Packaging</h3>
<p>Beautiful packaging options available for special occasions.</p>
</div>

</article>

<article class="product-card">

<img src="images/service3.jpg" alt="Service 3">

<div>
<h3>Customer Support</h3>
<p>Dedicated support team available anytime you need assistance.</p>
</div>

</article>

</div>

</section>

<section class="section contact-account">

<div class="contact-card" id="contact">

<span class="eyebrow">Contact Details</span>

<h2>We’re Here To Help.</h2>

<div class="contact-list">

<p><strong>Email:</strong> support@urbanwear.com</p>

<p><strong>Phone:</strong> +91 9876543210</p>

<p><strong>Location:</strong> Chennai, India</p>

</div>

</div>

<div class="account-card" id="account">

<span class="eyebrow">User Account</span>

<h2>Login To Your Account.</h2>

<form class="account-form">

<label>
Email Address
<input type="email" placeholder="Enter your email">
</label>

<label>
Password
<input type="password" placeholder="Enter your password">
</label>

<button type="submit" class="button button-primary">Sign In</button>

</form>

</div>

</section>

</main>

<footer class="footer">

<div>
<strong>UrbanWear</strong>
<p>Fashion that blends comfort, style, and confidence.</p>
</div>

<div class="socials">
<a href="#">Instagram</a>
<a href="#">Facebook</a>
<a href="#">Twitter</a>
<a href="#">YouTube</a>
</div>

<p class="copyright">© 2026 UrbanWear. All Rights Reserved.</p>

</footer>

</body>
</html>
```

## CSS Code
```
:root{
--bg:#ffffff;
--surface:#f5f5f5;
--text:#222222;
--muted:#666666;
--accent:#ff9800;
--accent-dark:#e68900;
--line:#dddddd;
}

*{
margin:0;
padding:0;
box-sizing:border-box;
}

html{
scroll-behavior:smooth;
}

body{
font-family:Arial,sans-serif;
background:var(--bg);
color:var(--text);
}

img{
width:100%;
display:block;
}

a{
text-decoration:none;
color:inherit;
}

.topbar{
width:min(1200px,calc(100% - 40px));
margin:20px auto;
padding:18px 24px;
display:flex;
justify-content:space-between;
align-items:center;
background:var(--surface);
border:1px solid var(--line);
border-radius:10px;
}

.brand{
font-size:28px;
font-weight:bold;
}

.nav{
display:flex;
gap:25px;
flex-wrap:wrap;
}

.nav a{
color:var(--muted);
font-weight:600;
transition:0.3s;
}

.nav a:hover{
color:var(--accent);
}

main{
width:min(1200px,calc(100% - 40px));
margin:auto;
}

.hero{
display:flex;
align-items:center;
gap:40px;
padding:50px 0;
}

.hero-copy{
flex:1;
}

.eyebrow{
display:inline-block;
text-transform:uppercase;
letter-spacing:2px;
color:var(--accent-dark);
font-size:13px;
font-weight:bold;
margin-bottom:15px;
}

.hero-copy h1{
font-size:65px;
line-height:1.1;
margin-bottom:20px;
}

.hero-copy p{
color:var(--muted);
line-height:1.7;
margin-bottom:25px;
font-size:18px;
}

.hero-actions{
display:flex;
gap:15px;
flex-wrap:wrap;
}

.button{
padding:14px 28px;
border-radius:5px;
border:none;
cursor:pointer;
font-weight:bold;
transition:0.3s;
}

.button-primary{
background:var(--accent);
color:white;
}

.button-primary:hover{
background:var(--accent-dark);
}

.button-secondary{
background:white;
border:1px solid var(--line);
}

.button-secondary:hover{
background:#eeeeee;
}

.hero-stats{
display:flex;
gap:15px;
margin-top:30px;
flex-wrap:wrap;
}

.hero-stats div{
background:white;
border:1px solid var(--line);
padding:15px 20px;
border-radius:8px;
}

.hero-stats strong{
display:block;
font-size:24px;
}

.hero-stats span{
color:var(--muted);
}

.hero-visual{
flex:1;
position:relative;
}

.hero-visual img{
height:650px;
object-fit:cover;
border-radius:12px;
}

.floating-card{
position:absolute;
background:white;
border:1px solid var(--line);
border-radius:8px;
padding:15px 18px;
box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

.card-one{
top:20px;
left:20px;
}

.card-two{
bottom:20px;
right:20px;
}

.floating-card span{
display:block;
color:var(--muted);
margin-bottom:5px;
}

.section{
padding:70px 0;
}

.section-heading{
margin-bottom:35px;
}

.section-heading h2{
font-size:42px;
margin-top:10px;
}

.products-section{
display:flex;
flex-direction:column;
}

.product-grid{
display:flex;
gap:25px;
flex-wrap:wrap;
}

.product-card{
flex:1;
min-width:280px;
background:white;
border:1px solid var(--line);
border-radius:12px;
overflow:hidden;
transition:0.3s;
}

.product-card:hover{
transform:translateY(-10px);
box-shadow:0 10px 20px rgba(0,0,0,0.1);
}

.product-card img{
height:300px;
object-fit:cover;
}

.product-card div{
padding:20px;
}

.product-card h3{
margin-bottom:10px;
font-size:24px;
}

.product-card p{
color:var(--muted);
line-height:1.6;
margin-bottom:20px;
}

.split-section{
display:flex;
gap:30px;
}

.about-panel{
flex:1;
display:flex;
flex-direction:column;
gap:20px;
}

.feature-row{
display:flex;
gap:20px;
background:white;
padding:20px;
border-radius:10px;
border:1px solid var(--line);
}

.feature-row strong{
color:var(--accent-dark);
font-size:20px;
}

.feature-row h3{
margin-bottom:8px;
}

.feature-row p{
color:var(--muted);
line-height:1.6;
}

.contact-account{
display:flex;
gap:30px;
}

.contact-card,
.account-card{
flex:1;
background:white;
border:1px solid var(--line);
border-radius:12px;
padding:30px;
}

.contact-card h2,
.account-card h2{
margin:15px 0;
font-size:36px;
}

.contact-list p{
margin-bottom:15px;
color:var(--muted);
}

.account-form{
display:flex;
flex-direction:column;
gap:18px;
margin-top:20px;
}

.account-form label{
display:flex;
flex-direction:column;
gap:8px;
font-weight:600;
}

.account-form input{
padding:14px;
border:1px solid #cccccc;
border-radius:6px;
font-size:16px;
}

.account-form input:focus{
outline:none;
border-color:var(--accent);
}

.footer{
width:min(1200px,calc(100% - 40px));
margin:auto;
padding:30px 0;
border-top:1px solid var(--line);
display:flex;
justify-content:space-between;
align-items:center;
gap:20px;
flex-wrap:wrap;
}

.footer strong{
display:block;
margin-bottom:10px;
font-size:22px;
}

.footer p{
color:var(--muted);
}

.socials{
display:flex;
gap:18px;
flex-wrap:wrap;
}

.socials a{
color:var(--muted);
transition:0.3s;
}

.socials a:hover{
color:var(--accent);
}

.copyright{
white-space:nowrap;
}

@media(max-width:992px){

.hero,
.split-section,
.contact-account{
flex-direction:column;
}

.hero-copy h1{
font-size:48px;
}

.hero-visual img{
height:500px;
}

}

@media(max-width:768px){

.topbar{
flex-direction:column;
align-items:flex-start;
gap:20px;
}

.nav{
gap:15px;
}

.hero-copy h1{
font-size:40px;
}

.section-heading h2{
font-size:32px;
}

.contact-card h2,
.account-card h2{
font-size:28px;
}

.hero-visual img{
height:400px;
}

.floating-card{
display:none;
}

}

@media(max-width:500px){

.hero-copy h1{
font-size:32px;
}

.button{
width:100%;
text-align:center;
}

.hero-stats{
flex-direction:column;
}

}
```

## OUTPUT
<img width="805" height="775" alt="output-1" src="https://github.com/user-attachments/assets/796773c7-201b-4036-be2b-3a7ac0769e95" />
<img width="716" height="675" alt="output-24" src="https://github.com/user-attachments/assets/ae22c12c-7caf-4fee-9602-d09ca14012bc" />
<img width="705" height="332" alt="op-3" src="https://github.com/user-attachments/assets/d975d3eb-7047-4a8a-8589-d3948dcc176a" />





## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
