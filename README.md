
<style>
@import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;700&family=Syne:wght@400;700;800&display=swap');
*{box-sizing:border-box;margin:0;padding:0}
.wrap{background:#0a0e17;border:1px solid #1e2d40;border-radius:14px;padding:32px;font-family:'JetBrains Mono',monospace;color:#a8b8cc;max-width:720px}
.top-bar{display:flex;align-items:center;gap:8px;margin-bottom:24px}
.dot{width:12px;height:12px;border-radius:50%}
.dot-r{background:#ff5f57}.dot-y{background:#febc2e}.dot-g{background:#28c840}
.bar-title{font-size:11px;color:#3d5570;margin-left:8px;letter-spacing:.05em}
.hero{margin-bottom:28px}
.prompt{color:#3d70a8;font-size:12px;margin-bottom:4px}
.name{font-family:'Syne',sans-serif;font-size:28px;font-weight:800;color:#e2eaf4;line-height:1.1;margin-bottom:6px}
.name span{color:#00d4ff}
.role-line{font-size:12px;color:#3d70a8;margin-bottom:10px}
.role-line span{color:#7ec8e3}
.bio{font-size:12px;color:#6a8099;line-height:1.7;border-left:2px solid #1a3a5c;padding-left:14px}
.bio b{color:#00d4ff;font-weight:500}
.section{margin-bottom:24px}
.sec-head{font-size:11px;color:#3d70a8;letter-spacing:.12em;text-transform:uppercase;margin-bottom:12px;display:flex;align-items:center;gap:8px}
.sec-head::after{content:'';flex:1;height:1px;background:#1a2d42}
.grid-2{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.skill-card{background:#0e1824;border:1px solid #1a2d42;border-radius:8px;padding:12px 14px}
.skill-card-title{font-size:10px;color:#3d5570;text-transform:uppercase;letter-spacing:.1em;margin-bottom:8px}
.tags{display:flex;flex-wrap:wrap;gap:5px}
.tag{font-size:11px;padding:3px 9px;border-radius:4px;font-family:'JetBrains Mono',monospace}
.t-js   {background:#2a2200;color:#e8c94a;border:1px solid #3d3300}
.t-py   {background:#001c2e;color:#4ab3e8;border:1px solid #003352}
.t-html {background:#2a0d00;color:#e87a4a;border:1px solid #3d1500}
.t-c    {background:#001a2a;color:#4a9de8;border:1px solid #002e42}
.t-ps   {background:#14002a;color:#a04ae8;border:1px solid #250040}
.t-n8n  {background:#2a0016;color:#e84a7a;border:1px solid #3d0022}
.t-ai   {background:#0a2a1a;color:#4ae8a0;border:1px solid #0d3d24}
.t-cy   {background:#002a0e;color:#00e84a;border:1px solid #004018}
.t-fe   {background:#2a1a00;color:#e8a04a;border:1px solid #3d2600}
.stats-row{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.stat-box{background:#0e1824;border:1px solid #1a2d42;border-radius:8px;padding:12px 14px}
.stat-label{font-size:10px;color:#3d5570;text-transform:uppercase;letter-spacing:.1em;margin-bottom:8px}
.bar-row{display:flex;align-items:center;gap:8px;margin-bottom:5px}
.bar-name{font-size:11px;color:#6a8099;min-width:80px}
.bar-track{flex:1;height:4px;background:#1a2d42;border-radius:2px}
.bar-fill{height:4px;border-radius:2px}
.b-js{background:#e8c94a;width:40%}
.b-py{background:#4ab3e8;width:25%}
.b-html{background:#e87a4a;width:20%}
.b-ps{background:#a04ae8;width:10%}
.b-c{background:#4a9de8;width:5%}
.bar-pct{font-size:10px;color:#3d5570;min-width:28px;text-align:right}
.focus-list{display:flex;flex-direction:column;gap:6px}
.focus-item{display:flex;align-items:center;gap:8px;font-size:11px;color:#6a8099}
.focus-icon{font-size:13px}
.cursor{display:inline-block;width:8px;height:14px;background:#00d4ff;margin-left:2px;animation:blink 1s step-end infinite}
@keyframes blink{0%,100%{opacity:1}50%{opacity:0}}
.contact-row{display:flex;gap:8px;flex-wrap:wrap}
.cbtn{font-family:'JetBrains Mono',monospace;font-size:11px;padding:7px 14px;border-radius:6px;text-decoration:none;display:inline-flex;align-items:center;gap:6px;border:1px solid}
.cbtn-email{background:#001830;color:#4ab3e8;border-color:#003352}
.cbtn-wa{background:#00180c;color:#4ae8a0;border-color:#003018}
.divider{border:none;border-top:1px solid #131f2e;margin:20px 0}
.cmd-line{font-size:11px;color:#3d5570;margin-bottom:4px}
.cmd-line span{color:#00d4ff}
</style>

<div class="wrap">
  <div class="top-bar">
    <div class="dot dot-r"></div>
    <div class="dot dot-y"></div>
    <div class="dot dot-g"></div>
    <span class="bar-title">filipepires1 — README.md</span>
  </div>

  <div class="hero">
    <div class="prompt">$ whoami</div>
    <div class="name">Filipe <span>Pires</span><span class="cursor"></span></div>
    <div class="role-line">// <span>Especialista Front-End</span> · Automação IA · Cybersec</div>
    <div class="bio">
      Desenvolvedor focado em criar <b>interfaces que funcionam de verdade</b> e automações que economizam horas de trabalho. Integro <b>IA</b> em fluxos com <b>n8n</b>, escrevo scripts que resolvem problemas reais e mantenho boas práticas de <b>segurança digital</b> em cada projeto.
    </div>
  </div>

  <hr class="divider">

  <div class="section">
    <div class="sec-head">stack</div>
    <div class="grid-2">
      <div class="skill-card">
        <div class="skill-card-title">// frontend</div>
        <div class="tags">
          <span class="tag t-html">HTML5</span>
          <span class="tag t-js">JavaScript</span>
          <span class="tag t-fe">CSS3</span>
        </div>
      </div>
      <div class="skill-card">
        <div class="skill-card-title">// backend & scripts</div>
        <div class="tags">
          <span class="tag t-py">Python</span>
          <span class="tag t-c">C</span>
          <span class="tag t-ps">PowerShell</span>
        </div>
      </div>
      <div class="skill-card">
        <div class="skill-card-title">// automação & ia</div>
        <div class="tags">
          <span class="tag t-n8n">n8n</span>
          <span class="tag t-ai">AI/LLM</span>
        </div>
      </div>
      <div class="skill-card">
        <div class="skill-card-title">// segurança</div>
        <div class="tags">
          <span class="tag t-cy">CyberSecurity</span>
        </div>
      </div>
    </div>
  </div>

  <div class="section">
    <div class="sec-head">stats</div>
    <div class="stats-row">
      <div class="stat-box">
        <div class="stat-label">// top languages</div>
        <div class="bar-row"><span class="bar-name">JavaScript</span><div class="bar-track"><div class="bar-fill b-js"></div></div><span class="bar-pct">40%</span></div>
        <div class="bar-row"><span class="bar-name">Python</span><div class="bar-track"><div class="bar-fill b-py"></div></div><span class="bar-pct">25%</span></div>
        <div class="bar-row"><span class="bar-name">HTML/CSS</span><div class="bar-track"><div class="bar-fill b-html"></div></div><span class="bar-pct">20%</span></div>
        <div class="bar-row"><span class="bar-name">PowerShell</span><div class="bar-track"><div class="bar-fill b-ps"></div></div><span class="bar-pct">10%</span></div>
        <div class="bar-row"><span class="bar-name">C</span><div class="bar-track"><div class="bar-fill b-c"></div></div><span class="bar-pct">5%</span></div>
      </div>
      <div class="stat-box">
        <div class="stat-label">// agora</div>
        <div class="focus-list">
          <div class="focus-item"><span class="focus-icon">🔭</span> Projetos Front-End</div>
          <div class="focus-item"><span class="focus-icon">🤖</span> Automações com IA & n8n</div>
          <div class="focus-item"><span class="focus-icon">🔐</span> Cybersegurança</div>
          <div class="focus-item"><span class="focus-icon">📍</span> Minas Gerais, Brasil</div>
        </div>
      </div>
    </div>
  </div>

  <hr class="divider">

  <div class="section">
    <div class="sec-head">contato</div>
    <div class="cmd-line">$ contact --reach-out <span>filipepires1</span></div>
    <div class="contact-row">
      <a class="cbtn cbtn-email" href="mailto:fpnogueira11@gmail.com">✉ fpnogueira11@gmail.com</a>
      <a class="cbtn cbtn-wa" href="https://wa.me/5531999657698">◎ WhatsApp</a>
    </div>
  </div>
</div>
