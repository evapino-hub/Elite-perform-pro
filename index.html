<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ElitePerform Pro | Dashboard</title>
  <link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;500;600;700;800&family=DM+Sans:ital,wght@0,300;0,400;0,500;1,300&display=swap" rel="stylesheet" />
  <style>
    /* ── Reset & tokens ─────────────────────────────────────────── */
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
    :root {
      --bg-base:        #080810;
      --bg-surface:     #0f0f1a;
      --bg-card:        #13131f;
      --bg-card-hover:  #18182a;
      --border:         rgba(255,255,255,0.07);
      --border-bright:  rgba(255,255,255,0.14);
      --text-primary:   #f0f0f8;
      --text-secondary: #8a8aa8;
      --text-muted:     #55556a;
      --accent-a:       #6c63ff;
      --accent-b:       #00d4ff;
      --accent-c:       #ff6b9d;
      --accent-green:   #00e5a0;
      --accent-amber:   #ffb547;
      --font-display:   'Syne', sans-serif;
      --font-body:      'DM Sans', sans-serif;
      --radius-sm:      8px;
      --radius-md:      14px;
      --radius-lg:      20px;
      --radius-xl:      28px;
    }

    html { scroll-behavior: smooth; }
    body {
      font-family: var(--font-body);
      background-color: var(--bg-base);
      color: var(--text-primary);
      min-height: 100vh;
      overflow-x: hidden;
    }

    /* ── Background ambient ─────────────────────────────────────── */
    .ambient {
      position: fixed; inset: 0; pointer-events: none; z-index: 0;
      background:
        radial-gradient(ellipse 60% 50% at 10% 15%, rgba(108,99,255,0.12) 0%, transparent 70%),
        radial-gradient(ellipse 40% 40% at 90% 80%, rgba(0,212,255,0.08) 0%, transparent 60%),
        radial-gradient(ellipse 50% 30% at 50% 100%, rgba(255,107,157,0.06) 0%, transparent 60%);
    }

    /* ── Layout wrapper ─────────────────────────────────────────── */
    .layout { position: relative; z-index: 1; display: flex; flex-direction: column; min-height: 100vh; }

    /* ── Navigation ─────────────────────────────────────────────── */
    nav {
      display: flex; align-items: center; justify-content: space-between;
      padding: 0 2rem; height: 64px;
      border-bottom: 1px solid var(--border);
      background: rgba(8,8,16,0.85);
      backdrop-filter: blur(20px);
      position: sticky; top: 0; z-index: 100;
    }
    .nav-logo {
      font-family: var(--font-display);
      font-weight: 800; font-size: 1.1rem;
      letter-spacing: 0.04em;
      color: var(--text-primary);
    }
    .nav-logo span { color: var(--accent-b); }
    .nav-actions { display: flex; align-items: center; gap: 0.75rem; }
    .nav-pill {
      font-family: var(--font-body);
      font-size: 0.78rem; font-weight: 500;
      padding: 0.4rem 1rem;
      border-radius: 99px;
      border: 1px solid var(--border-bright);
      background: transparent;
      color: var(--text-secondary);
      cursor: pointer;
      transition: background 0.2s, color 0.2s, border-color 0.2s;
    }
    .nav-pill:hover { background: var(--bg-card); color: var(--text-primary); border-color: var(--border-bright); }
    .nav-pill.primary {
      background: var(--accent-a);
      border-color: transparent;
      color: #fff;
    }
    .nav-pill.primary:hover { background: #7a72ff; }

    /* ── Avatar initials ────────────────────────────────────────── */
    .avatar {
      width: 32px; height: 32px; border-radius: 50%;
      background: linear-gradient(135deg, var(--accent-a), var(--accent-c));
      display: flex; align-items: center; justify-content: center;
      font-size: 0.7rem; font-weight: 700; color: #fff;
      flex-shrink: 0;
    }

    /* ── Main grid ──────────────────────────────────────────────── */
    main {
      flex: 1;
      display: grid;
      grid-template-columns: 280px 1fr;
      grid-template-rows: auto 1fr;
      gap: 0;
    }

    /* ── Sidebar ────────────────────────────────────────────────── */
    aside {
      grid-row: 1 / -1;
      border-right: 1px solid var(--border);
      padding: 1.5rem;
      display: flex; flex-direction: column; gap: 1.25rem;
      background: rgba(13,13,22,0.6);
    }

    /* ── Content area ───────────────────────────────────────────── */
    .content { padding: 1.5rem; display: flex; flex-direction: column; gap: 1.25rem; }

    /* ── Card base ──────────────────────────────────────────────── */
    .card {
      background: var(--bg-card);
      border: 1px solid var(--border);
      border-radius: var(--radius-lg);
      padding: 1.25rem 1.5rem;
      transition: border-color 0.2s;
    }
    .card:hover { border-color: var(--border-bright); }

    /* ── Section label ──────────────────────────────────────────── */
    .section-label {
      font-family: var(--font-display);
      font-size: 0.65rem; font-weight: 700;
      letter-spacing: 0.12em; text-transform: uppercase;
      color: var(--text-muted);
      margin-bottom: 1rem;
    }

    /* ── HRV Hero card ──────────────────────────────────────────── */
    .hrv-card {
      background: linear-gradient(145deg, #13131f 0%, #0e0e1e 100%);
      border: 1px solid rgba(108,99,255,0.3);
      border-radius: var(--radius-lg);
      padding: 1.5rem;
      position: relative;
      overflow: hidden;
    }
    .hrv-card::before {
      content: '';
      position: absolute; top: -40px; right: -40px;
      width: 140px; height: 140px; border-radius: 50%;
      background: radial-gradient(circle, rgba(108,99,255,0.18) 0%, transparent 70%);
    }
    .hrv-value {
      font-family: var(--font-display);
      font-size: 3.5rem; font-weight: 800;
      line-height: 1;
      color: var(--text-primary);
      letter-spacing: -0.02em;
    }
    .hrv-unit { font-size: 1.1rem; color: var(--text-secondary); font-weight: 400; }
    .status-badge {
      display: inline-flex; align-items: center; gap: 6px;
      padding: 0.3rem 0.75rem;
      border-radius: 99px;
      font-size: 0.75rem; font-weight: 500;
      margin-top: 0.5rem;
    }
    .status-badge.optimal { background: rgba(0,229,160,0.12); color: var(--accent-green); }
    .status-badge.warning { background: rgba(255,181,71,0.12); color: var(--accent-amber); }
    .status-badge.dot::before {
      content: ''; display: block;
      width: 6px; height: 6px; border-radius: 50%;
      background: currentColor;
      animation: pulse-dot 2s infinite;
    }
    @keyframes pulse-dot {
      0%,100% { opacity: 1; }
      50% { opacity: 0.3; }
    }
    .hrv-meta { display: flex; gap: 1rem; margin-top: 1rem; }
    .hrv-meta-item { font-size: 0.75rem; color: var(--text-secondary); }
    .hrv-meta-item strong { display: block; font-size: 0.95rem; font-weight: 600; color: var(--text-primary); }

    /* ── Sparkline ──────────────────────────────────────────────── */
    .sparkline { width: 100%; height: 48px; margin-top: 0.75rem; }

    /* ── Cycle card ─────────────────────────────────────────────── */
    .cycle-phases { display: flex; gap: 4px; margin: 0.75rem 0; }
    .cycle-phase {
      flex: 1; height: 6px; border-radius: 99px;
      background: var(--border);
      position: relative; overflow: hidden;
    }
    .cycle-phase.active { background: linear-gradient(90deg, var(--accent-a), var(--accent-b)); }
    .cycle-phase.past { background: rgba(108,99,255,0.35); }
    .phase-labels {
      display: flex; justify-content: space-between;
      font-size: 0.65rem; color: var(--text-muted);
    }
    .symptom-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 0.5rem; margin-top: 0.75rem; }
    .symptom-chip {
      font-size: 0.72rem; font-weight: 500;
      padding: 0.35rem 0.6rem;
      border-radius: var(--radius-sm);
      border: 1px solid var(--border-bright);
      color: var(--text-secondary);
      background: transparent;
      cursor: pointer;
      transition: all 0.15s;
      text-align: center;
    }
    .symptom-chip:hover, .symptom-chip.active { background: rgba(108,99,255,0.15); border-color: var(--accent-a); color: var(--text-primary); }

    /* ── Nav items sidebar ──────────────────────────────────────── */
    .nav-group-label {
      font-size: 0.62rem; font-weight: 700; letter-spacing: 0.1em;
      text-transform: uppercase; color: var(--text-muted);
      padding: 0 0.5rem; margin-top: 0.5rem;
    }
    .nav-item {
      display: flex; align-items: center; gap: 10px;
      padding: 0.6rem 0.75rem;
      border-radius: var(--radius-sm);
      font-size: 0.82rem; font-weight: 500;
      color: var(--text-secondary);
      cursor: pointer;
      transition: background 0.15s, color 0.15s;
      border: none; background: none; width: 100%; text-align: left;
    }
    .nav-item:hover { background: var(--bg-card); color: var(--text-primary); }
    .nav-item.active { background: rgba(108,99,255,0.15); color: var(--accent-a); }
    .nav-item .icon { font-size: 1rem; width: 20px; text-align: center; }
    .nav-item .badge {
      margin-left: auto; font-size: 0.65rem; font-weight: 600;
      padding: 2px 6px; border-radius: 99px;
      background: var(--accent-a); color: #fff;
    }

    /* ── Activity register ──────────────────────────────────────── */
    .sport-row { display: flex; gap: 0.75rem; align-items: center; }
    .sport-select {
      flex: 1;
      background: var(--bg-surface);
      border: 1px solid var(--border-bright);
      border-radius: var(--radius-sm);
      padding: 0.55rem 0.9rem;
      color: var(--text-primary);
      font-family: var(--font-body);
      font-size: 0.83rem;
      appearance: none;
      background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='12' height='12' fill='%238a8aa8' viewBox='0 0 16 16'%3E%3Cpath d='M7.247 11.14L2.451 5.658C1.885 5.013 2.345 4 3.204 4h9.592a1 1 0 0 1 .753 1.659l-4.796 5.48a1 1 0 0 1-1.506 0z'/%3E%3C/svg%3E");
      background-repeat: no-repeat;
      background-position: right 0.75rem center;
      cursor: pointer;
    }
    .sport-select:focus { outline: none; border-color: var(--accent-a); }
    .add-btn {
      font-family: var(--font-body); font-size: 0.8rem; font-weight: 500;
      padding: 0.55rem 1rem;
      border-radius: var(--radius-sm);
      border: 1px solid var(--border-bright);
      background: transparent; color: var(--text-secondary);
      cursor: pointer; white-space: nowrap;
      transition: all 0.15s;
    }
    .add-btn:hover { background: var(--bg-card); color: var(--text-primary); border-color: var(--accent-a); }

    /* ── RPE slider ─────────────────────────────────────────────── */
    .rpe-row { display: flex; align-items: center; gap: 1rem; margin-top: 1rem; }
    .rpe-label { font-size: 0.78rem; color: var(--text-secondary); min-width: 110px; }
    .rpe-value {
      font-family: var(--font-display); font-size: 1.2rem; font-weight: 700;
      color: var(--text-primary); min-width: 28px; text-align: right;
    }
    input[type="range"] {
      -webkit-appearance: none; appearance: none;
      flex: 1; height: 4px;
      border-radius: 99px;
      background: var(--border-bright);
      outline: none; cursor: pointer;
    }
    input[type="range"]::-webkit-slider-thumb {
      -webkit-appearance: none;
      width: 18px; height: 18px; border-radius: 50%;
      background: var(--accent-a);
      border: 2px solid var(--bg-base);
      box-shadow: 0 0 0 2px var(--accent-a);
      transition: transform 0.15s;
    }
    input[type="range"]:hover::-webkit-slider-thumb { transform: scale(1.15); }
    .rpe-zones { display: flex; justify-content: space-between; font-size: 0.62rem; color: var(--text-muted); margin-top: 4px; }

    /* ── Session meta ───────────────────────────────────────────── */
    .session-meta { display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 0.75rem; margin-top: 1rem; }
    .meta-input-wrap { display: flex; flex-direction: column; gap: 4px; }
    .meta-input-wrap label { font-size: 0.68rem; color: var(--text-muted); }
    .meta-input {
      background: var(--bg-surface);
      border: 1px solid var(--border);
      border-radius: var(--radius-sm);
      padding: 0.45rem 0.7rem;
      color: var(--text-primary);
      font-family: var(--font-body); font-size: 0.82rem;
      width: 100%;
    }
    .meta-input:focus { outline: none; border-color: var(--accent-a); }

    /* ── AI Chat ────────────────────────────────────────────────── */
    .chat-card {
      background: var(--bg-card);
      border: 1px solid rgba(0,212,255,0.2);
      border-radius: var(--radius-lg);
      padding: 1.25rem 1.5rem;
      display: flex; flex-direction: column; gap: 1rem;
    }
    .chat-header { display: flex; align-items: center; gap: 10px; }
    .ai-dot {
      width: 8px; height: 8px; border-radius: 50%;
      background: var(--accent-b);
      animation: pulse-dot 2s infinite;
    }
    .chat-label {
      font-family: var(--font-display); font-size: 0.65rem; font-weight: 700;
      letter-spacing: 0.12em; text-transform: uppercase; color: var(--text-muted);
    }
    .chat-history {
      max-height: 160px; overflow-y: auto;
      display: flex; flex-direction: column; gap: 0.6rem;
      scrollbar-width: thin; scrollbar-color: var(--border) transparent;
    }
    .chat-msg { font-size: 0.82rem; line-height: 1.5; }
    .chat-msg.ai { color: var(--accent-b); }
    .chat-msg.user { color: var(--text-secondary); align-self: flex-end; text-align: right; }
    .chat-input-row { display: flex; gap: 0.5rem; }
    .chat-input {
      flex: 1;
      background: var(--bg-surface);
      border: 1px solid var(--border-bright);
      border-radius: var(--radius-sm);
      padding: 0.6rem 1rem;
      color: var(--text-primary);
      font-family: var(--font-body); font-size: 0.82rem;
    }
    .chat-input::placeholder { color: var(--text-muted); }
    .chat-input:focus { outline: none; border-color: var(--accent-b); }
    .send-btn {
      padding: 0.6rem 1rem;
      border-radius: var(--radius-sm);
      background: rgba(0,212,255,0.15);
      border: 1px solid rgba(0,212,255,0.3);
      color: var(--accent-b);
      font-size: 0.82rem; font-weight: 500;
      cursor: pointer; transition: background 0.15s;
      font-family: var(--font-body);
    }
    .send-btn:hover { background: rgba(0,212,255,0.25); }

    /* ── Weekly load chart ──────────────────────────────────────── */
    .bar-chart { display: flex; align-items: flex-end; gap: 6px; height: 72px; margin-top: 0.75rem; }
    .bar-col { flex: 1; display: flex; flex-direction: column; align-items: center; gap: 4px; }
    .bar {
      width: 100%; border-radius: 5px 5px 0 0;
      transition: opacity 0.2s;
    }
    .bar-col:hover .bar { opacity: 0.75; }
    .bar-day { font-size: 0.62rem; color: var(--text-muted); }

    /* ── Metrics row ────────────────────────────────────────────── */
    .metrics-row { display: grid; grid-template-columns: repeat(3, 1fr); gap: 0.75rem; }
    .metric-card {
      background: var(--bg-card);
      border: 1px solid var(--border);
      border-radius: var(--radius-md);
      padding: 1rem;
      transition: border-color 0.2s;
    }
    .metric-card:hover { border-color: var(--border-bright); }
    .metric-title { font-size: 0.68rem; color: var(--text-muted); margin-bottom: 0.35rem; }
    .metric-value {
      font-family: var(--font-display); font-size: 1.6rem; font-weight: 700;
      line-height: 1; letter-spacing: -0.01em;
    }
    .metric-delta { font-size: 0.72rem; margin-top: 0.25rem; }
    .metric-delta.up { color: var(--accent-green); }
    .metric-delta.down { color: var(--accent-c); }
    .metric-delta.neutral { color: var(--text-muted); }

    /* ── Save button ────────────────────────────────────────────── */
    .save-session-btn {
      font-family: var(--font-display); font-size: 0.85rem; font-weight: 700;
      letter-spacing: 0.04em;
      padding: 0.75rem 1.5rem;
      border-radius: var(--radius-md);
      background: linear-gradient(135deg, var(--accent-a), var(--accent-b));
      border: none; color: #fff; cursor: pointer;
      width: 100%; margin-top: 1rem;
      transition: opacity 0.2s, transform 0.1s;
    }
    .save-session-btn:hover { opacity: 0.9; }
    .save-session-btn:active { transform: scale(0.98); }

    /* ── Notification toast ─────────────────────────────────────── */
    #toast {
      position: fixed; bottom: 2rem; right: 2rem;
      background: var(--bg-card); border: 1px solid var(--accent-green);
      color: var(--accent-green); border-radius: var(--radius-md);
      padding: 0.75rem 1.25rem; font-size: 0.82rem; font-weight: 500;
      opacity: 0; transform: translateY(12px);
      transition: opacity 0.25s, transform 0.25s;
      pointer-events: none; z-index: 200;
    }
    #toast.show { opacity: 1; transform: translateY(0); }

    /* ── Responsive ─────────────────────────────────────────────── */
    @media (max-width: 860px) {
      main { grid-template-columns: 1fr; }
      aside { border-right: none; border-bottom: 1px solid var(--border); flex-direction: row; flex-wrap: wrap; }
      .metrics-row { grid-template-columns: 1fr 1fr; }
    }
    @media (max-width: 560px) {
      .metrics-row { grid-template-columns: 1fr; }
      .session-meta { grid-template-columns: 1fr 1fr; }
    }
  </style>
