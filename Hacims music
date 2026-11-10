<!DOCTYPE html>
<html lang="en" data-theme="light">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="HACIMS Music Center — Online music courses from Kilimanjaro, Tanzania. Learn to read Nota, play piano, guitar, violin, drums, xylophone and flute.">
<title>HACIMS Music Center | Online Music Courses — Kilimanjaro, Tanzania</title>

<style>
/* ============================================================
   HACIMS MUSIC CENTER — GLOBAL STYLES
   ============================================================ */
*{box-sizing:border-box;margin:0;padding:0}

:root{
  --bg:#f5f7fb;
  --bg-alt:#ffffff;
  --card:#ffffff;
  --text:#141821;
  --muted:#5c6678;
  --accent:#6d28d9;
  --accent-soft:#ede9fe;
  --accent-2:#f59e0b;
  --border:#e2e7f0;
  --shadow:0 12px 34px rgba(16,24,40,.09);
  --shadow-sm:0 4px 14px rgba(16,24,40,.07);
  --hero:linear-gradient(135deg,#6d28d9 0%,#2563eb 55%,#f59e0b 100%);
  --ok:#10b981;
  --radius:16px;
}

[data-theme="dark"]{
  --bg:#0b1017;
  --bg-alt:#111a24;
  --card:#121b26;
  --text:#e9eef7;
  --muted:#96a4b8;
  --accent:#a78bfa;
  --accent-soft:#241a45;
  --accent-2:#fbbf24;
  --border:#1f2c3a;
  --shadow:0 12px 34px rgba(0,0,0,.55);
  --shadow-sm:0 4px 14px rgba(0,0,0,.45);
  --hero:linear-gradient(135deg,#4c1d95 0%,#1e3a8a 55%,#b45309 100%);
}

html{scroll-behavior:smooth}

body{
  font-family:'Segoe UI',system-ui,-apple-system,'Helvetica Neue',Arial,sans-serif;
  background:var(--bg);
  color:var(--text);
  line-height:1.75;
  transition:background .35s ease,color .35s ease;
  -webkit-font-smoothing:antialiased;
}

img{max-width:100%;display:block;border-radius:14px}
a{color:var(--accent);text-decoration:none}
a:hover{text-decoration:underline}
h1,h2,h3,h4{line-height:1.25;font-weight:800;letter-spacing:-.015em}
h1{font-size:clamp(1.9rem,4.2vw,3rem)}
h2{font-size:clamp(1.5rem,3vw,2.1rem);margin-bottom:.6rem}
h3{font-size:clamp(1.15rem,2vw,1.4rem);margin-bottom:.4rem}
h4{font-size:1.05rem;margin-bottom:.35rem}
p{margin-bottom:1rem}
ul,ol{margin:0 0 1rem 1.3rem}
li{margin-bottom:.45rem}
strong{font-weight:700}
small{color:var(--muted)}

.container{width:min(1150px,92%);margin-inline:auto}

/* ---------- HEADER ---------- */
.site-header{
  position:sticky;top:0;z-index:120;
  background:color-mix(in srgb,var(--bg-alt) 88%,transparent);
  backdrop-filter:blur(14px);
  border-bottom:1px solid var(--border);
  transition:background .35s ease,border-color .35s ease;
}
.header-top{
  display:flex;align-items:center;justify-content:space-between;
  gap:16px;padding:12px 0;flex-wrap:wrap;
}
.brand{display:flex;align-items:center;gap:12px;color:var(--text);font-weight:800;font-size:1.05rem}
.brand:hover{text-decoration:none}
.brand-logo{
  width:44px;height:44px;border-radius:14px;
  background:var(--hero);color:#fff;
  display:grid;place-items:center;font-size:1.4rem;
  box-shadow:var(--shadow-sm);flex:none;
}
.brand-sub{display:block;font-size:.72rem;font-weight:600;color:var(--muted);letter-spacing:.06em;text-transform:uppercase}
.header-actions{display:flex;align-items:center;gap:10px;flex-wrap:wrap}

.theme-btn{
  display:inline-flex;align-items:center;gap:7px;
  background:var(--bg);border:1px solid var(--border);color:var(--text);
  padding:9px 15px;border-radius:999px;cursor:pointer;font:inherit;
  font-size:.87rem;font-weight:600;transition:.25s;
}
.theme-btn:hover{border-color:var(--accent);color:var(--accent)}

.nav-strip{border-top:1px solid var(--border)}
.nav-links{
  display:flex;gap:4px;overflow-x:auto;padding:8px 0;
  scrollbar-width:none;
}
.nav-links::-webkit-scrollbar{display:none}
.nav-link{
  white-space:nowrap;padding:8px 14px;border-radius:999px;
  font-size:.88rem;font-weight:600;color:var(--muted);
  transition:.22s;border:1px solid transparent;
}
.nav-link:hover{color:var(--accent);background:var(--accent-soft);text-decoration:none}
.nav-link.active{
  color:#fff;background:var(--accent);border-color:var(--accent);
}

/* ---------- BUTTONS ---------- */
.btn{
  display:inline-flex;align-items:center;justify-content:center;gap:8px;
  padding:12px 24px;border-radius:999px;font-weight:700;font-size:.94rem;
  cursor:pointer;border:1px solid transparent;transition:.25s;font-family:inherit;
}
.btn:hover{text-decoration:none;transform:translateY(-2px)}
.btn-primary{background:var(--accent);color:#fff;box-shadow:0 8px 22px rgba(109,40,217,.32)}
.btn-primary:hover{background:color-mix(in srgb,var(--accent) 85%,#000)}
.btn-ghost{background:transparent;border-color:var(--border);color:var(--text)}
.btn-ghost:hover{border-color:var(--accent);color:var(--accent)}
.btn-gold{background:var(--accent-2);color:#1a1300;box-shadow:0 8px 22px rgba(245,158,11,.35)}
.btn-sm{padding:9px 18px;font-size:.85rem}

/* ---------- PAGES ---------- */
.page{display:none}
.page.active{display:block;animation:fadeUp .45s ease both}
@keyframes fadeUp{from{opacity:0;transform:translateY(14px)}to{opacity:1;transform:none}}

section.block{padding:56px 0}
section.block.tight{padding:34px 0}
.section-head{max-width:760px;margin-bottom:34px}
.eyebrow{
  display:inline-block;font-size:.75rem;font-weight:800;letter-spacing:.14em;
  text-transform:uppercase;color:var(--accent);
  background:var(--accent-soft);padding:6px 14px;border-radius:999px;margin-bottom:14px;
}
.lead{font-size:1.08rem;color:var(--muted)}

/* ---------- HERO ---------- */
.hero{
  background:var(--hero);color:#fff;padding:74px 0 84px;position:relative;overflow:hidden;
}
.hero::after{
  content:"";position:absolute;inset:0;
  background:radial-gradient(circle at 82% 18%,rgba(255,255,255,.22),transparent 42%),
             radial-gradient(circle at 12% 88%,rgba(255,255,255,.14),transparent 45%);
  pointer-events:none;
}
.hero-grid{display:grid;grid-template-columns:1.15fr .85fr;gap:44px;align-items:center;position:relative;z-index:2}
.hero h1{color:#fff;margin-bottom:18px}
.hero p{color:rgba(255,255,255,.93);font-size:1.06rem;max-width:600px}
.hero-badge{
  display:inline-flex;align-items:center;gap:8px;background:rgba(255,255,255,.18);
  border:1px solid rgba(255,255,255,.32);padding:7px 16px;border-radius:999px;
  font-size:.8rem;font-weight:700;letter-spacing:.05em;margin-bottom:20px;
}
.hero-actions{display:flex;gap:12px;flex-wrap:wrap;margin-top:24px}
.hero-actions .btn-ghost{border-color:rgba(255,255,255,.6);color:#fff}
.hero-actions .btn-ghost:hover{background:rgba(255,255,255,.16);color:#fff}
.hero-art{
  background:rgba(255,255,255,.12);border:1px solid rgba(255,255,255,.26);
  border-radius:24px;padding:16px;backdrop-filter:blur(6px);
}
.hero-art img{border-radius:16px}

/* ---------- STATS ---------- */
.stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(160px,1fr));gap:18px;margin-top:-42px;position:relative;z-index:5}
.stat{
  background:var(--card);border:1px solid var(--border);border-radius:var(--radius);
  padding:24px 20px;text-align:center;box-shadow:var(--shadow);
}
.stat-num{display:block;font-size:2rem;font-weight:800;color:var(--accent);line-height:1.1}
.stat-label{font-size:.85rem;color:var(--muted);font-weight:600}

/* ---------- CARDS & GRIDS ---------- */
.grid{display:grid;gap:22px}
.grid-2{grid-template-columns:repeat(auto-fit,minmax(300px,1fr))}
.grid-3{grid-template-columns:repeat(auto-fit,minmax(270px,1fr))}
.grid-4{grid-template-columns:repeat(auto-fit,minmax(215px,1fr))}

.card{
  background:var(--card);border:1px solid var(--border);border-radius:var(--radius);
  padding:26px;box-shadow:var(--shadow-sm);transition:.28s;
}
.card:hover{transform:translateY(-4px);box-shadow:var(--shadow);border-color:var(--accent)}
.card h3{margin-top:12px}
.card p:last-child{margin-bottom:0}
.card-icon{
  width:50px;height:50px;border-radius:14px;display:grid;place-items:center;
  font-size:1.5rem;background:var(--accent-soft);color:var(--accent);
}
.card .meta{font-size:.8rem;font-weight:700;color:var(--accent-2);letter-spacing:.05em;text-transform:uppercase}

.pill{
  display:inline-block;padding:5px 13px;border-radius:999px;font-size:.76rem;
  font-weight:700;background:var(--accent-soft);color:var(--accent);margin:0 6px 6px 0;
}
.pill.alt{background:rgba(245,158,11,.16);color:#b45309}
[data-theme="dark"] .pill.alt{color:var(--accent-2)}

/* ---------- SPLIT ---------- */
.split{display:grid;grid-template-columns:1fr 1fr;gap:42px;align-items:center}
.split img{box-shadow:var(--shadow)}

/* ---------- TABLE ---------- */
.table-wrap{overflow-x:auto;border:1px solid var(--border);border-radius:var(--radius);box-shadow:var(--shadow-sm)}
table{width:100%;border-collapse:collapse;background:var(--card);font-size:.92rem;min-width:560px}
th,td{padding:14px 16px;text-align:left;border-bottom:1px solid var(--border)}
th{background:var(--accent-soft);color:var(--accent);font-size:.78rem;letter-spacing:.07em;text-transform:uppercase;font-weight:800}
tbody tr:last-child td{border-bottom:none}
tbody tr:hover{background:color-mix(in srgb,var(--accent-soft) 45%,transparent)}

/* ---------- ACCORDION ---------- */
.acc{
  border:1px solid var(--border);border-radius:14px;background:var(--card);
  margin-bottom:12px;overflow:hidden;box-shadow:var(--shadow-sm);
}
.acc-head{
  width:100%;display:flex;justify-content:space-between;align-items:center;gap:14px;
  padding:16px 20px;background:none;border:none;font:inherit;font-weight:700;
  color:var(--text);cursor:pointer;text-align:left;transition:.2s;
}
.acc-head:hover{color:var(--accent)}
.acc-head::after{content:"+";font-size:1.4rem;color:var(--accent);line-height:1;flex:none}
.acc.open .acc-head::after{content:"–"}
.acc-body{max-height:0;overflow:hidden;transition:max-height .38s ease;padding:0 20px}
.acc.open .acc-body{max-height:1400px;padding-bottom:18px}
.acc-body ul{margin-bottom:0}

/* ---------- FORMS ---------- */
.form-card{
  background:var(--card);border:1px solid var(--border);border-radius:var(--radius);
  padding:32px;box-shadow:var(--shadow);
}
.form-grid{display:grid;grid-template-columns:1fr 1fr;gap:18px}
.field{display:flex;flex-direction:column;gap:7px}
.field.full{grid-column:1/-1}
label{font-size:.85rem;font-weight:700;color:var(--text)}
label span{color:#ef4444}
input,select,textarea{
  width:100%;padding:12px 15px;border-radius:11px;font:inherit;font-size:.93rem;
  background:var(--bg);border:1px solid var(--border);color:var(--text);
  transition:.22s;
}
input:focus,select:focus,textarea:focus{
  outline:none;border-color:var(--accent);
  box-shadow:0 0 0 4px color-mix(in srgb,var(--accent) 18%,transparent);
}
textarea{resize:vertical;min-height:120px}
.hint{font-size:.78rem;color:var(--muted)}
.form-msg{
  display:none;margin-top:18px;padding:15px 18px;border-radius:12px;
  background:rgba(16,185,129,.14);border:1px solid var(--ok);color:var(--ok);
  font-weight:600;font-size:.9rem;
}
.form-msg.show{display:block;animation:fadeUp .4s ease}

/* ---------- GALLERY ---------- */
.gallery{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:18px}
.gallery figure{
  position:relative;overflow:hidden;border-radius:var(--radius);
  border:1px solid var(--border);box-shadow:var(--shadow-sm);background:var(--card);
}
.gallery img{width:100%;height:220px;object-fit:cover;transition:transform .5s ease}
.gallery figure:hover img{transform:scale(1.07)}
.gallery figcaption{
  position:absolute;left:0;right:0;bottom:0;padding:26px 16px 14px;
  background:linear-gradient(transparent,rgba(0,0,0,.82));
  color:#fff;font-size:.86rem;font-weight:600;
}

/* ---------- CONTACT ---------- */
.contact-item{
  display:flex;gap:16px;align-items:flex-start;padding:18px;
  background:var(--card);border:1px solid var(--border);border-radius:14px;
  margin-bottom:14px;transition:.25s;
}
.contact-item:hover{border-color:var(--accent);transform:translateX(4px)}
.contact-icon{
  width:44px;height:44px;border-radius:12px;background:var(--accent-soft);
  color:var(--accent);display:grid;place-items:center;font-size:1.2rem;flex:none;
}
.contact-item strong{display:block;font-size:.78rem;text-transform:uppercase;letter-spacing:.08em;color:var(--muted)}

/* ---------- TIMELINE ---------- */
.timeline{position:relative;padding-left:32px}
.timeline::before{
  content:"";position:absolute;left:9px;top:6px;bottom:6px;width:3px;
  background:linear-gradient(var(--accent),var(--accent-2));border-radius:3px;
}
.tl-item{position:relative;margin-bottom:28px}
.tl-item::before{
  content:"";position:absolute;left:-30px;top:7px;width:15px;height:15px;
  border-radius:50%;background:var(--accent);border:3px solid var(--bg);
}
.tl-item h4{margin-bottom:4px}
.tl-item p{margin-bottom:0;color:var(--muted);font-size:.93rem}

/* ---------- CTA BANNER ---------- */
.cta-band{
  background:var(--hero);color:#fff;border-radius:24px;padding:52px 40px;
  text-align:center;box-shadow:var(--shadow);
}
.cta-band h2{color:#fff}
.cta-band p{color:rgba(255,255,255,.92);max-width:640px;margin-inline:auto}
.cta-band .btn{margin-top:20px}

/* ---------- FOOTER ---------- */
.site-footer{
  background:var(--bg-alt);border-top:1px solid var(--border);
  padding:56px 0 26px;margin-top:40px;
}
.footer-grid{display:grid;grid-template-columns:1.4fr 1fr 1fr 1.2fr;gap:32px}
.footer-grid h4{margin-bottom:14px;font-size:.82rem;letter-spacing:.1em;text-transform:uppercase;color:var(--muted)}
.footer-grid a{color:var(--text);font-size:.92rem;display:block;margin-bottom:9px;transition:.2s}
.footer-grid a:hover{color:var(--accent);text-decoration:none;transform:translateX(3px)}
.footer-bottom{
  margin-top:34px;padding-top:22px;border-top:1px solid var(--border);
  display:flex;justify-content:space-between;gap:14px;flex-wrap:wrap;
  font-size:.85rem;color:var(--muted);
}

/* ---------- RESPONSIVE ---------- */
@media(max-width:900px){
  .hero-grid{grid-template-columns:1fr}
  .split{grid-template-columns:1fr}
  .form-grid{grid-template-columns:1fr}
  .footer-grid{grid-template-columns:1fr 1fr}
  .stats{margin-top:26px}
  section.block{padding:40px 0}
  .hero{padding:52px 0 62px}
}
@media(max-width:560px){
  .footer-grid{grid-template-columns:1fr}
  .cta-band{padding:36px 22px}
  .form-card{padding:22px}
  .brand-sub{display:none}
}
</style>
</head>

<body>

<!-- ============================================================
     HEADER
     ============================================================ -->
<header class="site-header">
  <div class="container header-top">
    <a href="#home" class="brand">
      <span class="brand-logo">♪</span>
      <span>
        <strong>HACIMS</strong> Music Center
        <span class="brand-sub">Kilimanjaro · Tanzania</span>
      </span>
    </a>
    <div class="header-actions">
      <button id="themeToggle" class="theme-btn" aria-label="Toggle light and dark mode">
        <span id="themeIcon">🌙</span><span id="themeLabel">Dark</span>
      </button>
      <a href="#register" class="btn btn-primary btn-sm">Enroll Now</a>
    </div>
  </div>

  <nav class="nav-strip" aria-label="Main navigation">
    <div class="container nav-links">
      <a class="nav-link" href="#home">Home</a>
      <a class="nav-link" href="#about">About Us</a>
      <a class="nav-link" href="#team">Our Team</a>
      <a class="nav-link" href="#courses">All Courses</a>
      <a class="nav-link" href="#nota">Music Notation (Nota)</a>
      <a class="nav-link" href="#piano">Piano</a>
      <a class="nav-link" href="#guitar">Guitar</a>
      <a class="nav-link" href="#violin">Violin</a>
      <a class="nav-link" href="#drums">Drums</a>
      <a class="nav-link" href="#xylophone">Xylophone</a>
      <a class="nav-link" href="#flute">Flute</a>
      <a class="nav-link" href="#books">Books &amp; Resources</a>
      <a class="nav-link" href="#gallery">Gallery</a>
      <a class="nav-link" href="#schedule">Timetable</a>
      <a class="nav-link" href="#register">Registration</a>
      <a class="nav-link" href="#faq">FAQ</a>
      <a class="nav-link" href="#contact">Contact</a>
    </div>
  </nav>
</header>

<main id="app">

<!-- ============================================================
     PAGE 1 — HOME
     ============================================================ -->
<section class="page active" id="home">

  <div class="hero">
    <div class="container hero-grid">
      <div>
        <span class="hero-badge">🎼 ONLINE MUSIC SCHOOL · EST. KILIMANJARO, TANZANIA</span>
        <h1>Learn Music Properly — From Your First Note to Your First Performance</h1>
        <p>
          HACIMS Music Center teaches you how to <strong>read Nota (music notation)</strong> and how to
          play the <strong>piano, guitar, violin, drums, xylophone and flute</strong> through structured,
          week-by-week online lessons guided by real musicians in Tanzania. Every course runs for
          <strong>more than two weeks and less than ten months</strong> — long enough to build real skill,
          short enough to keep your momentum alive.
        </p>
        <div class="hero-actions">
          <a href="#register" class="btn btn-gold">Register for a Course</a>
          <a href="#courses" class="btn btn-ghost">Explore All Courses</a>
        </div>
      </div>
      <div class="hero-art">
        <img src="https://picsum.photos/seed/hacims-hero-music/760/560" alt="Music students learning together" loading="lazy">
      </div>
    </div>
  </div>

  <div class="container">
    <div class="stats">
      <div class="stat"><span class="stat-num" data-target="7">0</span><span class="stat-label">Structured Courses</span></div>
      <div class="stat"><span class="stat-num" data-target="1200">0</span><span class="stat-label">Lessons Delivered</span></div>
      <div class="stat"><span class="stat-num" data-target="480">0</span><span class="stat-label">Students Trained</span></div>
      <div class="stat"><span class="stat-num" data-target="100">0</span><span class="stat-label">Percent Online</span></div>
    </div>
  </div>

  <section class="block">
    <div class="container">
      <div class="section-head">
        <span class="eyebrow">Why HACIMS</span>
        <h2>A Music School Built Around the Student, Not the Clock</h2>
        <p class="lead">
          Most people give up on music because lessons are disorganised. At HACIMS every course follows a
          written curriculum, every week has a clear goal, and every student receives feedback on their
          playing. We teach the theory (Nota) and the instrument together, so you understand what you are
          playing — not just copying videos.
        </p>
      </div>

      <div class="grid grid-3">
        <div class="card">
          <div class="card-icon">🎯</div>
          <h3>Clear Weekly Goals</h3>
          <p>Each week has a defined target: a scale, a rhythm, a piece, or a theory concept. You always know exactly what to practise and how to measure progress.</p>
        </div>
        <div class="card">
          <div class="card-icon">📖</div>
          <h3>Nota From Day One</h3>
          <p>You learn to read the staff, clefs, note values, rests, time signatures and key signatures from the very first lesson — no guessing.</p>
        </div>
        <div class="card">
          <div class="card-icon">🎥</div>
          <h3>Live + Recorded Lessons</h3>
          <p>Join live online classes with our teachers and re-watch recordings anytime. Missed a lesson? Nothing is lost.</p>
        </div>
        <div class="card">
          <div class="card-icon">🧑‍🏫</div>
          <h3>Real Teachers</h3>
          <p>Our team is led by Haytham A. Munisi and supported by Emmanuel D. Shirima and Hacims A. Munisi — practising musicians, not automated bots.</p>
        </div>
        <div class="card">
          <div class="card-icon">💰</div>
          <h3>Affordable Fees</h3>
          <p>Courses are priced for East African students, with flexible payment in instalments across the course duration.</p>
        </div>
        <div class="card">
          <div class="card-icon">🌍</div>
          <h3>Learn From Anywhere</h3>
          <p>Based in Kilimanjaro, Tanzania — but our classroom is the internet. Students join from Tanzania, Kenya, Uganda, and beyond.</p>
        </div>
      </div>
    </div>
  </section>

  <section class="block tight">
    <div class="container">
      <div class="section-head">
        <span class="eyebrow">Popular Courses</span>
        <h2>Pick Your Instrument</h2>
        <p class="lead">Six instruments and one complete music theory course. Each one is a full curriculum, not a short tutorial series.</p>
      </div>

      <div class="grid grid-3">
        <a href="#piano" class="card">
          <div class="card-icon">🎹</div>
          <span class="meta">12 Weeks</span>
          <h3>Piano</h3>
          <p>From hand position and five-finger patterns to chords, scales, arpeggios and your first complete piece.</p>
        </a>
        <a href="#guitar" class="card">
          <div class="card-icon">🎸</div>
          <span class="meta">10 Weeks</span>
          <h3>Guitar</h3>
          <p>Open chords, barre chords, strumming patterns, fingerstyle and reading chord charts and tablature.</p>
        </a>
        <a href="#violin" class="card">
          <div class="card-icon">🎻</div>
          <span class="meta">16 Weeks</span>
          <h3>Violin</h3>
          <p>Bow hold, posture, intonation, first position, scales and beginner repertoire with careful technique work.</p>
        </a>
        <a href="#drums" class="card">
          <div class="card-icon">🥁</div>
          <span class="meta">8 Weeks</span>
          <h3>Drums</h3>
          <p>Rudiments, grooves, fills, time-keeping and playing with a metronome — the heartbeat of any band.</p>
        </a>
        <a href="#xylophone" class="card">
          <div class="card-icon">🎵</div>
          <span class="meta">6 Weeks</span>
          <h3>Xylophone</h3>
          <p>Mallet technique, the C major layout, two-mallet melodies and traditional East African rhythms.</p>
        </a>
        <a href="#flute" class="card">
          <div class="card-icon">🪈</div>
          <span class="meta">10 Weeks</span>
          <h3>Flute</h3>
          <p>Embouchure, breath control, tone production, articulation and your first melodies across two octaves.</p>
        </a>
      </div>

      <div class="cta-band" style="margin-top:44px">
        <h2>Not Sure Which Course Fits You?</h2>
        <p>Fill in our course inquiry form and our manager Haytham A. Munisi will personally recommend the right course, level and schedule for you.</p>
        <a href="#register" class="btn btn-gold">Request a Recommendation</a>
      </div>
    </div>
  </section>

  <section class="block">
    <div class="container">
      <div class="section-head">
        <span class="eyebrow">Student Voices</span>
        <h2>What Our Students Say</h2>
      </div>
      <div class="grid grid-3">
        <div class="card">
          <p>“I always thought reading Nota was impossible. After four weeks of the HACIMS theory course I could read a simple melody and clap the rhythm correctly.”</p>
          <p><strong>— Neema J., Moshi</strong></p>
        </div>
        <div class="card">
          <p>“The guitar course is well organised. Every week I knew exactly what to practise. The strumming module alone changed how I play in church.”</p>
          <p><strong>— Baraka M., Arusha</strong></p>
        </div>
        <div class="card">
          <p>“Mr. Haytham is patient and very clear. He corrects your technique instead of letting you build bad habits. Highly recommended.”</p>
          <p><strong>— Grace K., Dar es Salaam</strong></p>
        </div>
      </div>
    </div>
  </section>

</section>


<!-- ============================================================
     PAGE 2 — ABOUT
     ============================================================ -->
<section class="page" id="about">
  <div class="container">
    <section class="block">
      <div class="section-head">
        <span class="eyebrow">About HACIMS</span>
        <h2>Our Story, Our Mission, Our Method</h2>
        <p class="lead">
          HACIMS Music Center is an online music school founded in the Kilimanjaro Region of Tanzania.
          We exist for one reason: to make proper, structured music education available to anyone with
          an internet connection and a willingness to practise.
        </p>
      </div>

      <div class="split" style="margin-bottom:44px">
        <div>
          <h3>How We Started</h3>
          <p>
            HACIMS began as a small group of musicians teaching friends and church members in Kilimanjaro.
            What started as informal weekend sessions quickly grew into something bigger: students wanted
            a real curriculum, real assignments, and real feedback. They wanted to understand music — not
            just imitate it.
          </p>
          <p>
            Under the leadership of <strong>Haytham A. Munisi</strong>, the team formalised the teaching
            material into structured courses. Each course was broken into weekly modules, each module into
            lessons, and each lesson into specific practice tasks. The result is the programme you see on
            this website today — delivered fully online so that distance is never a barrier.
          </p>
          <p>
            Today HACIMS Music Center serves students across Tanzania and beyond, teaching music notation,
            piano, guitar, violin, drums, xylophone and flute.
          </p>
        </div>
        <div>
          <img src="https://picsum.photos/seed/hacims-about-studio/800/600" alt="HACIMS music studio session" loading="lazy">
        </div>
      </div>

      <div class="grid grid-3">
        <div class="card">
          <div class="card-icon">🎯</div>
          <h3>Our Mission</h3>
          <p>To provide affordable, structured and high-quality music education to every learner in Tanzania and beyond, combining solid theory with practical instrument training.</p>
        </div>
        <div class="card">
          <div class="card-icon">👁️</div>
          <h3>Our Vision</h3>
          <p>To become the most trusted online music school in East Africa — a place where a beginner in a village and a student in the city receive the same quality of instruction.</p>
        </div>
        <div class="card">
          <div class="card-icon">💎</div>
          <h3>Our Values</h3>
          <p>Discipline, patience, honesty, respect for the learner's pace, and a genuine love for music as an art form rather than a race to the finish.</p>
        </div>
      </div>
    </section>

    <section class="block tight">
      <div class="section-head">
        <span class="eyebrow">Our Method</span>
        <h2>The Four Pillars of a HACIMS Lesson</h2>
      </div>
      <div class="grid grid-4">
        <div class="card">
          <div class="card-icon">1️⃣</div>
          <h3>Theory</h3>
          <p>Every lesson starts with a short theory segment — notation, rhythm, intervals or harmony — so you understand the "why" before the "how".</p>
        </div>
        <div class="card">
          <div class="card-icon">2️⃣</div>
          <h3>Technique</h3>
          <p>Correct posture, hand position, embouchure or stick grip. Technique is taught first because bad habits are expensive to fix later.</p>
        </div>
        <div class="card">
          <div class="card-icon">3️⃣</div>
          <h3>Repertoire</h3>
          <p>You learn real pieces — short studies, songs and exercises — so that practice always feels like making music, not just doing drills.</p>
        </div>
        <div class="card">
          <div class="card-icon">4️⃣</div>
          <h3>Feedback</h3>
          <p>You submit a short recording or answer questions each week. Your teacher reviews it and tells you exactly what to correct.</p>
        </div>
      </div>
    </section>

    <section class="block tight">
      <div class="section-head">
        <span class="eyebrow">Milestones</span>
        <h2>Our Journey So Far</h2>
      </div>
      <div class="timeline">
        <div class="tl-item">
          <h4>Foundation</h4>
          <p>Informal weekend music sessions begin in Kilimanjaro with a handful of enthusiastic students.</p>
        </div>
        <div class="tl-item">
          <h4>Curriculum Development</h4>
          <p>The teaching team writes the first structured Nota syllabus and instrument modules.</p>
        </div>
        <div class="tl-item">
          <h4>Going Online</h4>
          <p>HACIMS moves its courses online, allowing students from other regions to join live classes.</p>
        </div>
        <div class="tl-item">
          <h4>Course Expansion</h4>
          <p>The programme expands to six instruments plus a dedicated music theory track.</p>
        </div>
        <div class="tl-item">
          <h4>Today</h4>
          <p>HACIMS Music Center continues to grow, guided by manager Haytham A. Munisi and a dedicated teaching team.</p>
        </div>
      </div>
    </section>

    <section class="block tight">
      <div class="container" style="width:100%">
        <div class="cta-band">
          <h2>Study With Us From Anywhere</h2>
          <p>All you need is a phone, tablet or laptop, an internet connection, and 30–45 minutes of practice a day. We provide the curriculum, the guidance and the feedback.</p>
          <a href="#register" class="btn btn-gold">Start Your Registration</a>
        </div>
      </div>
    </section>
  </div>
</section>


<!-- ============================================================
     PAGE 3 — TEAM
     ============================================================ -->
<section class="page" id="team">
  <div class="container">
    <section class="block">
      <div class="section-head">
        <span class="eyebrow">Our People</span>
        <h2>Meet the HACIMS Teaching Team</h2>
        <p class="lead">
          HACIMS is run by a small, dedicated team of musicians based in Tanzania. We teach every course
          ourselves, which means you always know who is guiding your progress.
        </p>
      </div>

      <div class="grid grid-3">
        <div class="card">
          <img src="https://picsum.photos/seed/hacims-manager-haytham/600/600" alt="Haytham A. Munisi" loading="lazy" style="height:240px;object-fit:cover">
          <h3 style="margin-top:16px">Haytham A. Munisi</h3>
          <p class="meta" style="color:var(--accent);font-weight:700;font-size:.82rem;letter-spacing:.06em;text-transform:uppercase">Manager &amp; Lead Instructor</p>
          <p>
            Haytham is the founder and manager of HACIMS Music Center, based in the Kilimanjaro Region of
            Tanzania. He leads the school's curriculum design and teaches the core music notation (Nota)
            course as well as piano and guitar.
          </p>
          <p>
            His teaching philosophy is simple: build understanding first, then speed. Students under his
            guidance are known for reading music confidently rather than relying on memory alone. He also
            handles course inquiries, student placement and scheduling for the whole school.
          </p>
          <span class="pill">Nota</span><span class="pill">Piano</span><span class="pill">Guitar</span>
        </div>

        <div class="card">
          <img src="https://picsum.photos/seed/hacims-emmanuel-shirima/600/600" alt="Emmanuel D. Shirima" loading="lazy" style="height:240px;object-fit:cover">
          <h3 style="margin-top:16px">Emmanuel D. Shirima</h3>
          <p class="meta" style="color:var(--accent);font-weight:700;font-size:.82rem;letter-spacing:.06em;text-transform:uppercase">Instructor — Rhythm &amp; Percussion</p>
          <p>
            Emmanuel specialises in rhythm training, drums and xylophone. He is the person who makes sure
            HACIMS students can keep time — a skill that quietly improves every other instrument they play.
          </p>
          <p>
            His lessons focus on rudiments, subdivision, groove and consistency with a metronome. He is
            particularly skilled at breaking complex rhythms into small, learnable steps for beginners.
          </p>
          <span class="pill">Drums</span><span class="pill">Xylophone</span><span class="pill">Rhythm</span>
        </div>

        <div class="card">
          <img src="https://picsum.photos/seed/hacims-hacims-munisi/600/600" alt="Hacims A. Munisi" loading="lazy" style="height:240px;object-fit:cover">
          <h3 style="margin-top:16px">Hacims A. Munisi</h3>
          <p class="meta" style="color:var(--accent);font-weight:700;font-size:.82rem;letter-spacing:.06em;text-transform:uppercase">Instructor — Strings &amp; Woodwind</p>
          <p>
            Hacims teaches violin and flute at HACIMS Music Center, with a strong emphasis on posture, tone
            production and intonation — the three pillars of good string and wind playing.
          </p>
          <p>
            He works closely with beginners to ensure they start with correct bow holds and embouchure,
            saving them months of correction later. He also assists with student recordings and progress
            reviews.
          </p>
          <span class="pill">Violin</span><span class="pill">Flute</span><span class="pill">Ear Training</span>
        </div>
      </div>
    </section>

    <section class="block tight">
      <div class="section-head">
        <span class="eyebrow">How We Work</span>
        <h2>Teaching Responsibilities</h2>
      </div>
      <div class="table-wrap">
        <table>
          <thead>
            <tr><th>Team Member</th><th>Primary Role</th><th>Courses Taught</th><th>Also Handles</th></tr>
          </thead>
          <tbody>
            <tr><td><strong>Haytham A. Munisi</strong></td><td>Manager &amp; Lead Instructor</td><td>Nota, Piano, Guitar</td><td>Curriculum, admissions, scheduling</td></tr>
            <tr><td><strong>Emmanuel D. Shirima</strong></td><td>Rhythm &amp; Percussion Instructor</td><td>Drums, Xylophone</td><td>Rhythm clinics, ensemble practice</td></tr>
            <tr><td><strong>Hacims A. Munisi</strong></td><td>Strings &amp; Woodwind Instructor</td><td>Violin, Flute</td><td>Ear training, student recordings</td></tr>
          </tbody>
        </table>
      </div>
    </section>

    <section class="block tight">
      <div class="section-head">
        <span class="eyebrow">Get In Touch</span>
        <h2>Talk Directly to the Team</h2>
        <p class="lead">Questions about a course, a schedule, or fees? Contact us directly — we answer personally.</p>
      </div>
      <div class="grid grid-2">
        <div class="contact-item">
          <div class="contact-icon">📞</div>
          <div><strong>Phone / WhatsApp</strong><a href="tel:+255671558607">+255 671 558 607</a> — Hacims</div>
        </div>
        <div class="contact-item">
          <div class="contact-icon">✉️</div>
          <div><strong>Email</strong><a href="mailto:hacims26munisi@gmail.com">hacims26munisi@gmail.com</a></div>
        </div>
        <div class="contact-item">
          <div class="contact-icon">🎵</div>
          <div><strong>TikTok</strong><a href="https://www.tiktok.com/@Hacims26" target="_blank" rel="noopener">@Hacims26</a></div>
        </div>
        <div class="contact-item">
          <div class="contact-icon">💻</div>
          <div><strong>GitHub</strong><a href="https://github.com/hacims26c" target="_blank" rel="noopener">hacims26c</a></div>
        </div>
      </div>
    </section>
  </div>
</section>


<!-- ============================================================
     PAGE 4 — ALL COURSES
     ============================================================ -->
<section class="page" id="courses">
  <div class="container">
    <section class="block">
      <div class="section-head">
        <span class="eyebrow">Course Catalogue</span>
        <h2>All HACIMS Online Courses</h2>
        <p class="lead">
          Every HACIMS course lasts <strong>more than two weeks</strong> and <strong>less than ten months</strong>.
          That range is deliberate: it is long enough to build genuine skill and short enough that you finish
          what you start. Choose a course below to see the full week-by-week curriculum.
        </p>
      </div>

      <div class="table-wrap">
        <table>
          <thead>
            <tr>
              <th>Course</th><th>Duration</th><th>Level</th><th>Lessons / Week</th><th>Fee (TZS)</th>
            </tr>
          </thead>
          <tbody>
            <tr><td><a href="#nota"><strong>Music Notation (Nota)</strong></a></td><td>4 weeks</td><td>Beginner</td><td>2</td><td>80,000</td></tr>
            <tr><td><a href="#piano"><strong>Piano</strong></a></td><td>12 weeks</td><td>Beginner → Intermediate</td><td>2</td><td>180,000</td></tr>
            <tr><td><a href="#guitar"><strong>Guitar</strong></a></td><td>10 weeks</td><td>Beginner → Intermediate</td><td>2</td><td>150,000</td></tr>
            <tr><td><a href="#violin"><strong>Violin</strong></a></td><td>16 weeks</td><td>Beginner</td><td>2</td><td>220,000</td></tr>
            <tr><td><a href="#drums"><strong>Drums</strong></a></td><td>8 weeks</td><td>Beginner</td><td>2</td><td>130,000</td></tr>
            <tr><td><a href="#xylophone"><strong>Xylophone</strong></a></td><td>6 weeks</td><td>Beginner</td><td>2</td><td>100,000</td></tr>
            <tr><td><a href="#flute"><strong>Flute</strong></a></td><td>10 weeks</td><td>Beginner</td><td>2</td><td>150,000</td></tr>
          </tbody>
        </table>
      </div>
      <p class="hint" style="margin-top:14px">
        Fees are payable in two instalments (50% at registration, 50% at the mid-point of the course).
        Students taking two or more courses receive a 15% discount on the second course.
      </p>
    </section>

    <section class="block tight">
      <div class="section-head">
        <span class="eyebrow">What's Included</span>
        <h2>Every HACIMS Course Includes</h2>
      </div>
      <div class="grid grid-3">
        <div class="card"><div class="card-icon">📚</div><h3>Written Curriculum</h3><p>A downloadable week-by-week syllabus so you always know where you are and what comes next.</p></div>
        <div class="card"><div class="card-icon">🎥</div><h3>Live Classes</h3><p>Two live online sessions per week with your instructor, plus recordings you can re-watch at any time.</p></div>
        <div class="card"><div class="card-icon">📝</div><h3>Weekly Assignments</h3><p>Short, focused practice tasks that take 20–45 minutes a day — realistic for students and workers.</p></div>
        <div class="card"><div class="card-icon">🔍</div><h3>Personal Feedback</h3><p>Submit a recording or answer theory questions; your teacher reviews and responds with corrections.</p></div>
        <div class="card"><div class="card-icon">🎓</div><h3>Certificate</h3><p>A HACIMS Music Center certificate of completion issued at the end of every course.</p></div>
        <div class="card"><div class="card-icon">🤝</div><h3>Community</h3><p>Access to the HACIMS student group where learners share recordings, ask questions and encourage each other.</p></div>
      </div>
    </section>

    <section class="block tight">
      <div class="section-head">
        <span class="eyebrow">Learning Path</span>
        <h2>A Suggested Order of Study</h2>
        <p class="lead">Not sure how to combine courses? Here is the path most successful HACIMS students follow.</p>
      </div>
      <div class="timeline">
        <div class="tl-item"><h4>Step 1 — Music Notation (Nota), 4 weeks</h4><p>Learn to read the staff, clefs, note values, rests and time signatures. This makes every instrument course easier.</p></div>
        <div class="tl-item"><h4>Step 2 — Your First Instrument, 6–16 weeks</h4><p>Choose piano, guitar, violin, drums, xylophone or flute and complete the full beginner curriculum.</p></div>
        <div class="tl-item"><h4>Step 3 — Rhythm Reinforcement, 6–8 weeks</h4><p>Optional: take drums or xylophone alongside your main instrument to sharpen timing and subdivision.</p></div>
        <div class="tl-item"><h4>Step 4 — Second Instrument</h4><p>With notation and rhythm already in place, a second instrument becomes dramatically easier.</p></div>
      </div>
    </section>

    <section class="block tight">
      <div class="cta-band">
        <h2>Ready to Choose?</h2>
        <p>Fill in the registration form and our manager will confirm your place, your start date and your class schedule.</p>
        <a href="#register" class="btn btn-gold">Go to Registration</a>
      </div>
    </section>
  </div>
</section>


<!-- ============================================================
     PAGE 5 — NOTA (MUSIC NOTATION)
     ============================================================ -->
<section class="page" id="nota">
  <div class="container">
    <section class="block">
      <div class="section-head">
        <span class="eyebrow">Course 1 · 4 Weeks</span>
        <h2>How to Read Nota — Music Notation for Beginners</h2>
        <p class="lead">
          "Nota" is the ability to read and write music. It is the single most valuable skill in music
          education, and it is the foundation on which every HACIMS instrument course is built. In four
          intensive weeks you will go from "I can't read music" to "I can read a simple melody and clap
          its rhythm accurately."
        </p>
      </div>

      <div class="split" style="margin-bottom:40px">
        <div>
          <h3>Why Learn Notation?</h3>
          <p>
            Players who cannot read music depend entirely on memory and imitation. They learn a song by
            watching someone else, and they forget it a month later. Players who read music can open any
            score, learn a piece independently, write down their own ideas, and communicate with other
            musicians using a shared language.
          </p>
          <p>
            Notation also makes theory understandable. Chords, scales, intervals and keys all live on the
            staff. Once you can read the staff, the rest of music theory stops feeling like magic.
          </p>
          <p><strong>This course requires no instrument.</strong> You can study it on its own, or alongside an instrument course.</p>
        </div>
        <div><img src="https://picsum.photos/seed/hacims-notation-sheet/800/600" alt="Music notation on a staff" loading="lazy"></div>
      </div>

      <h3 style="margin-bottom:16px">Course Curriculum — Week by Week</h3>

      <div class="acc">
        <button class="acc-head">Week 1 — The Staff, Clefs and Pitch</button>
        <div class="acc-body">
          <ul>
            <li>What the musical staff is and why it has five lines and four spaces.</li>
            <li>The treble clef (G clef) and the bass clef (F clef) — how to draw them and what they mean.</li>
            <li>Naming notes on lines and spaces: the "Every Good Boy Deserves Football" and "FACE" methods.</li>
            <li>Ledger lines above and below the staff.</li>
            <li>Reading your first ten notes aloud, then writing them from dictation.</li>
            <li><strong>Weekly task:</strong> name 30 notes on a worksheet and write 10 notes from memory.</li>
          </ul>
        </div>
      </div>

      <div class="acc">
        <button class="acc-head">Week 2 — Note Values, Rests and Rhythm</button>
        <div class="acc-body">
          <ul>
            <li>Whole notes, half notes, quarter notes, eighth notes and sixteenth notes.</li>
            <li>Their equivalent rests — silence is part of music too.</li>
            <li>Dotted notes and ties: how a dot adds half the value again.</li>
            <li>Beaming eighth notes correctly and understanding note grouping.</li>
            <li>Counting aloud: "1 and 2 and 3 and 4 and".</li>
            <li>Clapping rhythms from notation without any instrument.</li>
            <li><strong>Weekly task:</strong> clap and record four two-bar rhythms written by your teacher.</li>
          </ul>
        </div>
      </div>

      <div class="acc">
        <button class="acc-head">Week 3 — Time Signatures, Bar Lines and Accents</button>
        <div class="acc-body">
          <ul>
            <li>What the top and bottom numbers of a time signature mean.</li>
            <li>Simple time: 4/4, 3/4, 2/4 — and how each one feels different.</li>
            <li>Compound time: 6/8 and why it swings.</li>
            <li>Bar lines, double bar lines and repeat signs.</li>
            <li>Strong beats, weak beats and accent marks.</li>
            <li>Anacrusis (pickup notes) — starting before beat one.</li>
            <li><strong>Weekly task:</strong> complete three melodies by adding the correct bar lines.</li>
          </ul>
        </div>
      </div>

      <div class="acc">
        <button class="acc-head">Week 4 — Key Signatures, Accidentals and Reading a Melody</button>
        <div class="acc-body">
          <ul>
            <li>Sharps (♯), flats (♭) and naturals (♮) — where they sit and what they do.</li>
            <li>Key signatures: C major, G major, D major, F major.</li>
            <li>The order of sharps and flats in key signatures.</li>
            <li>Dynamics: p, mp, mf, f and crescendo/decrescendo marks.</li>
            <li>Tempo markings: Adagio, Andante, Moderato, Allegro.</li>
            <li>Reading a complete eight-bar melody and clapping the rhythm correctly.</li>
            <li><strong>Final assessment:</strong> a short written test plus reading one melody aloud.</li>
          </ul>
        </div>
      </div>

      <h3 style="margin:34px 0 16px">Notation Quick-Reference Table</h3>
      <div class="table-wrap">
        <table>
          <thead><tr><th>Symbol</th><th>Name</th><th>Value (in 4/4)</th><th>How to Count</th></tr></thead>
          <tbody>
            <tr><td>𝅝</td><td>Whole note (semibreve)</td><td>4 beats</td><td>1 – 2 – 3 – 4</td></tr>
            <tr><td>𝅗𝅥</td><td>Half note (minim)</td><td>2 beats</td><td>1 – 2</td></tr>
            <tr><td>♩</td><td>Quarter note (crotchet)</td><td>1 beat</td><td>1</td></tr>
            <tr><td>♪</td><td>Eighth note (quaver)</td><td>½ beat</td><td>"and"</td></tr>
            <tr><td>♬</td><td>Sixteenth note (semiquaver)</td><td>¼ beat</td><td>"e-and-a"</td></tr>
            <tr><td>𝄽</td><td>Quarter rest</td><td>1 beat of silence</td><td>Rest on 1</td></tr>
          </tbody>
        </table>
      </div>

      <h3 style="margin:34px 0 16px">Practice Tips That Actually Work</h3>
      <div class="grid grid-2">
        <div class="card"><h3>Clap Before You Play</h3><p>Before touching an instrument, clap the rhythm of the melody. Rhythm errors are the most common beginner mistake, and clapping isolates them.</p></div>
        <div class="card"><h3>Say the Note Names Out Loud</h3><p>Reading silently is slower to learn. Speak the note names as you read — it forces your brain to process each symbol.</p></div>
        <div class="card"><h3>Ten Minutes a Day</h3><p>Notation is a language. Ten focused minutes every day beats a two-hour session once a week, every single time.</p></div>
        <div class="card"><h3>Write Your Own Rhythms</h3><p>Composing four-bar rhythms yourself is the fastest way to internalise note values and bar lines.</p></div>
      </div>
    </section>

    <section class="block tight">
      <div class="cta-band">
        <h2>Start Reading Music in Four Weeks</h2>
        <p>The Nota course runs for four weeks with two live lessons per week. Fee: TZS 80,000.</p>
        <a href="#register" class="btn btn-gold">Register for Nota</a>
      </div>
    </section>
  </div>
</section>


<!-- ============================================================
     PAGE 6 — PIANO
     ============================================================ -->
<section class="page" id="piano">
  <div class="container">
    <section class="block">
      <div class="section-head">
        <span class="eyebrow">Course 2 · 12 Weeks</span>
        <h2>Piano Course — From First Touch to First Piece</h2>
        <p class="lead">
          The piano is the most visually logical instrument in music: every note is laid out in front of
          you. Our twelve-week piano course takes advantage of that clarity to build technique, note
          reading and musical confidence at the same time.
        </p>
      </div>

      <div class="split" style="margin-bottom:40px">
        <div><img src="https://picsum.photos/seed/hacims-piano-keys/800/600" alt="Piano keyboard close-up" loading="lazy"></div>
        <div>
          <h3>What You Will Be Able to Do</h3>
          <ul>
            <li>Sit with correct posture, hand shape and finger numbering.</li>
            <li>Play all twelve major scales with correct fingering.</li>
            <li>Read and play music in both treble and bass clefs simultaneously.</li>
            <li>Build and play all common major and minor chords and their inversions.</li>
            <li>Play simple arpeggios and broken chords smoothly.</li>
            <li>Perform two complete pieces from start to finish with correct rhythm.</li>
            <li>Accompany a simple melody using basic chord progressions.</li>
          </ul>
        </div>
      </div>

      <h3 style="margin-bottom:16px">Curriculum — Week by Week</h3>

      <div class="acc">
        <button class="acc-head">Module 1 (Weeks 1–3) — Foundations</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 1:</strong> Posture, bench height, hand shape, finger numbers 1–5. Finding Middle C. Five-finger pattern in C major. Playing single notes with a steady pulse.</li>
            <li><strong>Week 2:</strong> Reading treble clef notes in the C position. Quarter and half notes. Right-hand melodies with correct counting aloud.</li>
            <li><strong>Week 3:</strong> Introducing the bass clef. Left-hand five-finger patterns. Coordinating both hands in simple contrary motion.</li>
          </ul>
        </div>
      </div>

      <div class="acc">
        <button class="acc-head">Module 2 (Weeks 4–6) — Scales and Chords</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 4:</strong> The C major scale, two octaves, with correct thumb-under fingering. Whole steps and half steps explained.</li>
            <li><strong>Week 5:</strong> Major and minor triads. Root position chords in C, F and G. Chord changes with smooth hand movement.</li>
            <li><strong>Week 6:</strong> Chord inversions. Playing a I–IV–V–I progression in the left hand while the right hand plays a melody.</li>
          </ul>
        </div>
      </div>

      <div class="acc">
        <button class="acc-head">Module 3 (Weeks 7–9) — Reading and Independence</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 7:</strong> Eighth notes and dotted rhythms. Independent hands — different rhythms in each hand.</li>
            <li><strong>Week 8:</strong> Key signatures up to two sharps and two flats. Playing in G major and F major.</li>
            <li><strong>Week 9:</strong> Arpeggios and broken chords. Pedalling basics — when to press and when to lift.</li>
          </ul>
        </div>
      </div>

      <div class="acc">
        <button class="acc-head">Module 4 (Weeks 10–12) — Repertoire and Performance</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 10:</strong> Learning a complete piece section by section. Hands-separate practice strategy.</li>
            <li><strong>Week 11:</strong> Dynamics, phrasing and expression. Making the piece sound musical rather than mechanical.</li>
            <li><strong>Week 12:</strong> Final performance recording, self-assessment, and a written progress report from your teacher.</li>
          </ul>
        </div>
      </div>

      <h3 style="margin:34px 0 16px">Weekly Practice Routine</h3>
      <div class="table-wrap">
        <table>
          <thead><tr><th>Activity</th><th>Time</th><th>Purpose</th></tr></thead>
          <tbody>
            <tr><td>Finger warm-up / scales</td><td>8 min</td><td>Builds evenness and strength</td></tr>
            <tr><td>Sight reading</td><td>7 min</td><td>Trains note recognition speed</td></tr>
            <tr><td>Technique exercise</td><td>10 min</td><td>Targets the week's specific skill</td></tr>
            <tr><td>Repertoire piece</td><td>15 min</td><td>Applies everything to real music</td></tr>
            <tr><td>Free play / improvisation</td><td>5 min</td><td>Keeps the instrument fun</td></tr>
          </tbody>
        </table>
      </div>

      <h3 style="margin:34px 0 16px">What You Need</h3>
      <div class="grid grid-3">
        <div class="card"><h3>An Instrument</h3><p>A 61-key keyboard is enough to start; 88 weighted keys is ideal. Acoustic pianos are welcome too.</p></div>
        <div class="card"><h3>A Stand &amp; Bench</h3><p>Correct height matters more than people think. Elbows should be level with the keys.</p></div>
        <div class="card"><h3>A Phone to Record</h3><p>You will record short clips for feedback. Any smartphone camera is sufficient.</p></div>
      </div>
    </section>

    <section class="block tight">
      <div class="cta-band">
        <h2>Twelve Weeks to Your First Piece</h2>
        <p>Fee: TZS 180,000 — payable in two instalments. Two live lessons per week plus recordings.</p>
        <a href="#register" class="btn btn-gold">Register for Piano</a>
      </div>
    </section>
  </div>
</section>


<!-- ============================================================
     PAGE 7 — GUITAR
     ============================================================ -->
<section class="page" id="guitar">
  <div class="container">
    <section class="block">
      <div class="section-head">
        <span class="eyebrow">Course 3 · 10 Weeks</span>
        <h2>Guitar Course — Chords, Rhythm and Real Songs</h2>
        <p class="lead">
          Guitar is one of the most rewarding instruments to learn because you can play real music within
          weeks. Our ten-week course is carefully sequenced so that you build clean chord changes, solid
          strumming and correct left-hand technique — instead of the sloppy habits that self-taught players
          spend years fixing.
        </p>
      </div>

      <div class="split" style="margin-bottom:40px">
        <div>
          <h3>What You Will Be Able to Do</h3>
          <ul>
            <li>Tune your guitar by ear and with a tuner, and know why strings go out of tune.</li>
            <li>Play all open major and minor chords cleanly.</li>
            <li>Change chords smoothly and in time.</li>
            <li>Play at least six strumming patterns, including muted and syncopated patterns.</li>
            <li>Read chord charts and simple tablature.</li>
            <li>Play barre chords (F and B shapes) without buzzing.</li>
            <li>Perform two complete songs from start to finish.</li>
          </ul>
        </div>
        <div><img src="https://picsum.photos/seed/hacims-guitar-strings/800/600" alt="Acoustic guitar" loading="lazy"></div>
      </div>

      <h3 style="margin-bottom:16px">Curriculum — Week by Week</h3>

      <div class="acc">
        <button class="acc-head">Module 1 (Weeks 1–3) — Holding and First Chords</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 1:</strong> Guitar anatomy, tuning, posture, pick vs fingers. Fretting hand position — fingertips, not flats. Playing single notes on the low E string.</li>
            <li><strong>Week 2:</strong> The Em, Am and C chords. Pressing cleanly near the fret. Switching between Em and Am in time.</li>
            <li><strong>Week 3:</strong> G, D and A chords. The four-chord loop (G–D–Em–C). First full strumming pattern: down-down-up-up-down-up.</li>
          </ul>
        </div>
      </div>

      <div class="acc">
        <button class="acc-head">Module 2 (Weeks 4–6) — Rhythm and Strumming</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 4:</strong> Subdividing with eighth notes. Counting "1 and 2 and". Muted strums and percussive hits.</li>
            <li><strong>Week 5:</strong> Syncopated strumming patterns. Playing with a metronome at 60–80 BPM.</li>
            <li><strong>Week 6:</strong> Fingerstyle basics — thumb on bass strings, fingers on treble strings. Travis-style picking introduction.</li>
          </ul>
        </div>
      </div>

      <div class="acc">
        <button class="acc-head">Module 3 (Weeks 7–8) — Barre Chords and Scales</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 7:</strong> The F barre chord and its movable shape. Building hand strength without injury. The B minor shape.</li>
            <li><strong>Week 8:</strong> The minor pentatonic scale in two positions. Basic improvisation over a backing track. Hammer-ons and pull-offs.</li>
          </ul>
        </div>
      </div>

      <div class="acc">
        <button class="acc-head">Module 4 (Weeks 9–10) — Songs and Performance</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 9:</strong> Learning a complete song: structure, chord chart, dynamics. Playing and singing simultaneously (optional).</li>
            <li><strong>Week 10:</strong> Second song with a different strumming pattern. Final recorded performance and teacher assessment.</li>
          </ul>
        </div>
      </div>

      <h3 style="margin:34px 0 16px">Common Beginner Mistakes We Fix</h3>
      <div class="grid grid-2">
        <div class="card"><h3>Buzzing Strings</h3><p>Usually caused by pressing too far from the fret or using the flat of the finger. We correct this in week 1 before it becomes habit.</p></div>
        <div class="card"><h3>Death Grip</h3><p>Squeezing the neck too hard tires the hand and slows chord changes. Relaxed pressure is taught from the start.</p></div>
        <div class="card"><h3>Ignoring the Metronome</h3><p>Most self-taught guitarists have uneven timing. We practise with a metronome every single week.</p></div>
        <div class="card"><h3>Only Strumming Down</h3><p>Down-only strumming sounds mechanical. Up-strokes and muting are essential for real rhythm guitar.</p></div>
      </div>
    </section>

    <section class="block tight">
      <div class="cta-band">
        <h2>Ten Weeks to Real Songs</h2>
        <p>Fee: TZS 150,000 — payable in two instalments. Acoustic or classical guitar recommended for beginners.</p>
        <a href="#register" class="btn btn-gold">Register for Guitar</a>
      </div>
    </section>
  </div>
</section>


<!-- ============================================================
     PAGE 8 — VIOLIN
     ============================================================ -->
<section class="page" id="violin">
  <div class="container">
    <section class="block">
      <div class="section-head">
        <span class="eyebrow">Course 4 · 16 Weeks</span>
        <h2>Violin Course — Technique First, Music Always</h2>
        <p class="lead">
          The violin is the most demanding instrument in our catalogue, and the most rewarding when taught
          correctly. This sixteen-week course moves deliberately: we spend real time on posture, bow hold
          and intonation because those three things determine everything that follows.
        </p>
      </div>

      <div class="split" style="margin-bottom:40px">
        <div><img src="https://picsum.photos/seed/hacims-violin-bow/800/600" alt="Violin and bow" loading="lazy"></div>
        <div>
          <h3>What You Will Be Able to Do</h3>
          <ul>
            <li>Hold the violin and bow with correct, relaxed posture.</li>
            <li>Produce a clear, steady tone with controlled bow speed and pressure.</li>
            <li>Play in first position with accurate intonation.</li>
            <li>Play the D, G and A major scales across one octave.</li>
            <li>Read music in treble clef while playing.</li>
            <li>Use détaché, legato and staccato bowings.</li>
            <li>Perform two short pieces with correct rhythm and intonation.</li>
          </ul>
        </div>
      </div>

      <h3 style="margin-bottom:16px">Curriculum — Week by Week</h3>

      <div class="acc">
        <button class="acc-head">Module 1 (Weeks 1–4) — Setup and Sound</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 1:</strong> Violin anatomy, shoulder rest fitting, chin rest position. Standing and sitting posture. Holding the violin without tension.</li>
            <li><strong>Week 2:</strong> The bow hold — every finger's role. Bowing on open strings with a straight bow path. Bow speed vs bow pressure.</li>
            <li><strong>Week 3:</strong> Open-string rhythms: whole, half and quarter notes. String crossing. Bowing parallel to the bridge.</li>
            <li><strong>Week 4:</strong> First finger placement on the D string. Ear training for pitch accuracy. Introduction to intonation checking with a drone.</li>
          </ul>
        </div>
      </div>

      <div class="acc">
        <button class="acc-head">Module 2 (Weeks 5–8) — First Position Fingering</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 5:</strong> Fingers 1–2–3 on the D and A strings. The D major scale, one octave.</li>
            <li><strong>Week 6:</strong> The G major scale. Crossing between strings smoothly. Simple two-string melodies.</li>
            <li><strong>Week 7:</strong> Fourth finger introduction. Left-hand shape and hand frame. Avoiding collapsed wrists.</li>
            <li><strong>Week 8:</strong> The A major scale. First short study piece. Reading notation while playing.</li>
          </ul>
        </div>
      </div>

      <div class="acc">
        <button class="acc-head">Module 3 (Weeks 9–12) — Bowing and Expression</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 9:</strong> Détaché bowing — clean, separate strokes. Bow distribution: using the whole bow efficiently.</li>
            <li><strong>Week 10:</strong> Legato bowing — smooth string changes with no gaps. Slurring two and four notes.</li>
            <li><strong>Week 11:</strong> Staccato and martelé. Dynamics: crescendo and decrescendo with bow control.</li>
            <li><strong>Week 12:</strong> Vibrato introduction (arm vibrato basics). Keeping the left hand relaxed while the bow moves.</li>
          </ul>
        </div>
      </div>

      <div class="acc">
        <button class="acc-head">Module 4 (Weeks 13–16) — Repertoire and Review</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 13:</strong> Learning a full beginner piece, phrase by phrase.</li>
            <li><strong>Week 14:</strong> Intonation polishing with a tuner and drone. Slow practice with a metronome.</li>
            <li><strong>Week 15:</strong> Performance preparation: playing through without stopping, recovering from mistakes.</li>
            <li><strong>Week 16:</strong> Final recorded performance, technical review, and recommendations for the next level.</li>
          </ul>
        </div>
      </div>

      <h3 style="margin:34px 0 16px">The Three Violin Priorities</h3>
      <div class="grid grid-3">
        <div class="card"><div class="card-icon">🧍</div><h3>Posture</h3><p>Bad posture limits everything. We check your setup in week 1 and revisit it throughout the course.</p></div>
        <div class="card"><div class="card-icon">🎯</div><h3>Intonation</h3><p>The violin has no frets — pitch is your responsibility. We train your ear alongside your fingers.</p></div>
        <div class="card"><div class="card-icon">🎻</div><h3>Bow Control</h3><p>Tone comes from the bow, not the left hand. Bow speed, pressure and contact point are taught explicitly.</p></div>
      </div>
    </section>

    <section class="block tight">
      <div class="cta-band">
        <h2>Sixteen Weeks of Serious Violin Training</h2>
        <p>Fee: TZS 220,000 — payable in two instalments. A correctly sized instrument is essential; we will advise you before you buy.</p>
        <a href="#register" class="btn btn-gold">Register for Violin</a>
      </div>
    </section>
  </div>
</section>


<!-- ============================================================
     PAGE 9 — DRUMS
     ============================================================ -->
<section class="page" id="drums">
  <div class="container">
    <section class="block">
      <div class="section-head">
        <span class="eyebrow">Course 5 · 8 Weeks</span>
        <h2>Drum Course — Time, Groove and Control</h2>
        <p class="lead">
          Drumming is not about hitting fast. It is about keeping time so steady that the whole band can
          relax. This eight-week course builds your internal clock, your stick technique and your
          vocabulary of grooves and fills.
        </p>
      </div>

      <div class="split" style="margin-bottom:40px">
        <div>
          <h3>What You Will Be Able to Do</h3>
          <ul>
            <li>Hold the sticks correctly (matched grip) and strike without tension.</li>
            <li>Play single strokes, double strokes, paradiddles and flams.</li>
            <li>Play a solid basic rock beat with hi-hat, snare and bass drum.</li>
            <li>Keep steady time with a metronome at a range of tempos.</li>
            <li>Play fills that stay in time and return to the groove cleanly.</li>
            <li>Understand and count sixteenth notes, triplets and syncopation.</li>
            <li>Read drum notation on a five-line staff.</li>
          </ul>
        </div>
        <div><img src="https://picsum.photos/seed/hacims-drum-kit/800/600" alt="Drum kit" loading="lazy"></div>
      </div>

      <h3 style="margin-bottom:16px">Curriculum — Week by Week</h3>

      <div class="acc">
        <button class="acc-head">Module 1 (Weeks 1–2) — Sticks, Strokes and Time</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 1:</strong> Drum kit anatomy, stool height, matched grip. Free stroke vs rebound stroke. Single-stroke rolls on a practice pad at 60 BPM.</li>
            <li><strong>Week 2:</strong> Double strokes and the single paradiddle. Counting out loud in 4/4. Introduction to drum notation.</li>
          </ul>
        </div>
      </div>

      <div class="acc">
        <button class="acc-head">Module 2 (Weeks 3–4) — The Basic Groove</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 3:</strong> Hi-hat on eighth notes, snare on 2 and 4, bass drum on 1 and 3. The foundation of almost every pop and rock song.</li>
            <li><strong>Week 4:</strong> Bass drum variations. Adding the "and" of 2. Playing the groove for two full minutes without drifting.</li>
          </ul>
        </div>
      </div>

      <div class="acc">
        <button class="acc-head">Module 3 (Weeks 5–6) — Fills and Subdivision</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 5:</strong> Sixteenth-note subdivision. Simple fills on the snare and toms. Returning to the groove on beat 1.</li>
            <li><strong>Week 6:</strong> Triplets and shuffle feel. Flams and accents. Dynamics — playing soft and loud on purpose.</li>
          </ul>
        </div>
      </div>

      <div class="acc">
        <button class="acc-head">Module 4 (Weeks 7–8) — Playing With Music</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 7:</strong> Playing along to a full song. Keeping time when the music gets busy. Listening to the bass drum and bass guitar relationship.</li>
            <li><strong>Week 8:</strong> Recorded performance of a groove and a fill sequence. Teacher assessment and next-step recommendations.</li>
          </ul>
        </div>
      </div>

      <h3 style="margin:34px 0 16px">Rudiments You Will Learn</h3>
      <div class="table-wrap">
        <table>
          <thead><tr><th>Rudiment</th><th>Pattern</th><th>Why It Matters</th></tr></thead>
          <tbody>
            <tr><td>Single stroke roll</td><td>R L R L</td><td>Speed and evenness</td></tr>
            <tr><td>Double stroke roll</td><td>R R L L</td><td>Control and rebound</td></tr>
            <tr><td>Single paradiddle</td><td>R L R R / L R L L</td><td>Coordination and independence</td></tr>
            <tr><td>Flams</td><td>Both hands, slightly offset</td><td>Accents and texture</td></tr>
            <tr><td>Buzz roll</td><td>Multiple bounced strokes</td><td>Smooth sustained rolls</td></tr>
          </tbody>
        </table>
      </div>
      <p class="hint" style="margin-top:14px">No drum kit? You can complete the first three weeks on a practice pad and a pillow. We will advise you on affordable kit options.</p>
    </section>

    <section class="block tight">
      <div class="cta-band">
        <h2>Eight Weeks to a Rock-Solid Groove</h2>
        <p>Fee: TZS 130,000 — payable in two instalments. Practice pad recommended from week 1.</p>
        <a href="#register" class="btn btn-gold">Register for Drums</a>
      </div>
    </section>
  </div>
</section>


<!-- ============================================================
     PAGE 10 — XYLOPHONE
     ============================================================ -->
<section class="page" id="xylophone">
  <div class="container">
    <section class="block">
      <div class="section-head">
        <span class="eyebrow">Course 6 · 6 Weeks</span>
        <h2>Xylophone Course — Mallets, Melody and Rhythm</h2>
        <p class="lead">
          The xylophone is one of the most accessible melody instruments in the world, and it has deep
          roots in East African music. In six weeks you will learn correct mallet technique, the layout
          of the keyboard, and how to play melodies and traditional rhythms with confidence.
        </p>
      </div>

      <div class="split" style="margin-bottom:40px">
        <div><img src="https://picsum.photos/seed/hacims-xylophone-mallets/800/600" alt="Xylophone with mallets" loading="lazy"></div>
        <div>
          <h3>What You Will Be Able to Do</h3>
          <ul>
            <li>Hold mallets correctly with a relaxed grip.</li>
            <li>Strike bars accurately in the centre for the best tone.</li>
            <li>Play the C major scale across the full instrument.</li>
            <li>Read notation and play melodies on the xylophone.</li>
            <li>Play two-mallet patterns and simple rolls.</li>
            <li>Perform traditional East African rhythmic patterns.</li>
            <li>Play a complete melody with correct phrasing.</li>
          </ul>
        </div>
      </div>

      <h3 style="margin-bottom:16px">Curriculum — Week by Week</h3>

      <div class="acc">
        <button class="acc-head">Weeks 1–2 — Grip, Tone and Layout</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 1:</strong> Mallet grip, wrist motion, striking in the centre of the bar. Understanding the keyboard layout — where C is, and why the bars are arranged the way they are.</li>
            <li><strong>Week 2:</strong> The C major scale, ascending and descending. Alternating hands. Playing evenly — no accidental accents.</li>
          </ul>
        </div>
      </div>

      <div class="acc">
        <button class="acc-head">Weeks 3–4 — Melody and Reading</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 3:</strong> Reading notation on the xylophone. Simple eight-bar melodies. Rhythm accuracy with a metronome.</li>
            <li><strong>Week 4:</strong> Two-mallet independence. Simple chord and interval playing. Introduction to rolls for sustained notes.</li>
          </ul>
        </div>
      </div>

      <div class="acc">
        <button class="acc-head">Weeks 5–6 — Rhythm, Culture and Performance</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 5:</strong> Traditional East African rhythmic patterns. Playing melody and rhythm together. Ensemble awareness — listening while you play.</li>
            <li><strong>Week 6:</strong> Full melody performance with dynamics and phrasing. Recorded assessment and certificate.</li>
          </ul>
        </div>
      </div>

      <h3 style="margin:34px 0 16px">Why Start With Xylophone?</h3>
      <div class="grid grid-3">
        <div class="card"><h3>Visually Clear</h3><p>Like the piano, the xylophone lays notes out horizontally. Beginners can see exactly what they are playing.</p></div>
        <div class="card"><h3>Immediate Melody</h3><p>You can play a recognisable tune in the first lesson, which keeps motivation high.</p></div>
        <div class="card"><h3>Rhythm Foundation</h3><p>Mallet playing builds the same timing skills used in drums, and transfers to other instruments.</p></div>
      </div>
    </section>

    <section class="block tight">
      <div class="cta-band">
        <h2>Six Weeks to Your First Melody</h2>
        <p>Fee: TZS 100,000 — payable in two instalments. A basic diatonic xylophone or marimba is sufficient.</p>
        <a href="#register" class="btn btn-gold">Register for Xylophone</a>
      </div>
    </section>
  </div>
</section>


<!-- ============================================================
     PAGE 11 — FLUTE
     ============================================================ -->
<section class="page" id="flute">
  <div class="container">
    <section class="block">
      <div class="section-head">
        <span class="eyebrow">Course 7 · 10 Weeks</span>
        <h2>Flute Course — Breath, Tone and Melody</h2>
        <p class="lead">
          The flute is a wind instrument where the player *is* the sound source. That makes breath control
          and embouchure the foundation of everything. In ten weeks you will learn to produce a clean tone,
          play across two octaves, and perform melodies with expression.
        </p>
      </div>

      <div class="split" style="margin-bottom:40px">
        <div>
          <h3>What You Will Be Able to Do</h3>
          <ul>
            <li>Assemble, hold and care for the flute correctly.</li>
            <li>Form a correct embouchure and produce a stable tone.</li>
            <li>Control your breath for long, steady phrases.</li>
            <li>Play the C major scale across two octaves.</li>
            <li>Read notation in treble clef while playing.</li>
            <li>Use articulation: tonguing, legato and staccato.</li>
            <li>Perform two complete melodies with correct rhythm and phrasing.</li>
          </ul>
        </div>
        <div><img src="https://picsum.photos/seed/hacims-flute-music/800/600" alt="Flute on a music stand" loading="lazy"></div>
      </div>

      <h3 style="margin-bottom:16px">Curriculum — Week by Week</h3>

      <div class="acc">
        <button class="acc-head">Module 1 (Weeks 1–3) — Sound Production</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 1:</strong> Flute anatomy, assembly and cleaning. Posture and hand position. Headjoint-only tone exercises — producing a clear sound without the body.</li>
            <li><strong>Week 2:</strong> Embouchure formation. First notes on the assembled flute (B, A, G). Breath support from the diaphragm.</li>
            <li><strong>Week 3:</strong> Long tones for tone quality and stability. Playing four-beat notes without wavering. Introduction to articulation with the tongue.</li>
          </ul>
        </div>
      </div>

      <div class="acc">
        <button class="acc-head">Module 2 (Weeks 4–6) — Scales and Reading</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 4:</strong> The C major scale, first octave. Note reading in treble clef at playing speed.</li>
            <li><strong>Week 5:</strong> Extending to the second octave. Register changes and embouchure adjustment.</li>
            <li><strong>Week 6:</strong> Simple melodies within one octave. Counting rests correctly — silence is part of the music.</li>
          </ul>
        </div>
      </div>

      <div class="acc">
        <button class="acc-head">Module 3 (Weeks 7–8) — Articulation and Dynamics</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 7:</strong> Tonguing technique — single tonguing on repeated notes. Legato phrasing across slurs.</li>
            <li><strong>Week 8:</strong> Staccato articulation. Dynamics from pianissimo to forte without losing tone. Vibrato introduction.</li>
          </ul>
        </div>
      </div>

      <div class="acc">
        <button class="acc-head">Module 4 (Weeks 9–10) — Repertoire and Performance</button>
        <div class="acc-body">
          <ul>
            <li><strong>Week 9:</strong> Learning a complete melody. Phrase shaping — where to breathe and where not to.</li>
            <li><strong>Week 10:</strong> Second melody with a wider range. Final recorded performance and teacher feedback.</li>
          </ul>
        </div>
      </div>

      <h3 style="margin:34px 0 16px">Breathing Exercises We Teach</h3>
      <div class="grid grid-2">
        <div class="card"><h3>Four-Count Breath</h3><p>Inhale for 4 counts, hold for 4, exhale for 8. Builds capacity and control.</p></div>
        <div class="card"><h3>Long Tones</h3><p>Hold a single note for as long as possible with a steady sound. The single most effective flute exercise.</p></div>
        <div class="card"><h3>Diaphragmatic Support</h3><p>Learning to breathe from the belly rather than the chest for stable airflow.</p></div>
        <div class="card"><h3>Phrase Breathing</h3><p>Planning breaths at musically sensible points rather than wherever you run out of air.</p></div>
      </div>
    </section>

    <section class="block tight">
      <div class="cta-band">
        <h2>Ten Weeks to a Beautiful Tone</h2>
        <p>Fee: TZS 150,000 — payable in two instalments. A student-model flute in good repair is required.</p>
        <a href="#register" class="btn btn-gold">Register for Flute</a>
      </div>
    </section>
  </div>
</section>


<!-- ============================================================
     PAGE 12 — BOOKS & RESOURCES
     ============================================================ -->
<section class="page" id="books">
  <div class="container">
    <section class="block">
      <div class="section-head">
        <span class="eyebrow">Library</span>
        <h2>Books &amp; Free Music Resources</h2>
        <p class="lead">
          HACIMS students are expected to read. Below is a curated list of free, legal and highly
          respected music resources available online. Your instructor will tell you which ones to use
          for your specific course.
        </p>
      </div>

      <h3 style="margin-bottom:16px">Free Sheet Music Libraries</h3>
      <div class="grid grid-2">
        <div class="card">
          <h3>IMSLP — Petrucci Music Library</h3>
          <p>The largest free public-domain sheet music library in the world. Over 600,000 scores, from beginner studies to full orchestral works.</p>
          <p><a href="https://imslp.org" target="_blank" rel="noopener">Visit imslp.org →</a></p>
        </div>
        <div class="card">
          <h3>Mutopia Project</h3>
          <p>Free, beautifully typeset sheet music of public-domain works, available in PDF and editable formats.</p>
          <p><a href="https://www.mutopiaproject.org" target="_blank" rel="noopener">Visit mutopiaproject.org →</a></p>
        </div>
        <div class="card">
          <h3>Project Gutenberg — Music Books</h3>
          <p>Free public-domain books on music theory, history and instrument methods, downloadable in multiple formats.</p>
          <p><a href="https://www.gutenberg.org" target="_blank" rel="noopener">Visit gutenberg.org →</a></p>
        </div>
        <div class="card">
          <h3>Open Music Theory (Open Textbook)</h3>
          <p>A complete, free, university-level music theory textbook covering notation, harmony, form and analysis.</p>
          <p><a href="https://viva.pressbooks.pub/openmusictheory/" target="_blank" rel="noopener">Read Open Music Theory →</a></p>
        </div>
      </div>

      <h3 style="margin:34px 0 16px">Theory &amp; Ear Training Tools</h3>
      <div class="grid grid-3">
        <div class="card">
          <h3>musictheory.net</h3>
          <p>Free interactive lessons and exercises on notation, intervals, chords and key signatures.</p>
          <p><a href="https://www.musictheory.net" target="_blank" rel="noopener">musictheory.net →</a></p>
        </div>
        <div class="card">
          <h3>Teoria</h3>
          <p>Music theory tutorials with ear-training exercises for intervals, chords and scales.</p>
          <p><a href="https://www.teoria.com" target="_blank" rel="noopener">teoria.com →</a></p>
        </div>
        <div class="card">
          <h3>TONAL — Ear Trainer</h3>
          <p>A free ear-training tool that works on any device. Excellent for daily interval practice.</p>
          <p><a href="https://tonal.musictheory.net" target="_blank" rel="noopener">Try the ear trainer →</a></p>
        </div>
      </div>

      <h3 style="margin:34px 0 16px">Recommended Reading by Course</h3>
      <div class="table-wrap">
        <table>
          <thead><tr><th>Course</th><th>Recommended Resource</th><th>Why</th></tr></thead>
          <tbody>
            <tr><td>Nota (Notation)</td><td><a href="https://viva.pressbooks.pub/openmusictheory/" target="_blank" rel="noopener">Open Music Theory</a> — Fundamentals chapters</td><td>Clear, free, structured theory text</td></tr>
            <tr><td>Piano</td><td><a href="https://imslp.org" target="_blank" rel="noopener">IMSLP</a> — Czerny and Beyer studies</td><td>Classic beginner piano technique books in the public domain</td></tr>
            <tr><td>Guitar</td><td><a href="https://imslp.org" target="_blank" rel="noopener">IMSLP</a> — Carulli and Sor studies</td><td>Foundational classical guitar studies</td></tr>
            <tr><td>Violin</td><td><a href="https://imslp.org" target="_blank" rel="noopener">IMSLP</a> — Suzuki and Kayser material</td><td>Standard beginner violin repertoire</td></tr>
            <tr><td>Drums</td><td><a href="https://www.musictheory.net" target="_blank" rel="noopener">musictheory.net</a> — Rhythm lessons</td><td>Rhythm reading is the drummer's theory</td></tr>
            <tr><td>Xylophone</td><td><a href="https://www.mutopiaproject.org" target="_blank" rel="noopener">Mutopia</a> — simple folk melodies</td><td>Clean notation for reading practice</td></tr>
            <tr><td>Flute</td><td><a href="https://imslp.org" target="_blank" rel="noopener">IMSLP</a> — beginner flute studies</td><td>Tone and articulation exercises</td></tr>
          </tbody>
        </table>
      </div>

      <h3 style="margin:34px 0 16px">Free Apps We Recommend</h3>
      <ul>
        <li><strong>Metronome:</strong> Any free metronome app — you will use it every single week.</li>
        <li><strong>Tuner:</strong> A chromatic tuner app for guitar, violin and flute intonation checks.</li>
        <li><strong>Recorder:</strong> Your phone's voice recorder is enough for weekly submission recordings.</li>
        <li><strong>Note-reading drills:</strong> Free flashcard apps for daily note recognition practice.</li>
      </ul>

      <p class="hint" style="margin-top:18px">
        HACIMS does not sell books. All resources listed above are free and legally available. Your
        instructor will guide you on which chapters or exercises to use each week.
      </p>
    </section>
  </div>
</section>


<!-- ============================================================
     PAGE 13 — GALLERY
     ============================================================ -->
<section class="page" id="gallery">
  <div class="container">
    <section class="block">
      <div class="section-head">
        <span class="eyebrow">Gallery</span>
        <h2>Inside HACIMS Music Center</h2>
        <p class="lead">
          A look at the instruments we teach, the spaces we learn in, and the music we make. Our
          classrooms are in Kilimanjaro — our students are everywhere.
        </p>
      </div>

      <div class="gallery">
        <figure><img src="https://picsum.photos/seed/hacims-g1-piano/700/500" alt="Piano lesson" loading="lazy"><figcaption>Piano technique session — hand shape and finger independence</figcaption></figure>
        <figure><img src="https://picsum.photos/seed/hacims-g2-guitar/700/500" alt="Guitar lesson" loading="lazy"><figcaption>Guitar chord clinic — clean chord changes</figcaption></figure>
        <figure><img src="https://picsum.photos/seed/hacims-g3-violin/700/500" alt="Violin lesson" loading="lazy"><figcaption>Violin bow hold correction</figcaption></figure>
        <figure><img src="https://picsum.photos/seed/hacims-g4-drums/700/500" alt="Drum lesson" loading="lazy"><figcaption>Drum rudiments on the practice pad</figcaption></figure>
        <figure><img src="https://picsum.photos/seed/hacims-g5-xylophone/700/500" alt="Xylophone lesson" loading="lazy"><figcaption>Xylophone mallet technique workshop</figcaption></figure>
        <figure><img src="https://picsum.photos/seed/hacims-g6-flute/700/500" alt="Flute lesson" loading="lazy"><figcaption>Flute tone production exercises</figcaption></figure>
        <figure><img src="https://picsum.photos/seed/hacims-g7-notation/700/500" alt="Notation class" loading="lazy"><figcaption>Nota class — reading the staff</figcaption></figure>
        <figure><img src="https://picsum.photos/seed/hacims-g8-ensemble/700/500" alt="Ensemble" loading="lazy"><figcaption>Student ensemble rehearsal</figcaption></figure>
        <figure><img src="https://picsum.photos/seed/hacims-g9-studio/700/500" alt="Studio" loading="lazy"><figcaption>Recording session for weekly feedback</figcaption></figure>
      </div>

      <p class="hint" style="margin-top:22px">
        Images on this page are illustrative. Follow <a href="https://www.tiktok.com/@Hacims26" target="_blank" rel="noopener">@Hacims26 on TikTok</a>
        for real videos of HACIMS lessons, student performances and practice tips.
      </p>
    </section>
  </div>
</section>


<!-- ============================================================
     PAGE 14 — SCHEDULE
     ============================================================ -->
<section class="page" id="schedule">
  <div class="container">
    <section class="block">
      <div class="section-head">
        <span class="eyebrow">Timetable</span>
        <h2>Class Schedule (East Africa Time)</h2>
        <p class="lead">
          Live classes run in the evenings and on weekends so that students and working people can attend.
          All times are East Africa Time (EAT, UTC+3). If you are in another time zone, we will find a
          slot that works for you.
        </p>
      </div>

      <div class="table-wrap">
        <table>
          <thead><tr><th>Day</th><th>16:00 – 17:00</th><th>17:30 – 18:30</th><th>19:00 – 20:00</th></tr></thead>
          <tbody>
            <tr><td><strong>Monday</strong></td><td>Nota (Theory)</td><td>Piano — Beginner</td><td>Guitar — Beginner</td></tr>
            <tr><td><strong>Tuesday</strong></td><td>Flute</td><td>Violin</td><td>Drums</td></tr>
            <tr><td><strong>Wednesday</strong></td><td>Nota (Theory)</td><td>Piano — Beginner</td><td>Xylophone</td></tr>
            <tr><td><strong>Thursday</strong></td><td>Guitar — Beginner</td><td>Violin</td><td>Flute</td></tr>
            <tr><td><strong>Friday</strong></td><td>Drums</td><td>Xylophone</td><td>Open Q&amp;A Session</td></tr>
            <tr><td><strong>Saturday</strong></td><td>Piano — Practice Lab</td><td>Guitar — Practice Lab</td><td>Student Ensemble</td></tr>
          </tbody>
        </table>
      </div>

      <h3 style="margin:34px 0 16px">How the Weekly Rhythm Works</h3>
      <div class="grid grid-3">
        <div class="card"><div class="card-icon">📅</div><h3>Two Live Lessons</h3><p>Each course has two live sessions per week. Attendance is strongly encouraged, but recordings are always available.</p></div>
        <div class="card"><div class="card-icon">⏱️</div><h3>Daily Practice</h3><p>Plan for 20–45 minutes of practice per day. This is where progress actually happens.</p></div>
        <div class="card"><div class="card-icon">📤</div><h3>Weekly Submission</h3><p>Submit one short recording or theory exercise per week. Your teacher reviews it before the next lesson.</p></div>
      </div>

      <h3 style="margin:34px 0 16px">Term Dates</h3>
      <ul>
        <li><strong>Intake:</strong> New students are admitted at the start of each month.</li>
        <li><strong>Breaks:</strong> One week break between courses.</li>
        <li><strong>Make-up classes:</strong> If you miss a live session, a recording is provided, and a make-up slot can be arranged on request.</li>
      </ul>
    </section>
  </div>
</section>


<!-- ============================================================
     PAGE 15 — REGISTRATION
     ============================================================ -->
<section class="page" id="register">
  <div class="container">
    <section class="block">
      <div class="section-head">
        <span class="eyebrow">Join HACIMS</span>
        <h2>Course Registration Form</h2>
        <p class="lead">
          Fill in the form below to register for a HACIMS Music Center online course. Our manager,
          Haytham A. Munisi, will review your application and contact you within 48 hours with your
          class schedule and payment details.
        </p>
      </div>

      <div class="grid grid-2" style="align-items:start;gap:32px">
        <div class="form-card">
          <form id="regForm" novalidate>
            <div class="form-grid">
              <div class="field">
                <label for="fullName">Full Name <span>*</span></label>
                <input type="text" id="fullName" name="fullName" placeholder="e.g. Neema John Mushi" required>
              </div>
              <div class="field">
                <label for="email">Email Address <span>*</span></label>
                <input type="email" id="email" name="email" placeholder="you@example.com" required>
              </div>
              <div class="field">
                <label for="phone">Phone / WhatsApp <span>*</span></label>
                <input type="tel" id="phone" name="phone" placeholder="+255 7XX XXX XXX" required>
              </div>
              <div class="field">
                <label for="country">Country / Region</label>
                <input type="text" id="country" name="country" placeholder="e.g. Tanzania — Kilimanjaro">
              </div>
              <div class="field">
                <label for="course">Type of Course <span>*</span></label>
                <select id="course" name="course" required>
                  <option value="">— Select a course —</option>
                  <option>Music Notation (Nota) — 4 weeks</option>
                  <option>Piano — 12 weeks</option>
                  <option>Guitar — 10 weeks</option>
                  <option>Violin — 16 weeks</option>
                  <option>Drums — 8 weeks</option>
                  <option>Xylophone — 6 weeks</option>
                  <option>Flute — 10 weeks</option>
                  <option>Not sure — please advise me</option>
                </select>
              </div>
              <div class="field">
                <label for="level">Your Current Level</label>
                <select id="level" name="level">
                  <option>Complete beginner</option>
                  <option>Beginner (some basics)</option>
                  <option>Intermediate</option>
                  <option>Returning after a break</option>
                </select>
              </div>
              <div class="field">
                <label for="prefTime">Preferred Class Time (EAT)</label>
                <select id="prefTime" name="prefTime">
                  <option>16:00 – 17:00</option>
                  <option>17:30 – 18:30</option>
                  <option>19:00 – 20:00</option>
                  <option>Weekend only</option>
                  <option>Flexible</option>
                </select>
              </div>
              <div class="field">
                <label for="instrument">Do You Own an Instrument?</label>
                <select id="instrument" name="instrument">
                  <option>Yes, I have one</option>
                  <option>No, I need advice</option>
                  <option>I am about to buy one</option>
                </select>
              </div>
              <div class="field full">
                <label for="goals">Your Goals &amp; Anything Else We Should Know</label>
                <textarea id="goals" name="goals" placeholder="Tell us why you want to learn music, any previous experience, health considerations, or questions about the course..."></textarea>
              </div>
              <div class="field full">
                <label for="consent" style="display:flex;gap:10px;align-items:flex-start;font-weight:500">
                  <input type="checkbox" id="consent" name="consent" required style="width:auto;margin-top:4px">
                  <span>I confirm that the information above is correct and I agree to be contacted by HACIMS Music Center regarding my registration.</span>
                </label>
              </div>
            </div>
            <button type="submit" class="btn btn-primary" style="margin-top:22px;width:100%">Submit Registration</button>
            <div class="form-msg" id="regMsg"></div>
          </form>
        </div>

        <div>
          <div class="card" style="margin-bottom:18px">
            <h3>What Happens Next?</h3>
            <ol style="margin-bottom:0">
              <li>You submit the form.</li>
              <li>Haytham A. Munisi reviews your application within 48 hours.</li>
              <li>You receive an email or WhatsApp message confirming your course and schedule.</li>
              <li>You pay the first instalment and receive your course materials.</li>
              <li>You join your first live class.</li>
            </ol>
          </div>

          <div class="card" style="margin-bottom:18px">
            <h3>Payment Information</h3>
            <p>Fees are payable in two instalments: 50% at registration and 50% at the mid-point of the course.</p>
            <p>Accepted methods: mobile money (M-Pesa, Tigo Pesa, Airtel Money) and bank transfer. Payment details are sent after your application is confirmed.</p>
            <p style="margin-bottom:0"><strong>Students taking two courses receive 15% off the second course.</strong></p>
          </div>

          <div class="card">
            <h3>Need Help Registering?</h3>
            <p>Contact us directly:</p>
            <p>📞 <a href="tel:+255671558607">+255 671 558 607</a> — Hacims</p>
            <p>✉️ <a href="mailto:hacims26munisi@gmail.com">hacims26munisi@gmail.com</a></p>
            <p style="margin-bottom:0">🎵 TikTok: <a href="https://www.tiktok.com/@Hacims26" target="_blank" rel="noopener">@Hacims26</a></p>
          </div>
        </div>
      </div>
    </section>

    <section class="block tight">
      <div class="section-head">
        <span class="eyebrow">General Inquiry</span>
        <h2>Not Ready to Register? Send Us a Question</h2>
        <p class="lead">Ask anything about the courses, fees, schedules or instruments — we will reply personally.</p>
      </div>
      <div class="form-card">
        <form id="inquiryForm" novalidate>
          <div class="form-grid">
            <div class="field">
              <label for="inqName">Your Name <span>*</span></label>
              <input type="text" id="inqName" placeholder="Your full name" required>
            </div>
            <div class="field">
              <label for="inqEmail">Your Email <span>*</span></label>
              <input type="email" id="inqEmail" placeholder="you@example.com" required>
            </div>
            <div class="field full">
              <label for="inqSubject">Subject</label>
              <select id="inqSubject">
                <option>Question about a course</option>
                <option>Question about fees</option>
                <option>Question about schedule</option>
                <option>Question about instruments</option>
                <option>Other</option>
              </select>
            </div>
            <div class="field full">
              <label for="inqMessage">Your Message <span>*</span></label>
              <textarea id="inqMessage" placeholder="Write your question here..." required></textarea>
            </div>
          </div>
          <button type="submit" class="btn btn-primary" style="margin-top:22px;width:100%">Send Inquiry</button>
          <div class="form-msg" id="inqMsg"></div>
        </form>
      </div>
    </section>
  </div>
</section>


<!-- ============================================================
     PAGE 16 — FAQ
     ============================================================ -->
<section class="page" id="faq">
  <div class="container">
    <section class="block">
      <div class="section-head">
        <span class="eyebrow">Questions</span>
        <h2>Frequently Asked Questions</h2>
        <p class="lead">Everything students ask us before registering, answered honestly.</p>
      </div>

      <div class="acc">
        <button class="acc-head">Do I need to own an instrument before joining?</button>
        <div class="acc-body"><p>No. You can start the Nota (music notation) course with no instrument at all. For instrument courses we recommend having access to your instrument by week 2 — even a borrowed or basic model is enough to begin. We will advise you on what to buy and what to avoid.</p></div>
      </div>

      <div class="acc">
        <button class="acc-head">How long is each course?</button>
        <div class="acc-body"><p>Every HACIMS course lasts more than two weeks and less than ten months. The shortest is Xylophone at 6 weeks; the longest is Violin at 16 weeks. The Nota theory course is 4 weeks, Piano 12 weeks, Guitar 10 weeks, Drums 8 weeks and Flute 10 weeks.</p></div>
      </div>

      <div class="acc">
        <button class="acc-head">I am a complete beginner. Is that okay?</button>
        <div class="acc-body"><p>Absolutely — most of our students start with zero musical background. Every course begins from the very first step and assumes no prior knowledge.</p></div>
      </div>

      <div class="acc">
        <button class="acc-head">How are lessons delivered?</button>
        <div class="acc-body"><p>Lessons are delivered live online twice per week. You receive a link before each session. All live sessions are recorded, so you can re-watch them if you miss one or want to review a technique.</p></div>
      </div>

      <div class="acc">
        <button class="acc-head">How much practice time do I need per day?</button>
        <div class="acc-body"><p>Plan for 20–45 minutes per day. Short, consistent daily practice is far more effective than long sessions once a week. Your teacher will give you a specific weekly practice plan.</p></div>
      </div>

      <div class="acc">
        <button class="acc-head">How do I pay, and can I pay in instalments?</button>
        <div class="acc-body"><p>Yes. Every course can be paid in two instalments: 50% at registration and 50% at the mid-point. We accept mobile money (M-Pesa, Tigo Pesa, Airtel Money) and bank transfer. Payment details are provided after your registration is confirmed.</p></div>
      </div>

      <div class="acc">
        <button class="acc-head">Do I get a certificate?</button>
        <div class="acc-body"><p>Yes. Every student who completes the course requirements — attendance, weekly submissions and the final assessment — receives a HACIMS Music Center certificate of completion.</p></div>
      </div>

      <div class="acc">
        <button class="acc-head">I live outside Tanzania. Can I still join?</button>
        <div class="acc-body"><p>Yes. HACIMS is based in Kilimanjaro, Tanzania, but all classes are online. We schedule classes in East Africa Time (UTC+3), and we will work with you to find a suitable slot if you are in a different time zone.</p></div>
      </div>

      <div class="acc">
        <button class="acc-head">What if I miss a live class?</button>
        <div class="acc-body"><p>Every live class is recorded and made available to you. If you need extra help, you can request a make-up session or ask questions in the student group.</p></div>
      </div>

      <div class="acc">
        <button class="acc-head">Can I take more than one course at once?</button>
        <div class="acc-body"><p>Yes, and many students do — for example, Nota alongside Piano. We recommend starting with no more than two courses at a time so that you can practise both properly. Students taking two courses receive a 15% discount on the second course.</p></div>
      </div>

      <div class="acc">
        <button class="acc-head">Who teaches the courses?</button>
        <div class="acc-body"><p>Our team is led by manager Haytham A. Munisi, with Emmanuel D. Shirima teaching rhythm, drums and xylophone, and Hacims A. Munisi teaching violin and flute. See the <a href="#team">Our Team</a> page for full profiles.</p></div>
      </div>

      <div class="acc">
        <button class="acc-head">How do I contact HACIMS directly?</button>
        <div class="acc-body">
          <p>📞 Phone/WhatsApp: <a href="tel:+255671558607">+255 671 558 607</a> — Hacims</p>
          <p>✉️ Email: <a href="mailto:hacims26munisi@gmail.com">hacims26munisi@gmail.com</a></p>
          <p>🎵 TikTok: <a href="https://www.tiktok.com/@Hacims26" target="_blank" rel="noopener">@Hacims26</a></p>
          <p>💻 GitHub: <a href="https://github.com/hacims26c" target="_blank" rel="noopener">hacims26c</a></p>
        </div>
      </div>
    </section>
  </div>
</section>


<!-- ============================================================
     PAGE 17 — CONTACT
     ============================================================ -->
<section class="page" id="contact">
  <div class="container">
    <section class="block">
      <div class="section-head">
        <span class="eyebrow">Contact</span>
        <h2>Get In Touch With HACIMS Music Center</h2>
        <p class="lead">
          We are based in the Kilimanjaro Region of Tanzania and teach online worldwide. Reach us by
          phone, WhatsApp, email or social media — we reply personally.
        </p>
      </div>

      <div class="grid grid-2" style="gap:32px;align-items:start">
        <div>
          <div class="contact-item">
            <div class="contact-icon">📞</div>
            <div>
              <strong>Phone / WhatsApp</strong>
              <a href="tel:+255671558607">+255 671 558 607</a> — Hacims<br>
              <small>Available Monday to Saturday, 08:00 – 20:00 EAT</small>
            </div>
          </div>

          <div class="contact-item">
            <div class="contact-icon">✉️</div>
            <div>
              <strong>Email</strong>
              <a href="mailto:hacims26munisi@gmail.com">hacims26munisi@gmail.com</a><br>
              <small>We reply within 48 hours</small>
            </div>
          </div>

          <div class="contact-item">
            <div class="contact-icon">🎵</div>
            <div>
              <strong>TikTok</strong>
              <a href="https://www.tiktok.com/@Hacims26" target="_blank" rel="noopener">@Hacims26</a><br>
              <small>Lesson clips, practice tips and student performances</small>
            </div>
          </div>

          <div class="contact-item">
            <div class="contact-icon">💻</div>
            <div>
              <strong>GitHub</strong>
              <a href="https://github.com/hacims26c" target="_blank" rel="noopener">hacims26c</a><br>
              <small>Our open-source learning tools and projects</small>
            </div>
          </div>

          <div class="contact-item">
            <div class="contact-icon">📍</div>
            <div>
              <strong>Location</strong>
              Kilimanjaro Region, Tanzania<br>
              <small>All classes conducted online</small>
            </div>
          </div>

          <div class="contact-item">
            <div class="contact-icon">🕒</div>
            <div>
              <strong>Office Hours</strong>
              Monday – Friday: 08:00 – 20:00 EAT<br>
              Saturday: 09:00 – 17:00 EAT<br>
              <small>Sunday: closed (practice day!)</small>
            </div>
          </div>
        </div>

        <div class="form-card">
          <h3>Send Us a Message</h3>
          <form id="contactForm" novalidate>
            <div class="field" style="margin-bottom:16px">
              <label for="cName">Full Name <span>*</span></label>
              <input type="text" id="cName" placeholder="Your name" required>
            </div>
            <div class="field" style="margin-bottom:16px">
              <label for="cEmail">Email <span>*</span></label>
              <input type="email" id="cEmail" placeholder="you@example.com" required>
            </div>
            <div class="field" style="margin-bottom:16px">
              <label for="cPhone">Phone</label>
              <input type="tel" id="cPhone" placeholder="+255 7XX XXX XXX">
            </div>
            <div class="field" style="margin-bottom:16px">
              <label for="cMsg">Message <span>*</span></label>
              <textarea id="cMsg" placeholder="How can we help you?" required></textarea>
            </div>
            <button type="submit" class="btn btn-primary" style="width:100%">Send Message</button>
            <div class="form-msg" id="contactMsg"></div>
          </form>
        </div>
      </div>
    </section>

    <section class="block tight">
      <div class="cta-band">
        <h2>Music Starts With One Message</h2>
        <p>Whether you want to read Nota, play piano, or finally learn that guitar sitting in the corner — HACIMS is ready when you are.</p>
        <a href="#register" class="btn btn-gold">Register Now</a>
      </div>
    </section>
  </div>
</section>

</main>


<!-- ============================================================
     FOOTER
     ============================================================ -->
<footer class="site-footer">
  <div class="container">
    <div class="footer-grid">
      <div>
        <h4>HACIMS Music Center</h4>
        <p style="font-size:.92rem;color:var(--muted)">
          Online music school based in the Kilimanjaro Region, Tanzania. Teaching music notation and six
          instruments with structure, patience and care.
        </p>
        <p style="font-size:.92rem;margin-bottom:0">
          <strong>Manager:</strong> Haytham A. Munisi<br>
          <strong>Team:</strong> Emmanuel D. Shirima · Hacims A. Munisi
        </p>
      </div>

      <div>
        <h4>Courses</h4>
        <a href="#nota">Music Notation (Nota)</a>
        <a href="#piano">Piano</a>
        <a href="#guitar">Guitar</a>
        <a href="#violin">Violin</a>
        <a href="#drums">Drums</a>
        <a href="#xylophone">Xylophone</a>
        <a href="#flute">Flute</a>
      </div>

      <div>
        <h4>Information</h4>
        <a href="#about">About Us</a>
        <a href="#team">Our Team</a>
        <a href="#courses">All Courses</a>
        <a href="#books">Books &amp; Resources</a>
        <a href="#schedule">Timetable</a>
        <a href="#faq">FAQ</a>
        <a href="#gallery">Gallery</a>
      </div>

      <div>
        <h4>Contact</h4>
        <a href="tel:+255671558607">📞 +255 671 558 607</a>
        <a href="mailto:hacims26munisi@gmail.com">✉️ hacims26munisi@gmail.com</a>
        <a href="https://www.tiktok.com/@Hacims26" target="_blank" rel="noopener">🎵 TikTok @Hacims26</a>
        <a href="https://github.com/hacims26c" target="_blank" rel="noopener">💻 GitHub hacims26c</a>
        <a href="#register">📝 Register Now</a>
      </div>
    </div>

    <div class="footer-bottom">
      <span>© <span id="year"></span> HACIMS Music Center — Kilimanjaro, Tanzania. All rights reserved.</span>
      <span>Built with HTML, CSS &amp; JavaScript · Light/Dark mode ready</span>
    </div>
  </div>
</footer>


<script>
/* ============================================================
   1. THEME TOGGLE (LIGHT / DARK MODE)
   ============================================================ */
(function initTheme(){
  const root   = document.documentElement;
  const toggle = document.getElementById('themeToggle');
  const icon   = document.getElementById('themeIcon');
  const label  = document.getElementById('themeLabel');

  const saved = localStorage.getItem('hacims-theme');
  const prefersDark = window.matchMedia('(prefers-color-scheme: dark)').matches;
  const startTheme = saved || (prefersDark ? 'dark' : 'light');
  root.setAttribute('data-theme', startTheme);

  function paint(theme){
    const dark = theme === 'dark';
    icon.textContent  = dark ? '☀️' : '🌙';
    label.textContent = dark ? 'Light' : 'Dark';
  }
  paint(startTheme);

  toggle.addEventListener('click', function(){
    const next = root.getAttribute('data-theme') === 'dark' ? 'light' : 'dark';
    root.setAttribute('data-theme', next);
    localStorage.setItem('hacims-theme', next);
    paint(next);
  });
})();


/* ============================================================
   2. HASH ROUTER — MULTI-PAGE NAVIGATION
   ============================================================ */
(function initRouter(){
  const pages = Array.from(document.querySelectorAll('.page'));
  const links = Array.from(document.querySelectorAll('.nav-link'));

  function getRoute(){
    const raw = window.location.hash.replace('#', '').trim();
    if(!raw) return 'home';
    return document.getElementById(raw) ? raw : 'home';
  }

  function render(){
    const route = getRoute();

    pages.forEach(function(page){
      page.classList.toggle('active', page.id === route);
    });

    links.forEach(function(link){
      link.classList.toggle('active', link.getAttribute('href') === '#' + route);
    });

    // Update document title for clarity
    const activePage = document.getElementById(route);
    const heading = activePage ? activePage.querySelector('h1, h2') : null;
    document.title = (heading ? heading.textContent.trim() + ' | ' : '') +
                     'HACIMS Music Center';

    window.scrollTo({ top: 0, behavior: 'auto' });
  }

  window.addEventListener('hashchange', render);
  window.addEventListener('DOMContentLoaded', render);
  render();
})();


/* ============================================================
   3. ACCORDION COMPONENT
   ============================================================ */
document.addEventListener('click', function(event){
  const head = event.target.closest('.acc-head');
  if(!head) return;

  const item = head.parentElement;
  const wasOpen = item.classList.contains('open');

  // Close siblings inside the same page for a cleaner experience
  const page = item.closest('.page');
  if(page){
    page.querySelectorAll('.acc.open').forEach(function(openItem){
      if(openItem !== item) openItem.classList.remove('open');
    });
  }

  item.classList.toggle('open', !wasOpen);
});


/* ============================================================
   4. FORM VALIDATION & SUBMISSION FEEDBACK
   ============================================================ */
(function initForms(){

  function showMessage(el, text, isError){
    el.textContent = text;
    el.classList.add('show');
    el.style.background = isError ? 'rgba(239,68,68,.14)' : 'rgba(16,185,129,.14)';
    el.style.borderColor = isError ? '#ef4444' : '#10b981';
    el.style.color = isError ? '#ef4444' : '#10b981';
  }

  function isEmail(value){
    return /^[^\s@]+@[^\s@]+\.[^\s@]{2,}$/.test(value);
  }

  /* ---- Registration form ---- */
  const regForm = document.getElementById('regForm');
  if(regForm){
    regForm.addEventListener('submit', function(e){
      e.preventDefault();
      const msg = document.getElementById('regMsg');

      const name     = document.getElementById('fullName').value.trim();
      const email    = document.getElementById('email').value.trim();
      const phone    = document.getElementById('phone').value.trim();
      const course   = document.getElementById('course').value;
      const consent  = document.getElementById('consent').checked;

      if(name.length < 3){
        return showMessage(msg, '⚠️ Please enter your full name (at least 3 characters).', true);
      }
      if(!isEmail(email)){
        return showMessage(msg, '⚠️ Please enter a valid email address.', true);
      }
      if(phone.length < 9){
        return showMessage(msg, '⚠️ Please enter a valid phone number.', true);
      }
      if(!course){
        return showMessage(msg, '⚠️ Please select the course you want to study.', true);
      }
      if(!consent){
        return showMessage(msg, '⚠️ Please tick the confirmation box before submitting.', true);
      }

      showMessage(
        msg,
        '✅ Thank you, ' + name.split(' ')[0] + '! Your registration for "' + course +
        '" has been received. Haytham A. Munisi will contact you at ' + email +
        ' within 48 hours with your schedule and payment details.',
        false
      );

      regForm.reset();
    });
  }

  /* ---- Inquiry form ---- */
  const inqForm = document.getElementById('inquiryForm');
  if(inqForm){
    inqForm.addEventListener('submit', function(e){
      e.preventDefault();
      const msg = document.getElementById('inqMsg');

      const name    = document.getElementById('inqName').value.trim();
      const email   = document.getElementById('inqEmail').value.trim();
      const message = document.getElementById('inqMessage').value.trim();

      if(name.length < 3){
        return showMessage(msg, '⚠️ Please enter your name.', true);
      }
      if(!isEmail(email)){
        return showMessage(msg, '⚠️ Please enter a valid email address.', true);
      }
      if(message.length < 10){
        return showMessage(msg, '⚠️ Please write a little more detail in your message.', true);
      }

      showMessage(msg, '✅ Your inquiry has been sent. We will reply to ' + email + ' shortly.', false);
      inqForm.reset();
    });
  }

  /* ---- Contact form ---- */
  const contactForm = document.getElementById('contactForm');
  if(contactForm){
    contactForm.addEventListener('submit', function(e){
      e.preventDefault();
      const msg = document.getElementById('contactMsg');

      const name    = document.getElementById('cName').value.trim();
      const email   = document.getElementById('cEmail').value.trim();
      const message = document.getElementById('cMsg').value.trim();

      if(name.length < 3){
        return showMessage(msg, '⚠️ Please enter your name.', true);
      }
      if(!isEmail(email)){
        return showMessage(msg, '⚠️ Please enter a valid email address.', true);
      }
      if(message.length < 10){
        return showMessage(msg, '⚠️ Please write a longer message.', true);
      }

      showMessage(msg, '✅ Message sent! We will get back to you within 48 hours.', false);
      contactForm.reset();
    });
  }
})();


/* ============================================================
   5. ANIMATED STAT COUNTERS
   ============================================================ */
(function initCounters(){
  const counters = document.querySelectorAll('.stat-num');
  if(!counters.length) return;

  function animate(el){
    const target = parseInt(el.dataset.target, 10) || 0;
    const duration = 1400;
    const startTime = performance.now();

    function step(now){
      const progress = Math.min((now - startTime) / duration, 1);
      const eased = 1 - Math.pow(1 - progress, 3);
      el.textContent = Math.round(target * eased).toLocaleString();
      if(progress < 1) requestAnimationFrame(step);
    }
    requestAnimationFrame(step);
  }

  const observer = new IntersectionObserver(function(entries){
    entries.forEach(function(entry){
      if(entry.isIntersecting){
        animate(entry.target);
        observer.unobserve(entry.target);
      }
    });
  }, { threshold: 0.4 });

  counters.forEach(function(counter){ observer.observe(counter); });
})();


/* ============================================================
   6. FOOTER YEAR
   ============================================================ */
document.getElementById('year').textContent = new Date().getFullYear();


/* ============================================================
   7. KEYBOARD NAVIGATION HELPER
   ------------------------------------------------------------
   Press "t" anywhere (outside an input) to toggle the theme,
   and press "/" to jump to the registration page.
   ============================================================ */
document.addEventListener('keydown', function(e){
  const tag = (e.target.tagName || '').toLowerCase();
  if(tag === 'input' || tag === 'textarea' || tag === 'select') return;

  if(e.key === 't' || e.key === 'T'){
    document.getElementById('themeToggle').click();
  }
  if(e.key === '/'){
    e.preventDefault();
    window.location.hash = '#register';
  }
});
</script>

</body>
</html>