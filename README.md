<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Ahmed Al-Khameri | Electrical Design Engineer, MEP/BIM and Solar PV</title>
<meta name="description" content="Electrical design engineer in Cairo working on MEP/BIM coordination and solar PV design. Open to roles in the Gulf.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Barlow:wght@400;500;600&family=Barlow+Semi+Condensed:wght@500;600;700&display=swap" rel="stylesheet">
<style>
:root{
  color-scheme:light dark;
  --paper:#f1f4f7; --ink:#12263a; --muted:#4d6176; --rule:#c5d0da; --blue:#1f5fbf; --amber:#c98a00;
  --head:"Barlow Semi Condensed","Arial Narrow",Arial,sans-serif;
  --body:"Barlow",system-ui,Arial,sans-serif;
}
@media (prefers-color-scheme:dark){
  :root{--paper:#0e1b29; --ink:#e6edf4; --muted:#9db0c2; --rule:#2b3f54; --blue:#6aa5ff; --amber:#f0b429}
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;background:var(--paper);color:var(--ink);font:400 18px/1.6 var(--body)}
a{color:var(--blue);text-underline-offset:3px}
a:focus-visible{outline:3px solid var(--amber);outline-offset:3px}
main{max-width:920px;margin:0 auto;padding:0 24px 64px}
h1,h2,h3{font-family:var(--head);line-height:1.1;margin:0}
h1{font-size:clamp(44px,8vw,76px);font-weight:700;letter-spacing:-.01em}
h2{font-size:30px;font-weight:600;margin-bottom:20px}
h3{font-size:22px;font-weight:600}
p{margin:0 0 14px;max-width:62ch}
section{padding:48px 0;border-top:1px solid var(--rule)}
.hero{display:grid;grid-template-columns:1fr;gap:32px;padding:64px 0 48px;align-items:center;border:0}
@media(min-width:800px){.hero{grid-template-columns:1.1fr .9fr}}
.role{font:500 24px/1.3 var(--head);color:var(--muted);margin:12px 0 20px}
.links{display:flex;gap:20px;flex-wrap:wrap;margin-top:24px;font-weight:600}
.diagram{width:100%;height:auto}
.diagram *{vector-effect:non-scaling-stroke}
.bus,.feed{stroke:var(--ink);stroke-width:3;fill:none}
.feed{stroke-width:2}
.brk{fill:var(--paper);stroke:var(--ink);stroke-width:2}
.tx{fill:none;stroke:var(--ink);stroke-width:2}
.d-name{font:600 20px var(--head);fill:var(--ink)}
.d-note{font:400 15px var(--body);fill:var(--muted)}
.pv{stroke:var(--amber)}
.projects{display:grid;gap:0}
.project{display:grid;grid-template-columns:1fr;gap:4px 32px;padding:22px 0;border-top:1px solid var(--rule)}
.project:first-child{border-top:0;padding-top:0}
@media(min-width:700px){.project{grid-template-columns:240px 1fr}}
.where{color:var(--muted);font-weight:500}
.skills{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:24px}
.skills h3{font-size:19px;margin-bottom:6px}
.skills p{margin:0;color:var(--muted)}
.timeline{list-style:none;margin:0;padding:0}
.timeline li{padding:0 0 22px 22px;border-left:2px solid var(--rule);position:relative}
.timeline li::before{content:"";position:absolute;left:-6px;top:8px;width:10px;height:10px;background:var(--blue);border-radius:50%}
.timeline .when{color:var(--muted);font-weight:500}
footer{color:var(--muted);font-size:15px;padding-top:24px;border-top:1px solid var(--rule)}
</style>
</head>
<body>
<main>

<section class="hero" id="top">
  <div>
    <h1>Ahmed Al-Khameri</h1>
    <p class="role">Electrical design engineer. MEP/BIM coordination and solar PV design.</p>
    <p>I design electrical systems and coordinate them in Revit with the other disciplines. I have also supervised electrical works on site, so I design with construction in mind. Based in Cairo and interested in roles in the Gulf.</p>
    <div class="links">
      <a href="#projects">View projects</a>
      <a href="https://www.linkedin.com/in/ahmedalkhameri/">LinkedIn</a>
      <a href="mailto:YOUR_EMAIL@example.com">Email me</a>
    </div>
  </div>

  <!-- Single-line diagram: each feeder is a project below -->
  <svg class="diagram" viewBox="0 0 420 300" role="img" aria-label="Single-line diagram showing four feeders: hospital in Cairo, residential project in Yemen, mega project in the UAE, and a solar PV system of 1,500 kWp or more.">
    <circle class="tx" cx="16" cy="150" r="11"/><circle class="tx" cx="30" cy="150" r="11"/>
    <line class="feed" x1="41" y1="150" x2="60" y2="150"/>
    <line class="bus" x1="60" y1="20" x2="60" y2="280"/>

    <line class="feed" x1="60" y1="50" x2="104" y2="50"/><rect class="brk" x="104" y="42" width="16" height="16"/><line class="feed" x1="120" y1="50" x2="160" y2="50"/>
    <text class="d-name" x="172" y="48">Hospital</text><text class="d-note" x="172" y="68">Cairo, Egypt</text>

    <line class="feed" x1="60" y1="120" x2="104" y2="120"/><rect class="brk" x="104" y="112" width="16" height="16"/><line class="feed" x1="120" y1="120" x2="160" y2="120"/>
    <text class="d-name" x="172" y="118">Residential project</text><text class="d-note" x="172" y="138">Yemen</text>

    <line class="feed" x1="60" y1="190" x2="104" y2="190"/><rect class="brk" x="104" y="182" width="16" height="16"/><line class="feed" x1="120" y1="190" x2="160" y2="190"/>
    <text class="d-name" x="172" y="188">Mega project</text><text class="d-note" x="172" y="208">UAE</text>

    <line class="feed pv" x1="60" y1="260" x2="104" y2="260"/><rect class="brk pv" x="104" y="252" width="16" height="16"/><line class="feed pv" x1="120" y1="260" x2="160" y2="260"/>
    <text class="d-name" x="172" y="258">Solar PV</text><text class="d-note" x="172" y="278">1,500+ kWp, oil and gas</text>
  </svg>
</section>

<section id="projects">
  <h2>Projects</h2>
  <div class="projects">
    <article class="project">
      <div><h3>Hospital</h3><div class="where">Cairo, Egypt</div></div>
      <div>
        <p>Electrical design and Revit coordination with the other disciplines at Diar Consulting Group.</p>
        <!-- TODO: add scope, e.g. floor area, systems designed, your role -->
      </div>
    </article>
    <article class="project">
      <div><h3>Residential project</h3><div class="where">Yemen</div></div>
      <div>
        <p>Electrical design and Revit coordination with the other disciplines at Diar Consulting Group.</p>
        <!-- TODO: add scope -->
      </div>
    </article>
    <article class="project">
      <div><h3>Mega project</h3><div class="where">United Arab Emirates</div></div>
      <div>
        <p>Electrical design and Revit coordination with the other disciplines at Diar Consulting Group.</p>
        <!-- TODO: add scope -->
      </div>
    </article>
    <article class="project">
      <div><h3>Solar PV system</h3><div class="where">Oil and gas project</div></div>
      <div>
        <p>Design and simulation of a solar PV system of more than 1,500 kWp, using PVsyst.</p>
        <!-- TODO: add details, e.g. location, layout, yield results -->
      </div>
    </article>
  </div>
</section>

<section id="skills">
  <h2>Tools</h2>
  <div class="skills">
    <div><h3>BIM and drafting</h3><p>Revit, AutoCAD, Autodesk Forma, SketchUp</p></div>
    <div><h3>Power systems</h3><p>ETAP, Ecodial</p></div>
    <div><h3>Solar PV</h3><p>PVsyst</p></div>
    <div><h3>Lighting</h3><p>DIALux evo</p></div>
  </div>
</section>

<section id="background">
  <h2>Background</h2>
  <ul class="timeline">
    <li><h3>Electrical Design Engineer, Diar Consulting Group</h3><div class="when">Cairo, January 2026 to present</div></li>
    <li><h3>Site Supervision Engineer, Epos Innovation</h3><div class="when">August 2025 to January 2026</div></li>
    <li><h3>B.Sc. Electrical Power and Machine Engineering</h3><div class="when">Al-Azhar University, 2024</div></li>
    <li><h3>Diplomas</h3><div class="when">Electrical BIM (in progress), Electrical Revit, Solar Systems</div></li>
  </ul>
  <p>Languages: Arabic (native), English (very good).</p>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>I am looking for MEP, BIM and solar PV roles in the Gulf. The best way to reach me is by <a href="mailto:YOUR_EMAIL@example.com">email</a> or on <a href="https://www.linkedin.com/in/ahmedalkhameri/">LinkedIn</a>.</p>
  <!-- TODO: add your GitHub profile link and CV download, e.g. <a href="cv.pdf">Download CV</a> -->
</section>

<footer>Ahmed Al-Khameri, Cairo, Egypt</footer>
</main>
</body>
</html>
