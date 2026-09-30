<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sutanshu Shekhar | AI & ML Engineer</title>
<meta name="description" content="Portfolio of Sutanshu Shekhar, B.Tech CSE (AI & ML) student building machine learning, data analytics and web projects.">
<script src="https://cdn.tailwindcss.com"></script>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Rounded:opsz,wght,FILL,GRAD@24,500,0,0&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;600&family=Inter:wght@400;500;600&family=Outfit:wght@500;600;700;800&display=swap" rel="stylesheet">
<script>
tailwind.config = {
  theme: { extend: {
    colors: { ink:'#1b1740', violet:'#7c3aed', cyan:'#06b6d4', coral:'#f43f5e', amber:'#f59e0b', mint:'#10b981', mist:'#f6f5ff' },
    fontFamily: { sans:['Inter','sans-serif'], display:['Outfit','sans-serif'] }
  }}
}
</script>
<style>
  body { font-family:'Inter',sans-serif; color:#1f2937; }
  h1,h2,h3,h4,.font-display { font-family:'Outfit',sans-serif; }
  .hero-bg {
    background:
      radial-gradient(600px 400px at 85% 20%, rgba(6,182,212,.35), transparent 60%),
      radial-gradient(500px 400px at 10% 90%, rgba(244,63,94,.28), transparent 60%),
      linear-gradient(135deg,#1b1740 0%,#3b1f8f 55%,#7c3aed 100%);
  }
  .grad-text { background:linear-gradient(90deg,#06b6d4,#a78bfa,#f472b6); -webkit-background-clip:text; background-clip:text; color:transparent; }
  .photo-ring { background:conic-gradient(from 180deg,#06b6d4,#7c3aed,#f43f5e,#f59e0b,#06b6d4); }
  .card { transition:transform .25s ease, box-shadow .25s ease; }
  .card:hover { transform:translateY(-4px); box-shadow:0 20px 40px -18px rgba(76,29,149,.35); }
  .section-title::after { content:""; display:block; width:56px; height:4px; border-radius:4px; margin-top:12px; background:linear-gradient(90deg,#7c3aed,#06b6d4); }
  .center .section-title::after, .section-title.center::after { margin-left:auto; margin-right:auto; }
  .rise { animation:rise .8s ease both; }
  @keyframes rise { from { opacity:0; transform:translateY(24px);} to { opacity:1; transform:none;} }
  @media (prefers-reduced-motion: reduce) { .rise { animation:none; } .card { transition:none; } html { scroll-behavior:auto; } }
  a:focus-visible, button:focus-visible, input:focus-visible, textarea:focus-visible { outline:3px solid #06b6d4; outline-offset:2px; }
  section[id] { scroll-margin-top:72px; }

  /* ===== Hover effects for every section ===== */
  .section-title::after { transition:width .3s ease; }
  .section-title:hover::after { width:120px; }
  header nav a { transition:transform .2s ease, color .2s ease, opacity .2s ease; }
  header nav a:hover { transform:translateY(-2px); }
  #home a.rounded-full { transition:transform .2s ease, box-shadow .2s ease, background-color .2s ease, color .2s ease; }
  #home a.rounded-full:hover { transform:translateY(-3px); box-shadow:0 12px 24px -10px rgba(0,0,0,.5); }
  .photo-wrap .photo-ring { transition:transform .4s ease, box-shadow .4s ease; }
  .photo-wrap:hover .photo-ring { transform:rotate(-2deg) scale(1.03); box-shadow:0 30px 60px -20px rgba(6,182,212,.6); }
  .photo-wrap .badge-float { transition:transform .3s ease; }
  .photo-wrap:hover .badge-float { transform:translateY(-6px) scale(1.05); }
  .hover-pop { transition:transform .25s ease, background-color .25s ease; border-radius:1rem; padding:.5rem; }
  .hover-pop:hover { transform:translateY(-4px) scale(1.06); background:#f3f0ff; }
  .hover-row { transition:transform .2s ease, color .2s ease; }
  .hover-row:hover { transform:translateX(6px); color:#7c3aed; }
  #skills span.rounded-full { display:inline-block; transition:transform .2s ease, box-shadow .2s ease; cursor:default; }
  #skills span.rounded-full:hover { transform:translateY(-3px) scale(1.08); box-shadow:0 8px 16px -6px rgba(0,0,0,.35); }
  .proj-img { transition:transform .6s ease; }
  .card:hover .proj-img { transform:scale(1.08); }
  .proj-media .upload-btn { transition:opacity .2s ease, background-color .2s ease; }
  .proj-media .upload-btn:hover { background:#7c3aed; }
  .proj-media .upload-btn:focus-within { outline:3px solid #06b6d4; outline-offset:2px; }
  #education li { transition:transform .2s ease; }
  #education li:hover { transform:translateX(8px); }
  #education li i { transition:transform .2s ease; }
  #education li:hover i { transform:scale(1.3); }
  #education .card:hover { background:#ffffff; }
  #contact .space-y-6 > div { transition:transform .2s ease; }
  #contact .space-y-6 > div:hover { transform:translateX(8px); }
  #contact a[aria-label], footer a { display:inline-block; }
  #contact input, #contact textarea { transition:border-color .2s ease, box-shadow .2s ease; }
  #contact input:hover, #contact textarea:hover { border-color:#7c3aed; box-shadow:0 0 0 3px rgba(124,58,237,.12); }
  #contact button[type=submit] { transition:transform .2s ease, box-shadow .2s ease, opacity .2s ease; }
  #contact button[type=submit]:hover { transform:translateY(-2px); box-shadow:0 12px 24px -10px rgba(244,63,94,.6); }
  footer a { transition:transform .2s ease, color .2s ease; }
  footer a:hover { transform:translateY(-3px); }
  .sr-only { position:absolute; width:1px; height:1px; overflow:hidden; clip:rect(0,0,0,0); white-space:nowrap; }
  @media (prefers-reduced-motion: reduce) { * { transition:none !important; animation:none !important; } }

  /* ===== Social links ===== */
  .social-pill { display:inline-flex; align-items:center; gap:.5rem; border-radius:9999px; padding:.65rem 1.25rem; font-size:.875rem; font-weight:600; transition:transform .2s ease, box-shadow .2s ease, filter .2s ease; }
  .social-pill:hover { transform:translateY(-3px); box-shadow:0 12px 24px -10px rgba(0,0,0,.45); filter:brightness(1.1); }
  .rail a { display:flex; height:2.75rem; width:2.75rem; align-items:center; justify-content:center; border-radius:9999px; color:#fff; box-shadow:0 8px 20px -8px rgba(0,0,0,.5); transition:transform .2s ease, box-shadow .2s ease; }
  .rail a:hover { transform:scale(1.15) translateX(-3px); }
  .nav-social { display:inline-flex; height:2.25rem; width:2.25rem; align-items:center; justify-content:center; border-radius:9999px; background:rgba(255,255,255,.1); }
  .nav-social:hover { background:#fff; color:#1b1740; }

  /* ===== Google Material Symbols ===== */
  .ms { font-family:'Material Symbols Rounded'; font-weight:normal; font-style:normal; font-size:1.25rem; line-height:1; display:inline-block; width:1em; height:1em; overflow:hidden; white-space:nowrap; letter-spacing:normal; text-transform:none; vertical-align:middle; flex-shrink:0; -webkit-font-feature-settings:'liga'; font-feature-settings:'liga'; -webkit-font-smoothing:antialiased; }
  html:not(.icons-ready) .ms { visibility:hidden; }
  .title-icon { display:flex; height:3.5rem; width:3.5rem; align-items:center; justify-content:center; border-radius:1rem; color:#fff; margin-bottom:1rem; background:linear-gradient(135deg,#7c3aed,#06b6d4); box-shadow:0 12px 24px -10px rgba(124,58,237,.6); transition:transform .3s ease; }
  .title-icon .ms { font-size:1.9rem; }
  .section-title.center .title-icon { margin-left:auto; margin-right:auto; }
  .section-title:hover .title-icon { transform:rotate(-8deg) scale(1.1); }
  #education li .ms { transition:transform .2s ease; }
  #education li:hover .ms { transform:scale(1.3); }

  /* ===== Enquiry ===== */
  #enquiry input, #enquiry textarea { transition:border-color .2s ease, box-shadow .2s ease; }
  #enquiry input:hover, #enquiry textarea:hover { border-color:#7c3aed; box-shadow:0 0 0 3px rgba(124,58,237,.12); }
  #enquiry button[type=submit] { transition:transform .2s ease, box-shadow .2s ease, opacity .2s ease; }
  #enquiry button[type=submit]:hover { transform:translateY(-2px); box-shadow:0 12px 24px -10px rgba(244,63,94,.6); }
  #enquiry .perk { transition:transform .2s ease; }
  #enquiry .perk:hover { transform:translateX(8px); }

  /* ===== Dynamic enquiry form ===== */
  .field { width:100%; border-radius:.75rem; border:1px solid #d1d5db; background:#fff; padding:.625rem 1rem; transition:border-color .2s ease, box-shadow .2s ease; }
  .field[aria-invalid="true"] { border-color:#f43f5e; box-shadow:0 0 0 3px rgba(244,63,94,.12); }
  #enquiry select.field { appearance:none; -webkit-appearance:none; padding-right:2.5rem; cursor:pointer; }
  #enquiry select:hover { border-color:#7c3aed; box-shadow:0 0 0 3px rgba(124,58,237,.12); }
  .select-wrap { position:relative; }
  .select-caret { position:absolute; right:.75rem; top:50%; transform:translateY(-50%); pointer-events:none; color:#7c3aed; }
  .enq-label { display:flex; align-items:center; gap:.5rem; font-weight:500; margin-bottom:.5rem; }
  .err { font-size:.8rem; color:#e11d48; margin-top:.35rem; }
  .seg { display:inline-flex; gap:.25rem; padding:.25rem; border-radius:9999px; background:#f3f0ff; }
  .seg-btn { display:inline-flex; align-items:center; gap:.4rem; padding:.55rem 1.1rem; border-radius:9999px; font-size:.875rem; font-weight:600; color:#5b21b6; transition:background-color .2s ease, color .2s ease, box-shadow .2s ease, transform .2s ease; }
  .seg-btn:hover:not(.is-on) { background:#e9e3ff; transform:translateY(-1px); }
  .seg-btn.is-on { color:#fff; background:linear-gradient(135deg,#7c3aed,#f43f5e); box-shadow:0 8px 18px -8px rgba(124,58,237,.7); }
  .chip { position:relative; cursor:pointer; display:inline-block; }
  .chip input { position:absolute; opacity:0; inset:0; width:100%; height:100%; margin:0; cursor:pointer; }
  .chip .face { display:inline-flex; align-items:center; gap:.4rem; border-radius:9999px; border:1px solid #ddd6fe; background:#f5f3ff; color:#5b21b6; padding:.5rem 1rem; font-size:.875rem; font-weight:500; transition:transform .2s ease, background .2s ease, color .2s ease, border-color .2s ease, box-shadow .2s ease; }
  .chip:hover .face { transform:translateY(-2px); border-color:#7c3aed; }
  .chip input:checked + .face { color:#fff; border-color:transparent; background:linear-gradient(135deg,#7c3aed,#06b6d4); box-shadow:0 8px 18px -8px rgba(124,58,237,.7); }
  .chip input:focus-visible + .face { outline:3px solid #06b6d4; outline-offset:2px; }
  .hint-chip { border:1px dashed #a78bfa; border-radius:9999px; padding:.3rem .8rem; font-size:.78rem; color:#5b21b6; background:#faf9ff; transition:background .2s ease, transform .2s ease; }
  .hint-chip:hover { background:#ede9fe; transform:translateY(-2px); }
  .anim-in { animation:rise .4s ease both; }
  .perk-btn { width:100%; text-align:left; display:flex; gap:1rem; border-radius:1rem; padding:.75rem; transition:background-color .2s ease, transform .2s ease; }
  .perk-btn:hover { background:rgba(255,255,255,.16); transform:translateX(6px); }
  [hidden] { display:none !important; }

  /* ===== Get in touch corner widget (bottom-left) ===== */
  .touch { position:fixed; left:1rem; bottom:1rem; z-index:45; }
  .touch-fab { display:inline-flex; align-items:center; gap:.5rem; border-radius:9999px; padding:.8rem 1.2rem; font-weight:600; color:#fff; background:linear-gradient(135deg,#7c3aed,#f43f5e); box-shadow:0 14px 30px -10px rgba(124,58,237,.7); transition:transform .2s ease, box-shadow .2s ease; }
  .touch-fab:hover { transform:translateY(-3px); box-shadow:0 18px 34px -10px rgba(244,63,94,.65); }
  .touch-panel { position:absolute; left:0; bottom:calc(100% + .75rem); width:min(20rem, calc(100vw - 2rem)); border-radius:1.25rem; background:#fff; padding:1.25rem; box-shadow:0 24px 50px -16px rgba(27,23,64,.45); border:1px solid #ede9fe; }
  .touch-item { display:flex; align-items:center; gap:.75rem; border-radius:.9rem; padding:.55rem .6rem; color:#1f2937; transition:background-color .2s ease, transform .2s ease; }
  .touch-item:hover { background:#f3f0ff; transform:translateX(6px); }
  .touch-item .dot { display:flex; height:2.5rem; width:2.5rem; flex-shrink:0; align-items:center; justify-content:center; border-radius:9999px; color:#fff; }

  .brand-ico { position:relative; display:flex; height:3rem; width:3rem; flex-shrink:0; align-items:center; justify-content:center; border-radius:9999px; background:#fff; border:1px solid #e5e7eb; box-shadow:0 8px 18px -8px rgba(0,0,0,.35); transition:transform .2s ease, box-shadow .2s ease; }
  .brand-ico .ico, .brand-ico i { font-size:1.6rem; line-height:1; }
  .brand-ico:hover { transform:translateY(-4px) scale(1.08); box-shadow:0 14px 24px -10px rgba(0,0,0,.55); }

  /* ===== Page and section backgrounds (vivid) ===== */
  body { background:#f6f5ff; }
  body::before {
    content:""; position:fixed; inset:0; z-index:-1; pointer-events:none;
    background:
      radial-gradient(700px 500px at 0% 0%, rgba(124,58,237,.30), transparent 60%),
      radial-gradient(600px 500px at 100% 25%, rgba(6,182,212,.30), transparent 60%),
      radial-gradient(700px 500px at 0% 75%, rgba(244,63,94,.26), transparent 60%),
      radial-gradient(600px 500px at 100% 100%, rgba(245,158,11,.28), transparent 60%),
      linear-gradient(180deg,#ede9fe 0%,#cffafe 45%,#ffedd5 100%);
  }
  .band-about { background:
      radial-gradient(rgba(244,63,94,.18) 1.5px, transparent 2px) 0 0/26px 26px,
      linear-gradient(135deg, rgba(251,191,36,.38), rgba(244,114,182,.30) 55%, rgba(167,139,250,.34)), #fff; }
  .band-a { background:
      radial-gradient(rgba(124,58,237,.20) 1.5px, transparent 2px) 0 0/26px 26px,
      linear-gradient(135deg, rgba(139,92,246,.34), rgba(6,182,212,.38)), #fff; }
  .band-d { background:
      radial-gradient(rgba(37,99,235,.18) 1.5px, transparent 2px) 0 0/26px 26px,
      linear-gradient(135deg, rgba(59,130,246,.32), rgba(139,92,246,.30) 50%, rgba(236,72,153,.32)), #fff; }
  .band-b { background:
      radial-gradient(rgba(244,63,94,.20) 1.5px, transparent 2px) 0 0/26px 26px,
      linear-gradient(135deg, rgba(244,63,94,.32), rgba(251,146,60,.38) 55%, rgba(250,204,21,.36)), #fff; }
  .band-e { background:
      radial-gradient(rgba(16,185,129,.22) 1.5px, transparent 2px) 0 0/26px 26px,
      linear-gradient(135deg, rgba(16,185,129,.34), rgba(6,182,212,.34) 55%, rgba(59,130,246,.28)), #fff; }
  .band-f { background:
      radial-gradient(rgba(219,39,119,.18) 1.5px, transparent 2px) 0 0/26px 26px,
      linear-gradient(135deg, rgba(236,72,153,.32), rgba(139,92,246,.32) 55%, rgba(251,146,60,.30)), #fff; }
  .band-c { background:
      radial-gradient(rgba(16,185,129,.22) 1.5px, transparent 2px) 0 0/26px 26px,
      linear-gradient(135deg, rgba(34,197,94,.34), rgba(6,182,212,.38)), #fff; }
  /* Each section gets its own heading badge colour */
  #about .title-icon { background:linear-gradient(135deg,#f59e0b,#f43f5e); }
  #skills .title-icon { background:linear-gradient(135deg,#7c3aed,#06b6d4); }
  #projects .title-icon { background:linear-gradient(135deg,#2563eb,#ec4899); }
  #education .title-icon { background:linear-gradient(135deg,#f43f5e,#f59e0b); }
  #certifications .title-icon { background:linear-gradient(135deg,#10b981,#3b82f6); }
  #enquiry .title-icon { background:linear-gradient(135deg,#ec4899,#8b5cf6); }
  #contact .title-icon { background:linear-gradient(135deg,#22c55e,#06b6d4); }
  #about .section-title::after { background:linear-gradient(90deg,#f59e0b,#f43f5e); }
  #projects .section-title::after { background:linear-gradient(90deg,#2563eb,#ec4899); }
  #education .section-title::after { background:linear-gradient(90deg,#f43f5e,#f59e0b); }
  #certifications .section-title::after { background:linear-gradient(90deg,#10b981,#3b82f6); }
  #enquiry .section-title::after { background:linear-gradient(90deg,#ec4899,#8b5cf6); }
  #contact .section-title::after { background:linear-gradient(90deg,#22c55e,#06b6d4); }

  /* ===== Engineering-student theme ===== */
  .mono { font-family:'JetBrains Mono', ui-monospace, monospace; }
  .hero-bg { position:relative; }
  .hero-bg::before { content:""; position:absolute; inset:0; pointer-events:none;
    background-image:linear-gradient(rgba(255,255,255,.07) 1px, transparent 1px), linear-gradient(90deg, rgba(255,255,255,.07) 1px, transparent 1px);
    background-size:44px 44px; -webkit-mask-image:radial-gradient(ellipse at 50% 40%, #000 35%, transparent 80%); mask-image:radial-gradient(ellipse at 50% 40%, #000 35%, transparent 80%); }
  .hero-bg > .container { position:relative; z-index:1; }
  .hero-bg .float-ico { position:absolute; z-index:0; font-size:3.5rem; color:#fff; opacity:.16; pointer-events:none; animation:bob 7s ease-in-out infinite; }
  @keyframes bob { 0%,100% { transform:translateY(0) rotate(0deg); } 50% { transform:translateY(-16px) rotate(6deg); } }
  .caret { display:inline-block; width:.6ch; height:1.1em; margin-left:2px; vertical-align:-0.15em; background:#06b6d4; animation:blink 1s steps(1) infinite; }
  @keyframes blink { 50% { opacity:0; } }
  .kicker { display:block; margin-bottom:.35rem; font-family:'JetBrains Mono', monospace; font-size:.8rem; font-weight:600; letter-spacing:.04em; color:#7c3aed; }
  .section-title.center .kicker { text-align:center; }
  .term { border-radius:1rem; overflow:hidden; background:#0f172a; box-shadow:0 20px 40px -20px rgba(15,23,42,.7); }
  .term-bar { display:flex; align-items:center; gap:.4rem; padding:.6rem .9rem; background:#1e293b; color:#94a3b8; font-family:'JetBrains Mono', monospace; font-size:.75rem; }
  .term-bar i { display:inline-block; height:.65rem; width:.65rem; border-radius:9999px; }
  .term pre { margin:0; padding:1rem 1.1rem; overflow-x:auto; font-family:'JetBrains Mono', monospace; font-size:.78rem; line-height:1.7; color:#e2e8f0; }
  .term .k { color:#7dd3fc; } .term .s { color:#86efac; } .term .n { color:#fbbf24; } .term .b { color:#f472b6; }
  .prj-tag { position:absolute; left:.6rem; top:.6rem; z-index:1; border-radius:.4rem; background:rgba(15,23,42,.75); padding:.15rem .5rem; font-family:'JetBrains Mono', monospace; font-size:.7rem; color:#fff; }
  .learning { border-radius:1.25rem; background:#0f172a; color:#e2e8f0; padding:1.25rem 1.5rem; display:flex; flex-wrap:wrap; align-items:center; gap:.75rem; }
  .learning .pill { border:1px solid rgba(255,255,255,.25); border-radius:9999px; padding:.3rem .9rem; font-size:.85rem; transition:background .2s ease, transform .2s ease; }
  .learning .pill:hover { background:rgba(6,182,212,.25); transform:translateY(-2px); }
  .pulse-dot { height:.6rem; width:.6rem; border-radius:9999px; background:#22c55e; box-shadow:0 0 0 0 rgba(34,197,94,.7); animation:pulse 1.8s infinite; }
  @keyframes pulse { 70% { box-shadow:0 0 0 10px rgba(34,197,94,0); } 100% { box-shadow:0 0 0 0 rgba(34,197,94,0); } }
  #progress { position:fixed; top:0; left:0; z-index:60; height:4px; width:0; background:linear-gradient(90deg,#06b6d4,#7c3aed,#f43f5e,#f59e0b); }
  #to-top { position:fixed; right:1rem; bottom:1rem; z-index:40; display:flex; height:3rem; width:3rem; align-items:center; justify-content:center; border-radius:9999px; color:#fff; background:linear-gradient(135deg,#7c3aed,#06b6d4); box-shadow:0 12px 24px -10px rgba(124,58,237,.7); transition:transform .2s ease; }
  #to-top:hover { transform:translateY(-4px); }
  .js .reveal { opacity:0; transform:translateY(28px); transition:opacity .7s ease, transform .7s ease; }
  .js .reveal.in { opacity:1; transform:none; }
  .ico { display:inline-block; width:1em; height:1em; fill:currentColor; vertical-align:-0.125em; flex-shrink:0; }
</style>
<script>document.documentElement.classList.add("js");</script>
</head>
<body class="bg-mist">
<svg xmlns="http://www.w3.org/2000/svg" width="0" height="0" style="position:absolute" aria-hidden="true" focusable="false">
  <linearGradient id="ig-grad" x1="0%" y1="100%" x2="100%" y2="0%"><stop offset="0%" stop-color="#FEE411"/><stop offset="20%" stop-color="#FEDA77"/><stop offset="42%" stop-color="#F58529"/><stop offset="62%" stop-color="#DD2A7B"/><stop offset="82%" stop-color="#8134AF"/><stop offset="100%" stop-color="#515BD4"/></linearGradient><symbol id="i-instagram" viewBox="0 0 24 24"><rect x="2" y="2" width="20" height="20" rx="6" fill="url(#ig-grad)"/><circle cx="12" cy="12" r="5" fill="none" stroke="#fff" stroke-width="2"/><circle cx="17.35" cy="6.65" r="1.35" fill="#fff"/></symbol>
  <symbol id="i-facebook" viewBox="0 0 24 24"><path d="M9.101 23.691v-7.98H6.627v-3.667h2.474v-1.58c0-4.085 1.848-5.978 5.858-5.978.401 0 .955.042 1.468.103a8.68 8.68 0 0 1 1.141.195v3.325a8.623 8.623 0 0 0-.653-.036 26.805 26.805 0 0 0-.733-.009c-.707 0-1.259.096-1.675.309a1.686 1.686 0 0 0-.679.622c-.258.42-.374.995-.374 1.752v1.297h3.919l-.386 2.103-.287 1.564h-3.246v8.245C19.396 23.238 24 18.179 24 12.044c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.628 3.874 10.35 9.101 11.647Z"/></symbol>
  <symbol id="i-x" viewBox="0 0 24 24"><path d="M18.901 1.153h3.68l-8.04 9.19L24 22.846h-7.406l-5.8-7.584-6.638 7.584H.474l8.6-9.83L0 1.154h7.594l5.243 6.932ZM17.61 20.644h2.039L6.486 3.24H4.298Z"/></symbol>
  <symbol id="i-youtube" viewBox="0 0 24 24"><path d="M23.498 6.186a3.016 3.016 0 0 0-2.122-2.136C19.505 3.545 12 3.545 12 3.545s-7.505 0-9.377.505A3.017 3.017 0 0 0 .502 6.186C0 8.07 0 12 0 12s0 3.93.502 5.814a3.016 3.016 0 0 0 2.122 2.136c1.871.505 9.376.505 9.376.505s7.505 0 9.377-.505a3.015 3.015 0 0 0 2.122-2.136C24 15.93 24 12 24 12s0-3.93-.502-5.814zM9.545 15.568V8.432L15.818 12l-6.273 3.568z"/></symbol>
  <symbol id="i-telegram" viewBox="0 0 240 240"><path d="M170.6 66.6 38.2 118.1c-9 3.6-8.9 8.6-1.6 10.8l33.9 10.6 78.5-49.5c3.7-2.3 7.1-1 4.3 1.5l-63.6 57.4h-.1l2.3 36.1c3.4 0 4.9-1.6 6.8-3.4l16.3-15.8 33.9 25c6.2 3.5 10.7 1.7 12.3-5.8l22.2-104.8c2.3-9.2-3.5-13.3-9.4-10.6z" fill="currentColor"/></symbol>
</svg>


<div id="progress" aria-hidden="true"></div>
<!-- Navigation -->
<header class="fixed inset-x-0 top-0 z-50 bg-ink/90 backdrop-blur border-b border-white/10">
  <nav class="container mx-auto px-6 py-4 flex items-center justify-between">
    <a href="#home" class="mono text-lg font-bold text-white">&lt;Sutanshu<span class="text-cyan"> /&gt;</span></a>
    <div class="hidden md:flex items-center gap-6 text-sm font-medium text-indigo-100">
      <a href="#about" class="hover:text-cyan transition inline-flex items-center gap-1.5"><span class="ms text-lg" aria-hidden="true">person</span>About</a>
      <a href="#skills" class="hover:text-cyan transition inline-flex items-center gap-1.5"><span class="ms text-lg" aria-hidden="true">bolt</span>Skills</a>
      <a href="#projects" class="hover:text-cyan transition inline-flex items-center gap-1.5"><span class="ms text-lg" aria-hidden="true">rocket_launch</span>Projects</a>
      <a href="#education" class="hover:text-cyan transition inline-flex items-center gap-1.5"><span class="ms text-lg" aria-hidden="true">school</span>Education</a>
      <a href="#certifications" class="hover:text-cyan transition inline-flex items-center gap-1.5"><span class="ms text-lg" aria-hidden="true">workspace_premium</span>Certifications</a>
      <a href="#enquiry" class="hover:text-cyan transition inline-flex items-center gap-1.5"><span class="ms text-lg" aria-hidden="true">contact_support</span>Enquiry</a>
      <a href="#contact" class="rounded-full bg-gradient-to-r from-violet to-coral px-5 py-2 text-white hover:opacity-90 transition">Contact</a>
    </div>
    <button id="menu-toggle" class="md:hidden text-white" aria-label="Toggle menu" aria-expanded="false"><span class="ms text-2xl" aria-hidden="true">menu</span></button>
  </nav>
  <div id="mobile-menu" class="hidden md:hidden px-6 pb-4 text-indigo-100">
    <a href="#about" class="flex items-center gap-2 py-2"><span class="ms text-lg" aria-hidden="true">person</span>About</a>
    <a href="#skills" class="flex items-center gap-2 py-2"><span class="ms text-lg" aria-hidden="true">bolt</span>Skills</a>
    <a href="#projects" class="flex items-center gap-2 py-2"><span class="ms text-lg" aria-hidden="true">rocket_launch</span>Projects</a>
    <a href="#education" class="flex items-center gap-2 py-2"><span class="ms text-lg" aria-hidden="true">school</span>Education</a>
    <a href="#certifications" class="flex items-center gap-2 py-2"><span class="ms text-lg" aria-hidden="true">workspace_premium</span>Certifications</a>
    <a href="#enquiry" class="flex items-center gap-2 py-2"><span class="ms text-lg" aria-hidden="true">contact_support</span>Enquiry</a>
    <a href="#contact" class="flex items-center gap-2 py-2"><span class="ms text-lg" aria-hidden="true">mail</span>Contact</a>
  </div>
</header>



<!-- Get in touch: bottom-left corner -->
<div class="touch" id="touch">
  <div id="touch-panel" class="touch-panel anim-in" role="dialog" aria-label="Get in touch" hidden>
    <div class="mb-3 flex items-center justify-between">
      <p class="font-display text-lg font-bold text-ink">Get in touch</p>
      <button type="button" id="touch-close" class="flex h-8 w-8 items-center justify-center rounded-full text-gray-500 hover:bg-mist hover:text-violet" aria-label="Close"><span class="ms " aria-hidden="true">close</span></button>
    </div>
    <div class="space-y-1">
      <a href="mailto:sutanshushekhar@gmail.com" class="touch-item"><span class="dot bg-coral"><span class="ms " aria-hidden="true">mail</span></span><span><span class="block text-sm font-semibold">Email</span><span class="block text-xs text-gray-500">sutanshushekhar@gmail.com</span></span></a>
      <a href="tel:+917654133893" class="touch-item"><span class="dot bg-mint"><span class="ms " aria-hidden="true">call</span></span><span><span class="block text-sm font-semibold">Call</span><span class="block text-xs text-gray-500">+91 76541 33893</span></span></a>
      <a href="https://wa.me/917654133893" class="touch-item" target="_blank" rel="noopener"><span class="dot bg-white ring-1 ring-gray-200"><i class="fab fa-whatsapp text-2xl text-[#25D366]"></i></span><span><span class="block text-sm font-semibold">WhatsApp</span><span class="block text-xs text-gray-500">+91 76541 33893</span></span></a>
      <a href="#enquiry" class="touch-item"><span class="dot bg-violet"><span class="ms " aria-hidden="true">contact_support</span></span><span><span class="block text-sm font-semibold">Send an enquiry</span><span class="block text-xs text-gray-500">Quick or detailed form</span></span></a>
      <a href="#contact" class="touch-item"><span class="dot bg-cyan"><span class="ms " aria-hidden="true">location_on</span></span><span><span class="block text-sm font-semibold">Contact details</span><span class="block text-xs text-gray-500">Bhopal, Madhya Pradesh</span></span></a>
    </div>
    <div class="mt-4 border-t border-violet/10 pt-4">
      <p class="mb-3 text-center text-xs font-medium text-gray-500">Find me on</p>
      <div class="flex flex-wrap items-center justify-center gap-3">
        <a href="https://wa.me/917654133893" target="_blank" rel="noopener" aria-label="WhatsApp" title="WhatsApp" class="brand-ico"><i class="fab fa-whatsapp text-[#25D366]"></i></a>
        <a href="https://www.linkedin.com/in/sutanshushekhar" target="_blank" rel="noopener" aria-label="LinkedIn" title="LinkedIn" class="brand-ico"><i class="fab fa-linkedin text-[#0A66C2]"></i></a>
        <a href="https://github.com/Sutanshu2006" target="_blank" rel="noopener" aria-label="GitHub" title="GitHub" class="brand-ico"><i class="fab fa-github text-[#181717]"></i></a>
        <a href="https://www.instagram.com/YOUR_USERNAME" target="_blank" rel="noopener" aria-label="Instagram" title="Instagram" class="brand-ico"><svg class="ico" aria-hidden="true"><use href="#i-instagram"/></svg></a>
        <a href="https://www.facebook.com/YOUR_USERNAME" target="_blank" rel="noopener" aria-label="Facebook" title="Facebook" class="brand-ico"><svg class="ico text-[#1877F2]" aria-hidden="true"><use href="#i-facebook"/></svg></a>
        <a href="https://x.com/YOUR_USERNAME" target="_blank" rel="noopener" aria-label="X (Twitter)" title="X (Twitter)" class="brand-ico"><svg class="ico text-[#111827]" aria-hidden="true"><use href="#i-x"/></svg></a>
        <a href="https://www.youtube.com/@YOUR_USERNAME" target="_blank" rel="noopener" aria-label="YouTube" title="YouTube" class="brand-ico"><svg class="ico text-[#FF0000]" aria-hidden="true"><use href="#i-youtube"/></svg></a>
        <a href="https://t.me/YOUR_USERNAME" target="_blank" rel="noopener" aria-label="Telegram" title="Telegram" class="brand-ico"><svg class="ico text-[#26A5E4]" aria-hidden="true"><use href="#i-telegram"/></svg></a>
      </div>
    </div>
  </div>
  <button type="button" id="touch-fab" class="touch-fab" aria-expanded="false" aria-controls="touch-panel"><span class="ms text-xl" aria-hidden="true">forum</span><span>Get in touch</span></button>
</div>

<button type="button" id="to-top" aria-label="Back to top" hidden><span class="ms " aria-hidden="true">arrow_upward</span></button>

<!-- Hero -->
<section id="home" class="hero-bg text-white pt-32 pb-24 overflow-hidden">
  <span class="ms float-ico" style="top:14%;left:5%;animation-delay:0s;animation-duration:7s" aria-hidden="true">memory</span><span class="ms float-ico" style="top:68%;left:38%;animation-delay:1.2s;animation-duration:9s" aria-hidden="true">terminal</span><span class="ms float-ico" style="top:10%;right:38%;animation-delay:0.6s;animation-duration:8s" aria-hidden="true">developer_board</span><span class="ms float-ico" style="bottom:10%;right:6%;animation-delay:2s;animation-duration:10s" aria-hidden="true">data_object</span><span class="ms float-ico" style="top:52%;left:2%;animation-delay:1.6s;animation-duration:8s" aria-hidden="true">precision_manufacturing</span><span class="ms float-ico" style="top:8%;right:4%;animation-delay:0.3s;animation-duration:9s" aria-hidden="true">bar_chart</span>
  <div class="container mx-auto px-6">
    <div class="flex flex-col-reverse md:flex-row items-center gap-14">
      <div class="md:w-1/2 rise">
        <span class="inline-flex items-center gap-2 rounded-full bg-white/10 border border-white/20 px-4 py-1.5 text-sm text-indigo-100">
          <span class="ms text-base text-mint" aria-hidden="true">work</span> Open to entry-level roles
        </span>
        <h1 class="mt-6 text-5xl md:text-6xl font-extrabold leading-tight">Hi, I'm <span class="grad-text">Sutanshu Shekhar</span></h1>
        <h2 class="mt-3 text-2xl md:text-3xl font-semibold text-indigo-100" aria-label="B.Tech CSE (AI and ML) engineering student"><span class="mono text-cyan">&gt;</span> <span id="typed">AI &amp; ML Engineering Student</span><span class="caret" aria-hidden="true"></span></h2>
        <p class="mt-6 text-lg text-indigo-100/90 max-w-xl">Final-year B.Tech student who turns data into predictions and products. I build machine learning models, data analysis dashboards and clean web interfaces.</p>
        <div class="mt-9 flex flex-wrap gap-4">
          <a href="#projects" class="inline-flex items-center gap-2 rounded-full bg-white text-violet px-7 py-3 font-semibold hover:bg-indigo-50 transition"><span class="ms " aria-hidden="true">rocket_launch</span>View my projects</a>
          <a href="Sutanshu_Shekhar_Resume.pdf" download class="inline-flex items-center gap-2 rounded-full bg-gradient-to-r from-coral to-amber px-7 py-3 font-semibold text-white hover:opacity-90 transition"><span class="ms " aria-hidden="true">download</span>Download resume</a>
          <a href="#contact" class="inline-flex items-center gap-2 rounded-full border-2 border-white/60 px-7 py-3 font-semibold hover:bg-white hover:text-violet transition"><span class="ms " aria-hidden="true">chat</span>Contact me</a>
        </div>
      </div>

      <!-- Framed photo -->
      <div class="md:w-1/2 flex justify-center rise" style="animation-delay:.15s">
        <div class="relative photo-wrap">
          <div class="absolute -inset-4 rounded-full bg-gradient-to-br from-cyan/50 to-coral/50 blur-2xl"></div>
          <div class="absolute -right-4 -bottom-4 h-full w-full rounded-full border-2 border-dashed border-cyan/80"></div>
          <div class="relative photo-ring p-[6px] rounded-full">
            <div class="bg-ink p-3 rounded-full">
              <img src="data:image/jpeg;base64,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" alt="Portrait of Sutanshu Shekhar in a blazer and striped tie" class="w-64 sm:w-72 md:w-80 aspect-square object-cover object-[50%_15%] rounded-full">
            </div>
          </div>
          <div class="absolute -left-6 top-10 badge-float rounded-2xl bg-white text-ink px-4 py-3 shadow-xl">
            <p class="flex items-center gap-1 text-xs text-gray-500"><span class="ms text-sm" aria-hidden="true">school</span>Degree</p>
            <p class="font-display font-bold text-sm">B.Tech CSE (AI &amp; ML)</p>
          </div>
          <div class="absolute -right-4 -top-4 badge-float rounded-2xl bg-amber text-ink px-4 py-3 shadow-xl">
            <p class="flex items-center gap-1 text-xs"><span class="ms text-sm" aria-hidden="true">grade</span>CGPA</p>
            <p class="font-display font-bold text-lg leading-none">7.95</p>
          </div>
          <div class="absolute -left-4 -bottom-5 badge-float rounded-2xl bg-violet text-white px-4 py-3 shadow-xl">
            <p class="font-display font-bold text-sm"><i class="fab fa-python mr-2"></i>Python · ML · Power BI</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Stats -->
<section class="-mt-10 relative z-10">
  <div class="container mx-auto px-6">
    <div class="grid grid-cols-2 md:grid-cols-4 gap-4 rounded-3xl bg-white p-6 shadow-xl">
      <div class="text-center hover-pop"><span class="ms text-3xl text-violet" aria-hidden="true">folder_special</span><p class="font-display text-3xl font-extrabold text-violet">5</p><p class="text-sm text-gray-600">Projects built</p></div>
      <div class="text-center hover-pop"><span class="ms text-3xl text-cyan" aria-hidden="true">workspace_premium</span><p class="font-display text-3xl font-extrabold text-cyan">11</p><p class="text-sm text-gray-600">Certifications</p></div>
      <div class="text-center hover-pop"><span class="ms text-3xl text-coral" aria-hidden="true">grade</span><p class="font-display text-3xl font-extrabold text-coral">7.95</p><p class="text-sm text-gray-600">Current CGPA</p></div>
      <div class="text-center hover-pop"><span class="ms text-3xl text-amber" aria-hidden="true">code</span><p class="font-display text-3xl font-extrabold text-amber">4</p><p class="text-sm text-gray-600">Languages: C, C++, Python, SQL</p></div>
    </div>
  </div>
</section>

<!-- About -->
<section id="about" class="py-24 band-about">
  <div class="container mx-auto px-6">
    <div class="grid lg:grid-cols-2 gap-14 items-center">
      <div>
        <h2 class="section-title text-4xl font-bold text-ink"><span class="title-icon"><span class="ms " aria-hidden="true">person</span></span><span class="kicker">// 01 · about()</span>About me</h2>
        <p class="mt-8 text-gray-700 leading-relaxed">I'm a final-year B.Tech student in Computer Science &amp; Engineering with a specialisation in AI &amp; ML at Jagran Lakecity University, Bhopal. I like problems where data can point to a decision, such as spotting risky road locations, flagging phishing emails or detecting abnormal heart rhythms from sensor signals.</p>
        <p class="mt-4 text-gray-700 leading-relaxed">I work with Python, NumPy, Pandas, Scikit-learn and TensorFlow/Keras for modelling, Power BI and MySQL for analytics, and HTML, CSS and JavaScript for web interfaces. I'm currently exploring agentic AI, RAG and MCP.</p>
        <p class="mt-4 text-gray-700 leading-relaxed">I'm looking for an entry-level role where I can apply these skills to real-world problems and grow with an innovative technology team.</p>
        <div class="mt-8 grid grid-cols-1 sm:grid-cols-2 gap-4 text-sm">
          <p class="hover-row flex items-center gap-2"><span class="ms text-xl text-violet" aria-hidden="true">person</span><span><span class="font-semibold text-violet">Name:</span> Sutanshu Shekhar</span></p>
          <p class="hover-row flex items-center gap-2"><span class="ms text-xl text-violet" aria-hidden="true">location_on</span><span><span class="font-semibold text-violet">Location:</span> Bhopal, Madhya Pradesh</span></p>
          <p class="hover-row flex items-center gap-2"><span class="ms text-xl text-violet" aria-hidden="true">mail</span><span><span class="font-semibold text-violet">Email:</span> sutanshushekhar@gmail.com</span></p>
          <p class="hover-row flex items-center gap-2"><span class="ms text-xl text-violet" aria-hidden="true">call</span><span><span class="font-semibold text-violet">Phone:</span> +91 76541 33893</span></p>
        </div>
</div>
      <div class="grid sm:grid-cols-2 gap-5">
        <div class="term sm:col-span-2">
          <div class="term-bar"><i style="background:#f87171"></i><i style="background:#fbbf24"></i><i style="background:#4ade80"></i><span class="ml-3">engineer.json</span></div>
<pre>{
  <span class="k">"name"</span>: <span class="s">"Sutanshu Shekhar"</span>,
  <span class="k">"degree"</span>: <span class="s">"B.Tech CSE (AI &amp; ML)"</span>,
  <span class="k">"university"</span>: <span class="s">"Jagran Lakecity University"</span>,
  <span class="k">"cgpa"</span>: <span class="n">7.95</span>,
  <span class="k">"focus"</span>: [<span class="s">"Machine Learning"</span>, <span class="s">"Data Analytics"</span>, <span class="s">"Web"</span>],
  <span class="k">"learning"</span>: [<span class="s">"Agentic AI"</span>, <span class="s">"RAG"</span>, <span class="s">"MCP"</span>],
  <span class="k">"openToWork"</span>: <span class="b">true</span>
}</pre>
        </div>
        
        <div class="card rounded-2xl bg-white p-6 border-t-4 border-violet"><span class="ms text-4xl text-violet" aria-hidden="true">psychology</span><h3 class="mt-4 font-bold text-lg">Machine learning</h3><p class="mt-1 text-sm text-gray-600">Classification, prediction and deep learning models, from feature engineering to evaluation.</p></div>
        <div class="card rounded-2xl bg-white p-6 border-t-4 border-cyan"><span class="ms text-4xl text-cyan" aria-hidden="true">insights</span><h3 class="mt-4 font-bold text-lg">Data analytics</h3><p class="mt-1 text-sm text-gray-600">Exploratory analysis, visualisation and Power BI dashboards that explain the data.</p></div>
        <div class="card rounded-2xl bg-white p-6 border-t-4 border-coral"><span class="ms text-4xl text-coral" aria-hidden="true">web</span><h3 class="mt-4 font-bold text-lg">Web development</h3><p class="mt-1 text-sm text-gray-600">Responsive interfaces with HTML, CSS, JavaScript, Tailwind CSS and Bootstrap.</p></div>
        <div class="card rounded-2xl bg-white p-6 border-t-4 border-amber"><span class="ms text-4xl text-amber" aria-hidden="true">smart_toy</span><h3 class="mt-4 font-bold text-lg">Agentic AI</h3><p class="mt-1 text-sm text-gray-600">Learning RAG and MCP to build assistants that use tools and data.</p></div>
      </div>
    </div>
  </div>
</section>

<!-- Skills -->
<section id="skills" class="py-24 band-a">
  <div class="container mx-auto px-6">
    <h2 class="section-title center text-4xl font-bold text-ink text-center"><span class="title-icon"><span class="ms " aria-hidden="true">bolt</span></span><span class="kicker">// 02 · skills[]</span>Skills</h2>
    <p class="mt-6 text-center text-gray-600 max-w-2xl mx-auto">The languages, libraries and tools I use day to day.</p>
    <div class="mt-14 grid md:grid-cols-2 gap-8">
      <div class="card rounded-2xl p-8 bg-gradient-to-br from-violet/10 to-white border border-violet/20">
        <h3 class="flex items-center gap-3 text-xl font-bold"><span class="h-10 w-10 rounded-xl bg-violet text-white flex items-center justify-center"><span class="ms " aria-hidden="true">code</span></span>Programming languages</h3>
        <div class="mt-6 flex flex-wrap gap-2">
          <span class="rounded-full bg-violet text-white px-4 py-1.5 text-sm">Python</span>
          <span class="rounded-full bg-violet text-white px-4 py-1.5 text-sm">C</span>
          <span class="rounded-full bg-violet text-white px-4 py-1.5 text-sm">C++</span>
          <span class="rounded-full bg-violet text-white px-4 py-1.5 text-sm">SQL</span>
        </div>
      </div>
      <div class="card rounded-2xl p-8 bg-gradient-to-br from-coral/10 to-white border border-coral/20">
        <h3 class="flex items-center gap-3 text-xl font-bold"><span class="h-10 w-10 rounded-xl bg-coral text-white flex items-center justify-center"><span class="ms " aria-hidden="true">psychology</span></span>AI / machine learning</h3>
        <div class="mt-6 flex flex-wrap gap-2">
          <span class="rounded-full bg-coral text-white px-4 py-1.5 text-sm">NumPy</span>
          <span class="rounded-full bg-coral text-white px-4 py-1.5 text-sm">Pandas</span>
          <span class="rounded-full bg-coral text-white px-4 py-1.5 text-sm">Scikit-learn</span>
          <span class="rounded-full bg-coral text-white px-4 py-1.5 text-sm">TensorFlow / Keras</span>
          <span class="rounded-full bg-coral text-white px-4 py-1.5 text-sm">Seaborn</span>
          <span class="rounded-full bg-coral text-white px-4 py-1.5 text-sm">RAG</span>
          <span class="rounded-full bg-coral text-white px-4 py-1.5 text-sm">MCP</span>
          <span class="rounded-full bg-coral text-white px-4 py-1.5 text-sm">Agentic AI</span>
          <span class="rounded-full bg-coral text-white px-4 py-1.5 text-sm">Data analytics</span>
        </div>
      </div>
      <div class="card rounded-2xl p-8 bg-gradient-to-br from-cyan/10 to-white border border-cyan/20">
        <h3 class="flex items-center gap-3 text-xl font-bold"><span class="h-10 w-10 rounded-xl bg-cyan text-white flex items-center justify-center"><span class="ms " aria-hidden="true">web</span></span>Frontend</h3>
        <div class="mt-6 flex flex-wrap gap-2">
          <span class="rounded-full bg-cyan text-white px-4 py-1.5 text-sm">HTML</span>
          <span class="rounded-full bg-cyan text-white px-4 py-1.5 text-sm">CSS</span>
          <span class="rounded-full bg-cyan text-white px-4 py-1.5 text-sm">JavaScript</span>
          <span class="rounded-full bg-cyan text-white px-4 py-1.5 text-sm">Tailwind CSS</span>
          <span class="rounded-full bg-cyan text-white px-4 py-1.5 text-sm">Bootstrap</span>
        </div>
      </div>
      <div class="card rounded-2xl p-8 bg-gradient-to-br from-amber/15 to-white border border-amber/30">
        <h3 class="flex items-center gap-3 text-xl font-bold"><span class="h-10 w-10 rounded-xl bg-amber text-white flex items-center justify-center"><span class="ms " aria-hidden="true">database</span></span>Database, BI &amp; tools</h3>
        <div class="mt-6 flex flex-wrap gap-2">
          <span class="rounded-full bg-amber text-ink px-4 py-1.5 text-sm">Power BI</span>
          <span class="rounded-full bg-amber text-ink px-4 py-1.5 text-sm">MySQL</span>
          <span class="rounded-full bg-amber text-ink px-4 py-1.5 text-sm">Database design</span>
          <span class="rounded-full bg-amber text-ink px-4 py-1.5 text-sm">Git &amp; GitHub</span>
          <span class="rounded-full bg-amber text-ink px-4 py-1.5 text-sm">VS Code</span>
          <span class="rounded-full bg-amber text-ink px-4 py-1.5 text-sm">Jupyter Notebook</span>
          <span class="rounded-full bg-amber text-ink px-4 py-1.5 text-sm">Google Colab</span>
        </div>
      </div>
    </div>
    <div class="learning mt-10">
      <span class="pulse-dot" aria-hidden="true"></span>
      <span class="mono text-sm text-cyan">$ currently_learning</span>
      <span class="pill">Agentic AI</span><span class="pill">RAG</span><span class="pill">MCP</span><span class="pill">Power BI</span><span class="pill">Data structures &amp; algorithms</span>
    </div>
</div>
</section>

<!-- Projects -->
<section id="projects" class="py-24 band-d">
  <div class="container mx-auto px-6">
    <h2 class="section-title center text-4xl font-bold text-ink text-center"><span class="title-icon"><span class="ms " aria-hidden="true">rocket_launch</span></span><span class="kicker">// 03 · projects()</span>Projects</h2>
    <p class="mt-6 text-center text-gray-600 max-w-2xl mx-auto">From web apps to machine learning systems, each project targets a real problem.</p>
    <div class="mt-14 grid md:grid-cols-2 lg:grid-cols-3 gap-8">

      <article class="card group rounded-2xl bg-white overflow-hidden shadow-md">
        <div class="proj-media relative h-44 overflow-hidden bg-gradient-to-br from-cyan to-blue-600">
          <div class="absolute inset-0 flex items-center justify-center"><span class="ms text-6xl text-white/90" aria-hidden="true">partly_cloudy_day</span></div>
          <img src="images/weather-web.jpg" alt="Weather Web project screenshot" loading="lazy" class="proj-img absolute inset-0 h-full w-full object-cover" onerror="this.style.display='none'">
          <span class="prj-tag">PRJ-01</span>
          <label class="upload-btn absolute bottom-2 right-2 cursor-pointer rounded-full bg-ink/80 px-3 py-1.5 text-xs font-medium text-white opacity-100 md:opacity-0 group-hover:opacity-100"><span class="ms text-sm mr-1" aria-hidden="true">photo_camera</span>Change image<input type="file" accept="image/*" class="proj-upload sr-only"></label>
        </div>
        <div class="p-6">
          <p class="flex items-center gap-1 text-xs font-medium text-cyan"><span class="ms text-sm" aria-hidden="true">calendar_month</span>Feb 2025 – May 2025</p>
          <h3 class="mt-1 text-xl font-bold">Weather Web</h3>
          <p class="mt-3 text-sm text-gray-600">A responsive weather app that fetches real-time data from a public weather API and shows current conditions and multi-day forecasts, with a focus on clean UI and API integration.</p>
          <div class="mt-4 flex flex-wrap gap-2 text-xs">
            <span class="rounded-full bg-cyan/15 text-cyan-800 px-3 py-1">HTML</span><span class="rounded-full bg-cyan/15 text-cyan-800 px-3 py-1">CSS</span><span class="rounded-full bg-cyan/15 text-cyan-800 px-3 py-1">JavaScript</span>
          </div>
        </div>
      </article>

      <article class="card group rounded-2xl bg-white overflow-hidden shadow-md">
        <div class="proj-media relative h-44 overflow-hidden bg-gradient-to-br from-amber to-coral">
          <div class="absolute inset-0 flex items-center justify-center"><span class="ms text-6xl text-white/90" aria-hidden="true">car_crash</span></div>
          <img src="images/traffic-eda.jpg" alt="Traffic accident analysis chart" loading="lazy" class="proj-img absolute inset-0 h-full w-full object-cover" onerror="this.style.display='none'">
          <span class="prj-tag">PRJ-02</span>
          <label class="upload-btn absolute bottom-2 right-2 cursor-pointer rounded-full bg-ink/80 px-3 py-1.5 text-xs font-medium text-white opacity-100 md:opacity-0 group-hover:opacity-100"><span class="ms text-sm mr-1" aria-hidden="true">photo_camera</span>Change image<input type="file" accept="image/*" class="proj-upload sr-only"></label>
        </div>
        <div class="p-6">
          <p class="flex items-center gap-1 text-xs font-medium text-amber"><span class="ms text-sm" aria-hidden="true">calendar_month</span>Oct 2025 – Dec 2025</p>
          <h3 class="mt-1 text-xl font-bold">Traffic Accident Data EDA</h3>
          <p class="mt-3 text-sm text-gray-600">Exploratory analysis of a traffic accident dataset to find accident patterns, high-risk locations and contributing factors, with visualisations that lead to road-safety insights.</p>
          <div class="mt-4 flex flex-wrap gap-2 text-xs">
            <span class="rounded-full bg-amber/20 text-amber-800 px-3 py-1">Python</span><span class="rounded-full bg-amber/20 text-amber-800 px-3 py-1">Pandas</span><span class="rounded-full bg-amber/20 text-amber-800 px-3 py-1">NumPy</span><span class="rounded-full bg-amber/20 text-amber-800 px-3 py-1">Matplotlib</span><span class="rounded-full bg-amber/20 text-amber-800 px-3 py-1">Seaborn</span>
          </div>
        </div>
      </article>

      <article class="card group rounded-2xl bg-white overflow-hidden shadow-md">
        <div class="proj-media relative h-44 overflow-hidden bg-gradient-to-br from-coral to-pink-600">
          <div class="absolute inset-0 flex items-center justify-center"><span class="ms text-6xl text-white/90" aria-hidden="true">monitor_heart</span></div>
          <img src="images/cardiac-sensor.jpg" alt="Wearable cardiac sensor analysis" loading="lazy" class="proj-img absolute inset-0 h-full w-full object-cover" onerror="this.style.display='none'">
          <span class="prj-tag">PRJ-03</span>
          <label class="upload-btn absolute bottom-2 right-2 cursor-pointer rounded-full bg-ink/80 px-3 py-1.5 text-xs font-medium text-white opacity-100 md:opacity-0 group-hover:opacity-100"><span class="ms text-sm mr-1" aria-hidden="true">photo_camera</span>Change image<input type="file" accept="image/*" class="proj-upload sr-only"></label>
        </div>
        <div class="p-6">
          <p class="flex items-center gap-1 text-xs font-medium text-coral"><span class="ms text-sm" aria-hidden="true">calendar_month</span>May 2026 – Jul 2026</p>
          <h3 class="mt-1 text-xl font-bold">Wearable Sensor Analysis for Real-Time Cardiac Events</h3>
          <p class="mt-3 text-sm text-gray-600">Signal processing and machine learning on wearable sensor data to detect abnormal cardiac patterns in real time, with classification models built and evaluated for early warning.</p>
          <div class="mt-4 flex flex-wrap gap-2 text-xs">
            <span class="rounded-full bg-coral/15 text-rose-800 px-3 py-1">Python</span><span class="rounded-full bg-coral/15 text-rose-800 px-3 py-1">NumPy</span><span class="rounded-full bg-coral/15 text-rose-800 px-3 py-1">Pandas</span><span class="rounded-full bg-coral/15 text-rose-800 px-3 py-1">Scikit-learn</span>
          </div>
        </div>
      </article>

      <article class="card group rounded-2xl bg-white overflow-hidden shadow-md">
        <div class="proj-media relative h-44 overflow-hidden bg-gradient-to-br from-violet to-indigo-600">
          <div class="absolute inset-0 flex items-center justify-center"><span class="ms text-6xl text-white/90" aria-hidden="true">security</span></div>
          <img src="images/phishing-detection.jpg" alt="Phishing email detection system" loading="lazy" class="proj-img absolute inset-0 h-full w-full object-cover" onerror="this.style.display='none'">
          <span class="prj-tag">PRJ-04</span>
          <label class="upload-btn absolute bottom-2 right-2 cursor-pointer rounded-full bg-ink/80 px-3 py-1.5 text-xs font-medium text-white opacity-100 md:opacity-0 group-hover:opacity-100"><span class="ms text-sm mr-1" aria-hidden="true">photo_camera</span>Change image<input type="file" accept="image/*" class="proj-upload sr-only"></label>
        </div>
        <div class="p-6">
          <p class="flex items-center gap-1 text-xs font-medium text-violet"><span class="ms text-sm" aria-hidden="true">calendar_month</span>Dec 2026 – Feb 2027</p>
          <h3 class="mt-1 text-xl font-bold">AI-Based Phishing Email Detection</h3>
          <p class="mt-3 text-sm text-gray-600">A machine learning system that classifies phishing emails using NLP on email content and metadata, comparing several classification models to improve detection accuracy.</p>
          <div class="mt-4 flex flex-wrap gap-2 text-xs">
            <span class="rounded-full bg-violet/15 text-violet px-3 py-1">Python</span><span class="rounded-full bg-violet/15 text-violet px-3 py-1">Scikit-learn</span><span class="rounded-full bg-violet/15 text-violet px-3 py-1">NLTK</span>
          </div>
        </div>
      </article>

      <article class="card group rounded-2xl bg-white overflow-hidden shadow-md md:col-span-2 lg:col-span-2">
        <div class="md:flex">
          <div class="proj-media relative md:w-64 h-44 md:h-auto overflow-hidden bg-gradient-to-br from-mint to-teal-600">
          <div class="absolute inset-0 flex items-center justify-center"><span class="ms text-6xl text-white/90" aria-hidden="true">medication</span></div>
          <img src="images/pharmacy-cost.jpg" alt="Pharmacy cost prediction model" loading="lazy" class="proj-img absolute inset-0 h-full w-full object-cover" onerror="this.style.display='none'">
          <span class="prj-tag">PRJ-05</span>
          <label class="upload-btn absolute bottom-2 right-2 cursor-pointer rounded-full bg-ink/80 px-3 py-1.5 text-xs font-medium text-white opacity-100 md:opacity-0 group-hover:opacity-100"><span class="ms text-sm mr-1" aria-hidden="true">photo_camera</span>Change image<input type="file" accept="image/*" class="proj-upload sr-only"></label>
        </div>
          <div class="p-6 flex-1">
            <p class="flex items-center gap-1 text-xs font-medium text-mint"><span class="ms text-sm" aria-hidden="true">calendar_month</span>Jul 2027 – Sep 2027</p>
            <h3 class="mt-1 text-xl font-bold">Scalable Hybrid Deep Models for Individual Pharmacy Cost Prediction</h3>
            <p class="mt-3 text-sm text-gray-600">A hybrid deep learning model that combines statistical and neural network approaches to predict individual pharmacy costs at scale, with a focus on feature engineering and model optimisation.</p>
            <div class="mt-4 flex flex-wrap gap-2 text-xs">
              <span class="rounded-full bg-mint/15 text-emerald-800 px-3 py-1">Python</span><span class="rounded-full bg-mint/15 text-emerald-800 px-3 py-1">TensorFlow / Keras</span><span class="rounded-full bg-mint/15 text-emerald-800 px-3 py-1">Pandas</span><span class="rounded-full bg-mint/15 text-emerald-800 px-3 py-1">Scikit-learn</span>
            </div>
          </div>
        </div>
      </article>
    </div>
  </div>
</section>

<!-- Experience & Education -->
<section id="education" class="py-24 band-b">
  <div class="container mx-auto px-6">
    <h2 class="section-title center text-4xl font-bold text-ink text-center"><span class="title-icon"><span class="ms " aria-hidden="true">school</span></span><span class="kicker">// 04 · education</span>Learning &amp; education</h2>
    <div class="mt-14 grid lg:grid-cols-2 gap-10">
      <div>
        <h3 class="flex items-center gap-3 text-2xl font-bold"><span class="h-10 w-10 rounded-xl bg-coral text-white flex items-center justify-center"><span class="ms " aria-hidden="true">engineering</span></span>Technical experience</h3>
        <ul class="mt-8 space-y-4 text-gray-700">
          <li class="flex gap-3"><span class="ms text-xl mt-0.5 text-coral" aria-hidden="true">check_circle</span>Building real-world problem-solving projects in Python.</li>
          <li class="flex gap-3"><span class="ms text-xl mt-0.5 text-violet" aria-hidden="true">check_circle</span>Designing applications with HTML, CSS and JavaScript.</li>
          <li class="flex gap-3"><span class="ms text-xl mt-0.5 text-cyan" aria-hidden="true">check_circle</span>Implementing machine learning models for prediction and classification.</li>
          <li class="flex gap-3"><span class="ms text-xl mt-0.5 text-amber" aria-hidden="true">check_circle</span>Practising data structures and algorithms to sharpen logic and coding skills.</li>
          <li class="flex gap-3"><span class="ms text-xl mt-0.5 text-mint" aria-hidden="true">check_circle</span>Using Git, VS Code and Jupyter Notebook for development and version control.</li>
          <li class="flex gap-3"><span class="ms text-xl mt-0.5 text-coral" aria-hidden="true">check_circle</span>Learning agentic AI and Power BI to work more efficiently.</li>
        </ul>
      </div>
      <div>
        <h3 class="flex items-center gap-3 text-2xl font-bold"><span class="h-10 w-10 rounded-xl bg-violet text-white flex items-center justify-center"><span class="ms " aria-hidden="true">school</span></span>Education</h3>
        <div class="mt-8 relative pl-8 border-l-4 border-violet/30">
          <span class="absolute -left-[10px] top-1 h-4 w-4 rounded-full bg-violet ring-4 ring-white"></span>
          <div class="card rounded-2xl bg-mist p-6">
            <div class="flex flex-wrap items-start justify-between gap-2">
              <div>
                <h4 class="text-xl font-bold">B.Tech in Computer Science &amp; Engineering (AI &amp; ML)</h4>
                <p class="text-gray-600">Jagran Lakecity University, Bhopal</p>
              </div>
              <span class="rounded-full bg-violet text-white px-3 py-1 text-sm">Aug 2023 – Present</span>
            </div>
            <p class="mt-4 inline-flex items-center gap-2 rounded-full bg-amber/20 px-4 py-1.5 text-sm font-semibold text-amber-800"><span class="ms text-base" aria-hidden="true">grade</span>CGPA 7.95</p>
          </div>
        </div>
      </div>
    </div>
</div>
</section>

<!-- Certifications -->
<section id="certifications" class="py-24 band-e">
  <div class="container mx-auto px-6">
    <h2 class="section-title center text-4xl font-bold text-ink text-center"><span class="title-icon"><span class="ms " aria-hidden="true">workspace_premium</span></span><span class="kicker">// 05 · certificates</span>Certifications &amp; achievements</h2>
    <div class="mt-14 grid md:grid-cols-2 lg:grid-cols-3 gap-5">
      <div class="card flex items-start gap-4 rounded-2xl bg-white p-5 border-l-4 border-violet"><span class="ms text-3xl text-violet" aria-hidden="true">bar_chart</span><div><p class="font-semibold">Mastering Power BI: Data Analysis and Dashboard Creation</p><p class="text-sm text-gray-600">PHN Technology, Skill India Digital Hub · Aug 2026</p></div></div>
      <div class="card flex items-start gap-4 rounded-2xl bg-white p-5 border-l-4 border-cyan"><span class="ms text-3xl text-cyan" aria-hidden="true">precision_manufacturing</span><div><p class="font-semibold">AI in Manufacturing</p><p class="text-sm text-gray-600">Microsoft, NSQF Level 4, Skill India / NCVET · Jun 2026</p></div></div>
      <div class="card flex items-start gap-4 rounded-2xl bg-white p-5 border-l-4 border-coral"><span class="ms text-3xl text-coral" aria-hidden="true">smart_toy</span><div><p class="font-semibold">Unlocking AI for Everyone (Beginner)</p><p class="text-sm text-gray-600">Microsoft, NSQF Level 2, Skill India / NCVET · Jun 2026</p></div></div>
      <div class="card flex items-start gap-4 rounded-2xl bg-white p-5 border-l-4 border-amber"><span class="ms text-3xl text-amber" aria-hidden="true">lightbulb</span><div><p class="font-semibold">Design Thinking for Innovation</p><p class="text-sm text-gray-600">University of Virginia, Coursera · Aug 2024</p></div></div>
      <div class="card flex items-start gap-4 rounded-2xl bg-white p-5 border-l-4 border-mint"><span class="ms text-3xl text-mint" aria-hidden="true">record_voice_over</span><div><p class="font-semibold">Dynamic Public Speaking (Specialization)</p><p class="text-sm text-gray-600">University of Washington, Coursera · May 2024</p></div></div>
      <div class="card flex items-start gap-4 rounded-2xl bg-white p-5 border-l-4 border-violet"><span class="ms text-3xl text-violet" aria-hidden="true">forum</span><div><p class="font-semibold">Communication in the 21st Century Workplace</p><p class="text-sm text-gray-600">University of California, Irvine, Coursera · Jan 2024</p></div></div>
      <div class="card flex items-start gap-4 rounded-2xl bg-white p-5 border-l-4 border-cyan"><span class="ms text-3xl text-cyan" aria-hidden="true">sports_esports</span><div><p class="font-semibold">Introduction to Basic Game Development using Scratch</p><p class="text-sm text-gray-600">Coursera · Nov 2023</p></div></div>
      <div class="card flex items-start gap-4 rounded-2xl bg-white p-5 border-l-4 border-coral"><span class="ms text-3xl text-coral" aria-hidden="true">translate</span><div><p class="font-semibold">Improve Your English Communication Skills (Specialization)</p><p class="text-sm text-gray-600">Georgia Institute of Technology, Coursera · Oct 2023</p></div></div>
      <div class="card flex items-start gap-4 rounded-2xl bg-white p-5 border-l-4 border-amber"><span class="ms text-3xl text-amber" aria-hidden="true">sports_esports</span><div><p class="font-semibold">Using Interfaces with C# in Unity</p><p class="text-sm text-gray-600">Coursera · Oct 2023</p></div></div>
      <div class="card flex items-start gap-4 rounded-2xl bg-white p-5 border-l-4 border-mint"><span class="ms text-3xl text-mint" aria-hidden="true">merge</span><div><p class="font-semibold">Using Collaborate for Version-Control in Unity</p><p class="text-sm text-gray-600">Coursera · Oct 2023</p></div></div>
      <div class="card flex items-start gap-4 rounded-2xl bg-white p-5 border-l-4 border-violet"><span class="ms text-3xl text-violet" aria-hidden="true">terminal</span><div><p class="font-semibold">Fundamentals of Computer Programming with C Language</p><p class="text-sm text-gray-600">Coursera · Oct 2023</p></div></div>
    </div>

    <h3 class="mt-16 text-2xl font-bold text-center">Achievements</h3>
    <div class="mt-8 grid md:grid-cols-2 gap-6 max-w-5xl mx-auto">
      <div class="card rounded-2xl bg-gradient-to-br from-ink to-violet text-white p-6">
        <span class="ms text-4xl text-cyan" aria-hidden="true">verified_user</span>
        <p class="mt-3 font-semibold">Quiz on Safe and Responsible Use of Artificial Intelligence</p>
        <p class="mt-1 text-sm text-indigo-100">Organised by the ISEA Project, MeitY, Govt. of India, with MyGov, for Safer Internet Day.</p>
      </div>
      <div class="card rounded-2xl bg-gradient-to-br from-coral to-amber text-white p-6">
        <span class="ms text-4xl" aria-hidden="true">emoji_events</span>
        <p class="mt-3 font-semibold">Quiz Competition for 8th Jan Aushadhi Diwas 2026</p>
        <p class="mt-1 text-sm text-white/90">Organised by the Pharmaceuticals &amp; Medical Devices Bureau of India (PMBI), Ministry of Chemicals &amp; Fertilizers, with MyGov.</p>
      </div>
    </div>
</div>
</section>

<!-- Enquiry -->
<section id="enquiry" class="py-24 band-f">
  <div class="container mx-auto px-6">
    <h2 class="section-title center text-4xl font-bold text-ink text-center"><span class="title-icon"><span class="ms " aria-hidden="true">contact_support</span></span><span class="kicker">// 06 · enquiry()</span>Send an enquiry</h2>
    <p class="mt-6 text-center text-gray-600 max-w-2xl mx-auto">Use the quick form for a short note, or switch to detailed to pick options such as enquiry type, contact method and best time.</p>
    <div class="mt-14 grid lg:grid-cols-5 gap-10 items-start">
      <div class="lg:col-span-2 rounded-3xl bg-gradient-to-br from-violet via-indigo-600 to-cyan p-8 text-white lg:sticky lg:top-24">
        <h3 class="text-2xl font-bold">How can I help?</h3>
        <p class="mt-3 text-indigo-100">Tap a topic to start a detailed enquiry.</p>
        <div class="mt-6 space-y-2"><button type="button" class="perk-btn" data-type="job"><span class="h-11 w-11 shrink-0 rounded-full bg-white/20 flex items-center justify-center"><span class="ms " aria-hidden="true">work</span></span><span><span class="block font-semibold">Jobs and internships</span><span class="block text-sm text-indigo-100">Entry-level roles in AI, ML and data analytics.</span></span></button><button type="button" class="perk-btn" data-type="project"><span class="h-11 w-11 shrink-0 rounded-full bg-white/20 flex items-center justify-center"><span class="ms " aria-hidden="true">handshake</span></span><span><span class="block font-semibold">Project collaboration</span><span class="block text-sm text-indigo-100">Machine learning, analysis or web projects.</span></span></button><button type="button" class="perk-btn" data-type="question"><span class="h-11 w-11 shrink-0 rounded-full bg-white/20 flex items-center justify-center"><span class="ms " aria-hidden="true">help</span></span><span><span class="block font-semibold">Questions about my work</span><span class="block text-sm text-indigo-100">Ask about any project, skill or certification.</span></span></button></div>
      </div>

      <form id="enquiry-form" class="lg:col-span-3 rounded-3xl bg-white p-6 sm:p-8 shadow-lg" novalidate>
        <div class="seg" role="group" aria-label="Enquiry mode">
          <button type="button" class="seg-btn is-on" data-mode="quick" aria-pressed="true"><span class="ms text-lg" aria-hidden="true">bolt</span>Quick enquiry</button>
          <button type="button" class="seg-btn" data-mode="detailed" aria-pressed="false"><span class="ms text-lg" aria-hidden="true">tune</span>Detailed enquiry</button>
        </div>

        <div id="detail-top" class="mt-6" hidden>
          <p class="enq-label"><span class="ms text-lg text-violet" aria-hidden="true">category</span>What is this about?</p>
          <div class="flex flex-wrap gap-2" role="radiogroup" aria-label="Enquiry type"><label class="chip"><input type="radio" name="enq-type" value="job" checked><span class="face"><span class="ms text-lg" aria-hidden="true">work</span>Job or internship</span></label><label class="chip"><input type="radio" name="enq-type" value="project"><span class="face"><span class="ms text-lg" aria-hidden="true">handshake</span>Project collaboration</span></label><label class="chip"><input type="radio" name="enq-type" value="question"><span class="face"><span class="ms text-lg" aria-hidden="true">help</span>Question about my work</span></label><label class="chip"><input type="radio" name="enq-type" value="other"><span class="face"><span class="ms text-lg" aria-hidden="true">more_horiz</span>Something else</span></label></div>
          <div id="dyn-fields" class="mt-5 grid sm:grid-cols-2 gap-5"></div>
        </div>

        <div class="mt-6 grid md:grid-cols-2 gap-5">
          <div><label for="enq-name" class="enq-label"><span class="ms text-lg text-violet" aria-hidden="true">person</span>Name</label><input type="text" id="enq-name" class="field" autocomplete="name" placeholder="Your full name"><p class="err" id="err-enq-name" hidden></p></div>
          <div><label for="enq-phone" class="enq-label"><span class="ms text-lg text-violet" aria-hidden="true">call</span>Contact no.</label><input type="tel" id="enq-phone" class="field" autocomplete="tel" inputmode="tel" placeholder="+91 00000 00000"><p class="err" id="err-enq-phone" hidden></p></div>
        </div>
        <div class="mt-5">
          <div><label for="enq-address" class="enq-label"><span class="ms text-lg text-violet" aria-hidden="true">location_on</span>Address</label><input type="text" id="enq-address" class="field" autocomplete="street-address" placeholder="Area, city, state"><p class="err" id="err-enq-address" hidden></p></div>
        </div>

        <div id="detail-contact" class="mt-5" hidden>
          <p class="enq-label"><span class="ms text-lg text-violet" aria-hidden="true">forum</span>How should I reach you?</p>
          <div class="flex flex-wrap gap-2" role="radiogroup" aria-label="Preferred contact method"><label class="chip"><input type="radio" name="enq-method" value="phone" checked><span class="face"><span class="ms text-lg" aria-hidden="true">call</span>Phone call</span></label><label class="chip"><input type="radio" name="enq-method" value="email"><span class="face"><span class="ms text-lg" aria-hidden="true">mail</span>Email</span></label><label class="chip"><input type="radio" name="enq-method" value="whatsapp"><span class="face"><i class="fab fa-whatsapp text-lg"></i>WhatsApp</span></label></div>
          <div class="mt-5 grid sm:grid-cols-2 gap-5">
            <div><label for="enq-time" class="enq-label"><span class="ms text-lg text-violet" aria-hidden="true">schedule</span>Best time to reach you</label><div class="select-wrap"><select id="enq-time" class="field"><option>Any time</option><option>Morning, 9 am to 12 pm</option><option>Afternoon, 12 pm to 5 pm</option><option>Evening, 5 pm to 9 pm</option></select><span class="ms select-caret" aria-hidden="true">expand_more</span></div></div>
            <div id="email-wrap" hidden><div><label for="enq-email" class="enq-label"><span class="ms text-lg text-violet" aria-hidden="true">mail</span>Your email</label><input type="email" id="enq-email" class="field" autocomplete="email" placeholder="you@example.com"><p class="err" id="err-enq-email" hidden></p></div></div>
          </div>
        </div>

        <div class="mt-5">
          <label for="enq-message" class="enq-label"><span class="ms text-lg text-violet" aria-hidden="true">chat</span>Message</label>
          <textarea id="enq-message" class="field" rows="5" maxlength="500" placeholder="Tell me what you need"></textarea>
          <div class="mt-2 flex items-start justify-between gap-3">
            <div id="hints" class="flex flex-wrap gap-2"></div>
            <p id="count" class="shrink-0 text-xs text-gray-500">0 / 500</p>
          </div>
          <p class="err" id="err-enq-message" hidden></p>
        </div>

        <div class="mt-6">
          <p class="enq-label"><span class="ms text-lg text-violet" aria-hidden="true">send</span>Send it via</p>
          <div class="flex flex-wrap gap-2" role="radiogroup" aria-label="Send enquiry via"><label class="chip"><input type="radio" name="enq-via" value="email" checked><span class="face"><span class="ms text-lg" aria-hidden="true">mail</span>Email</span></label><label class="chip"><input type="radio" name="enq-via" value="whatsapp"><span class="face"><i class="fab fa-whatsapp text-lg"></i>WhatsApp</span></label></div>
        </div>

        <button type="submit" class="mt-7 w-full rounded-full bg-gradient-to-r from-violet to-coral px-6 py-3 font-semibold text-white hover:opacity-90 transition flex items-center justify-center gap-2">
          <span id="send-icon-mail"><span class="ms " aria-hidden="true">send</span></span><i id="send-icon-wa" class="fab fa-whatsapp text-xl" hidden></i><span id="send-label">Send enquiry via Email</span>
        </button>
        <div class="mt-4 flex flex-wrap items-center justify-between gap-2">
          <p id="enquiry-status" class="text-sm text-gray-600" role="status" aria-live="polite"></p>
          <button type="button" id="enq-clear" class="text-sm font-medium text-violet hover:underline">Clear form</button>
        </div>
      </form>
    </div>
  </div>
</section>
<!-- Contact -->
<section id="contact" class="py-24 band-c">
  <div class="container mx-auto px-6">
    <h2 class="section-title center text-4xl font-bold text-ink text-center"><span class="title-icon"><span class="ms " aria-hidden="true">mail</span></span><span class="kicker">// 07 · contact</span>Get in touch</h2>
    <p class="mt-6 text-center text-gray-600 max-w-2xl mx-auto">Hiring for an entry-level AI, ML or data role, or have a project idea? Reach me by email, phone, GitHub or LinkedIn.</p>
    <div class="mt-14 max-w-2xl mx-auto">
      <div class="rounded-3xl bg-gradient-to-br from-ink to-violet p-8 text-white">
        <h3 class="text-xl font-bold">Contact information</h3>
        <div class="mt-8 space-y-6">
          <div class="flex gap-4"><span class="h-11 w-11 shrink-0 rounded-full bg-white/15 flex items-center justify-center"><span class="ms " aria-hidden="true">mail</span></span><div><p class="font-semibold">Email</p><a href="mailto:sutanshushekhar@gmail.com" class="text-indigo-100 hover:text-white break-all">sutanshushekhar@gmail.com</a></div></div>
          <div class="flex gap-4"><span class="h-11 w-11 shrink-0 rounded-full bg-white/15 flex items-center justify-center"><span class="ms " aria-hidden="true">call</span></span><div><p class="font-semibold">Phone</p><a href="tel:+917654133893" class="text-indigo-100 hover:text-white">+91 76541 33893</a></div></div>
          <div class="flex gap-4"><span class="h-11 w-11 shrink-0 rounded-full bg-white/15 flex items-center justify-center"><i class="fab fa-whatsapp text-xl"></i></span><div><p class="font-semibold">WhatsApp</p><a href="https://wa.me/917654133893" target="_blank" rel="noopener" class="text-indigo-100 hover:text-white">+91 76541 33893</a></div></div>
          <div class="flex gap-4"><span class="h-11 w-11 shrink-0 rounded-full bg-white/15 flex items-center justify-center"><span class="ms " aria-hidden="true">location_on</span></span><div><p class="font-semibold">Location</p><p class="text-indigo-100">Bhopal, Madhya Pradesh, India</p></div></div>
          <div class="flex gap-4"><span class="h-11 w-11 shrink-0 rounded-full bg-white/15 flex items-center justify-center"><i class="fab fa-github text-xl"></i></span><div><p class="font-semibold">GitHub</p><a href="https://github.com/Sutanshu2006" target="_blank" rel="noopener" class="text-indigo-100 hover:text-white break-all">github.com/Sutanshu2006</a></div></div>
          <div class="flex gap-4"><span class="h-11 w-11 shrink-0 rounded-full bg-white/15 flex items-center justify-center"><i class="fab fa-linkedin text-xl"></i></span><div><p class="font-semibold">LinkedIn</p><a href="https://www.linkedin.com/in/sutanshushekhar" target="_blank" rel="noopener" class="text-indigo-100 hover:text-white break-all">linkedin.com/in/sutanshushekhar</a></div></div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Footer -->
<footer class="bg-ink text-indigo-100 py-10">
  <div class="container mx-auto px-6 flex flex-col md:flex-row items-center justify-between gap-4 text-sm">
    <p class="font-display text-lg font-bold text-white">Sutanshu<span class="text-cyan">.</span></p>
    <p>&copy; <span id="year"></span> Sutanshu Shekhar. All rights reserved.</p>
  </div>
</footer>

<script>
  var toggle = document.getElementById('menu-toggle');
  var menu = document.getElementById('mobile-menu');
  toggle.addEventListener('click', function () {
    var open = menu.classList.toggle('hidden') === false;
    toggle.setAttribute('aria-expanded', open);
  });
  menu.querySelectorAll('a').forEach(function (a) {
    a.addEventListener('click', function () { menu.classList.add('hidden'); toggle.setAttribute('aria-expanded', 'false'); });
  });
  document.getElementById('year').textContent = new Date().getFullYear();

  document.querySelectorAll('.proj-upload').forEach(function (input) {
    input.addEventListener('change', function () {
      var file = input.files && input.files[0];
      if (!file) return;
      var img = input.closest('.proj-media').querySelector('.proj-img');
      var reader = new FileReader();
      reader.onload = function () { img.src = reader.result; img.style.display = 'block'; };
      reader.readAsDataURL(file);
    });
  });

  if (document.fonts && document.fonts.load) {
    document.fonts.load('24px "Material Symbols Rounded"').then(function (f) {
      if (f.length) document.documentElement.classList.add('icons-ready');
    });
  }


  (function () {
    var form = document.getElementById('enquiry-form');
    if (!form) return;
    var $ = function (id) { return document.getElementById(id); };
    var WA_NUMBER = '917654133893';
    var EMAIL = 'sutanshushekhar@gmail.com';
    var MAX = 500;

    var TYPES = {
      job: { label: 'Job or internship', ph: 'Tell me about the role and your team.',
        hints: ['I would like to discuss an opening.', 'Can we schedule an interview?', 'Please share your resume.'],
        fields: [
          { id: 'org', label: 'Company', icon: 'apartment', kind: 'text', ph: 'Company name' },
          { id: 'role', label: 'Role', icon: 'badge', kind: 'select', opts: ['AI / ML engineer', 'Data analyst', 'Web developer', 'Internship', 'Other'] }
        ] },
      project: { label: 'Project collaboration', ph: 'Describe the project and what you need.',
        hints: ['I have a project idea to discuss.', 'Can you build a prototype?', 'What would you need from me?'],
        fields: [
          { id: 'ptype', label: 'Project type', icon: 'category', kind: 'select', opts: ['Machine learning', 'Data analysis / Power BI', 'Web development', 'Other'] },
          { id: 'timeline', label: 'Timeline', icon: 'schedule', kind: 'select', opts: ['Under 1 month', '1 to 3 months', 'More than 3 months', 'Not sure yet'] }
        ] },
      question: { label: 'Question about my work', ph: 'What would you like to know?',
        hints: ['Can you explain one of your projects?', 'Which tools did you use?', 'How can I see the code?'],
        fields: [
          { id: 'topic', label: 'Topic', icon: 'help', kind: 'select', opts: ['Projects', 'Skills', 'Certifications', 'Education', 'Other'] }
        ] },
      other: { label: 'Something else', ph: 'How can I help?', hints: [], fields: [] }
    };
    var METHODS = { phone: 'Phone call', email: 'Email', whatsapp: 'WhatsApp' };

    var mode = 'quick';
    var reduceMotion = window.matchMedia && window.matchMedia('(prefers-reduced-motion: reduce)').matches;

    function checked(name) { var el = form.querySelector('input[name="' + name + '"]:checked'); return el ? el.value : ''; }
    function setChecked(name, value) { var el = form.querySelector('input[name="' + name + '"][value="' + value + '"]'); if (el) el.checked = true; }
    function el(tag, cls, html) { var e = document.createElement(tag); if (cls) e.className = cls; if (html) e.innerHTML = html; return e; }

    /* ---- Quick / detailed mode ---- */
    function setMode(m) {
      mode = m;
      form.querySelectorAll('.seg-btn').forEach(function (b) {
        var on = b.getAttribute('data-mode') === m;
        b.classList.toggle('is-on', on);
        b.setAttribute('aria-pressed', on ? 'true' : 'false');
      });
      var detailed = m === 'detailed';
      [$('detail-top'), $('detail-contact')].forEach(function (s) {
        var wasHidden = s.hidden;
        s.hidden = !detailed;
        if (detailed && wasHidden) { s.classList.remove('anim-in'); void s.offsetWidth; s.classList.add('anim-in'); }
      });
      renderType();
      toggleEmail();
    }

    /* ---- Enquiry type: dynamic extra fields + message hints ---- */
    function renderType() {
      var key = mode === 'detailed' ? checked('enq-type') : '';
      var cfg = TYPES[key];
      var box = $('dyn-fields');
      box.innerHTML = '';
      $('hints').innerHTML = '';
      $('enq-message').placeholder = cfg ? cfg.ph : 'Tell me what you need';
      if (!cfg) return;
      cfg.fields.forEach(function (f) {
        var wrap = el('div', 'anim-in');
        var label = el('label', 'enq-label', '<span class="ms text-lg text-violet" aria-hidden="true">' + f.icon + '</span>' + f.label);
        label.setAttribute('for', 'dyn-' + f.id);
        wrap.appendChild(label);
        if (f.kind === 'select') {
          var sw = el('div', 'select-wrap');
          var sel = el('select', 'field');
          sel.id = 'dyn-' + f.id;
          sel.setAttribute('data-label', f.label);
          sel.appendChild(new Option('Choose one', ''));
          f.opts.forEach(function (o) { sel.appendChild(new Option(o, o)); });
          sw.appendChild(sel);
          sw.appendChild(el('span', 'ms select-caret', 'expand_more'));
          wrap.appendChild(sw);
        } else {
          var inp = el('input', 'field');
          inp.type = 'text'; inp.id = 'dyn-' + f.id; inp.placeholder = f.ph || '';
          inp.setAttribute('data-label', f.label);
          wrap.appendChild(inp);
        }
        box.appendChild(wrap);
      });
      cfg.hints.forEach(function (h) {
        var b = el('button', 'hint-chip');
        b.type = 'button'; b.textContent = h;
        b.addEventListener('click', function () {
          var ta = $('enq-message');
          var next = (ta.value.trim() ? ta.value.trim() + ' ' : '') + h;
          ta.value = next.slice(0, MAX);
          updateCount(); clearErr('enq-message'); ta.focus();
        });
        $('hints').appendChild(b);
      });
    }

    /* ---- Preferred contact method: show email field only when needed ---- */
    function toggleEmail() {
      $('email-wrap').hidden = !(mode === 'detailed' && checked('enq-method') === 'email');
    }

    /* ---- Send-via option updates the button ---- */
    function updateVia() {
      var wa = checked('enq-via') === 'whatsapp';
      $('send-label').textContent = 'Send enquiry via ' + (wa ? 'WhatsApp' : 'Email');
      $('send-icon-mail').hidden = wa;
      $('send-icon-wa').hidden = !wa;
    }

    /* ---- Message counter ---- */
    function updateCount() {
      var n = $('enq-message').value.length;
      var c = $('count');
      c.textContent = n + ' / ' + MAX;
      c.style.color = n > MAX - 50 ? '#f43f5e' : '';
    }

    /* ---- Errors ---- */
    function showErr(id, msg) { var p = $('err-' + id); if (p) { p.textContent = msg; p.hidden = false; } $(id).setAttribute('aria-invalid', 'true'); }
    function clearErr(id) { var p = $('err-' + id); if (p) p.hidden = true; $(id).removeAttribute('aria-invalid'); }

    /* ---- Events ---- */
    form.querySelectorAll('.seg-btn').forEach(function (b) { b.addEventListener('click', function () { setMode(b.getAttribute('data-mode')); }); });
    form.querySelectorAll('input[name="enq-type"]').forEach(function (r) { r.addEventListener('change', renderType); });
    form.querySelectorAll('input[name="enq-method"]').forEach(function (r) { r.addEventListener('change', toggleEmail); });
    form.querySelectorAll('input[name="enq-via"]').forEach(function (r) { r.addEventListener('change', updateVia); });
    $('enq-message').addEventListener('input', function () { updateCount(); clearErr('enq-message'); });
    ['enq-name', 'enq-address', 'enq-email'].forEach(function (id) { $(id).addEventListener('input', function () { clearErr(id); }); });
    $('enq-phone').addEventListener('input', function (e) {
      e.target.value = e.target.value.replace(/[^0-9+\s-]/g, '');
      clearErr('enq-phone');
    });

    document.querySelectorAll('.perk-btn').forEach(function (b) {
      b.addEventListener('click', function () {
        setMode('detailed');
        setChecked('enq-type', b.getAttribute('data-type'));
        renderType();
        form.scrollIntoView({ behavior: reduceMotion ? 'auto' : 'smooth', block: 'start' });
        $('enq-name').focus({ preventScroll: true });
      });
    });

    $('enq-clear').addEventListener('click', function () {
      form.reset();
      ['enq-name', 'enq-phone', 'enq-address', 'enq-message', 'enq-email'].forEach(clearErr);
      $('enquiry-status').textContent = '';
      setMode(mode); updateVia(); updateCount();
    });

    /* ---- Submit ---- */
    form.addEventListener('submit', function (e) {
      e.preventDefault();
      var status = $('enquiry-status');
      var name = $('enq-name').value.trim();
      var phone = $('enq-phone').value.trim();
      var address = $('enq-address').value.trim();
      var message = $('enq-message').value.trim();
      var email = $('enq-email').value.trim();
      var method = checked('enq-method');
      var digits = phone.replace(/\D/g, '').length;
      var bad = [];

      ['enq-name', 'enq-phone', 'enq-address', 'enq-message', 'enq-email'].forEach(clearErr);
      if (name.length < 2) { showErr('enq-name', 'Enter your name.'); bad.push('enq-name'); }
      if (digits < 10 || digits > 13) { showErr('enq-phone', 'Enter a valid contact number, for example +91 76541 33893.'); bad.push('enq-phone'); }
      if (address.length < 3) { showErr('enq-address', 'Enter your address, for example the area and city.'); bad.push('enq-address'); }
      if (message.length < 10) { showErr('enq-message', 'Write at least 10 characters so I know how to help.'); bad.push('enq-message'); }
      if (mode === 'detailed' && method === 'email' && !/^[^@\s]+@[^@\s]+\.[^@\s]+$/.test(email)) { showErr('enq-email', 'Enter a valid email address.'); bad.push('enq-email'); }
      if (bad.length) {
        status.textContent = 'Check the highlighted fields and try again.';
        status.className = 'text-sm text-coral';
        $(bad[0]).focus();
        return;
      }

      var lines = [];
      if (mode === 'detailed') lines.push('Enquiry type: ' + TYPES[checked('enq-type')].label);
      lines.push('Name: ' + name, 'Contact no.: ' + phone, 'Address: ' + address);
      if (mode === 'detailed') {
        lines.push('Preferred contact: ' + METHODS[method]);
        if (method === 'email') lines.push('Email: ' + email);
        lines.push('Best time to reach: ' + $('enq-time').value);
        $('dyn-fields').querySelectorAll('.field').forEach(function (f) {
          if (f.value.trim()) lines.push(f.getAttribute('data-label') + ': ' + f.value.trim());
        });
      }
      lines.push('', 'Message:', message);
      var body = lines.join('\n');
      var subject = 'Portfolio enquiry from ' + name;

      if (checked('enq-via') === 'whatsapp') {
        var a = document.createElement('a');
        a.href = 'https://wa.me/' + WA_NUMBER + '?text=' + encodeURIComponent('Portfolio enquiry\n\n' + body);
        a.target = '_blank'; a.rel = 'noopener';
        document.body.appendChild(a); a.click(); a.remove();
        status.textContent = 'WhatsApp is opening with your enquiry filled in. Press send there to finish.';
      } else {
        window.location.href = 'mailto:' + EMAIL + '?subject=' + encodeURIComponent(subject) + '&body=' + encodeURIComponent(body);
        status.textContent = 'Your email app is opening with your enquiry filled in. Press send there to finish.';
      }
      status.className = 'text-sm text-mint';
    });

    setMode('quick'); updateVia(); updateCount();
  })();

  (function () {
    var box = document.getElementById('touch');
    var fab = document.getElementById('touch-fab');
    var panel = document.getElementById('touch-panel');
    if (!box || !fab || !panel) return;
    function setOpen(open) {
      panel.hidden = !open;
      fab.setAttribute('aria-expanded', open ? 'true' : 'false');
    }
    fab.addEventListener('click', function () { setOpen(panel.hidden); });
    document.getElementById('touch-close').addEventListener('click', function () { setOpen(false); fab.focus(); });
    panel.querySelectorAll('a').forEach(function (a) { a.addEventListener('click', function () { setOpen(false); }); });
    document.addEventListener('click', function (e) { if (!box.contains(e.target)) setOpen(false); });
    document.addEventListener('keydown', function (e) { if (e.key === 'Escape' && !panel.hidden) { setOpen(false); fab.focus(); } });
  })();

  (function () {
    var reduce = window.matchMedia && window.matchMedia('(prefers-reduced-motion: reduce)').matches;

    /* Scroll progress + back to top */
    var bar = document.getElementById('progress');
    var top = document.getElementById('to-top');
    function onScroll() {
      var h = document.documentElement;
      var max = h.scrollHeight - h.clientHeight;
      bar.style.width = (max > 0 ? (h.scrollTop / max) * 100 : 0) + '%';
      top.hidden = h.scrollTop < 600;
    }
    window.addEventListener('scroll', onScroll, { passive: true });
    onScroll();
    top.addEventListener('click', function () { window.scrollTo({ top: 0, behavior: reduce ? 'auto' : 'smooth' }); });

    /* Typing effect for the hero role */
    var typed = document.getElementById('typed');
    var roles = ['B.Tech CSE (AI & ML) Student', 'Machine Learning Enthusiast', 'Data Analyst in the Making', 'Python Problem Solver'];
    if (typed && !reduce) {
      var r = 0, c = 0, del = false;
      (function tick() {
        var word = roles[r];
        typed.textContent = word.slice(0, c);
        var wait = del ? 35 : 70;
        if (!del && c === word.length) { del = true; wait = 1600; }
        else if (del && c === 0) { del = false; r = (r + 1) % roles.length; wait = 350; }
        else { c += del ? -1 : 1; }
        setTimeout(tick, wait);
      })();
    } else if (typed) { typed.textContent = roles[0]; }

    /* Animated counters */
    function countUp(el) {
      var raw = el.textContent.trim();
      var target = parseFloat(raw);
      if (isNaN(target)) return;
      var dec = (raw.split('.')[1] || '').length;
      if (reduce) return;
      var start = null, dur = 1400;
      function step(ts) {
        if (start === null) start = ts;
        var p = Math.min((ts - start) / dur, 1);
        var eased = 1 - Math.pow(1 - p, 3);
        el.textContent = (target * eased).toFixed(dec);
        if (p < 1) requestAnimationFrame(step); else el.textContent = raw;
      }
      el.textContent = (0).toFixed(dec);
      requestAnimationFrame(step);
    }

    /* Scroll reveal + counters */
    var stats = document.querySelectorAll('.hover-pop .font-display');
    if (!('IntersectionObserver' in window)) return;
    if (!reduce) {
      var targets = document.querySelectorAll('.card, .section-title, .term, .learning, #enquiry-form, #touch-panel-none');
      var io = new IntersectionObserver(function (entries) {
        entries.forEach(function (en) {
          if (!en.isIntersecting) return;
          var e = en.target;
          e.classList.add('in');
          io.unobserve(e);
          setTimeout(function () { e.classList.remove('reveal', 'in'); e.style.transitionDelay = ''; }, 1200);
        });
      }, { threshold: 0.12 });
      targets.forEach(function (e, i) {
        e.classList.add('reveal');
        e.style.transitionDelay = ((i % 4) * 90) + 'ms';
        io.observe(e);
      });
    }
    var cio = new IntersectionObserver(function (entries) {
      entries.forEach(function (en) { if (en.isIntersecting) { countUp(en.target); cio.unobserve(en.target); } });
    }, { threshold: 0.6 });
    stats.forEach(function (s) { cio.observe(s); });
  })();
</script>
</body>
</html>
