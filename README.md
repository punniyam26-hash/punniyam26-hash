<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Punniyamoorthy K | Python Backend Developer</title>
  <meta name="description" content="Python Backend Developer with 2+ years of experience in healthcare and fraud detection platforms. Django, DRF, Flask, FastAPI, PostgreSQL, ML." />

  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'ui-sans-serif', 'system-ui'],
            mono: ['Fira Code', 'ui-monospace', 'monospace'],
          },
          colors: {
            brand: { 400: '#38bdf8', 500: '#0ea5e9', 600: '#0284c7' },
            ink: { 900: '#070d14', 800: '#0b1520', 700: '#0f2027', 600: '#203a43', 500: '#2c5364' },
          },
          keyframes: {
            float: { '0%,100%': { transform: 'translateY(0)' }, '50%': { transform: 'translateY(-14px)' } },
            blob: { '0%,100%': { transform: 'translate(0,0) scale(1)' }, '50%': { transform: 'translate(30px,-40px) scale(1.15)' } },
            blink: { '0%,100%': { opacity: 1 }, '50%': { opacity: 0 } },
          },
          animation: {
            float: 'float 6s ease-in-out infinite',
            blob: 'blob 12s ease-in-out infinite',
            blink: 'blink 1s step-end infinite',
          },
        },
      },
    };
  </script>

  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;500;600&family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet" />
  <script src="https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.min.js"></script>

  <style>
    body { background: #070d14; }
    .glass { background: rgba(255,255,255,0.04); backdrop-filter: blur(12px); border: 1px solid rgba(255,255,255,0.08); }
    .grad-text { background: linear-gradient(90deg, #38bdf8, #a78bfa, #34d399); -webkit-background-clip: text; background-clip: text; color: transparent; }
    .reveal { opacity: 0; transform: translateY(28px); transition: all .8s cubic-bezier(.2,.7,.2,1); }
    .reveal.show { opacity: 1; transform: none; }
    .grid-bg { background-image: linear-gradient(rgba(255,255,255,.03) 1px, transparent 1px), linear-gradient(90deg, rgba(255,255,255,.03) 1px, transparent 1px); background-size: 48px 48px; }
    ::-webkit-scrollbar { width: 8px; } ::-webkit-scrollbar-track { background: #070d14; } ::-webkit-scrollbar-thumb { background: #2c5364; border-radius: 8px; }
    .mermaid svg { max-width: 100%; height: auto; }
  </style>
</head>

<body class="font-sans text-slate-300 antialiased selection:bg-brand-500/40 selection:text-white">

  <!-- Scroll progress -->
  <div id="progress" class="fixed top-0 left-0 h-1 w-0 z-[60] bg-gradient-to-r from-brand-400 via-violet-400 to-emerald-400"></div>

  <!-- NAV -->
  <header class="fixed top-0 inset-x-0 z-50">
    <nav class="glass mx-auto mt-3 max-w-6xl rounded-2xl px-5 py-3 flex items-center justify-between">
      <a href="#home" class="font-mono font-semibold text-white">punniyam<span class="text-brand-400">.dev</span></a>
      <ul class="hidden md:flex items-center gap-7 text-sm">
        <li><a class="hover:text-brand-400 transition" href="#about">About</a></li>
        <li><a class="hover:text-brand-400 transition" href="#impact">Impact</a></li>
        <li><a class="hover:text-brand-400 transition" href="#architecture">Architecture</a></li>
        <li><a class="hover:text-brand-400 transition" href="#stack">Stack</a></li>
        <li><a class="hover:text-brand-400 transition" href="#experience">Experience</a></li>
        <li><a class="hover:text-brand-400 transition" href="#projects">Projects</a></li>
        <li><a class="hover:text-brand-400 transition" href="#contact">Contact</a></li>
      </ul>
      <a href="mailto:punniyam26@gmail.com" class="hidden md:inline-block rounded-xl bg-brand-500 hover:bg-brand-600 px-4 py-2 text-sm font-medium text-white transition">Hire me</a>
      <button id="menuBtn" class="md:hidden text-white" aria-label="Menu">
        <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" d="M4 7h16M4 12h16M4 17h16"/></svg>
      </button>
    </nav>
    <div id="mobileMenu" class="hidden md:hidden glass mx-4 mt-2 rounded-2xl p-5 space-y-3 text-sm">
      <a class="block" href="#about">About</a><a class="block" href="#impact">Impact</a><a class="block" href="#architecture">Architecture</a>
      <a class="block" href="#stack">Stack</a><a class="block" href="#experience">Experience</a><a class="block" href="#projects">Projects</a><a class="block" href="#contact">Contact</a>
    </div>
  </header>

  <!-- HERO -->
  <section id="home" class="relative min-h-screen flex items-center overflow-hidden grid-bg bg-gradient-to-br from-ink-900 via-ink-700 to-ink-500/60">
    <div class="absolute -top-24 -left-24 w-96 h-96 rounded-full bg-brand-500/30 blur-3xl animate-blob"></div>
    <div class="absolute bottom-0 right-0 w-[28rem] h-[28rem] rounded-full bg-violet-500/20 blur-3xl animate-blob" style="animation-delay:-5s"></div>

    <div class="relative max-w-6xl mx-auto px-6 pt-32 pb-20 grid lg:grid-cols-2 gap-14 items-center">
      <div>
        <span class="inline-flex items-center gap-2 rounded-full bg-emerald-500/10 text-emerald-400 border border-emerald-500/30 px-4 py-1.5 text-xs font-semibold tracking-wider">
          <span class="relative flex h-2 w-2"><span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-emerald-400 opacity-75"></span><span class="relative inline-flex rounded-full h-2 w-2 bg-emerald-400"></span></span>
          OPEN TO WORK
        </span>
        <h1 class="mt-6 text-5xl sm:text-6xl font-extrabold text-white leading-tight">
          Hi, I'm <span class="grad-text">Punniyamoorthy K</span>
        </h1>
        <p class="mt-4 text-xl sm:text-2xl font-mono text-brand-400 h-9">
          <span id="typed"></span><span class="animate-blink">|</span>
        </p>
        <p class="mt-6 text-lg text-slate-400 max-w-xl leading-relaxed">
          Python Backend Developer with <b class="text-white">2+ years</b> building REST APIs and data-driven systems in
          <b class="text-white">healthcare</b> and <b class="text-white">fraud detection</b> using Django, Flask, FastAPI, PostgreSQL and MySQL.
        </p>

        <div class="mt-8 flex flex-wrap gap-4">
          <a href="#projects" class="rounded-xl bg-brand-500 hover:bg-brand-600 shadow-lg shadow-brand-500/30 px-6 py-3 font-semibold text-white transition hover:-translate-y-0.5">View Projects</a>
          <a href="#contact" class="rounded-xl glass hover:bg-white/10 px-6 py-3 font-semibold text-white transition hover:-translate-y-0.5">Contact Me</a>
        </div>

        <div class="mt-8 flex flex-wrap gap-3 text-xs font-medium">
          <span class="rounded-full bg-sky-500/10 text-sky-300 border border-sky-500/30 px-3 py-1">📍 Chennai, India</span>
          <span class="rounded-full bg-amber-500/10 text-amber-300 border border-amber-500/30 px-3 py-1">⏱ 2+ Years</span>
          <span class="rounded-full bg-violet-500/10 text-violet-300 border border-violet-500/30 px-3 py-1">🗣 Tamil · English</span>
        </div>
      </div>

      <!-- Code card -->
      <div class="animate-float">
        <div class="glass rounded-2xl shadow-2xl shadow-black/40 overflow-hidden">
          <div class="flex items-center gap-2 px-4 py-3 bg-white/5 border-b border-white/10">
            <span class="w-3 h-3 rounded-full bg-red-400"></span><span class="w-3 h-3 rounded-full bg-yellow-400"></span><span class="w-3 h-3 rounded-full bg-green-400"></span>
            <span class="ml-3 text-xs font-mono text-slate-400">developer.py</span>
          </div>
<pre class="p-5 text-[13px] leading-6 font-mono overflow-x-auto"><code><span class="text-violet-400">class</span> <span class="text-yellow-300">Developer</span>:
    name   = <span class="text-emerald-300">"Punniyamoorthy K"</span>
    role   = <span class="text-emerald-300">"Python Backend Developer"</span>
    stack  = [<span class="text-emerald-300">"Django"</span>, <span class="text-emerald-300">"DRF"</span>, <span class="text-emerald-300">"Flask"</span>,
              <span class="text-emerald-300">"FastAPI"</span>, <span class="text-emerald-300">"PostgreSQL"</span>]
    ai_ml  = [<span class="text-emerald-300">"Scikit-learn"</span>, <span class="text-emerald-300">"LangChain"</span>,
              <span class="text-emerald-300">"ChromaDB"</span>, <span class="text-emerald-300">"OpenAI"</span>]
    secure = [<span class="text-emerald-300">"JWT"</span>, <span class="text-emerald-300">"OAuth2"</span>, <span class="text-emerald-300">"RBAC"</span>]

    <span class="text-violet-400">def</span> <span class="text-sky-300">ship</span>(self, feature):
        self.test(coverage=<span class="text-orange-300">75</span>)
        self.deploy(downtime=<span class="text-orange-300">0</span>)
        <span class="text-violet-400">return</span> <span class="text-emerald-300">"✅ production ready"</span></code></pre>
        </div>
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about" class="relative py-24 max-w-6xl mx-auto px-6">
    <div class="reveal">
      <p class="font-mono text-brand-400 text-sm">01 / about</p>
      <h2 class="mt-2 text-3xl sm:text-4xl font-bold text-white">Professional Summary</h2>
    </div>
    <div class="mt-10 grid lg:grid-cols-5 gap-8">
      <div class="reveal lg:col-span-3 glass rounded-2xl p-7 space-y-4">
        <p class="leading-relaxed">I build REST APIs and data-driven backend systems for regulated domains where <b class="text-white">explainability, traceability and reliability</b> matter.</p>
        <ul class="space-y-3 text-slate-300">
          <li class="flex gap-3"><span class="text-brand-400">▹</span> Built an <b class="text-white">anomaly-detection and rule-based fraud monitoring platform</b> with audit trails and case review workflows</li>
          <li class="flex gap-3"><span class="text-brand-400">▹</span> Delivered a <b class="text-white">patient risk-prediction API</b> with <b class="text-white">87%+ model accuracy</b></li>
          <li class="flex gap-3"><span class="text-brand-400">▹</span> Cut audit query times by <b class="text-white">30%</b> through schema indexing</li>
          <li class="flex gap-3"><span class="text-brand-400">▹</span> Maintained <b class="text-white">70–75%+ test coverage</b> with pytest and unittest</li>
          <li class="flex gap-3"><span class="text-brand-400">▹</span> Integrated <b class="text-white">Scikit-learn models</b> and <b class="text-white">LLM-based semantic search</b> into production services</li>
        </ul>
      </div>

      <div class="reveal lg:col-span-2 glass rounded-2xl p-7">
        <dl class="divide-y divide-white/10 text-sm">
          <div class="py-3 flex justify-between gap-4"><dt class="text-slate-500">Role</dt><dd class="text-right text-white">Python Backend / API Developer</dd></div>
          <div class="py-3 flex justify-between gap-4"><dt class="text-slate-500">Experience</dt><dd class="text-right text-white">2+ years</dd></div>
          <div class="py-3 flex justify-between gap-4"><dt class="text-slate-500">Core Stack</dt><dd class="text-right text-white">Django · DRF · Flask · FastAPI · PostgreSQL · MySQL · Docker · pytest</dd></div>
          <div class="py-3 flex justify-between gap-4"><dt class="text-slate-500">AI / ML</dt><dd class="text-right text-white">Scikit-learn · Pandas · NumPy · ChromaDB · LangChain · OpenAI</dd></div>
          <div class="py-3 flex justify-between gap-4"><dt class="text-slate-500">Security</dt><dd class="text-right text-white">JWT · OAuth 2.0 · RBAC</dd></div>
          <div class="py-3 flex justify-between gap-4"><dt class="text-slate-500">Location</dt><dd class="text-right text-white">Chennai, Tamil Nadu</dd></div>
          <div class="py-3 flex justify-between gap-4"><dt class="text-slate-500">Languages</dt><dd class="text-right text-white">Tamil (Native) · English (Pro)</dd></div>
        </dl>
      </div>
    </div>
  </section>

  <!-- IMPACT -->
  <section id="impact" class="py-24 bg-ink-800/60 border-y border-white/5">
    <div class="max-w-6xl mx-auto px-6">
      <div class="reveal text-center">
        <p class="font-mono text-brand-400 text-sm">02 / impact</p>
        <h2 class="mt-2 text-3xl sm:text-4xl font-bold text-white">Impact at a Glance</h2>
      </div>

      <div class="mt-12 grid grid-cols-2 lg:grid-cols-3 gap-5">
        <div class="reveal glass rounded-2xl p-6 text-center hover:-translate-y-1 transition">
          <div class="text-4xl font-extrabold text-sky-400"><span class="count" data-to="87">0</span>%+</div>
          <p class="mt-2 text-xs tracking-widest text-slate-400">ML ACCURACY</p>
        </div>
        <div class="reveal glass rounded-2xl p-6 text-center hover:-translate-y-1 transition">
          <div class="text-4xl font-extrabold text-violet-400"><span class="count" data-to="30000" data-comma="1">0</span>+</div>
          <p class="mt-2 text-xs tracking-widest text-slate-400">PATIENT RECORDS PROCESSED</p>
        </div>
        <div class="reveal glass rounded-2xl p-6 text-center hover:-translate-y-1 transition">
          <div class="text-4xl font-extrabold text-emerald-400"><span class="count" data-to="30">0</span>%</div>
          <p class="mt-2 text-xs tracking-widest text-slate-400">FASTER AUDIT QUERIES</p>
        </div>
        <div class="reveal glass rounded-2xl p-6 text-center hover:-translate-y-1 transition">
          <div class="text-4xl font-extrabold text-amber-400"><span class="count" data-to="75">0</span>%+</div>
          <p class="mt-2 text-xs tracking-widest text-slate-400">TEST COVERAGE</p>
        </div>
        <div class="reveal glass rounded-2xl p-6 text-center hover:-translate-y-1 transition">
          <div class="text-4xl font-extrabold text-pink-400">+<span class="count" data-to="12">0</span>%</div>
          <p class="mt-2 text-xs tracking-widest text-slate-400">MODEL ACCURACY GAIN</p>
        </div>
        <div class="reveal glass rounded-2xl p-6 text-center hover:-translate-y-1 transition">
          <div class="text-4xl font-extrabold text-teal-400"><span class="count" data-to="0">0</span></div>
          <p class="mt-2 text-xs tracking-widest text-slate-400">DOWNTIME INCIDENTS</p>
        </div>
      </div>

      <!-- Problems -->
      <h3 class="reveal mt-20 text-2xl font-bold text-white">🧩 Problems I've Solved</h3>
      <div class="mt-8 grid md:grid-cols-2 gap-5">
        <article class="reveal glass rounded-2xl p-6">
          <p class="text-xs font-mono text-rose-400">PROBLEM</p>
          <h4 class="font-semibold text-white">Raw patient data was too noisy for reliable predictions</h4>
          <p class="mt-3 text-sm text-slate-400">Cleaned and preprocessed 30,000+ records (missing values, categorical encoding, StandardScaler).</p>
          <p class="mt-3 text-sm font-semibold text-emerald-400">→ +12% model accuracy</p>
        </article>
        <article class="reveal glass rounded-2xl p-6">
          <p class="text-xs font-mono text-rose-400">PROBLEM</p>
          <h4 class="font-semibold text-white">Audit queries were slow on large data</h4>
          <p class="mt-3 text-sm text-slate-400">Added composite indexes on <code class="text-brand-400">patient_id</code>, <code class="text-brand-400">risk_level</code>, <code class="text-brand-400">created_at</code> in MySQL.</p>
          <p class="mt-3 text-sm font-semibold text-emerald-400">→ 30% faster audit queries</p>
        </article>
        <article class="reveal glass rounded-2xl p-6">
          <p class="text-xs font-mono text-rose-400">PROBLEM</p>
          <h4 class="font-semibold text-white">Healthcare predictions had to be justified</h4>
          <p class="mt-3 text-sm text-slate-400">Stored every prediction with confidence score and top risk factors.</p>
          <p class="mt-3 text-sm font-semibold text-emerald-400">→ Complete audit trail for compliance</p>
        </article>
        <article class="reveal glass rounded-2xl p-6">
          <p class="text-xs font-mono text-rose-400">PROBLEM</p>
          <h4 class="font-semibold text-white">Clinical notes were hard to search by keyword</h4>
          <p class="mt-3 text-sm text-slate-400">Built a semantic search layer with ChromaDB, LangChain, Sentence Transformers and OpenAI embeddings.</p>
          <p class="mt-3 text-sm font-semibold text-emerald-400">→ Natural-language retrieval</p>
        </article>
        <article class="reveal glass rounded-2xl p-6">
          <p class="text-xs font-mono text-rose-400">PROBLEM</p>
          <h4 class="font-semibold text-white">Fraud investigators were flooded with false alerts</h4>
          <p class="mt-3 text-sm text-slate-400">Combined a rule engine with Isolation Forest and tuned thresholds for precision vs. recall.</p>
          <p class="mt-3 text-sm font-semibold text-emerald-400">→ Fewer false positives</p>
        </article>
        <article class="reveal glass rounded-2xl p-6">
          <p class="text-xs font-mono text-rose-400">PROBLEM</p>
          <h4 class="font-semibold text-white">Flagged transactions needed accountability</h4>
          <p class="mt-3 text-sm text-slate-400">Built an immutable audit trail of every flagged event, rule triggered, risk score and reviewer action.</p>
          <p class="mt-3 text-sm font-semibold text-emerald-400">→ Explainability &amp; audit reporting</p>
        </article>
      </div>
    </div>
  </section>

  <!-- ARCHITECTURE -->
  <section id="architecture" class="py-24 max-w-6xl mx-auto px-6">
    <div class="reveal">
      <p class="font-mono text-brand-400 text-sm">03 / architecture</p>
      <h2 class="mt-2 text-3xl sm:text-4xl font-bold text-white">Architecture Deep Dives</h2>
    </div>

    <div class="mt-10 grid lg:grid-cols-2 gap-8">
      <div class="reveal glass rounded-2xl p-6">
        <h3 class="font-semibold text-white mb-4">🛡️ Fraud Detection &amp; Audit Monitoring</h3>
        <div class="mermaid">
flowchart TD
    A[Incoming Transactions] --> B[Django REST API<br/>JWT + RBAC]
    B --> C[Rule Engine<br/>Threshold · Velocity · Duplicate]
    B --> D[Isolation Forest<br/>Anomaly Detection]
    C --> E{Risk Scoring}
    D --> E
    E -->|Flagged| F[Alert Triage &<br/>Case Management]
    E -->|Cleared| G[Cleared]
    F --> H[(PostgreSQL<br/>Immutable Audit Trail)]
    G --> H
    H --> I[Chart.js Dashboards]
        </div>
      </div>

      <div class="reveal glass rounded-2xl p-6">
        <h3 class="font-semibold text-white mb-4">🏥 Patient Risk Prediction API</h3>
        <div class="mermaid">
flowchart TD
    A[Client / Clinical Dashboard] -->|REST| B[Flask API<br/>4 endpoints]
    B --> C[Preprocessing<br/>Pandas · NumPy · Scaler]
    B --> D[Semantic Search<br/>LangChain + ChromaDB]
    D --> E[OpenAI Embeddings<br/>Sentence Transformers]
    C --> F[RandomForest<br/>Low / Medium / High]
    F --> G[(MySQL<br/>Predictions + Audit)]
    D --> G
        </div>
      </div>
    </div>
  </section>

  <!-- STACK -->
  <section id="stack" class="py-24 bg-ink-800/60 border-y border-white/5">
    <div class="max-w-6xl mx-auto px-6">
      <div class="reveal">
        <p class="font-mono text-brand-400 text-sm">04 / stack</p>
        <h2 class="mt-2 text-3xl sm:text-4xl font-bold text-white">Tech Stack</h2>
      </div>

      <div class="mt-10 grid md:grid-cols-2 lg:grid-cols-3 gap-6" id="stackGrid"></div>
    </div>
  </section>

  <!-- EXPERIENCE -->
  <section id="experience" class="py-24 max-w-4xl mx-auto px-6">
    <div class="reveal">
      <p class="font-mono text-brand-400 text-sm">05 / experience</p>
      <h2 class="mt-2 text-3xl sm:text-4xl font-bold text-white">Experience</h2>
    </div>

    <ol class="mt-12 relative border-l border-white/10 ml-3 space-y-12">
      <li class="reveal pl-8 relative">
        <span class="absolute -left-[9px] top-1.5 w-4 h-4 rounded-full bg-brand-500 ring-4 ring-ink-900"></span>
        <div class="glass rounded-2xl p-6">
          <div class="flex flex-wrap items-baseline justify-between gap-2">
            <h3 class="text-xl font-semibold text-white">Python Backend Developer · <span class="text-brand-400">Flay High Software</span></h3>
            <span class="text-xs font-mono text-slate-400">Dec 2025 – Present</span>
          </div>
          <p class="text-sm italic text-slate-400 mt-1">Fraud Detection &amp; Audit Monitoring Platform</p>
          <ul class="mt-4 space-y-2 text-sm leading-relaxed list-disc list-inside marker:text-brand-400">
            <li>Designed and built a fraud detection and audit monitoring backend that screens transactions in real time and flags suspicious activity for audit and compliance teams.</li>
            <li>Implemented a configurable rule engine (threshold, velocity, duplicate-entry, unusual-pattern) combined with Scikit-learn <b class="text-white">Isolation Forest</b> to generate risk scores.</li>
            <li>Engineered features with Pandas and NumPy and tuned alert thresholds to balance precision and recall, reducing false positives.</li>
            <li>Built alert triage and case management APIs (assignment, status, investigator notes, resolution) with <b class="text-white">RBAC</b> and <b class="text-white">JWT</b>.</li>
            <li>Created an immutable audit trail logging every flagged event, rule triggered, risk score and reviewer action.</li>
            <li>Developed Chart.js dashboards for flagged transactions, risk trends and alert status.</li>
            <li>Wrote pytest suites for rules, scoring and alert workflows; containerized with Docker.</li>
          </ul>
          <div class="mt-4 flex flex-wrap gap-2 text-xs font-mono">
            <span class="px-2 py-1 rounded bg-white/5">Python</span><span class="px-2 py-1 rounded bg-white/5">DRF</span><span class="px-2 py-1 rounded bg-white/5">PostgreSQL</span><span class="px-2 py-1 rounded bg-white/5">Pandas</span><span class="px-2 py-1 rounded bg-white/5">Scikit-learn</span><span class="px-2 py-1 rounded bg-white/5">Docker</span><span class="px-2 py-1 rounded bg-white/5">pytest</span>
          </div>
        </div>
      </li>

      <li class="reveal pl-8 relative">
        <span class="absolute -left-[9px] top-1.5 w-4 h-4 rounded-full bg-violet-500 ring-4 ring-ink-900"></span>
        <div class="glass rounded-2xl p-6">
          <div class="flex flex-wrap items-baseline justify-between gap-2">
            <h3 class="text-xl font-semibold text-white">Python Backend Developer · <span class="text-violet-400">NSEIT</span></h3>
            <span class="text-xs font-mono text-slate-400">Oct 2024 – Nov 2025</span>
          </div>
          <p class="text-sm italic text-slate-400 mt-1">Healthcare Patient Risk Prediction API</p>
          <ul class="mt-4 space-y-2 text-sm leading-relaxed list-disc list-inside marker:text-violet-400">
            <li>Built and deployed a Flask REST API serving a Scikit-learn <b class="text-white">RandomForest</b> model that classifies patient risk (Low / Medium / High) with <b class="text-white">87%+ accuracy</b>, via 4 REST endpoints.</li>
            <li>Preprocessed <b class="text-white">30,000+ patient records</b> with Pandas and NumPy, improving model accuracy by <b class="text-white">12%</b>.</li>
            <li>Optimized MySQL schema with composite indexes, reducing audit query response time by <b class="text-white">30%</b>.</li>
            <li>Stored every prediction with confidence score and top risk factors for compliance reporting and monitoring.</li>
            <li>Built a semantic search layer over clinical notes using ChromaDB, LangChain, Sentence Transformers and OpenAI embeddings.</li>
            <li>Reached <b class="text-white">75%+ code coverage</b> with unittest and deployed to Linux production with <b class="text-white">zero downtime incidents</b>.</li>
          </ul>
          <div class="mt-4 flex flex-wrap gap-2 text-xs font-mono">
            <span class="px-2 py-1 rounded bg-white/5">Flask</span><span class="px-2 py-1 rounded bg-white/5">Scikit-learn</span><span class="px-2 py-1 rounded bg-white/5">MySQL</span><span class="px-2 py-1 rounded bg-white/5">ChromaDB</span><span class="px-2 py-1 rounded bg-white/5">LangChain</span><span class="px-2 py-1 rounded bg-white/5">OpenAI API</span>
          </div>
        </div>
      </li>
    </ol>
  </section>

  <!-- PROJECTS -->
  <section id="projects" class="py-24 bg-ink-800/60 border-y border-white/5">
    <div class="max-w-6xl mx-auto px-6">
      <div class="reveal">
        <p class="font-mono text-brand-400 text-sm">06 / projects</p>
        <h2 class="mt-2 text-3xl sm:text-4xl font-bold text-white">Featured Projects</h2>
      </div>

      <div class="mt-10 grid md:grid-cols-2 gap-8">
        <article class="reveal group glass rounded-2xl p-7 hover:border-brand-500/50 hover:-translate-y-1 transition">
          <div class="text-4xl">🛡️</div>
          <h3 class="mt-4 text-xl font-bold text-white">Fraud Detection &amp; Audit Monitoring</h3>
          <p class="text-sm text-slate-400 italic">Rule engine + ML anomaly detection</p>
          <ul class="mt-4 space-y-1.5 text-sm list-disc list-inside marker:text-brand-400">
            <li>Configurable rules: threshold, velocity, duplicates</li>
            <li>Isolation Forest risk scoring</li>
            <li>Alert triage, case management, RBAC + JWT</li>
            <li>Immutable audit trail</li>
            <li>Chart.js dashboards</li>
            <li>Dockerized and tested with pytest</li>
          </ul>
          <div class="mt-5 flex flex-wrap gap-2 text-xs font-mono text-brand-400">
            <span class="px-2 py-1 rounded bg-brand-500/10">Django REST</span><span class="px-2 py-1 rounded bg-brand-500/10">PostgreSQL</span><span class="px-2 py-1 rounded bg-brand-500/10">Scikit-learn</span><span class="px-2 py-1 rounded bg-brand-500/10">Docker</span>
          </div>
          <a href="https://github.com/punniyam26-hash?tab=repositories" target="_blank" rel="noopener" class="mt-6 inline-flex items-center gap-1 text-sm font-semibold text-white group-hover:text-brand-400 transition">View Repository <span>→</span></a>
        </article>

        <article class="reveal group glass rounded-2xl p-7 hover:border-violet-500/50 hover:-translate-y-1 transition">
          <div class="text-4xl">🏥</div>
          <h3 class="mt-4 text-xl font-bold text-white">Patient Risk Prediction API</h3>
          <p class="text-sm text-slate-400 italic">ML-powered healthcare risk classifier</p>
          <ul class="mt-4 space-y-1.5 text-sm list-disc list-inside marker:text-violet-400">
            <li>87%+ accuracy RandomForest model</li>
            <li>Predictions stored with confidence scores</li>
            <li>Semantic search over clinical notes</li>
            <li>Composite-indexed MySQL (30% faster queries)</li>
            <li>75%+ test coverage with unittest</li>
          </ul>
          <div class="mt-5 flex flex-wrap gap-2 text-xs font-mono text-violet-300">
            <span class="px-2 py-1 rounded bg-violet-500/10">Flask</span><span class="px-2 py-1 rounded bg-violet-500/10">Scikit-learn</span><span class="px-2 py-1 rounded bg-violet-500/10">MySQL</span><span class="px-2 py-1 rounded bg-violet-500/10">ChromaDB</span><span class="px-2 py-1 rounded bg-violet-500/10">LangChain</span>
          </div>
          <a href="https://github.com/punniyam26-hash?tab=repositories" target="_blank" rel="noopener" class="mt-6 inline-flex items-center gap-1 text-sm font-semibold text-white group-hover:text-violet-300 transition">View Repository <span>→</span></a>
        </article>
      </div>

      <!-- What I bring -->
      <h3 class="reveal mt-20 text-2xl font-bold text-white">What I Bring to Your Team</h3>
      <div class="mt-8 grid sm:grid-cols-2 lg:grid-cols-4 gap-5">
        <div class="reveal glass rounded-2xl p-5"><div class="text-2xl">🔁</div><h4 class="mt-2 font-semibold text-white">End-to-end ownership</h4><p class="mt-1 text-sm text-slate-400">Requirements → data model → API → ML integration → deployment.</p></div>
        <div class="reveal glass rounded-2xl p-5"><div class="text-2xl">⚙️</div><h4 class="mt-2 font-semibold text-white">Production mindset</h4><p class="mt-1 text-sm text-slate-400">Indexing, audit trails, RBAC, testing and zero-downtime deployments.</p></div>
        <div class="reveal glass rounded-2xl p-5"><div class="text-2xl">🏛️</div><h4 class="mt-2 font-semibold text-white">Regulated domains</h4><p class="mt-1 text-sm text-slate-400">Healthcare and fraud work taught explainability and traceability.</p></div>
        <div class="reveal glass rounded-2xl p-5"><div class="text-2xl">💼</div><h4 class="mt-2 font-semibold text-white">Business understanding</h4><p class="mt-1 text-sm text-slate-400">MBA in Business Management &amp; Operations.</p></div>
      </div>
    </div>
  </section>

  <!-- EDUCATION -->
  <section id="education" class="py-24 max-w-6xl mx-auto px-6">
    <div class="reveal">
      <p class="font-mono text-brand-400 text-sm">07 / education</p>
      <h2 class="mt-2 text-3xl sm:text-4xl font-bold text-white">Education &amp; Certifications</h2>
    </div>
    <div class="mt-10 grid md:grid-cols-3 gap-6">
      <div class="reveal glass rounded-2xl p-6"><div class="text-3xl">🎓</div><h3 class="mt-3 font-semibold text-white">MBA, Business Management &amp; Operations</h3><p class="text-sm text-slate-400 mt-1">Anna University, Chennai</p><p class="text-xs font-mono text-brand-400 mt-3">2022 – 2024</p></div>
      <div class="reveal glass rounded-2xl p-6"><div class="text-3xl">📘</div><h3 class="mt-3 font-semibold text-white">B.Com, Commerce, Accounting &amp; Business Studies</h3><p class="text-sm text-slate-400 mt-1">Bharathidasan University</p><p class="text-xs font-mono text-brand-400 mt-3">2019 – 2022</p></div>
      <div class="reveal glass rounded-2xl p-6"><div class="text-3xl">📜</div><h3 class="mt-3 font-semibold text-white">Python, React, FastAPI</h3><p class="text-sm text-slate-400 mt-1">Udemy Certification</p><p class="text-xs font-mono text-brand-400 mt-3">2024</p></div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="relative py-28 overflow-hidden bg-gradient-to-br from-ink-700 via-ink-600 to-ink-500">
    <div class="absolute inset-0 grid-bg opacity-60"></div>
    <div class="relative max-w-3xl mx-auto px-6 text-center reveal">
      <p class="font-mono text-brand-400 text-sm">08 / contact</p>
      <h2 class="mt-2 text-3xl sm:text-5xl font-extrabold text-white">Hiring for a Python Backend / API role?</h2>
      <p class="mt-4 text-lg text-slate-300">Open to opportunities in <b class="text-white">Chennai</b> (on-site / hybrid) &amp; <b class="text-white">Remote</b>.</p>

      <form id="contactForm" class="mt-10 glass rounded-2xl p-6 text-left space-y-4">
        <div class="grid sm:grid-cols-2 gap-4">
          <input required name="name" placeholder="Your name" class="w-full rounded-xl bg-white/5 border border-white/10 px-4 py-3 text-white placeholder-slate-500 focus:outline-none focus:ring-2 focus:ring-brand-500" />
          <input required type="email" name="email" placeholder="Your email" class="w-full rounded-xl bg-white/5 border border-white/10 px-4 py-3 text-white placeholder-slate-500 focus:outline-none focus:ring-2 focus:ring-brand-500" />
        </div>
        <textarea required name="message" rows="4" placeholder="Tell me about the role..." class="w-full rounded-xl bg-white/5 border border-white/10 px-4 py-3 text-white placeholder-slate-500 focus:outline-none focus:ring-2 focus:ring-brand-500"></textarea>
        <button class="w-full rounded-xl bg-brand-500 hover:bg-brand-600 py-3 font-semibold text-white transition">Send Message</button>
      </form>

      <div class="mt-8 flex flex-wrap justify-center gap-4">
        <a href="mailto:punniyam26@gmail.com" class="rounded-xl bg-red-500 hover:bg-red-600 px-6 py-3 font-semibold text-white transition">✉️ Email Me</a>
        <a href="https://www.linkedin.com/in/punniyamoorthy-k" target="_blank" rel="noopener" class="rounded-xl bg-[#0A66C2] hover:brightness-110 px-6 py-3 font-semibold text-white transition">in LinkedIn</a>
        <a href="https://github.com/punniyam26-hash" target="_blank" rel="noopener" class="rounded-xl bg-slate-800 hover:bg-slate-700 px-6 py-3 font-semibold text-white transition">GitHub</a>
      </div>
    </div>
  </section>

  <footer class="py-8 text-center text-sm text-slate-500 border-t border-white/5">
    <p class="font-mono italic">"Make it work, make it right, make it fast."</p>
    <p class="mt-2">© <span id="year"></span> Punniyamoorthy K · Built with Tailwind CSS</p>
  </footer>

  <button id="toTop" class="fixed bottom-6 right-6 z-50 hidden rounded-full bg-brand-500 hover:bg-brand-600 w-11 h-11 text-white shadow-lg" aria-label="Back to top">↑</button>

  <script>
    // Year
    document.getElementById('year').textContent = new Date().getFullYear();

    // Mobile menu
    const menuBtn = document.getElementById('menuBtn'), mobileMenu = document.getElementById('mobileMenu');
    menuBtn.addEventListener('click', () => mobileMenu.classList.toggle('hidden'));
    mobileMenu.querySelectorAll('a').forEach(a => a.addEventListener('click', () => mobileMenu.classList.add('hidden')));

    // Typing effect
    const phrases = [
      'Python Backend | API Developer',
      'Django · DRF · Flask · FastAPI · PostgreSQL',
      'Fraud Detection & Audit Monitoring',
      'Machine Learning · LLM Semantic Search',
    ];
    let p = 0, c = 0, del = false;
    const typed = document.getElementById('typed');
    (function tick() {
      const cur = phrases[p];
      typed.textContent = cur.slice(0, c);
      if (!del && c < cur.length) c++;
      else if (del && c > 0) c--;
      else if (!del) { del = true; return setTimeout(tick, 1400); }
      else { del = false; p = (p + 1) % phrases.length; }
      setTimeout(tick, del ? 28 : 65);
    })();

    // Scroll reveal
    const io = new IntersectionObserver(es => es.forEach(e => {
      if (e.isIntersecting) { e.target.classList.add('show'); io.unobserve(e.target); }
    }), { threshold: 0.12 });
    document.querySelectorAll('.reveal').forEach(el => io.observe(el));

    // Counters
    const co = new IntersectionObserver(es => es.forEach(e => {
      if (!e.isIntersecting) return;
      const el = e.target, to = +el.dataset.to, comma = el.dataset.comma;
      const start = performance.now(), dur = 1600;
      (function step(t) {
        const k = Math.min((t - start) / dur, 1), v = Math.round(to * (1 - Math.pow(1 - k, 3)));
        el.textContent = comma ? v.toLocaleString() : v;
        if (k < 1) requestAnimationFrame(step);
      })(start);
      co.unobserve(el);
    }), { threshold: 0.6 });
    document.querySelectorAll('.count').forEach(el => co.observe(el));

    // Scroll progress + back to top
    const bar = document.getElementById('progress'), toTop = document.getElementById('toTop');
    addEventListener('scroll', () => {
      const h = document.documentElement;
      bar.style.width = (h.scrollTop / (h.scrollHeight - h.clientHeight) * 100) + '%';
      toTop.classList.toggle('hidden', h.scrollTop < 600);
    });
    toTop.addEventListener('click', () => scrollTo({ top: 0, behavior: 'smooth' }));

    // Tech stack
    const stack = [
      { t: 'Languages', c: 'sky', i: ['Python', 'SQL', 'JavaScript', 'HTML5', 'CSS3'] },
      { t: 'Backend', c: 'emerald', i: ['Django', 'Django REST Framework', 'Flask', 'FastAPI', 'JWT', 'OAuth 2.0', 'RBAC'] },
      { t: 'Databases', c: 'blue', i: ['PostgreSQL', 'MySQL', 'Schema Design', 'Indexing', 'Query Optimization'] },
      { t: 'AI / ML', c: 'orange', i: ['Scikit-learn', 'Pandas', 'NumPy', 'ChromaDB', 'LangChain', 'OpenAI API', 'Sentence Transformers', 'joblib', 'Isolation Forest', 'RandomForest', 'Logistic Regression', 'Anomaly Detection', 'Feature Engineering', 'Semantic Search'] },
      { t: 'Fraud & Audit', c: 'rose', i: ['Rule Engines', 'Risk Scoring', 'Alert Triage', 'Audit Trail Logging', 'Case Management', 'Compliance Reporting'] },
      { t: 'Testing', c: 'amber', i: ['pytest', 'unittest', 'TDD', 'Integration Testing', 'Code Coverage'] },
      { t: 'Tools & DevOps', c: 'violet', i: ['Git', 'GitHub', 'Docker', 'Linux', 'Postman', 'Agile / Scrum', 'CI/CD (foundational)'] },
      { t: 'Frontend (working)', c: 'cyan', i: ['React', 'Chart.js', 'Tailwind CSS'] },
    ];
    const colors = {
      sky: 'bg-sky-500/10 text-sky-300 border-sky-500/30', emerald: 'bg-emerald-500/10 text-emerald-300 border-emerald-500/30',
      blue: 'bg-blue-500/10 text-blue-300 border-blue-500/30', orange: 'bg-orange-500/10 text-orange-300 border-orange-500/30',
      rose: 'bg-rose-500/10 text-rose-300 border-rose-500/30', amber: 'bg-amber-500/10 text-amber-300 border-amber-500/30',
      violet: 'bg-violet-500/10 text-violet-300 border-violet-500/30', cyan: 'bg-cyan-500/10 text-cyan-300 border-cyan-500/30',
    };
    document.getElementById('stackGrid').innerHTML = stack.map(s => `
      <div class="reveal glass rounded-2xl p-6">
        <h3 class="font-semibold text-white mb-4">${s.t}</h3>
        <div class="flex flex-wrap gap-2">
          ${s.i.map(x => `<span class="text-xs font-medium border rounded-full px-3 py-1 ${colors[s.c]} hover:scale-105 transition">${x}</span>`).join('')}
        </div>
      </div>`).join('');
    document.querySelectorAll('#stackGrid .reveal').forEach(el => io.observe(el));

    // Contact form -> opens mail client
    document.getElementById('contactForm').addEventListener('submit', e => {
      e.preventDefault();
      const f = new FormData(e.target);
      const body = `${f.get('message')}\n\n— ${f.get('name')} (${f.get('email')})`;
      location.href = `mailto:punniyam26@gmail.com?subject=${encodeURIComponent('Opportunity for Punniyamoorthy K')}&body=${encodeURIComponent(body)}`;
    });

    // Mermaid
    mermaid.initialize({
      startOnLoad: true, theme: 'dark',
      themeVariables: { primaryColor: '#0f2027', primaryBorderColor: '#38bdf8', lineColor: '#38bdf8', primaryTextColor: '#e2e8f0', fontFamily: 'Inter' },
      flowchart: { htmlLabels: true, curve: 'basis' },
    });
  </script>
</body>
</html>
