*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family:Arial,Helvetica,sans-serif;
background:#f5f7fa;
color:#333;
line-height:1.6;
}

header{
background:#0057b8;
color:white;
padding:20px 8%;
display:flex;
justify-content:space-between;
align-items:center;
position:sticky;
top:0;
}

.logo{
font-size:30px;
font-weight:bold;
}

nav a{
color:white;
text-decoration:none;
margin-left:20px;
font-weight:bold;
}

.hero{
background:linear-gradient(rgba(0,87,184,.8),rgba(0,87,184,.8)),url('https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=1600&q=80');
background-size:cover;
background-position:center;
color:white;
text-align:center;
padding:120px 20px;
}

.hero h1{
font-size:50px;
margin-bottom:20px;
}

.hero p{
font-size:20px;
margin-bottom:30px;
}

.btn{
display:inline-block;
background:#ff9800;
color:white;
padding:15px 35px;
text-decoration:none;
border-radius:5px;
font-weight:bold;
}

.container{
width:90%;
max-width:1200px;
margin:auto;
padding:60px 0;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
}

.card{
background:white;
padding:25px;
border-radius:10px;
box-shadow:0 5px 15px rgba(0,0,0,.1);
}

.card h3{
color:#0057b8;
margin-bottom:15px;
}

footer{
background:#111827;
color:white;
text-align:center;
padding:30px;
margin-top:50px;
}

@media(max-width:768px){

header{
flex-direction:column;
}

nav{
margin-top:15px;
}

.hero h1{
font-size:34px;
}

}
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Carasurance - Compare Car Insurance Quotes</title>

<style>
body{
    margin:0;
    font-family:Arial,sans-serif;
    background:#f5f5f5;
}
header{
    background:#004aad;
    color:white;
    padding:20px;
    text-align:center;
}
nav{
    background:#003580;
    padding:10px;
    text-align:center;
}
nav a{
    color:white;
    text-decoration:none;
    margin:15px;
    font-weight:bold;
}
.hero{
    padding:60px 20px;
    text-align:center;
    background:white;
}
.hero h1{
    color:#004aad;
}
.btn{
    background:#ff9800;
    color:white;
    padding:15px 30px;
    text-decoration:none;
    border-radius:5px;
}
.section{
    padding:40px 20px;
    text-align:center;
}
.cards{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:20px;
}
.card{
    background:white;
    width:250px;
    padding:20px;
    border-radius:10px;
    box-shadow:0 0 10px rgba(0,0,0,.1);
}
footer{
    background:#004aad;
    color:white;
    text-align:center;
    padding:20px;
}
</style>

</head>
<body>

<header>
<h1>CARASURANCE</h1>
<p>Compare Car Insurance Quotes in the USA</p>
</header>

<nav>
<a href="#">Home</a>
<a href="#">About</a>
<a href="#">Blog</a>
<a href="#">Contact</a>
</nav>

<div class="hero">
<h1>Save Money on Car Insurance</h1>
<p>Compare affordable auto insurance quotes from trusted providers.</p>
<br>
<a class="btn" href="#">Get Free Quote</a>
</div>

<div class="section">

<h2>Why Choose Carasurance?</h2>

<div class="cards">

<div class="card">
<h3>Compare Quotes</h3>
<p>Find competitive insurance prices quickly.</p>
</div>

<div class="card">
<h3>Insurance Guides</h3>
<p>Learn everything about car insurance coverage.</p>
</div>

<div class="card">
<h3>Save Money</h3>
<p>Discover tips to reduce your insurance premium.</p>
</div>

</div>

</div>

<footer>

<p>© 2026 Carasurance.com | All Rights Reserved</p>

</footer>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>About Us - Carasurance</title>

<style>
body{
font-family:Arial,sans-serif;
margin:0;
background:#f4f4f4;
}

header{
background:#004aad;
color:white;
padding:20px;
text-align:center;
}

.container{
max-width:900px;
margin:40px auto;
background:white;
padding:30px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,.1);
}

h1{
color:#004aad;
}

footer{
background:#004aad;
color:white;
text-align:center;
padding:15px;
margin-top:40px;
}
</style>

</head>

<body>

<header>
<h1>About Carasurance</h1>
</header>

<div class="container">

<h1>Who We Are</h1>

<p>
Carasurance is an independent website created to help drivers learn about car insurance and compare insurance information.
</p>

<p>
Our goal is to provide simple, accurate, and easy-to-understand guides about auto insurance in the United States.
</p>

<p>
We publish helpful articles, insurance tips, and comparison guides to help visitors make informed decisions.
</p>

<p>
Carasurance is not an insurance company. We provide educational content and may recommend trusted partners in the future.
</p>

</div>

<footer>

© 2026 Carasurance.com

</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Contact - Carasurance</title>
<style>
body{font-family:Arial,sans-serif;background:#f5f5f5;margin:0;}
header{background:#004aad;color:#fff;text-align:center;padding:20px;}
.container{max-width:800px;margin:40px auto;background:#fff;padding:25px;border-radius:10px;}
input,textarea{
width:100%;
padding:12px;
margin:10px 0;
border:1px solid #ccc;
border-radius:5px;
}
button{
background:#004aad;
color:white;
padding:12px 20px;
border:none;
border-radius:5px;
cursor:pointer;
}
footer{
background:#004aad;
color:white;
text-align:center;
padding:15px;
margin-top:40px;
}
</style>
</head>
<body>

<header>
<h1>Contact Us</h1>
</header>

<div class="container">
<h2>Get in Touch</h2>

<form>
<input type="text" placeholder="Your Name">
<input type="email" placeholder="Your Email">
<textarea rows="6" placeholder="Your Message"></textarea>
<button type="submit">Send Message</button>
</form>

</div>

<footer>
© 2026 Carasurance.com
</footer>

</body>
</html>