</head>
<body>
<div class="ambient" aria-hidden="true"></div>
<div class="layout">

  <!-- ── Navigation ─────────────────────────────────────────── -->
  <nav>
    <span class="nav-logo">ELITE<span>PERFORM</span></span>
    <div class="nav-actions">
      <div class="avatar">MA</div>
      <button class="nav-pill" onclick="showToast('Perfil en desarrollo')">Perfil</button>
      <button class="nav-pill primary" onclick="exportData()">Exportar CSV</button>
    </div>
  </nav>

  <!-- ── Main grid ───────────────────────────────────────────── -->
  <main>

    <!-- ══ Sidebar ═══════════════════════════════════════════════ -->
    <aside>

      <!-- HRV Hero -->
      <div class="hrv-card">
        <div class="section-label">Estado Fisiológico</div>
        <div class="hrv-value">78<span class="hrv-unit">ms</span></div>
        <div class="status-badge optimal dot">HRV Óptimo — Listo para entrenar</div>
        <div class="hrv-meta">
          <div class="hrv-meta-item"><strong>58 bpm</strong>Frec. Cardíaca</div>
          <div class="hrv-meta-item"><strong>42 ms</strong>rMSSD</div>
          <div class="hrv-meta-item"><strong>94%</strong>SpO₂</div>
        </div>
        <svg class="sparkline" viewBox="0 0 200 48" preserveAspectRatio="none" aria-hidden="true">
          <defs>
            <linearGradient id="sg" x1="0" y1="0" x2="1" y2="0">
              <stop offset="0%" stop-color="#6c63ff"/>
              <stop offset="100%" stop-color="#00d4ff"/>
            </linearGradient>
          </defs>
          <polyline points="0,38 28,34 56,28 84,20 112,24 140,15 168,10 200,14"
            fill="none" stroke="url(#sg)" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
          <polyline points="0,38 28,34 56,28 84,20 112,24 140,15 168,10 200,14 200,48 0,48"
            fill="url(#sg)" opacity="0.12"/>
        </svg>
      </div>

      <!-- Salud femenina -->
      <div class="card">
        <div class="section-label">Salud Femenina</div>
        <div style="font-size:0.85rem;color:var(--text-secondary);margin-bottom:0.5rem;">
          Ciclo: <strong style="color:var(--text-primary);">Día 12 de 28</strong>
          &nbsp;·&nbsp; Fase: <strong style="color:var(--accent-a);">Folicular</strong>
        </div>
        <div class="cycle-phases">
          <div class="cycle-phase past" title="Menstrual (d.1-5)"></div>
          <div class="cycle-phase active" title="Folicular (d.6-13)"></div>
          <div class="cycle-phase" title="Ovulación (d.14)"></div>
          <div class="cycle-phase" title="Lútea (d.15-28)"></div>
        </div>
        <div class="phase-labels">
          <span>Menstrual</span><span>Folicular</span><span>Ovul.</span><span>Lútea</span>
        </div>
        <div style="font-size:0.75rem;color:var(--text-muted);margin:0.5rem 0 0.25rem;">Síntomas hoy</div>
        <div class="symptom-grid">
          <button class="symptom-chip" onclick="toggleChip(this)">Sin cólicos</button>
          <button class="symptom-chip" onclick="toggleChip(this)">Flujo ligero</button>
          <button class="symptom-chip" onclick="toggleChip(this)">Alta energía</button>
          <button class="symptom-chip" onclick="toggleChip(this)">Buen humor</button>
        </div>
      </div>

      <!-- Sidebar nav -->
      <div style="display:flex;flex-direction:column;gap:2px;margin-top:auto;">
        <div class="nav-group-label">Módulos</div>
        <button class="nav-item active"><span class="icon">◈</span> Dashboard</button>
        <button class="nav-item" onclick="showToast('Historial próximamente')"><span class="icon">◷</span> Historial <span class="badge">24</span></button>
        <button class="nav-item" onclick="showToast('Nutrición próximamente')"><span class="icon">◉</span> Nutrición</button>
        <button class="nav-item" onclick="showToast('Sueño próximamente')"><span class="icon">◎</span> Sueño</button>
        <button class="nav-item" onclick="showToast('Ajustes próximamente')"><span class="icon">⚙</span> Ajustes</button>
      </div>
    </aside>

    <!-- ══ Content ════════════════════════════════════════════════ -->
    <div class="content">

      <!-- Metrics row -->
      <div class="metrics-row">
        <div class="metric-card">
          <div class="metric-title">Carga Semanal</div>
          <div class="metric-value" style="color:var(--accent-a);">847<span style="font-size:1rem;font-weight:400;"> UA</span></div>
          <div class="metric-delta up">▲ 12% vs semana ant.</div>
        </div>
        <div class="metric-card">
          <div class="metric-title">Sesiones este mes</div>
          <div class="metric-value" style="color:var(--accent-b);">18</div>
          <div class="metric-delta neutral">— promedio: 16</div>
        </div>
        <div class="metric-card">
          <div class="metric-title">Fatiga acumulada</div>
          <div class="metric-value" style="color:var(--accent-amber);">34<span style="font-size:1rem;font-weight:400;">%</span></div>
          <div class="metric-delta down">▼ óptimo &lt;40%</div>
        </div>
      </div>

      <!-- Carga semanal chart -->
      <div class="card">
        <div class="section-label">Carga Semanal — Últimos 7 días</div>
        <div class="bar-chart" id="weekChart"></div>
      </div>

      <!-- Registro de actividad -->
      <div class="card">
        <div class="section-label">Registro de Actividad</div>
        <div class="sport-row">
          <select class="sport-select" id="sport-select">
            <option value="rugby">🏉 Rugby</option>
            <option value="running">🏃 Running</option>
            <option value="gym">🏋 Gimnasio</option>
            <option value="natacion">🏊 Natación</option>
            <option value="ciclismo">🚴 Ciclismo</option>
          </select>
          <button class="add-btn" onclick="addNewSport()">+ Añadir deporte</button>
        </div>

        <div class="session-meta">
          <div class="meta-input-wrap">
            <label for="inp-dur">Duración (min)</label>
            <input class="meta-input" type="number" id="inp-dur" min="1" max="300" placeholder="60" />
          </div>
          <div class="meta-input-wrap">
            <label for="inp-dist">Distancia (km)</label>
            <input class="meta-input" type="number" id="inp-dist" min="0" step="0.1" placeholder="5.0" />
          </div>
          <div class="meta-input-wrap">
            <label for="inp-date">Fecha</label>
            <input class="meta-input" type="date" id="inp-date" />
          </div>
        </div>

        <div class="rpe-row" style="margin-top:1.1rem;">
          <span class="rpe-label">Intensidad (RPE)</span>
          <input type="range" min="1" max="10" value="6" id="rpe-slider" step="1" oninput="updateRpe(this.value)" />
          <span class="rpe-value" id="rpe-display">6</span>
        </div>
        <div class="rpe-zones">
          <span>1 Muy ligero</span><span>5 Moderado</span><span>10 Máximo</span>
        </div>
        <button class="save-session-btn" onclick="saveSession()">Guardar sesión</button>
      </div>

      <!-- AI Coach -->
      <div class="chat-card">
        <div class="chat-header">
          <div class="ai-dot"></div>
          <span class="chat-label">Coach IA Personalizado</span>
        </div>
        <div class="chat-history" id="chat-history">
          <div class="chat-msg ai">Tu HRV (78 ms) indica una recuperación excelente post-rugby. Fase folicular activa: momento ideal para trabajar fuerza e intensidad alta. ¿Qué tipo de sesión prefieres hoy?</div>
        </div>
        <div class="chat-input-row">
          <input class="chat-input" type="text" id="chat-inp" placeholder="Pregunta sobre tus datos…" onkeydown="if(event.key==='Enter')sendMsg()" />
          <button class="send-btn" onclick="sendMsg()">Enviar ↗</button>
        </div>
      </div>

    </div>
  </main>
