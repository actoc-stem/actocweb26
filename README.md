<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ACTOC | Advancing Children in Technology Orange County</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800;900&display=swap" rel="stylesheet">
  <style>
    *{margin:0;padding:0;box-sizing:border-box;scroll-behavior:smooth;font-family:'Inter',sans-serif;}
    body{background:linear-gradient(to bottom,#071a2d,#0d2238,#f5efe3);color:white;}
    nav{position:sticky;top:0;display:flex;justify-content:space-between;align-items:center;padding:20px 7%;background:rgba(7,26,45,.92);backdrop-filter:blur(10px);z-index:1000;border-bottom:1px solid rgba(255,255,255,.08);}
    nav a{text-decoration:none;color:white;margin:0 15px;font-size:14px;}
    nav a:hover{color:#e7c07d;}
    .btn{padding:14px 24px;border-radius:16px;text-decoration:none;display:inline-block;transition:.3s;}
    .gold{background:#e7c07d;color:black;font-weight:700;}
    .white{background:white;color:black;font-weight:700;}
    .outline{border:1px solid rgba(255,255,255,.2);color:white;}
    .btn:hover,.card:hover{transform:translateY(-4px);}
    .hero,.section{padding:90px 7%;}
    .hero{display:grid;grid-template-columns:1fr 1fr;gap:50px;align-items:center;}
    h1{font-size:64px;line-height:1.1;font-weight:900;margin-bottom:25px;}
    h2{font-size:48px;font-weight:900;margin-bottom:25px;color:black;}
    .hero p,.sub{font-size:18px;color:rgba(255,255,255,.75);max-width:600px;margin-bottom:30px;}
    .stats{display:flex;gap:35px;margin-top:35px;}
    .logo-box{height:430px;border-radius:32px;background:rgba(255,255,255,.05);display:flex;justify-content:center;align-items:center;border:1px solid rgba(255,255,255,.08);}
    .logo-box img{max-width:80%;max-height:80%;}
    .white-section{background:white;color:black;border-radius:50px 50px 0 0;}
    .cards{display:grid;grid-template-columns:1fr 1fr;gap:30px;margin-top:35px;}
    .card{padding:35px;border-radius:28px;box-shadow:0 10px 30px rgba(0,0,0,.08);transition:.3s;}
    .blue{background:#d9edf2;}
    .pink{background:#f4ddd6;}
    .cream{background:#f5efe3;}
    .impact{background:#071a2d;color:white;}
    .impact h2{color:white;}
    .goal-grid{display:grid;grid-template-columns:repeat(5,1fr);gap:20px;}
    .goal{padding:25px;background:rgba(255,255,255,.05);border-radius:24px;text-align:center;}
    footer{text-align:center;padding:40px;background:#071a2d;color:rgba(255,255,255,.7);}
    input,textarea{width:100%;padding:15px;border:none;border-radius:14px;margin-bottom:12px;}
    @media(max-width:900px){
      .hero,.cards,.goal-grid{grid-template-columns:1fr;display:grid;}
      h1{font-size:42px;} h2{font-size:34px;}
      nav{flex-direction:column;gap:10px;}
      .stats{flex-direction:column;gap:15px;}
    }
  </style>
</head>
<body>

<nav>
  <div><strong style="font-size:28px;">ACTOC</strong><br><small style="color:rgba(255,255,255,.6)">Advancing Children in Technology Orange County</small></div>
  <div>
    <a href="#about">About</a>
    <a href="#programs">Programs</a>
    <a href="#impact">Impact</a>
    <a href="#founders">Founders</a>
    <a href="#partner" class="btn gold">Get Involved</a>
  </div>
</nav>

<section class="hero">
  <div>
    <h1>Every child deserves <span style="color:#e7c07d">STEM</span>, <span style="color:#8fc7d6">robotics</span>, and <span style="color:#c96a5a">wellness</span> for free.</h1>
    <p>Two high school students built ACTOC because too many children never get access to the opportunities that shape confidence, health, and future careers.</p>
    <a href="#programs" class="btn white">See Our Programs</a>
    <a href="#partner" class="btn outline">Partner With Us</a>
    <div class="stats">
      <div><h3 style="color:#e7c07d;font-size:34px;">$0</h3><span>Cost to families</span></div>
      <div><h3 style="color:#8fc7d6;font-size:34px;">2</h3><span>Programs</span></div>
      <div><h3 style="color:#c96a5a;font-size:34px;">∞</h3><span>Potential</span></div>
    </div>
  </div>
  <div class="logo-box"><img src="actoc-logo.png" alt="ACTOC Logo"></div>
</section>

<section id="about" class="section white-section">
  <h2>Kids do not miss out for one reason. They miss out because every barrier shows up at once.</h2>
  <div class="cards">
    <div class="card blue"><h3>The STEM Access Gap</h3><br><p>School budgets cannot sustain STEM programs. Families cannot afford robotics fees and materials. Many students never get early exposure.</p></div>
    <div class="card pink"><h3>The Wellness Education Gap</h3><br><p>Nutrition, body literacy, and mental health education are often deprioritized, leaving children without child-friendly wellness resources.</p></div>
  </div>
</section>

<section id="programs" class="section white-section" style="border-radius:0;">
  <h2>Two Programs. One Mission.</h2>
  <div class="cards">
    <div class="card blue"><h3>ACTOC Robotics</h3><br><p>Free hands-on STEM and robotics workshops for elementary students. No materials cost. No school budget required. We bring everything.</p></div>
    <div class="card cream"><h3>ACTOC Wellness Series</h3><br><p>A three-book wellness series on Nutrition, Body Health, and Mental Health with free presentations at schools and libraries.</p></div>
  </div>
</section>

<section id="impact" class="section impact">
  <h2>Our 2026 Goals</h2>
  <div class="goal-grid">
    <div class="goal">Launch Workshops</div>
    <div class="goal">Publish 3 Wellness Books</div>
    <div class="goal">Start Chapters</div>
    <div class="goal">International Outreach</div>
    <div class="goal">Increase Volunteers</div>
  </div>
</section>

<section id="founders" class="section white-section" style="border-radius:0;">
  <h2>Built by students. For every student.</h2>
  <div class="cards">
    <div class="card cream"><h3>Nitika Metharamitta</h3><br><p><b>Co-Founder & President</b><br><br>Focused on creating equal access to STEM education and helping students discover innovation pathways early.</p></div>
    <div class="card cream"><h3>Amulya Atluri</h3><br><p><b>Co-Founder & Vice President</b><br><br>Dedicated to child wellness education and building stronger health literacy for young learners.</p></div>
  </div>
</section>

<section id="partner" class="section" style="background:#e7c07d;color:black;text-align:center;">
  <h2 style="color:black;">Help us build access that actually reaches every child.</h2>
  <p class="sub" style="color:rgba(0,0,0,.7);margin:auto;margin-bottom:25px;">Partner, volunteer, donate materials, or host ACTOC at your school, library, or organization.</p>
  <div style="max-width:600px;margin:40px auto;background:rgba(255,255,255,.45);padding:35px;border-radius:30px;">
    <input placeholder="Name">
    <input placeholder="Email">
    <textarea rows="4" placeholder="Message"></textarea>
    <a href="#" class="btn gold">Send Message</a>
  </div>
</section>

<footer>
  <p>ACTOC • Advancing Children in Technology Orange County</p>
  <p style="margin-top:10px;">Student-led 501(c)(3) nonprofit organization • info@actoc.org</p>
</footer>

</body>
</html>
