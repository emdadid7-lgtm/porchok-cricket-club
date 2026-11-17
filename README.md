# porchok-cricket-club
Official Website of Porchok Cricket Club, Established 1996.

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Porchok Cricket Club | Official</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:Arial,sans-serif;background:#f5f7f5;color:#17251e;line-height:1.6}
header{background:#102b20;color:white;padding:18px 6%;display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap}
.logo{font-size:21px;font-weight:bold;color:#e7c66b}
nav{display:flex;gap:17px;flex-wrap:wrap}
nav a{color:white;text-decoration:none;font-size:14px}
.hero{background:linear-gradient(120deg,#0b281c,#17613c);color:white;text-align:center;padding:90px 20px}
.hero small{color:#e7c66b;letter-spacing:3px}
.hero h1{font-size:clamp(34px,7vw,62px);line-height:1.15;margin:18px 0}
.hero p{color:#dce9df}
.btn{display:inline-block;background:#e7c66b;color:#15271d;padding:12px 24px;border-radius:5px;text-decoration:none;font-weight:bold;margin-top:24px}
section{padding:55px 7%;scroll-margin-top:15px}
h2{text-align:center;color:#145333;font-size:29px;margin-bottom:12px}
.sub{text-align:center;color:#68756d;margin-bottom:30px}
.about{text-align:center;max-width:750px;margin:auto}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(210px,1fr));gap:18px}
.card{background:white;padding:22px;border-radius:10px;box-shadow:0 3px 14px #0000000d}
.card h3{color:#145333;margin-bottom:8px}
.number{text-align:center;background:#e8f1e9;padding:25px;border-radius:10px}
.number strong{font-size:30px;color:#145333;display:block}
.dark{background:#eaf0eb}
.form{max-width:600px;margin:auto;background:white;padding:25px;border-radius:10px}
input,select,textarea{width:100%;padding:12px;margin:8px 0 15px;border:1px solid #ccd6ce;border-radius:5px;font-size:15px}
button{background:#145333;color:white;padding:13px 22px;border:0;border-radius:5px;font-size:15px}
footer{background:#102b20;color:#dce9df;text-align:center;padding:30px 15px}
footer strong{color:#e7c66b}
@media(max-width:600px){header{justify-content:center;gap:12px}nav{justify-content:center;gap:12px}.hero{padding:65px 15px}section{padding:42px 5%}}
</style>
</head>
<body>

<header>
<div class="logo">PCC | PORCHOK</div>
<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#players">Players</a>
<a href="#tournament">Tournament</a>
<a href="#gallery">Gallery</a>
<a href="#news">News</a>
<a href="#register">Registration</a>
</nav>
</header>

<div class="hero" id="home">
<small>ESTABLISHED 1996</small>
<h1>PORCHOK<br>CRICKET CLUB</h1>
<p>One Club. One Passion. One Legacy.</p>
<p>1 No. Barohal Union, Zakiganj, Sylhet, Bangladesh</p>
<a class="btn" href="#about">EXPLORE OUR CLUB</a>
</div>

<section id="about">
<h2>ABOUT OUR CLUB</h2>
<p class="sub">Our History • Our Passion • Our Future</p>
<div class="about">
<p>Established in 1996, Porchok Cricket Club is a community-based cricket club from Barohal, Zakiganj, Sylhet, Bangladesh.</p>
<p>Our mission is to develop talented cricketers, promote sportsmanship and create opportunities for local cricket players.</p>
</div>
</section>

<section class="dark">
<div class="cards">
<div class="number"><strong>1996</strong>Established</div>
<div class="number"><strong>PCC</strong>Our Club</div>
<div class="number"><strong>XI</strong>Our Team Spirit</div>
</div>
</section>

<section id="players">
<h2>OUR PLAYERS</h2>
<p class="sub">Meet the players of Porchok Cricket Club</p>
<div class="cards">
<div class="card"><h3>Player Profile 01</h3><p>Player name and photograph will be added.</p></div>
<div class="card"><h3>Player Profile 02</h3><p>Player name and photograph will be added.</p></div>
<div class="card"><h3>Player Profile 03</h3><p>Player name and photograph will be added.</p></div>
</div>
</section>

<section class="dark" id="tournament">
<h2>TOURNAMENT & FIXTURES</h2>
<p class="sub">Our matches, tournaments and achievements</p>
<div class="cards">
<div class="card"><h3>Upcoming Matches</h3><p>Match schedules will be announced here.</p></div>
<div class="card"><h3>Match Results</h3><p>Scores and match results will be updated here.</p></div>
<div class="card"><h3>Achievements</h3><p>Our tournament achievements and awards.</p></div>
</div>
</section>

<section id="gallery">
<h2>PHOTO GALLERY</h2>
<p class="sub">Memories of our cricket journey</p>
<div class="cards">
<div class="number">🏏<br>Club Matches</div>
<div class="number">🏆<br>Tournaments</div>
<div class="number">📸<br>Club Events</div>
</div>
</section>

<section class="dark" id="news">
<h2>NEWS & UPDATES</h2>
<p class="sub">Latest news from Porchok Cricket Club</p>
<div class="card"><h3>Welcome to PCC Official Website</h3><p>Stay connected for club news, tournament updates and player information.</p></div>
</section>

<section id="register">
<h2>PLAYER REGISTRATION</h2>
<p class="sub">Join Porchok Cricket Club</p>
<form class="form" onsubmit="event.preventDefault();alert('Registration form connection will be activated in the next setup step.');">
<label>Full Name</label>
<input required placeholder="Enter your name">
<label>Mobile Number</label>
<input required type="tel" placeholder="01XXXXXXXXX">
<label>Address</label>
<input required placeholder="Your address">
<label>Playing Role</label>
<select><option>Batsman</option><option>Bowler</option><option>All-rounder</option><option>Wicketkeeper</option></select>
<label>About Yourself</label>
<textarea rows="3" placeholder="Your cricket experience"></textarea>
<button type="submit">SUBMIT REGISTRATION</button>
</form>
</section>

<footer>
<strong>PORCHOK CRICKET CLUB</strong>
<p>Established 1996 | Barohal, Zakiganj, Sylhet</p>
<p>One Club. One Passion. One Legacy.</p>
<p>© 2026 Porchok Cricket Club. All Rights Reserved.</p>
</footer>
</body>
</html>
