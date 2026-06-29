<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jolibee Paradise</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Georgia, serif;
}

body{
    background:#f7f5f0;
    color:#333;
}

/* Navigation */
nav{
    background:#111;
    color:white;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 60px;
}

nav h1{
    font-size:30px;
    letter-spacing:2px;
}

nav ul{
    display:flex;
    list-style:none;
}

nav ul li{
    margin-left:30px;
}

nav ul li a{
    color:white;
    text-decoration:none;
    transition:.3s;
}

nav ul li a:hover{
    color:gold;
}

/* Hero */

.hero{
    height:90vh;
    background:linear-gradient(rgba(0,0,0,.45),rgba(0,0,0,.45)),
    url("https://images.unsplash.com/photo-1566073771259-6a8506099945?auto=format&fit=crop&w=1600&q=80");
    background-size:cover;
    background-position:center;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
}

.hero h2{
    font-size:60px;
}

.hero p{
    margin-top:15px;
    font-size:22px;
}

.hero button{
    margin-top:30px;
    padding:15px 35px;
    font-size:18px;
    background:gold;
    border:none;
    cursor:pointer;
    border-radius:5px;
}

/* About */

section{
    padding:70px 10%;
}

h3{
    font-size:38px;
    margin-bottom:20px;
    text-align:center;
}

.about{
    text-align:center;
    line-height:1.8;
    font-size:18px;
}

/* Rooms */

.rooms{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:white;
    border-radius:10px;
    overflow:hidden;
    box-shadow:0 5px 15px rgba(0,0,0,.15);
}

.card img{
    width:100%;
    height:220px;
    object-fit:cover;
}

.card h4{
    padding:15px;
}

.card p{
    padding:0 15px 20px;
}

/* Pool */

.pool{
    display:flex;
    flex-wrap:wrap;
    gap:40px;
    align-items:center;
}

.pool img{
    width:500px;
    max-width:100%;
    border-radius:10px;
}

.pool-text{
    flex:1;
    font-size:18px;
    line-height:1.8;
}

/* Contact */

.contact{
    background:#111;
    color:white;
    text-align:center;
    padding:40px;
}

footer{
    text-align:center;
    background:black;
    color:white;
    padding:20px;
}
</style>

</head>
<body>

<nav>
<h1>Jolibee Paradise</h1>

<ul>
<li><a href="#">Home</a></li>
<li><a href="#">Rooms</a></li>
<li><a href="#">Pool</a></li>
<li><a href="#">Contact</a></li>
</ul>

</nav>

<div class="hero">
<div>
<h2>Welcome to Jolibee Paradise</h2>
<p>Classic Luxury • Elegant Comfort • Unforgettable Memories</p>
<button>Book Your Stay</button>
</div>
</div>

<section>

<h3>About Us</h3>

<p class="about">
Experience timeless elegance at <strong>Jolibee Paradise</strong>, where luxury meets relaxation.
Our beautifully designed hotel offers spacious rooms, premium dining,
and a stunning outdoor swimming pool for guests seeking the perfect getaway.
</p>

</section>

<section>

<h3>Luxury Rooms</h3>

<div class="rooms">

<div class="card">
<img src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?auto=format&fit=crop&w=800&q=80">
<h4>Deluxe Room</h4>
<p>Elegant interiors with king-size beds and city views.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1522708323590-d24dbb6b0267?auto=format&fit=crop&w=800&q=80">
<h4>Executive Suite</h4>
<p>Luxury suite with modern amenities and spacious living area.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1582719478250-c89cae4dc85b?auto=format&fit=crop&w=800&q=80">
<h4>Family Room</h4>
<p>Perfect for families looking for comfort and relaxation.</p>
</div>

</div>

</section>

<section>

<h3>Infinity Pool</h3>

<div class="pool">

<img src="https://images.unsplash.com/photo-1571896349842-33c89424de2d?auto=format&fit=crop&w=900&q=80">

<div class="pool-text">

<p>
Relax beside our crystal-clear infinity pool surrounded by tropical scenery.
Enjoy comfortable lounge chairs, refreshing drinks, and peaceful sunsets that
make every stay unforgettable.
</p>

</div>

</div>

</section>

<div class="contact">

<h3>Contact Us</h3>

<p>Email: reservations@jolibeeparadise.com</p>

<p>Phone: +1 (671) 555-1234</p>

<p>Open 24 Hours</p>

</div>

<footer>

© 2026 Jolibee Paradise | Classic Luxury Hotel

</footer>

</body>
</html>


