<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Emine Optik</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#f5f7fa;
    color:#333;
}

header{
    background:#0d6efd;
    color:white;
    padding:20px 50px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

header h1{
    font-size:30px;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
    font-weight:bold;
}

.hero{
    height:500px;
    background:linear-gradient(rgba(0,0,0,.5),rgba(0,0,0,.5)),
    url("https://images.unsplash.com/photo-1511499767150-a48a237f0083?auto=format&fit=crop&w=1500&q=80");
    background-size:cover;
    background-position:center;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
}

.hero h2{
    font-size:50px;
    margin-bottom:15px;
}

.hero p{
    font-size:22px;
}

.btn{
    margin-top:30px;
    display:inline-block;
    background:#0d6efd;
    color:white;
    padding:15px 35px;
    text-decoration:none;
    border-radius:30px;
    font-size:18px;
}

.section{
    padding:70px 50px;
}

.section h2{
    text-align:center;
    margin-bottom:40px;
    font-size:35px;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:white;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 5px 15px rgba(0,0,0,.15);
}

.card img{
    width:100%;
    height:220px;
    object-fit:cover;
}

.card h3{
    padding:15px;
}

.card p{
    padding:0 15px 20px;
}

footer{
    background:#111;
    color:white;
    text-align:center;
    padding:30px;
}
</style>

</head>
<body>

<header>
<h1>👓 Emine Optik</h1>

<nav>
<a href="#">Anasayfa</a>
<a href="#">Ürünler</a>
<a href="#">Hakkımızda</a>
<a href="#">İletişim</a>
</nav>

</header>

<section class="hero">

<div>

<h2>Emine Optik'e Hoş Geldiniz</h2>

<p>Kaliteli Gözlük • Güneş Gözlüğü • Lens • Güvenilir Hizmet</p>

<a href="#" class="btn">Ürünleri İncele</a>

</div>

</section>

<section class="section">

<h2>Ürün Kategorilerimiz</h2>

<div class="cards">

<div class="card">
<img src="https://images.unsplash.com/photo-1574258495973-f010dfbb5371?auto=format&fit=crop&w=600&q=80">
<h3>Numaralı Gözlükler</h3>
<p>Birbirinden şık ve kaliteli çerçeveler.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1517841905240-472988babdf9?auto=format&fit=crop&w=600&q=80">
<h3>Güneş Gözlükleri</h3>
<p>UV korumalı, en yeni sezon modelleri.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1511920170033-f8396924c348?auto=format&fit=crop&w=600&q=80">
<h3>Kontakt Lens</h3>
<p>Günlük, aylık ve yıllık lens seçenekleri.</p>
</div>

</div>

</section>

<section class="section">

<h2>İletişim</h2>

<center>

<p><strong>📍 Adres:</strong> Mağaza Adresi Buraya</p><br>

<p><strong>📞 Telefon:</strong> 05XX XXX XX XX</p><br>

<p><strong>📧 E-posta:</strong> info@emineoptik.com</p>

</center>

</section>

<footer>

© 2026 Emine Optik | Tüm Hakları Saklıdır.

</footer>

</body>
</html>