</div>

<!-- Toast -->
<div id="toast"></div>

<script>
  /* ── Inicialización ─────────────────────────────────────────── */
  document.addEventListener('DOMContentLoaded', () => {
    setTodayDate();
    renderWeekChart();
  });

  function setTodayDate() {
    const d = new Date();
    const iso = d.toISOString().split('T')[0];
    const el = document.getElementById('inp-date');
    if (el) el.value = iso;
  }

  /* ── Gráfico de barras semanal ──────────────────────────────── */
  const weekData = [
    { day: 'L', load: 95, color: '#6c63ff' },
    { day: 'M', load: 140, color: '#6c63ff' },
    { day: 'X', load: 60, color: '#3a3a5c' },
    { day: 'J', load: 175, color: '#00d4ff' },
    { day: 'V', load: 200, color: '#00d4ff' },
    { day: 'S', load: 80, color: '#ff6b9d' },
    { day: 'D', load: 97, color: '#6c63ff' },
  ];

  function renderWeekChart() {
    const container = document.getElementById('weekChart');
    if (!container) return;
    const max = Math.max(...weekData.map(d => d.load));
    container.innerHTML = weekData.map(d => {
      const pct = Math.round((d.load / max) * 100);
      return `<div class="bar-col">
        <div class="bar" style="height:${pct}%;background:${d.color};opacity:0.85;" title="${d.load} UA"></div>
        <span class="bar-day">${d.day}</span>
      </div>`;
    }).join('');
  }

  /* ── RPE update ─────────────────────────────────────────────── */
  function updateRpe(v) {
    document.getElementById('rpe-display').textContent = v;
  }

  /* ── Toggle symptom chips ───────────────────────────────────── */
  function toggleChip(el) {
    el.classList.toggle('active');
  }

  /* ── Añadir nuevo deporte ───────────────────────────────────── */
  function addNewSport() {
    const name = prompt('Nombre del nuevo deporte:');
    if (!name || !name.trim()) return;
    const clean = name.trim();
    const select = document.getElementById('sport-select');
    const opt = document.createElement('option');
    opt.value = clean.toLowerCase();
    opt.text = clean.charAt(0).toUpperCase() + clean.slice(1);
    opt.selected = true;
    select.add(opt);
    showToast(`"${opt.text}" añadido correctamente`);
  }

  /* ── Guardar sesión ─────────────────────────────────────────── */
  function saveSession() {
    const sport = document.getElementById('sport-select');
    const dur   = document.getElementById('inp-dur').value;
    const dist  = document.getElementById('inp-dist').value;
    const rpe   = document.getElementById('rpe-slider').value;
    const date  = document.getElementById('inp-date').value;
    const label = sport ? sport.options[sport.selectedIndex].text : '—';
    showToast(`Sesión de ${label} guardada · RPE ${rpe}`);
    // aquí se integraría la llamada a la API/backend
    console.log('Sesión guardada:', { sport: label, dur, dist, rpe, date });
  }

  /* ── Exportar datos ─────────────────────────────────────────── */
  function exportData() {
    const rows = [
      ['Fecha','Deporte','Duración (min)','Distancia (km)','RPE','HRV (ms)'],
      ['2025-04-21','Rugby','75','—','7','72'],
      ['2025-04-23','Running','50','8.2','5','80'],
      ['2025-04-25','Gimnasio','60','—','8','78'],
    ];
    const csv = rows.map(r => r.join(',')).join('\n');
    const blob = new Blob([csv], { type: 'text/csv;charset=utf-8;' });
    const url = URL.createObjectURL(blob);
    const link = document.createElement('a');
    link.href = url; link.download = 'eliteperform_historial.csv';
    document.body.appendChild(link);
    link.click();
    document.body.removeChild(link);
    URL.revokeObjectURL(url);
    showToast('CSV exportado correctamente');
  }

  /* ── AI Coach chat ──────────────────────────────────────────── */
  const aiReplies = [
    'Basándome en tu HRV de 78 ms y tu fase folicular, recomiendo una sesión de fuerza al 85% RM con descansos cortos.',
    'Tu fatiga acumulada es del 34%, todavía dentro del rango óptimo. Puedes mantener la carga esta semana.',
    'El pico de carga fue el viernes. Considera una sesión regenerativa mañana para mantener el equilibrio.',
    'Tu rMSSD (42 ms) indica un sistema nervioso autónomo en buenas condiciones. Ideal para trabajo explosivo.',
    'En fase folicular el estrógeno potencia la síntesis proteica. Es un buen momento para aumentar volumen de entrenamiento.',
  ];
  let replyIdx = 0;

  function sendMsg() {
    const inp = document.getElementById('chat-inp');
    const hist = document.getElementById('chat-history');
    const text = inp.value.trim();
    if (!text) return;

    const userDiv = document.createElement('div');
    userDiv.className = 'chat-msg user';
    userDiv.textContent = text;
    hist.appendChild(userDiv);
    inp.value = '';

    setTimeout(() => {
      const aiDiv = document.createElement('div');
      aiDiv.className = 'chat-msg ai';
      aiDiv.textContent = aiReplies[replyIdx % aiReplies.length];
      replyIdx++;
      hist.appendChild(aiDiv);
      hist.scrollTop = hist.scrollHeight;
    }, 700);

    hist.scrollTop = hist.scrollHeight;
  }

  /* ── Toast ──────────────────────────────────────────────────── */
  let toastTimer = null;
  function showToast(msg) {
    const t = document.getElementById('toast');
    t.textContent = msg;
    t.classList.add('show');
    clearTimeout(toastTimer);
    toastTimer = setTimeout(() => t.classList.remove('show'), 2800);
  }
</script>
</body>
</html>
