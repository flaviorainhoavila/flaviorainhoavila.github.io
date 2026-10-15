<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Flavio Avila</title>
<meta name="claude:viewport-fit-sides" content="cover">
<meta name="description" content="Flavio Avila: speech, audio and statistical signal processing. Research, code and writing.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Sora:wght@500;600&family=Literata:opsz,wght@7..72,400;7..72,600&family=JetBrains+Mono:wght@400;500&display=swap">
<style>
html{-webkit-text-size-adjust:100%}body{margin:0}img{max-width:100%}
/* Layout: one reading column with a spectrogram band as the masthead; sections are plain, ruled lists. */
:root{
  --bg:#f5f7f8; --surface:#ffffff; --ink:#15202a; --muted:#56636e; --rule:#d9e0e5;
  --accent:#0d5c66; --accent-soft:#e2eff0; --heat:#c7772a; --todo:#8a5a12; --todo-bg:#fbf3e4;
  --f-display:"Sora", "Segoe UI", system-ui, sans-serif;
  --f-body:"Literata", Georgia, "Times New Roman", serif;
  --f-mono:"JetBrains Mono", ui-monospace, "SFMono-Regular", Menlo, monospace;
}
@media (prefers-color-scheme: dark){ :root:not([data-theme="light"]){
  --bg:#0f1519; --surface:#151d22; --ink:#e3e9ec; --muted:#9aa8b1; --rule:#28343b;
  --accent:#5fb7c0; --accent-soft:#16292d; --heat:#e0a35e; --todo:#e3b56a; --todo-bg:#2a2216; color-scheme:dark }}
:root[data-theme="dark"]{
  --bg:#0f1519; --surface:#151d22; --ink:#e3e9ec; --muted:#9aa8b1; --rule:#28343b;
  --accent:#5fb7c0; --accent-soft:#16292d; --heat:#e0a35e; --todo:#e3b56a; --todo-bg:#2a2216; color-scheme:dark }

*{box-sizing:border-box}
body{background:var(--bg);color:var(--ink);font-family:var(--f-body);font-size:17px;line-height:1.6;
  padding-left:max(16px,env(safe-area-inset-left,0px));padding-right:max(16px,env(safe-area-inset-right,0px))}
.wrap{max-width:46rem;margin:0 auto;padding-block:2.5rem 4rem;display:flex;flex-direction:column;gap:3.25rem}
a{color:var(--accent);text-decoration-thickness:1px;text-underline-offset:3px}
a:hover{text-decoration-thickness:2px}
a:focus-visible,button:focus-visible{outline:2px solid var(--accent);outline-offset:3px;border-radius:2px}
h1,h2,h3{font-family:var(--f-display);font-weight:600;text-wrap:balance;margin:0;line-height:1.2}
h1{font-size:clamp(2rem,5vw,2.75rem);letter-spacing:-.01em}
h2{font-size:.8rem;text-transform:uppercase;letter-spacing:.14em;color:var(--muted);font-weight:500;
  display:flex;align-items:center;gap:.75rem}
h2::after{content:"";flex:1;height:1px;background:var(--rule)}
h3{font-size:1.1rem}
p{margin:0}
.mono{font-family:var(--f-mono);font-size:.78rem;letter-spacing:.02em}

/* Masthead */
header{display:flex;flex-direction:column;gap:1.25rem}
.spec{width:100%;height:110px;display:block;border-radius:6px;background:var(--surface);border:1px solid var(--rule)}
.spec-cap{display:flex;justify-content:space-between;gap:1rem;color:var(--muted)}
.lede{font-size:1.15rem;max-width:38rem}
.meta{display:flex;flex-wrap:wrap;gap:.5rem 1.25rem;color:var(--muted)}
.links{display:flex;flex-wrap:wrap;gap:.6rem}
.btn{font-family:var(--f-mono);font-size:.8rem;padding:.45rem .8rem;border:1px solid var(--rule);border-radius:4px;
  background:var(--surface);color:var(--ink);text-decoration:none;cursor:pointer}
.btn:hover{border-color:var(--accent);color:var(--accent)}

/* Sections */
section{display:flex;flex-direction:column;gap:1.25rem}
.list{list-style:none;margin:0;padding:0;display:flex;flex-direction:column}
.item{display:grid;grid-template-columns:7.5rem 1fr;gap:.25rem 1.25rem;padding-block:1rem;border-top:1px solid var(--rule)}
.item:first-child{border-top:0;padding-top:0}
.item > *{min-width:0}
.when{font-family:var(--f-mono);font-size:.78rem;color:var(--muted);padding-top:.2rem;font-variant-numeric:tabular-nums}
.body{display:flex;flex-direction:column;gap:.4rem}
.body p{color:var(--ink)}
.tags{display:flex;flex-wrap:wrap;gap:.35rem;margin-top:.2rem}
.tag{font-family:var(--f-mono);font-size:.7rem;padding:.12rem .45rem;border-radius:3px;background:var(--accent-soft);color:var(--accent)}
.rowlinks{display:flex;flex-wrap:wrap;gap:.9rem;font-family:var(--f-mono);font-size:.78rem}
.status{font-family:var(--f-mono);font-size:.7rem;color:var(--heat);text-transform:uppercase;letter-spacing:.1em}
.todo{background:var(--todo-bg);color:var(--todo);font-family:var(--f-mono);font-size:.78rem;padding:.05rem .35rem;border-radius:3px}
.note{color:var(--muted);font-size:.95rem}
.contact{display:flex;flex-wrap:wrap;align-items:center;gap:.75rem}
.email{font-family:var(--f-mono);font-size:.9rem;user-select:all}
footer{color:var(--muted);border-top:1px solid var(--rule);padding-top:1.25rem}

@media (max-width:560px){
  .item{grid-template-columns:1fr}
  .when{padding-top:0}
  body{font-size:16px}
}
</style>
</head>
<body>

<div class="wrap">

<header>
  <canvas class="spec" id="spec" aria-label="Spectrogram of a synthetic voiced sound with harmonics and formant bands"></canvas>
  <div class="spec-cap mono"><span>0–4 kHz · harmonics of a voiced vowel</span><span>t →</span></div>
  <h1>Flavio Avila</h1>
  <p class="lede">I build machine learning and signal-processing systems that work on messy, real-world signals: speech, audio and scientific instruments. My background is Bayesian statistical signal processing; my work has been in taking models from research into production, and in measuring honestly whether they got better.</p>
  <div class="meta mono"><span>D.Sc. Electrical Engineering, UFRJ</span><span>Evanston, Illinois</span><span>US citizen</span></div>
  <div class="links">
    <a class="btn" href="https://www.linkedin.com/in/flavioavila" target="_blank" rel="noopener">LinkedIn</a>
    <a class="btn" href="https://github.com/YOUR-USERNAME" target="_blank" rel="noopener">GitHub</a>
    <a class="btn" href="https://scholar.google.com/citations?user=YOUR-ID" target="_blank" rel="noopener">Google Scholar</a>
    <a class="btn" href="resume.pdf" target="_blank" rel="noopener">Résumé (PDF)</a>
  </div>
</header>

<section id="work" aria-labelledby="h-work">
  <h2 id="h-work">Current work</h2>
  <ul class="list">
    <li class="item">
      <span class="when">2026 –</span>
      <div class="body">
        <h3>ASR robustness and intelligibility-aware speech enhancement</h3>
        <p>How much does recognition accuracy fall as input quality drops, and for which systems? I compare a commercial recognizer with open-source models such as Whisper across controlled degradations, then use learned quality and intelligibility predictors as training objectives for enhancement, so the enhancer optimizes for what the recognizer and the listener need rather than for signal-level scores.</p>
        <div class="tags"><span class="tag">ASR evaluation</span><span class="tag">WER</span><span class="tag">speech enhancement</span><span class="tag">PyTorch</span></div>
        <div class="rowlinks"><span class="status">In progress</span><a href="https://github.com/YOUR-USERNAME/asr-robustness" target="_blank" rel="noopener">Code</a><a href="#writing">Write-up</a></div>
      </div>
    </li>
  </ul>
</section>

<section id="code" aria-labelledby="h-code">
  <h2 id="h-code">Code</h2>
  <p class="note">Most of my industry code is proprietary, so these are research code published with its original dates, and reimplementations on public data of approaches I built in production. Each README says which is which.</p>
  <ul class="list">
    <li class="item">
      <span class="when">2019 – 22 · 2026</span>
      <div class="body">
        <h3>Audio quality gate and diarization pipeline</h3>
        <p>A reimplementation, on public speech corpora, of the preprocessing I built for a production speech analytics platform: format and integrity checks, noise and interference screening, normalization and speaker diarization, served behind a small API with tests and CI.</p>
        <div class="tags"><span class="tag">Python</span><span class="tag">diarization</span><span class="tag">FastAPI</span><span class="tag">CI</span></div>
        <div class="rowlinks"><a href="https://github.com/YOUR-USERNAME/audio-quality-gate" target="_blank" rel="noopener">Code</a></div>
      </div>
    </li>
    <li class="item">
      <span class="when">2008 – 12 · 2026</span>
      <div class="body">
        <h3>Bayesian methods for audio signals</h3>
        <p>Code from my doctoral research, published as originally written in MATLAB, with a Python port and tests added later.</p>
        <div class="tags"><span class="tag">Bayesian inference</span><span class="tag">MCMC</span><span class="tag">MATLAB</span><span class="tag">Python</span></div>
        <div class="rowlinks"><a href="https://github.com/YOUR-USERNAME/bayesian-audio" target="_blank" rel="noopener">Code</a><span class="todo">add dissertation link</span></div>
      </div>
    </li>
    <li class="item">
      <span class="when">2023 – 26 · 2026</span>
      <div class="body">
        <h3>Regression detection for ML evaluation</h3>
        <p>A small library for deciding whether a model change is a real improvement: paired comparisons over fixed seeds, bootstrap confidence intervals and false-discovery control across many metrics. It generalizes the evaluation practice behind release gating on a team I worked on.</p>
        <div class="tags"><span class="tag">statistics</span><span class="tag">bootstrap</span><span class="tag">MLflow</span></div>
        <div class="rowlinks"><a href="https://github.com/YOUR-USERNAME/ml-regression-checks" target="_blank" rel="noopener">Code</a></div>
      </div>
    </li>
  </ul>
</section>

<section id="writing" aria-labelledby="h-writing">
  <h2 id="h-writing">Writing</h2>
  <ul class="list">
    <li class="item">
      <span class="when"><span class="todo">date</span></span>
      <div class="body">
        <h3><a href="#">Enhancement for recognizers, not for ears</a></h3>
        <p>Why a speech enhancer that improves signal-level metrics can make transcripts worse, and what to optimize instead.</p>
      </div>
    </li>
    <li class="item">
      <span class="when"><span class="todo">date</span></span>
      <div class="body">
        <h3><a href="#">Did the model actually get better?</a></h3>
        <p>Paired seeds, bootstrap intervals and multiple-comparison control for ML regression testing.</p>
      </div>
    </li>
    <li class="item">
      <span class="when"><span class="todo">date</span></span>
      <div class="body">
        <h3><a href="#">Bayesian inference is not Bayesian optimization</a></h3>
        <p>Two ideas that share a name, and when an engineering problem is really one or the other.</p>
      </div>
    </li>
  </ul>
</section>

<section id="research" aria-labelledby="h-research">
  <h2 id="h-research">Publications and patents</h2>
  <p class="note">15+ peer-reviewed papers and a book chapter in IEEE journals, Interspeech, ICASSP, WASPAA and EUSIPCO. Full list on <a href="https://scholar.google.com/citations?user=YOUR-ID" target="_blank" rel="noopener">Google Scholar</a>.</p>
  <ul class="list">
    <li class="item">
      <span class="when">2020</span>
      <div class="body">
        <h3>Systems and Methods for Machine Learning of Voice Attributes</h3>
        <p class="mono">US Patent Applications 16/889,326 and 16/889,307</p>
      </div>
    </li>
    <li class="item">
      <span class="when"><span class="todo">year</span></span>
      <div class="body">
        <h3><span class="todo">Selected paper title</span></h3>
        <p class="mono"><span class="todo">Authors · Venue</span></p>
        <div class="rowlinks"><a href="#">PDF</a><a href="#">Code</a></div>
      </div>
    </li>
    <li class="item">
      <span class="when"><span class="todo">year</span></span>
      <div class="body">
        <h3><span class="todo">Selected paper title</span></h3>
        <p class="mono"><span class="todo">Authors · Venue</span></p>
        <div class="rowlinks"><a href="#">PDF</a></div>
      </div>
    </li>
    <li class="item">
      <span class="when">2012</span>
      <div class="body">
        <h3>Doctoral dissertation: Bayesian methods for audio signal processing</h3>
        <p class="mono">D.Sc., Electrical Engineering, Federal University of Rio de Janeiro</p>
      </div>
    </li>
  </ul>
</section>

<section id="experience" aria-labelledby="h-exp">
  <h2 id="h-exp">Experience</h2>
  <ul class="list">
    <li class="item"><span class="when">2023 – 26</span><div class="body"><h3>Agilent Technologies</h3><p>R&amp;D AI/ML Engineer. Deep-learning detection and quantification for analytical-instrument signals; Bayesian method optimization; part of the team that built evaluation and regression infrastructure.</p></div></li>
    <li class="item"><span class="when">2022 – 23</span><div class="body"><h3>Amazon, Alexa</h3><p>Applied Scientist. Transformer models for question answering and product search; evaluation datasets and human-in-the-loop protocols.</p></div></li>
    <li class="item"><span class="when">2019 – 22</span><div class="body"><h3>Verisk Financial / TransUnion</h3><p>AI/ML Engineer to Data Science Manager. Led a team of seven building a production speech analytics platform and an in-house speech recognizer for life-insurance risk detection.</p></div></li>
    <li class="item"><span class="when">2013 – 19</span><div class="body"><h3>Rio de Janeiro State University</h3><p>Associate Professor. Signal processing, detection and estimation theory, probability; graduate supervision and research in audio.</p></div></li>
  </ul>
</section>

<section id="contact" aria-labelledby="h-contact">
  <h2 id="h-contact">Contact</h2>
  <div class="contact">
    <span class="email" id="email">flavio.rainho.avila@gmail.com</span>
    <button class="btn" id="copy" type="button">Copy email</button>
    <span class="mono" id="copied" aria-live="polite"></span>
  </div>
</section>

<footer class="mono">© 2026 Flavio Avila</footer>
</div>

<script>
(function(){
  // Static synthetic spectrogram: a voiced vowel with a gliding pitch and three formant bands.
  const c=document.getElementById('spec'); if(!c) return;
  function draw(){
    const dpr=Math.min(window.devicePixelRatio||1,2), w=c.clientWidth, h=c.clientHeight;
    c.width=Math.round(w*dpr); c.height=Math.round(h*dpr);
    const g=c.getContext('2d'); g.setTransform(dpr,0,0,dpr,0,0);
    const css=getComputedStyle(document.documentElement);
    const bg=css.getPropertyValue('--surface').trim(), hot=css.getPropertyValue('--heat').trim(), acc=css.getPropertyValue('--accent').trim();
    g.fillStyle=bg; g.fillRect(0,0,w,h);
    const cols=Math.max(60,Math.floor(w/4)), rows=Math.floor(h/3), fmax=4000;
    const formants=[[700,160],[1220,200],[2600,260]];
    let seed=7; const rnd=()=>{seed=(seed*16807)%2147483647; return seed/2147483647;};
    for(let i=0;i<cols;i++){
      const t=i/cols, voiced=t>0.08&&t<0.92;
      const f0=120+40*Math.sin(t*Math.PI)+10*Math.sin(t*9);
      for(let j=0;j<rows;j++){
        const f=(1-j/rows)*fmax;
        let env=0; for(const [fc,bw] of formants){ env+=Math.exp(-((f-fc)**2)/(2*bw*bw)); }
        const k=f/f0, near=Math.exp(-((k-Math.round(k))**2)/0.012);
        let e=voiced? (0.15+env)*near*Math.exp(-f/3500) : 0;
        e+=0.06*rnd()*(voiced?1:0.5);
        e=Math.min(1,e*1.4);
        if(e<0.05) continue;
        g.globalAlpha=e; g.fillStyle=e>0.55?hot:acc;
        g.fillRect(i*(w/cols), j*(h/rows), w/cols+0.5, h/rows+0.5);
      }
    }
    g.globalAlpha=1;
  }
  draw();
  let t; window.addEventListener('resize',()=>{clearTimeout(t);t=setTimeout(draw,150);});
  if(window.matchMedia) window.matchMedia('(prefers-color-scheme: dark)').addEventListener?.('change',draw);
  new MutationObserver(draw).observe(document.documentElement,{attributes:true,attributeFilter:['data-theme']});

  const btn=document.getElementById('copy'), out=document.getElementById('copied'), em=document.getElementById('email').textContent;
  btn.addEventListener('click',()=>{
    const ok=()=>{out.textContent='Copied';setTimeout(()=>out.textContent='',2000)};
    const fallback=()=>{const r=document.createRange();r.selectNodeContents(document.getElementById('email'));const s=getSelection();s.removeAllRanges();s.addRange(r);out.textContent='Selected, press Ctrl+C';};
    try{ navigator.clipboard.writeText(em).then(ok,fallback); }catch(e){ fallback(); }
  });
})();
</script>
</body>
</html>
