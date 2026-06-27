
<style>
*{box-sizing:border-box;margin:0;padding:0}
.root{font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif;padding:0 0 2rem}
.hero{background:#0d0d0d;border-radius:16px;padding:2.5rem 2rem 2rem;margin-bottom:1.5rem;position:relative;overflow:hidden}
.hero-grid{display:grid;grid-template-columns:56px 1fr;gap:1rem;align-items:start}
.avatar{width:56px;height:56px;border-radius:14px;background:#1a1a1a;border:1.5px solid #2a2a2a;display:flex;align-items:center;justify-content:center;font-size:20px;font-weight:500;color:#e0e0e0;letter-spacing:-1px;flex-shrink:0}
.hero-name{font-size:22px;font-weight:500;color:#f0f0f0;line-height:1.2}
.hero-title{font-size:13px;color:#888;margin-top:4px}
.hero-contact{font-size:12px;color:#555;margin-top:6px}
.terminal{background:#111;border:0.5px solid #222;border-radius:10px;padding:1rem 1.25rem;margin-top:1.25rem;font-family:'Fira Code','Courier New',monospace}
.terminal-bar{display:flex;gap:6px;margin-bottom:10px}
.dot{width:10px;height:10px;border-radius:50%}
.d1{background:#ff5f57}.d2{background:#febc2e}.d3{background:#28c840}
.term-line{font-size:12px;color:#555;line-height:1.8}
.term-prompt{color:#4ec9b0}
.term-cmd{color:#9cdcfe}
.term-out{color:#ce9178}
.term-cur{display:inline-block;width:8px;height:13px;background:#4ec9b0;vertical-align:middle;animation:blink 1s step-end infinite}
@keyframes blink{50%{opacity:0}}
.accent-bar{display:flex;gap:6px;margin-top:1.25rem;flex-wrap:wrap}
.pill{font-size:11px;font-weight:500;padding:3px 10px;border-radius:20px;background:#1a1a1a;color:#888;border:0.5px solid #2a2a2a}
.pill.hot{background:#1a0a00;color:#f97316;border-color:#3a1500}
.pill.cool{background:#00101a;color:#38bdf8;border-color:#003050}
.pill.go{background:#001a0a;color:#4ade80;border-color:#003020}
.section{margin-bottom:1.25rem}
.sec-head{display:flex;align-items:center;gap:8px;margin-bottom:0.75rem}
.sec-title{font-size:13px;font-weight:500;color:var(--text-secondary);text-transform:uppercase;letter-spacing:.08em}
.sec-line{flex:1;height:0.5px;background:var(--border)}
.proj-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.proj-card{background:var(--surface-2);border:0.5px solid var(--border);border-radius:12px;padding:1rem;position:relative;overflow:hidden}
.proj-card.featured{border-color:#f97316;border-width:1.5px}
.proj-tag{position:absolute;top:10px;right:10px;font-size:10px;font-weight:500;padding:2px 8px;border-radius:10px}
.live-tag{background:#1a0a00;color:#f97316}
.repo-tag{background:var(--surface-1);color:var(--text-muted)}
.proj-icon{font-size:20px;margin-bottom:8px}
.proj-name{font-size:13px;font-weight:500;color:var(--text-primary);line-height:1.3}
.proj-desc{font-size:11px;color:var(--text-secondary);margin-top:3px;line-height:1.4}
.proj-stack{display:flex;flex-wrap:wrap;gap:4px;margin-top:8px}
.stack-chip{font-size:10px;padding:2px 6px;border-radius:4px;background:var(--surface-1);color:var(--text-muted);border:0.5px solid var(--border)}
.proj-link{display:inline-flex;align-items:center;gap:4px;font-size:11px;color:#f97316;text-decoration:none;margin-top:8px;font-weight:500}
.skills-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:8px}
.skill-card{background:var(--surface-2);border:0.5px solid var(--border);border-radius:10px;padding:0.75rem 1rem}
.skill-label{font-size:11px;color:var(--text-muted);margin-bottom:6px;font-weight:500;text-transform:uppercase;letter-spacing:.06em}
.skill-items{display:flex;flex-wrap:wrap;gap:4px}
.sk{font-size:11px;padding:2px 7px;border-radius:4px;background:var(--surface-1);color:var(--text-secondary);border:0.5px solid var(--border)}
.stats-row{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.stat-card{background:var(--surface-2);border:0.5px solid var(--border);border-radius:10px;padding:0.75rem 1rem}
.stat-num{font-size:22px;font-weight:500;color:var(--text-primary)}
.stat-label{font-size:11px;color:var(--text-muted);margin-top:2px}
.stat-bar{height:3px;background:var(--border);border-radius:2px;margin-top:8px;overflow:hidden}
.stat-fill{height:100%;border-radius:2px;background:#f97316}
.footer{text-align:center;padding-top:1rem;border-top:0.5px solid var(--border);font-size:12px;color:var(--text-muted)}
.footer a{color:#f97316;text-decoration:none}
</style>

<div class="root">

<div class="hero">
  <div class="hero-grid">
    <div class="avatar">AK</div>
    <div>
      <div class="hero-name">Abhinay K.</div>
      <div class="hero-title">Full-stack developer &nbsp;·&nbsp; B.Tech CSE</div>
      <div class="hero-contact">abhinayak2585@gmail.com</div>
    </div>
  </div>

  <div class="terminal">
    <div class="terminal-bar">
      <div class="dot d1"></div><div class="dot d2"></div><div class="dot d3"></div>
    </div>
    <div class="term-line"><span class="term-prompt">~</span> <span class="term-cmd">whoami</span></div>
    <div class="term-line"><span class="term-out">builder · problem-solver · shipping real products</span></div>
    <div class="term-line" style="margin-top:4px"><span class="term-prompt">~</span> <span class="term-cmd">status</span></div>
    <div class="term-line"><span class="term-out" id="ttype"></span><span class="term-cur"></span></div>
  </div>

  <div class="accent-bar">
    <span class="pill hot">Django</span>
    <span class="pill hot">Python</span>
    <span class="pill cool">JavaScript</span>
    <span class="pill cool">React</span>
    <span class="pill go">Open to work</span>
    <span class="pill">B.Tech CSE</span>
  </div>
</div>

<div class="section">
  <div class="sec-head"><span class="sec-title">Projects</span><div class="sec-line"></div></div>
  <div class="proj-grid">

    <div class="proj-card featured">
      <span class="proj-tag live-tag">Live</span>
      <div class="proj-icon"><i class="ti ti-shirt" aria-hidden="true" style="font-size:22px;color:#f97316"></i></div>
      <div class="proj-name">Stitch90 — Football Jersey Store</div>
      <div class="proj-desc">Full e-commerce platform with custom jersey builder, Razorpay payments, and admin dashboard.</div>
      <div class="proj-stack">
        <span class="stack-chip">Django</span><span class="stack-chip">Python</span><span class="stack-chip">SQLite</span><span class="stack-chip">Bootstrap</span>
      </div>
      <a class="proj-link" href="https://aby10.pythonanywhere.com"><i class="ti ti-external-link" aria-hidden="true"></i> aby10.pythonanywhere.com</a>
    </div>

    <div class="proj-card">
      <span class="proj-tag repo-tag">Repo</span>
      <div class="proj-icon"><i class="ti ti-brain" aria-hidden="true" style="font-size:22px;color:#38bdf8"></i></div>
      <div class="proj-name">Feedback Sentiment</div>
      <div class="proj-desc">ML-powered sentiment analyzer that classifies user feedback in real time.</div>
      <div class="proj-stack">
        <span class="stack-chip">Python</span><span class="stack-chip">ML</span><span class="stack-chip">JavaScript</span>
      </div>
      <a class="proj-link" href="https://github.com/abhiiinay/feedback-sentiment"><i class="ti ti-external-link" aria-hidden="true"></i> View repo</a>
    </div>

    <div class="proj-card">
      <span class="proj-tag repo-tag">Repo</span>
      <div class="proj-icon"><i class="ti ti-school" aria-hidden="true" style="font-size:22px;color:#4ade80"></i></div>
      <div class="proj-name">E-Learning Platform</div>
      <div class="proj-desc">Online course platform built with Django featuring user enrollment and content delivery.</div>
      <div class="proj-stack">
        <span class="stack-chip">Django</span><span class="stack-chip">Python</span><span class="stack-chip">HTML/CSS</span>
      </div>
      <a class="proj-link" href="https://github.com/abhiiinay/E-learning"><i class="ti ti-external-link" aria-hidden="true"></i> View repo</a>
    </div>

    <div class="proj-card">
      <span class="proj-tag repo-tag">Repo</span>
      <div class="proj-icon"><i class="ti ti-layout-grid" aria-hidden="true" style="font-size:22px;color:#a78bfa"></i></div>
      <div class="proj-name">More Projects</div>
      <div class="proj-desc">Portfolio · Furniture Store UI · Blog · Neaty · Survey Form — all on GitHub.</div>
      <div class="proj-stack">
        <span class="stack-chip">HTML</span><span class="stack-chip">CSS</span><span class="stack-chip">JS</span>
      </div>
      <a class="proj-link" href="https://github.com/abhiiinay"><i class="ti ti-external-link" aria-hidden="true"></i> See all repos</a>
    </div>

  </div>
</div>

<div class="section">
  <div class="sec-head"><span class="sec-title">Skills</span><div class="sec-line"></div></div>
  <div class="skills-grid">
    <div class="skill-card">
      <div class="skill-label">Languages</div>
      <div class="skill-items">
        <span class="sk">Python</span><span class="sk">JavaScript</span><span class="sk">C</span><span class="sk">PHP</span><span class="sk">SQL</span>
      </div>
    </div>
    <div class="skill-card">
      <div class="skill-label">Frameworks</div>
      <div class="skill-items">
        <span class="sk">Django</span><span class="sk">React</span><span class="sk">Bootstrap</span>
      </div>
    </div>
    <div class="skill-card">
      <div class="skill-label">Tools</div>
      <div class="skill-items">
        <span class="sk">Git</span><span class="sk">GitHub</span><span class="sk">VS Code</span><span class="sk">PythonAnywhere</span>
      </div>
    </div>
  </div>
</div>

<div class="section">
  <div class="sec-head"><span class="sec-title">At a glance</span><div class="sec-line"></div></div>
  <div class="stats-row">
    <div class="stat-card">
      <div class="stat-num">7+</div>
      <div class="stat-label">Projects shipped</div>
      <div class="stat-bar"><div class="stat-fill" style="width:70%"></div></div>
    </div>
    <div class="stat-card">
      <div class="stat-num">1</div>
      <div class="stat-label">Live production app</div>
      <div class="stat-bar"><div class="stat-fill" style="width:100%;background:#4ade80"></div></div>
    </div>
  </div>
</div>

<div class="footer">
  If this work resonates — <a href="https://github.com/abhiiinay">star a repo</a> or reach out.
</div>

</div>

<script>
const lines = [
  "learning Django, shipping products daily",
  "B.Tech CSE · full-stack developer",
  "open to opportunities · abhinayak2585@gmail.com"
];
let li=0,ci=0,del=false;
const el=document.getElementById('ttype');
function tick(){
  const cur=lines[li];
  if(!del){el.textContent=cur.slice(0,++ci);if(ci===cur.length){del=true;setTimeout(tick,2000);return;}}
  else{el.textContent=cur.slice(0,--ci);if(ci===0){del=false;li=(li+1)%lines.length;}}
  setTimeout(tick,del?35:55);
}
tick();
</script>

<!---
abhiiinay/abhiiinay is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
