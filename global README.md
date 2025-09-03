 #global-hire-assist.
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>GlobalHireAssist — Smarter Hiring, Globally</title>
  <meta name="description" content="GlobalHireAssist helps companies source, vet, and onboard talent worldwide. ATS-integrated recruiting, compliance-ready onboarding, and global payroll support." />
  <meta name="theme-color" content="#0ea5e9" />
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Ccircle cx='50' cy='50' r='50' fill='%230ea5e9'/%3E%3Ctext x='50' y='58' text-anchor='middle' font-size='52' font-family='Arial' fill='white'%3EG%3C/text%3E%3C/svg%3E"/>
  <meta property="og:title" content="GlobalHireAssist — Smarter Hiring, Globally" />
  <meta property="og:description" content="Source, vet, and onboard talent worldwide with GlobalHireAssist." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://dummyimage.com/1200x630/0ea5e9/ffffff&text=GlobalHireAssist" />  <style>
    :root{
      --bg: #0b1020;
      --panel: #0f172a;
      --muted: #94a3b8;
      --text: #e2e8f0;
      --brand: #0ea5e9;
      --brand-2: #22d3ee;
      --accent: #a855f7;
      --ok: #10b981;
      --warn: #f59e0b;
      --danger: #ef4444;
      --radius: 18px;
      --shadow: 0 10px 30px rgba(2,6,23,.25);
    }
    *{box-sizing:border-box}
    html{scroll-behavior:smooth}
    body{
      margin:0; background:radial-gradient(1200px 800px at 80% -10%, rgba(14,165,233,.25), transparent 60%),
      radial-gradient(1200px 800px at -10% 10%, rgba(168,85,247,.15), transparent 60%), var(--bg);
      color:var(--text); font:16px/1.6 system-ui, -apple-system, Segoe UI, Roboto, Inter, Arial, sans-serif;
    }
    a{color:inherit; text-decoration:none}
    .container{width:min(1200px, 92%); margin-inline:auto}
    .chip{display:inline-flex; gap:.5rem; align-items:center; padding:.35rem .65rem; border-radius:999px; background:rgba(255,255,255,.06); border:1px solid rgba(148,163,184,.2); font-size:.85rem; color:var(--muted)}
    .btn{display:inline-flex; align-items:center; gap:.6rem; padding:.9rem 1.1rem; border-radius:calc(var(--radius) - 6px); border:1px solid rgba(148,163,184,.2); background:linear-gradient(180deg, rgba(255,255,255,.06), rgba(255,255,255,.02)); color:var(--text); font-weight:600; box-shadow:var(--shadow); transition:.2s transform, .2s box-shadow, .2s background}
    .btn:hover{transform:translateY(-2px); box-shadow:0 12px 34px rgba(2,6,23,.35)}
    .btn.primary{background:linear-gradient(180deg, rgba(14,165,233,.9), rgba(34,211,238,.9)); color:#001018; border:0}
    .btn.ghost{background:transparent; border:1px solid rgba(148,163,184,.35)}
    .grid{display:grid; gap:1.2rem}
    .card{background:linear-gradient(180deg, rgba(255,255,255,.06), rgba(255,255,255,.02)); border:1px solid rgba(148,163,184,.15); border-radius:var(--radius); box-shadow:var(--shadow)}
    header.site{position:sticky; top:0; z-index:50; backdrop-filter:blur(10px); background:rgba(11,16,32,.6); border-bottom:1px solid rgba(148,163,184,.12)}
    nav{display:flex; align-items:center; justify-content:space-between; gap:1rem; padding:.8rem 0}
    nav .brand{display:flex; align-items:center; gap:.7rem; font-weight:800}
    nav .brand .logo{width:36px; height:36px; display:grid; place-items:center; border-radius:10px; background:conic-gradient(from 180deg at 50% 50%, var(--brand), var(--brand-2) 60%, var(--accent)); color:#001018; font-weight:900}
    .nav-links{display:flex; gap:.9rem; align-items:center}
    .nav-links a{padding:.55rem .75rem; border-radius:10px; color:var(--muted)}
    .nav-links a:hover{background:rgba(255,255,255,.06); color:var(--text)}
    .mobile-toggle{display:none}

    /* Hero */
    .hero{padding:5rem 0 3rem; position:relative; overflow:hidden}
    .hero h1{font-size:clamp(2.3rem, 5vw, 3.6rem); line-height:1.1; letter-spacing:-.02em; margin:0}
    .hero p{color:var(--muted); font-size:1.1rem; margin:1rem 0 1.6rem}
    .hero .actions{display:flex; gap:.9rem; flex-wrap:wrap}
    .hero-illu{position:absolute; inset:auto -20% -35% -20%; pointer-events:none; opacity:.25; filter:blur(40px)}

    /* Sections */
    section{padding:3.5rem 0}
    section h2{font-size:clamp(1.6rem, 3.2vw, 2.2rem); margin:0 0 1rem; letter-spacing:-.02em}
    section .lead{color:var(--muted); margin:.2rem 0 1.8rem}

    /* Feature grid */
    .features{grid-template-columns:repeat(12, 1fr)}
    .features .feature{grid-column:span 4; padding:1.2rem}
    .feature h3{margin:.6rem 0 .4rem}
    .feature p{color:var(--muted); font-size:.98rem}

    /* Services */
    .services{grid-template-columns:repeat(3, 1fr)}
    .service{padding:1.2rem}
    .badge{font-size:.75rem; padding:.25rem .55rem; border-radius:999px; border:1px solid rgba(148,163,184,.25); color:var(--muted)}

    /* Stats */
    .stats{display:grid; grid-template-columns:repeat(4, 1fr); gap:1rem}
    .stat{padding:1.2rem; text-align:center}
    .stat strong{font-size:2rem}
    .stat span{display:block; color:var(--muted)}

    /* Testimonials */
    .testimonials{grid-template-columns:repeat(3, 1fr)}
    blockquote{margin:0}
    .quote{padding:1.2rem; min-height:180px}
    .quote footer{margin-top:1rem; color:var(--muted)}

    /* Pricing */
    .pricing{grid-template-columns:repeat(3, 1fr)}
    .price{padding:1.2rem; position:relative}
    .price .ribbon{position:absolute; top:14px; right:-8px; transform:rotate(15deg); background:linear-gradient(90deg, var(--brand), var(--brand-2)); color:#001018; padding:.25rem .6rem; border-radius:6px; font-size:.8rem; font-weight:700}
    .price .tag{font-size:2rem; font-weight:800}

    /* CTA */
    .cta{display:grid; grid-template-columns:1.5fr 1fr; gap:1.2rem; align-items:center}

    /* Footer */
    footer{border-top:1px solid rgba(148,163,184,.12); padding:2.5rem 0; color:var(--muted)}
    .footer-grid{display:grid; grid-template-columns:1.5fr repeat(4, 1fr); gap:1.4rem}
    .footer-col a{display:block; padding:.25rem 0; color:var(--muted)}
    .footer-col a:hover{color:var(--text)}

    /* Utilities */
    .icon{width:22px; height:22px}
    .row{display:flex; gap:.8rem; align-items:center}
    .pill{border:1px dashed rgba(255,255,255,.2); padding:.5rem .75rem; border-radius:999px}

    /* Contact */
    form{display:grid; gap:.9rem}
    input, textarea, select{width:100%; padding:.85rem 1rem; background:rgba(255,255,255,.03); border:1px solid rgba(148,163,184,.25); color:var(--text); border-radius:12px}
    textarea{min-height:120px}
    label{font-size:.9rem; color:var(--muted)}
    .form-row{display:grid; grid-template-columns:repeat(2,1fr); gap:.9rem}

    /* Responsive */
    @media (max-width: 980px){
      .features .feature{grid-column:span 6}
      .services{grid-template-columns:repeat(2, 1fr)}
      .stats{grid-template-columns:repeat(2, 1fr)}
      .pricing{grid-template-columns:repeat(2, 1fr)}
      .cta{grid-template-columns:1fr}
      .footer-grid{grid-template-columns:1fr 1fr}
    }
    @media (max-width: 720px){
      .features .feature{grid-column:span 12}
      .services{grid-template-columns:1fr}
      .testimonials{grid-template-columns:1fr}
      .pricing{grid-template-columns:1fr}
      .form-row{grid-template-columns:1fr}
      .nav-links{display:none}
      .mobile-toggle{display:flex; align-items:center; justify-content:center; width:42px; height:42px; border-radius:10px; border:1px solid rgba(148,163,184,.25); background:rgba(255,255,255,.04)}
      .mobile-panel{position:fixed; inset:60px 0 0 0; background:rgba(11,16,32,.96); backdrop-filter:blur(12px); display:none; padding:1rem}
      .mobile-panel a{display:block; padding:1rem; border-bottom:1px solid rgba(148,163,184,.15)}
    }

    /* Animated gradient ring */
    .ring{
      --s: 400px; position:absolute; width:var(--s); height:var(--s); border-radius:50%;
      background:conic-gradient(from 0deg, var(--brand), var(--brand-2), var(--accent), var(--brand));
      filter:blur(50px); opacity:.16; animation:spin 14s linear infinite
    }
    .ring.r1{top:-120px; left:-60px}
    .ring.r2{bottom:-140px; right:-40px; animation-direction:reverse}
    @keyframes spin{to{transform:rotate(360deg)}}

    /* Table */
    table{width:100%; border-collapse:separate; border-spacing:0; overflow:hidden; border-radius:12px}
    th, td{padding:.85rem 1rem; border-bottom:1px solid rgba(148,163,184,.15)}
    th{text-align:left; color:var(--muted); font-weight:600; background:rgba(255,255,255,.03)}
  </style>  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Organization",
    "name": "GlobalHireAssist",
    "url": "https://www.globalhireassist.example",
    "logo": "https://dummyimage.com/200x200/0ea5e9/ffffff&text=G",
    "sameAs": ["https://www.linkedin.com/company/globalhireassist"]
  }
  </script></head>
<body>  <!-- Header / Nav -->  <header class="site">
    <div class="container">
      <nav>
        <a href="#top" class="brand" aria-label="GlobalHireAssist Home">
          <span class="logo">G</span>
          <span>GlobalHireAssist</span>
        </a>
        <div class="nav-links" aria-label="Primary">
          <a href="#solutions">Solutions</a>
          <a href="#services">Services</a>
          <a href="#pricing">Pricing</a>
          <a href="#about">About</a>
          <a href="#contact">Contact</a>
        </div>
        <div class="row">
          <a class="btn ghost" href="#demo">Book a demo</a>
          <button class="mobile-toggle" aria-label="Open menu" id="menuBtn">
            <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 6h16M4 12h16M4 18h16"/></svg>
          </button>
        </div>
      </nav>
    </div>
    <div class="mobile-panel" id="mobilePanel">
      <a href="#solutions">Solutions</a>
      <a href="#services">Services</a>
      <a href="#pricing">Pricing</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
      <div style="padding:1rem 0">
        <a class="btn primary" href="#demo">Book a demo</a>
      </div>
    </div>
  </header>  <!-- Hero -->  <section class="hero container" id="top">
    <span class="chip">
      <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M5 13l4 4L19 7"/></svg>
      Trusted by 500+ teams
    </span>
    <h1>Hire anywhere. <span style="background:linear-gradient(90deg, var(--brand), var(--brand-2)); -webkit-background-clip:text; background-clip:text; color:transparent">Onboard in days.</span></h1>
    <p>GlobalHireAssist is the recruiting copilot for modern companies — source talent worldwide, run compliant hiring workflows, and onboard in days with built‑in verifications and payroll assistance.</p>
    <div class="actions">
      <a href="#demo" class="btn primary">
        <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M5 12h14M12 5l7 7-7 7"/></svg>
        Get started
      </a>
      <a href="#solutions" class="btn">
        <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"/><path d="M12 6v6l4 2"/></svg>
        See how it works
      </a>
    </div>
    <div class="ring r1" aria-hidden="true"></div>
    <div class="ring r2" aria-hidden="true"></div>
    <img class="hero-illu" alt="Decorative gradient" src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 1200 500'%3E%3Cdefs%3E%3ClinearGradient id='g' x1='0' x2='1'%3E%3Cstop offset='0' stop-color='%230ea5e9'/%3E%3Cstop offset='1' stop-color='%2322d3ee'/%3E%3C/linearGradient%3E%3C/defs%3E%3Ccircle cx='200' cy='120' r='180' fill='url(%23g)' opacity='.25'/%3E%3Ccircle cx='1000' cy='360' r='240' fill='%23a855f7' opacity='.18'/%3E%3C/svg%3E"/>
  </section>  <!-- Logos / social proof -->  <section>
    <div class="container card" style="padding:1rem">
      <marquee behavior="scroll" direction="left" scrollamount="5" onmouseover="this.stop()" onmouseout="this.start()">
        <span class="pill">AWS Partner</span>
        <span class="pill">ISO 27001 Ready</span>
        <span class="pill">SOC 2 Type II</span>
        <span class="pill">GDPR Compliant</span>
        <span class="pill">HRIS + ATS Integrations</span>
      </marquee>
    </div>
  </section>  <!-- Solutions / Features -->  <section id="solutions">
    <div class="container">
      <h2>One platform. End‑to‑end hiring.</h2>
      <p class="lead">Source, screen, schedule, evaluate, offer, and onboard — with analytics at every step.</p>
      <div class="grid features">
        <div class="card feature">
          <span class="badge">Sourcing</span>
          <h3>Global talent discovery</h3>
          <p>AI‑assisted search across public profiles & talent pools, with geo, skills, and seniority filters.</p>
        </div>
        <div class="card feature">
          <span class="badge">Screening</span>
          <h3>Smart assessments</h3>
          <p>Role‑based tests and structured interviews to reduce bias and increase signal.</p>
        </div>
        <div class="card feature">
          <span class="badge">Scheduling</span>
          <h3>Calendar orchestration</h3>
          <p>Instant scheduling across time zones and panel availability, with auto‑timezone detection.</p>
        </div>
        <div class="card feature">
          <span class="badge">Compliance</span>
          <h3>KYC / Right‑to‑work</h3>
          <p>Document capture, e‑signature, and automated checks for global compliance.</p>
        </div>
        <div class="card feature">
          <span class="badge">Offers</span>
          <h3>Compensation packages</h3>
          <p>Localized offers with salary bands, equity, and benefits; approval workflows built‑in.</p>
        </div>
        <div class="card feature">
          <span class="badge">Onboarding</span>
          <h3>Ready on day one</h3>
          <p>Pre‑boarding tasks, equipment provisioning, and payroll connections in 150+ countries.</p>
        </div>
      </div>
    </div>
  </section>  <!-- Services -->  <section id="services">
    <div class="container">
      <h2>Services designed for your growth</h2>
      <p class="lead">Pair the platform with expert services when you need a boost.</p>
      <div class="grid services">
        <div class="card service">
          <h3>RPO (Recruitment Process Outsourcing)</h3>
          <p>Elastic recruiting pods to scale reqs up or down, embedded with your team.</p>
          <ul>
            <li>Dedicated sourcers & recruiters</li>
            <li>Weekly pipeline reporting</li>
            <li>Employer brand playbooks</li>
          </ul>
        </div>
        <div class="card service">
          <h3>Executive Search</h3>
          <p>Retained search for leadership roles with rigorous vetting and references.</p>
          <ul>
            <li>Market mapping</li>
            <li>Competency interviews</li>
            <li>Board-ready shortlists</li>
          </ul>
        </div>
        <div class="card service">
          <h3>Global Payroll Setup</h3>
          <p>We coordinate EOR/PEO partners and configure payroll, benefits, and taxes.</p>
          <ul>
            <li>Country-by-country guidance</li>
            <li>Localized benefits catalog</li>
            <li>SLAs and ongoing support</li>
          </ul>
        </div>
      </div>
    </div>
  </section>  <!-- Stats -->  <section aria-label="Key results">
    <div class="container stats card">
      <div class="stat"><strong>42%</strong><span>Faster time‑to‑hire</span></div>
      <div class="stat"><strong>+68</strong><span>NPS from candidates</span></div>
      <div class="stat"><strong>28%</strong><span>Cost per hire saved</span></div>
      <div class="stat"><strong>150+</strong><span>Countries supported</span></div>
    </div>
  </section>  <!-- Testimonials -->  <section>
    <div class="container">
      <h2>Loved by modern People teams</h2>
      <div class="grid testimonials">
        <blockquote class="card quote">
          <p>“GlobalHireAssist gave us a single pane of glass for global hiring. Our lead time dropped from weeks to days.”</p>
          <footer>— Priya N., VP People, Fintech</footer>
        </blockquote>
        <blockquote class="card quote">
          <p>“The built‑in compliance checks removed so much anxiety around cross‑border onboarding.”</p>
          <footer>— Louis M., COO, SaaS</footer>
        </blockquote>
        <blockquote class="card quote">
          <p>“Candidates consistently praise our process now — structured, fair, and fast.”</p>
          <footer>— Ada O., Head of Talent, HealthTech</footer>
        </blockquote>
      </div>
    </div>
  </section>  <!-- Pricing -->  <section id="pricing">
    <div class="container">
      <h2>Simple, transparent pricing</h2>
      <p class="lead">Pick a plan and scale as you grow. Cancel anytime.</p>
      <div class="grid pricing">
        <div class="card price">
          <h3>Starter</h3>
          <p class="lead">For new teams hiring a few roles per month.</p>
          <p class="tag">$99 <span style="font-size:.9rem; color:var(--muted)">/mo</span></p>
          <ul>
            <li>Up to 5 active roles</li>
            <li>Email & calendar sync</li>
            <li>Basic assessments</li>
            <li>Community support</li>
          </ul>
          <a class="btn" href="#demo">Choose Starter</a>
        </div>
        <div class="card price">
          <span class="ribbon">Popular</span>
          <h3>Growth</h3>
          <p class="lead">Best for fast‑growing companies.</p>
          <p class="tag">$299 <span style="font-size:.9rem; color:var(--muted)">/mo</span></p>
          <ul>
            <li>Unlimited roles</li>
            <li>Advanced automations</li>
            <li>Compliance checks</li>
            <li>ATS integrations</li>
          </ul>
          <a class="btn primary" href="#demo">Choose Growth</a>
        </div>
        <div class="card price">
          <h3>Enterprise</h3>
          <p class="lead">For complex orgs with custom needs.</p>
          <p class="tag">Custom</p>
          <ul>
            <li>SSO / SCIM</li>
            <li>Custom security review</li>
            <li>Dedicated CSM</li>
            <li>Premium support</li>
          </ul>
          <a class="btn" href="#contact">Talk to sales</a>
        </div>
      </div>
    </div>
  </section>  <!-- Integrations Table -->  <section>
    <div class="container">
      <h2>Integrations</h2>
      <p class="lead">Connect your favorite tools in minutes.</p>
      <div class="card" style="overflow:auto">
        <table role="table" aria-label="Integrations">
          <thead>
            <tr><th>Category</th><th>Products</th><th>Notes</th></tr>
          </thead>
          <tbody>
            <tr><td>ATS</td><td>Greenhouse, Lever, Ashby</td><td>Two‑way sync (candidates, stages)</td></tr>
            <tr><td>Calendars</td><td>Google, Microsoft 365</td><td>Availability & scheduling</td></tr>
            <tr><td>HRIS</td><td>Workday, BambooHR, Rippling</td><td>Employee profiles & onboarding</td></tr>
            <tr><td>Payroll</td><td>Deel, Remote, Oyster</td><td>Global payroll + EOR</td></tr>
            <tr><td>Communication</td><td>Slack, Teams</td><td>Notifications & approvals</td></tr>
          </tbody>
        </table>
      </div>
    </div>
  </section>  <!-- About -->  <section id="about">
    <div class="container">
      <h2>About GlobalHireAssist</h2>
      <p class="lead">We exist to make great hiring universal. Founded in 2023, we’re a fully remote team across 10 countries.</p>
      <div class="grid" style="grid-template-columns:2fr 1fr">
        <div class="card" style="padding:1.2rem">
          <h3>Our principles</h3>
          <ul>
            <li>🧭 Candidate‑first experiences</li>
            <li
