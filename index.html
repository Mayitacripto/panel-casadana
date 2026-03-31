# panel-casadana
Panel publicitario casa dan<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Casadana | Meta Ads Q1 2026</title>
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.js"></script>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700;900&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
  :root {
    --cream:#FAF6EF; --warm-white:#FFFDF8; --espresso:#1C120A; --mocha:#3D2314;
    --caramel:#C47C3F; --gold:#E8A838; --sage:#5C7A5A; --blush:#D4896A;
    --light-caramel:#F0DCC0; --muted:#8C7B6B; --red:#B94040; --green:#4A7A4A; --blue:#4A6FA5;
  }
  *{margin:0;padding:0;box-sizing:border-box;}
  body{font-family:'DM Sans',sans-serif;background:var(--cream);color:var(--espresso);font-size:14px;}

  /* NAV */
  nav{position:sticky;top:0;z-index:100;background:var(--espresso);display:flex;align-items:center;justify-content:space-between;padding:0 32px;height:52px;border-bottom:2px solid var(--caramel);}
  nav .brand{font-family:'Playfair Display',serif;font-size:20px;color:var(--gold);font-weight:700;}
  nav .nav-tabs{display:flex;gap:4px;}
  nav .nav-tab{padding:6px 16px;border-radius:4px;font-size:12px;cursor:pointer;background:transparent;color:rgba(250,246,239,0.6);border:none;font-weight:500;transition:all 0.15s;font-family:'DM Sans',sans-serif;}
  nav .nav-tab.active{background:var(--caramel);color:#fff;}
  nav .nav-tab:hover:not(.active){background:rgba(196,124,63,0.15);color:#fff;}
  nav .period{font-size:11px;color:var(--muted);letter-spacing:0.1em;}

  /* SECTIONS */
  .section{display:none;padding:0;}
  .section.active{display:block;}

  /* ── DASHBOARD ── */
  .db{padding:28px 36px;}
  .db-header{display:flex;align-items:center;justify-content:space-between;margin-bottom:24px;flex-wrap:wrap;gap:12px;}
  .db-title{font-family:'Playfair Display',serif;font-size:24px;color:var(--mocha);}
  .db-title span{font-size:13px;font-weight:400;color:var(--muted);font-family:'DM Sans',sans-serif;margin-left:8px;}
  .month-tabs{display:flex;gap:6px;}
  .mtab{padding:6px 16px;border-radius:4px;border:1px solid var(--light-caramel);font-size:12px;cursor:pointer;background:transparent;color:var(--muted);font-family:'DM Sans',sans-serif;font-weight:500;transition:all 0.15s;}
  .mtab.active{background:var(--caramel);color:#fff;border-color:var(--caramel);}
  .mtab:hover:not(.active){background:#f5ede0;}

  .metrics-grid{display:grid;grid-template-columns:repeat(5,1fr);gap:12px;margin-bottom:24px;}
  .m-card{background:#F5F0E8;border-radius:8px;padding:14px 16px;}
  .m-card.accent{background:var(--mocha);}
  .m-label{font-size:10px;color:var(--muted);text-transform:uppercase;letter-spacing:0.1em;margin-bottom:6px;font-weight:600;}
  .m-card.accent .m-label{color:rgba(196,124,63,0.9);}
  .m-value{font-family:'Playfair Display',serif;font-size:24px;font-weight:700;color:var(--mocha);line-height:1;}
  .m-card.accent .m-value{color:var(--gold);}
  .m-delta{font-size:11px;margin-top:4px;}
  .m-delta.up{color:var(--green);} .m-delta.down{color:var(--red);} .m-delta.neu{color:var(--muted);}

  .charts-row{display:grid;grid-template-columns:1fr 1fr;gap:16px;margin-bottom:16px;}
  .chart-box{background:#fff;border:1px solid var(--light-caramel);border-radius:10px;padding:18px;}
  .chart-box.full{grid-column:1/-1;}
  .ch-label{font-size:13px;font-weight:600;color:var(--mocha);margin-bottom:2px;}
  .ch-sub{font-size:11px;color:var(--muted);margin-bottom:10px;}
  .legend{display:flex;flex-wrap:wrap;gap:14px;margin-bottom:8px;font-size:11px;color:var(--muted);}
  .legend span{display:flex;align-items:center;gap:5px;}
  .legend-sq{width:10px;height:10px;border-radius:2px;flex-shrink:0;}

  .bottom-row{display:grid;grid-template-columns:1fr 1fr 1fr;gap:16px;}
  .rank-box{background:#fff;border:1px solid var(--light-caramel);border-radius:10px;padding:18px;}
  .rank-title{font-size:13px;font-weight:600;color:var(--mocha);margin-bottom:12px;}
  .rank-item{display:flex;align-items:center;gap:10px;padding:7px 0;border-bottom:1px solid var(--light-caramel);}
  .rank-item:last-child{border-bottom:none;}
  .rank-n{font-size:11px;color:var(--muted);min-width:14px;font-weight:600;}
  .rank-name{font-size:11px;color:var(--espresso);flex:1;line-height:1.35;}
  .rank-val{font-size:12px;font-weight:600;flex-shrink:0;}
  .rank-val.g{color:var(--green);} .rank-val.r{color:var(--red);}

  /* ── INFORME ── */
  .informe{max-width:1000px;margin:0 auto;padding:36px 40px;}

  /* cover */
  .slide-cover{background:var(--espresso);border-radius:12px;padding:48px 56px;position:relative;overflow:hidden;margin-bottom:24px;}
  .slide-cover::before{content:'';position:absolute;top:-80px;right:-80px;width:380px;height:380px;border-radius:50%;background:radial-gradient(circle,rgba(196,124,63,0.18) 0%,transparent 70%);pointer-events:none;}
  .cover-eyebrow{font-size:10px;letter-spacing:0.25em;text-transform:uppercase;color:var(--caramel);font-weight:700;margin-bottom:16px;}
  .cover-title{font-family:'Playfair Display',serif;font-size:56px;font-weight:900;line-height:1.05;color:var(--cream);margin-bottom:10px;}
  .cover-title span{color:var(--gold);}
  .cover-sub{font-size:14px;color:var(--muted);max-width:480px;line-height:1.6;margin-bottom:40px;}
  .cover-meta{display:flex;gap:28px;flex-wrap:wrap;}
  .cover-meta-item label{font-size:9px;letter-spacing:0.2em;text-transform:uppercase;color:var(--caramel);display:block;margin-bottom:3px;}
  .cover-meta-item span{font-size:13px;color:var(--cream);font-weight:600;}

  /* slides */
  .i-slide{background:#fff;border:1px solid var(--light-caramel);border-radius:12px;padding:32px 36px;margin-bottom:24px;}
  .slide-badge{display:inline-block;background:var(--caramel);color:#fff;font-size:9px;font-weight:700;letter-spacing:0.15em;text-transform:uppercase;padding:4px 10px;border-radius:3px;margin-bottom:8px;}
  .slide-badge.blue{background:var(--blue);}
  .slide-badge.green{background:var(--sage);}
  .slide-badge.red{background:var(--red);}
  .slide-badge.gold{background:var(--gold);color:var(--espresso);}
  .slide-h2{font-family:'Playfair Display',serif;font-size:26px;color:var(--mocha);margin-bottom:20px;}

  /* kpi grid */
  .kpi-grid{display:grid;grid-template-columns:repeat(5,1fr);gap:12px;margin-bottom:20px;}
  .kpi-card{background:#F5F0E8;border-radius:8px;padding:16px;}
  .kpi-card.accent{background:var(--mocha);}
  .kpi-card .kc-label{font-size:9px;text-transform:uppercase;letter-spacing:0.12em;color:var(--muted);margin-bottom:6px;font-weight:700;}
  .kpi-card.accent .kc-label{color:rgba(196,124,63,0.85);}
  .kpi-card .kc-val{font-family:'Playfair Display',serif;font-size:26px;font-weight:700;color:var(--mocha);}
  .kpi-card.accent .kc-val{color:var(--gold);}
  .kpi-card .kc-sub{font-size:11px;color:var(--muted);margin-top:3px;}

  /* exec bullets */
  .exec-grid{display:grid;grid-template-columns:1fr 1fr;gap:14px;}
  .exec-bullet{display:flex;gap:12px;padding:16px;background:var(--warm-white);border:1px solid var(--light-caramel);border-radius:8px;align-items:flex-start;}
  .exec-bullet .eb-text strong{display:block;font-size:12px;font-weight:700;color:var(--mocha);margin-bottom:4px;}
  .exec-bullet .eb-text p{font-size:11px;color:var(--muted);line-height:1.5;}

  /* table */
  table{width:100%;border-collapse:collapse;font-size:12px;margin-bottom:16px;}
  thead tr{background:var(--mocha);}
  thead th{padding:10px 12px;text-align:left;color:var(--cream);font-size:10px;font-weight:700;letter-spacing:0.08em;text-transform:uppercase;}
  tbody tr{border-bottom:1px solid var(--light-caramel);}
  tbody tr:nth-child(even){background:#FDFAF4;}
  tbody td{padding:10px 12px;}
  .td-g{color:var(--green);font-weight:700;} .td-r{color:var(--red);font-weight:700;} .td-a{color:var(--caramel);font-weight:700;}
  .tr-g td{background:#EFF5EF!important;} .tr-r td{background:#FAEAEA!important;}

  /* camp cards */
  .camp-grid{display:grid;grid-template-columns:1fr 1fr 1fr;gap:14px;}
  .camp-card{border:1px solid var(--light-caramel);border-radius:8px;padding:16px;background:var(--warm-white);}
  .camp-card.top{border-left:4px solid var(--sage);}
  .camp-card.bot{border-left:4px solid var(--red);}
  .c-tag{font-size:9px;font-weight:700;letter-spacing:0.12em;text-transform:uppercase;margin-bottom:6px;}
  .camp-card.top .c-tag{color:var(--green);}
  .camp-card.bot .c-tag{color:var(--red);}
  .c-name{font-family:'Playfair Display',serif;font-size:13px;font-weight:700;color:var(--mocha);margin-bottom:10px;line-height:1.3;}
  .c-stats{display:grid;grid-template-columns:repeat(4,1fr);gap:6px;margin-bottom:10px;}
  .c-stat label{font-size:9px;color:var(--muted);display:block;text-transform:uppercase;}
  .c-stat span{font-family:'Playfair Display',serif;font-size:15px;font-weight:700;}
  .camp-card.top .c-stat span{color:var(--sage);}
  .camp-card.bot .c-stat span{color:var(--red);}
  .c-why{font-size:11px;color:var(--muted);line-height:1.5;border-top:1px solid var(--light-caramel);padding-top:8px;}
  .c-why strong{color:var(--espresso);}

  /* insights */
  .ins-grid{display:grid;grid-template-columns:1fr 1fr 1fr;gap:14px;}
  .ins-box{background:var(--warm-white);border:1px solid var(--light-caramel);border-radius:8px;padding:16px;}
  .ins-top{height:4px;margin:-16px -16px 12px;border-radius:8px 8px 0 0;}
  .ins-box h4{font-size:12px;font-weight:700;color:var(--mocha);margin-bottom:6px;}
  .ins-box p{font-size:11px;color:var(--muted);line-height:1.5;}
  .ins-box p strong{color:var(--espresso);}

  /* recs */
  .rec-list{display:flex;flex-direction:column;gap:12px;}
  .rec-item{display:flex;gap:14px;background:var(--warm-white);border:1px solid var(--light-caramel);border-left:3px solid var(--caramel);border-radius:8px;padding:14px 16px;align-items:flex-start;}
  .rec-num{background:var(--caramel);color:#fff;font-family:'Playfair Display',serif;font-size:15px;font-weight:700;width:30px;height:30px;border-radius:50%;display:flex;align-items:center;justify-content:center;flex-shrink:0;}
  .rec-content h4{font-size:12px;font-weight:700;color:var(--mocha);margin-bottom:4px;}
  .rec-content p{font-size:11px;color:var(--muted);line-height:1.5;}
  .rec-content p strong{color:var(--espresso);}
  .pr-badge{display:inline-block;font-size:9px;font-weight:700;padding:2px 7px;border-radius:8px;margin-left:6px;vertical-align:middle;}
  .pr-high{background:#FAEAEA;color:var(--red);}
  .pr-med{background:#F8EDD8;color:var(--caramel);}

  /* monthly */
  .month-cols{display:grid;grid-template-columns:1fr 1fr 1fr;gap:16px;margin-bottom:16px;}
  .month-col{border:1px solid var(--light-caramel);border-radius:8px;padding:18px;background:#F8F2E8;}
  .month-col.best{background:var(--mocha);}
  .month-col.best h3{color:var(--gold);}
  .best-crown{display:inline-block;background:var(--gold);color:var(--espresso);font-size:9px;font-weight:700;padding:2px 10px;border-radius:8px;margin-bottom:8px;letter-spacing:0.1em;text-transform:uppercase;}
  .month-col h3{font-family:'Playfair Display',serif;font-size:18px;margin-bottom:12px;color:var(--mocha);}
  .m-row{display:flex;justify-content:space-between;padding:5px 0;border-bottom:1px solid rgba(196,124,63,0.15);font-size:12px;}
  .m-row:last-child{border-bottom:none;}
  .m-row .ml{color:var(--muted);}
  .m-row .mv{font-family:'Playfair Display',serif;font-size:13px;font-weight:700;color:var(--mocha);}
  .month-col.best .m-row .ml{color:rgba(196,124,63,0.7);}
  .month-col.best .m-row .mv{color:var(--cream);}
  .mv.warn{color:var(--red)!important;}

  .trend-row{display:grid;grid-template-columns:1fr 1fr;gap:14px;}
  .trend-box{padding:14px 16px;border-radius:8px;background:var(--warm-white);border:1px solid var(--light-caramel);}
  .trend-box.keep{border-left:3px solid var(--sage);}
  .trend-box.change{border-left:3px solid var(--red);}
  .trend-box label{display:block;font-size:10px;font-weight:700;letter-spacing:0.12em;text-transform:uppercase;margin-bottom:8px;}
  .trend-box.keep label{color:var(--sage);}
  .trend-box.change label{color:var(--red);}
  .trend-box ul{list-style:none;padding:0;}
  .trend-box ul li{font-size:11px;color:var(--muted);padding:4px 0;border-bottom:1px solid var(--light-caramel);line-height:1.4;}
  .trend-box ul li:last-child{border-bottom:none;}
  .trend-box ul li::before{content:'→ ';color:var(--caramel);font-weight:700;}

  /* conclusion */
  .slide-conc{background:var(--mocha);border-radius:12px;padding:36px;margin-bottom:24px;}
  .slide-conc .c-header{font-size:10px;letter-spacing:0.2em;text-transform:uppercase;color:var(--caramel);margin-bottom:8px;font-weight:700;}
  .slide-conc h2{font-family:'Playfair Display',serif;font-size:30px;color:var(--cream);margin-bottom:4px;}
  .slide-conc h2 span{color:var(--gold);}
  .conc-cards{display:grid;grid-template-columns:1fr 1fr 1fr;gap:16px;margin-top:24px;}
  .conc-card{background:rgba(255,255,255,0.05);border:1px solid rgba(196,124,63,0.25);border-radius:8px;padding:18px;}
  .conc-num{font-family:'Playfair Display',serif;font-size:36px;font-weight:700;color:var(--gold);line-height:1;margin-bottom:4px;}
  .conc-card h4{font-size:12px;font-weight:700;color:var(--cream);margin-bottom:6px;}
  .conc-card p{font-size:11px;color:rgba(250,246,239,0.55);line-height:1.5;}
  .conc-footer{margin-top:24px;padding-top:18px;border-top:1px solid rgba(196,124,63,0.2);display:flex;justify-content:space-between;align-items:center;}
  .conc-footer p{font-size:11px;color:rgba(250,246,239,0.3);}
  .conc-brand{font-family:'Playfair Display',serif;font-size:16px;color:var(--gold);font-weight:700;}

  /* hlight cards row */
  .hl-row{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;margin-top:16px;}
  .hl-card{background:var(--warm-white);border:1px solid var(--light-caramel);border-radius:8px;padding:14px;border-top:3px solid var(--caramel);text-align:center;}
  .hl-card.g{border-top-color:var(--green);}
  .hl-card.r{border-top-color:var(--red);}
  .hl-label{font-size:9px;text-transform:uppercase;letter-spacing:0.1em;color:var(--muted);font-weight:700;margin-bottom:4px;}
  .hl-val{font-family:'Playfair Display',serif;font-size:22px;font-weight:700;}
  .hl-card.g .hl-val{color:var(--green);}
  .hl-card.r .hl-val{color:var(--red);}
  .hl-card.a .hl-val{color:var(--caramel);}
  .hl-sub{font-size:10px;color:var(--muted);margin-top:2px;}

  @media(max-width:768px){
    .metrics-grid,.kpi-grid{grid-template-columns:repeat(2,1fr)!important;}
    .charts-row,.bottom-row,.camp-grid,.ins-grid,.conc-cards,.month-cols,.trend-row,.hl-row{grid-template-columns:1fr!important;}
    .exec-grid{grid-template-columns:1fr!important;}
    .informe,.db{padding:20px;}
    .cover-title{font-size:36px;}
  }
</style>
</head>
<body>

<nav>
  <span class="brand">Casadana</span>
  <div class="nav-tabs">
    <button class="nav-tab active" onclick="showSection('dashboard')">Dashboard</button>
    <button class="nav-tab" onclick="showSection('informe')">Informe Ejecutivo</button>
  </div>
  <span class="period">Meta Ads · Q1 2026</span>
</nav>

<!-- ═══════════════════════════════
     SECTION: DASHBOARD
═══════════════════════════════ -->
<div class="section active" id="sec-dashboard">
<div class="db">
  <div class="db-header">
    <div class="db-title">Dashboard Interactivo <span>Q1 2026 — @Casadana</span></div>
    <div class="month-tabs">
      <button class="mtab active" onclick="setMonth('all',this)">Q1 Total</button>
      <button class="mtab" onclick="setMonth('Enero',this)">Enero</button>
      <button class="mtab" onclick="setMonth('Febrero',this)">Febrero</button>
      <button class="mtab" onclick="setMonth('Marzo',this)">Marzo</button>
    </div>
  </div>

  <div class="metrics-grid" id="metricsGrid"></div>

  <div class="charts-row">
    <div class="chart-box">
      <div class="ch-label">Inversión vs Resultados MOFU</div>
      <div class="ch-sub">Gasto mensual y conversaciones WhatsApp</div>
      <div class="legend">
        <span><span class="legend-sq" style="background:#C47C3F"></span>Gasto (USD)</span>
        <span><span class="legend-sq" style="background:#5C7A5A"></span>Conv. WhatsApp</span>
      </div>
      <div style="position:relative;height:200px;"><canvas id="c1"></canvas></div>
    </div>
    <div class="chart-box">
      <div class="ch-label">CPA por mes</div>
      <div class="ch-sub">Costo por conversación iniciada (USD)</div>
      <div class="legend"><span><span class="legend-sq" style="background:#4A6FA5"></span>CPA MOFU</span></div>
      <div style="position:relative;height:200px;"><canvas id="c2"></canvas></div>
    </div>
  </div>

  <div class="charts-row">
    <div class="chart-box">
      <div class="ch-label">CPM por mes</div>
      <div class="ch-sub">Costo por mil impresiones</div>
      <div class="legend">
        <span><span class="legend-sq" style="background:#B94040"></span>MOFU</span>
        <span><span class="legend-sq" style="background:#C47C3F"></span>TOFU</span>
      </div>
      <div style="position:relative;height:200px;"><canvas id="c3"></canvas></div>
    </div>
    <div class="chart-box">
      <div class="ch-label">Tasa de conversión WhatsApp</div>
      <div class="ch-sub">% de clics que inician conversación</div>
      <div class="legend"><span><span class="legend-sq" style="background:#5C7A5A"></span>Tasa conv. WA</span></div>
      <div style="position:relative;height:200px;"><canvas id="c4"></canvas></div>
    </div>
  </div>

  <div class="charts-row">
    <div class="chart-box">
      <div class="ch-label">Alcance & Frecuencia MOFU</div>
      <div class="ch-sub">Personas únicas alcanzadas por mes</div>
      <div class="legend">
        <span><span class="legend-sq" style="background:#C47C3F"></span>Alcance</span>
        <span><span class="legend-sq" style="background:#4A6FA5"></span>Frecuencia</span>
      </div>
      <div style="position:relative;height:200px;"><canvas id="c5"></canvas></div>
    </div>
    <div class="chart-box">
      <div class="ch-label">CPA por categoría (MOFU)</div>
      <div class="ch-sub">Costo promedio por conversación WA</div>
      <div class="legend">
        <span><span class="legend-sq" style="background:#5C7A5A"></span>Beirut</span>
        <span><span class="legend-sq" style="background:#C47C3F"></span>Postres</span>
        <span><span class="legend-sq" style="background:#B94040"></span>Fast Food</span>
      </div>
      <div style="position:relative;height:200px;"><canvas id="c6"></canvas></div>
    </div>
  </div>

  <div class="bottom-row">
    <div class="rank-box">
      <div class="rank-title">Top anuncios — CPA más bajo</div>
      <div id="topAds"></div>
    </div>
    <div class="rank-box">
      <div class="rank-title">Bottom anuncios — CPA más alto</div>
      <div id="botAds"></div>
    </div>
    <div class="rank-box">
      <div class="rank-title">Distribución de gasto por objetivo</div>
      <div class="legend" style="margin-bottom:8px;">
        <span><span class="legend-sq" style="background:#C47C3F"></span>MOFU</span>
        <span><span class="legend-sq" style="background:#4A6FA5"></span>TOFU Tráfico</span>
        <span><span class="legend-sq" style="background:#888"></span>Reconocimiento</span>
      </div>
      <div style="position:relative;height:160px;"><canvas id="c7"></canvas></div>
      <div id="spendSummary" style="margin-top:10px;"></div>
    </div>
  </div>
</div>
</div>

<!-- ═══════════════════════════════
     SECTION: INFORME EJECUTIVO
═══════════════════════════════ -->
<div class="section" id="sec-informe">
<div class="informe">

  <!-- PORTADA -->
  <div class="slide-cover">
    <div class="cover-eyebrow">Análisis Estratégico · Meta Ads · Q1 2026</div>
    <div class="cover-title">Reporte de<br><span>Campañas</span><br>Publicitarias</div>
    <div class="cover-sub">Evaluación de rendimiento, eficiencia de inversión y recomendaciones accionables para @Casadana — Enero, Febrero y Marzo 2026.</div>
    <div class="cover-meta">
      <div class="cover-meta-item"><label>Periodo</label><span>Ene – Mar 2026</span></div>
      <div class="cover-meta-item"><label>Inversión Total</label><span>$2,422.71 USD</span></div>
      <div class="cover-meta-item"><label>Campañas</label><span>13 campañas · 132 anuncios</span></div>
      <div class="cover-meta-item"><label>Plataforma</label><span>Meta Ads (Facebook / Instagram)</span></div>
    </div>
  </div>

  <!-- RESUMEN EJECUTIVO -->
  <div class="i-slide">
    <span class="slide-badge blue">Resumen Ejecutivo</span>
    <div class="slide-h2">Visión General</div>
    <div class="kpi-grid">
      <div class="kpi-card accent"><div class="kc-label">Inversión Total</div><div class="kc-val">$2,423</div><div class="kc-sub" style="color:rgba(196,124,63,0.7)">USD · Q1 2026</div></div>
      <div class="kpi-card"><div class="kc-label">Conv. WhatsApp</div><div class="kc-val">1,616</div><div class="kc-sub">Conversaciones MOFU</div></div>
      <div class="kpi-card"><div class="kc-label">CPA Promedio</div><div class="kc-val">$0.87</div><div class="kc-sub">Por conversación WA</div></div>
      <div class="kpi-card"><div class="kc-label">Alcance Total</div><div class="kc-val">1.67M</div><div class="kc-sub">Personas únicas</div></div>
      <div class="kpi-card"><div class="kc-label">Impresiones</div><div class="kc-val">3.26M</div><div class="kc-sub">Total Q1 2026</div></div>
    </div>
    <div class="exec-grid">
      <div class="exec-bullet"><div style="font-size:18px;flex-shrink:0">✅</div><div class="eb-text"><strong>CPA muy competitivo en MOFU</strong><p>Las campañas de Interacción generaron 1,616 conversaciones WA a $0.87 USD promedio, con picos de eficiencia en $0.49 por conversación.</p></div></div>
      <div class="exec-bullet"><div style="font-size:18px;flex-shrink:0">✅</div><div class="eb-text"><strong>TOFU con CPM ultra bajo</strong><p>Tráfico y Reconocimiento lograron CPM promedio de $0.48 USD, generando 1.67M de personas alcanzadas con inversión moderada.</p></div></div>
      <div class="exec-bullet"><div style="font-size:18px;flex-shrink:0">⚠️</div><div class="eb-text"><strong>Alerta: Marzo muestra deterioro</strong><p>CPM de MOFU subió de $1.49 → $3.04 (+104%). El alcance cayó 54% y los resultados bajaron 32% vs Enero.</p></div></div>
      <div class="exec-bullet"><div style="font-size:18px;flex-shrink:0">⚠️</div><div class="eb-text"><strong>Fast Food con bajo rendimiento</strong><p>Fasto Food tiene CPA de $2.09 vs $1.10 de Postres/Beirut. El mismo presupuesto genera 37% menos conversaciones.</p></div></div>
      <div class="exec-bullet"><div style="font-size:18px;flex-shrink:0">💡</div><div class="eb-text"><strong>Postres & Beirut dominan la conversión</strong><p>Los creativos de bebidas frías y comida árabe generan hasta 70.3% de tasa WA — los activos más valiosos del trimestre.</p></div></div>
      <div class="exec-bullet"><div style="font-size:18px;flex-shrink:0">💡</div><div class="eb-text"><strong>Febrero: el mes de mayor eficiencia</strong><p>Mejor CPA ($0.79), más resultados (636 convs.) y mayor tasa WA (34.1%). Esta lógica debe replicarse en Q2.</p></div></div>
    </div>
  </div>

  <!-- KPIs -->
  <div class="i-slide">
    <span class="slide-badge blue">KPIs Clave</span>
    <div class="slide-h2">Métricas Prioritarias por Campaña</div>
    <table>
      <thead><tr><th>Campaña</th><th>Objetivo</th><th>Gasto</th><th>Resultados</th><th>CPA</th><th>Tasa WA</th><th>CTR</th><th>CPM</th><th>Estado</th></tr></thead>
      <tbody>
        <tr class="tr-g"><td><strong>MOFU | Postres & Dulces</strong></td><td style="color:var(--muted)">Interacción</td><td>$461.68</td><td class="td-g">609</td><td class="td-g">$1.10</td><td class="td-g">34.4%</td><td>125.1%</td><td>$2.12</td><td class="td-g">🟢 Top</td></tr>
        <tr class="tr-g"><td><strong>MOFU | Beirut Rest</strong></td><td style="color:var(--muted)">Interacción</td><td>$462.22</td><td class="td-g">620</td><td class="td-g">$1.09</td><td class="td-g">32.8%</td><td>154.9%</td><td>$2.07</td><td class="td-g">🟢 Top</td></tr>
        <tr class="tr-r"><td><strong>MOFU | Fasto Food</strong></td><td style="color:var(--muted)">Interacción</td><td>$461.92</td><td class="td-r">387</td><td class="td-r">$2.09</td><td class="td-r">25.4%</td><td>112.6%</td><td>$1.84</td><td class="td-r">🔴 Optimizar</td></tr>
        <tr><td><strong>TOFU | Casa Dana VAP</strong></td><td style="color:var(--muted)">Tráfico</td><td>$321.05</td><td class="td-a">9,240</td><td class="td-a">$0.055</td><td style="color:var(--muted)">—</td><td>104.3%</td><td>$0.49</td><td class="td-a">🟡 TOFU</td></tr>
        <tr><td><strong>TOFU | Reconocimiento Video</strong></td><td style="color:var(--muted)">Reconocimiento</td><td>$317.28</td><td class="td-a">197,799</td><td class="td-a">$0.003</td><td style="color:var(--muted)">—</td><td>56.6%</td><td>$0.35</td><td class="td-a">🟡 Alcance</td></tr>
      </tbody>
    </table>
    <div class="hl-row">
      <div class="hl-card g"><div class="hl-label">Mejor CPA MOFU</div><div class="hl-val">$0.49</div><div class="hl-sub">Frapuchino Feb · Postres</div></div>
      <div class="hl-card r"><div class="hl-label">Peor CPA MOFU</div><div class="hl-val">$5.25</div><div class="hl-sub">Fast Food · Marzo</div></div>
      <div class="hl-card g"><div class="hl-label">Mejor Tasa WA</div><div class="hl-val">70.3%</div><div class="hl-sub">Frapuchino · Febrero</div></div>
      <div class="hl-card a"><div class="hl-label">CPM TOFU más bajo</div><div class="hl-val">$0.09</div><div class="hl-sub">Reconocimiento Lechería</div></div>
    </div>
  </div>

  <!-- TOP & BOTTOM -->
  <div class="i-slide">
    <span class="slide-badge green">Top Campañas</span> <span class="slide-badge red" style="margin-left:4px">Bottom Campañas</span>
    <div class="slide-h2">Top 3 vs Bottom 3</div>
    <div class="camp-grid">
      <div class="camp-card top"><div class="c-tag">🥇 Top 1 — Mejor CPA + Tasa WA</div><div class="c-name">Reel Frapuchino · 30 Ene 2026</div><div class="c-stats"><div class="c-stat"><label>CPA</label><span>$0.49</span></div><div class="c-stat"><label>Conv.</label><span>199</span></div><div class="c-stat"><label>Tasa WA</label><span>70.3%</span></div><div class="c-stat"><label>CTR</label><span>203%</span></div></div><p class="c-why"><strong>¿Por qué funciona?</strong> Visual de bebida fría con alto poder de atracción. Tasa WA del 70% indica alta intención de compra. Producto aspiracional + precio accesible = combinación ganadora.</p></div>
      <div class="camp-card top"><div class="c-tag">🥈 Top 2 — Volumen + Eficiencia</div><div class="c-name">Reel Shawarma Libanés · 07 Ene 2026</div><div class="c-stats"><div class="c-stat"><label>CPA</label><span>$0.50</span></div><div class="c-stat"><label>Conv.</label><span>192</span></div><div class="c-stat"><label>Tasa WA</label><span>55.2%</span></div><div class="c-stat"><label>CTR</label><span>192%</span></div></div><p class="c-why"><strong>¿Por qué funciona?</strong> El shawarma es el producto estrella de Beirut Rest. Alta frecuencia de consumo y diferenciador cultural. Genera urgencia visual que convierte eficientemente.</p></div>
      <div class="camp-card top"><div class="c-tag">🥉 Top 3 — TOFU eficiente</div><div class="c-name">Reel Panes Favoritos · 15 Ene 2026</div><div class="c-stats"><div class="c-stat"><label>CPA</label><span>$0.027</span></div><div class="c-stat"><label>Visitas</label><span>3,426</span></div><div class="c-stat"><label>CTR</label><span>127%</span></div><div class="c-stat"><label>CPM</label><span>$0.41</span></div></div><p class="c-why"><strong>¿Por qué funciona?</strong> CPM bajísimo + alto CTR = audiencia amplia que responde al contenido de panadería artesanal. Ideal para construir reconocimiento de marca.</p></div>
      <div class="camp-card bot"><div class="c-tag">🔴 Bottom 1 — CPA Crítico</div><div class="c-name">Reel Tantas Formas de Desayunar</div><div class="c-stats"><div class="c-stat"><label>CPA</label><span>$5.25</span></div><div class="c-stat"><label>Conv.</label><span>2</span></div><div class="c-stat"><label>Tasa WA</label><span>14.3%</span></div><div class="c-stat"><label>CTR</label><span>94%</span></div></div><p class="c-why"><strong>¿Por qué falla?</strong> Mensaje genérico sin diferenciación. Sin urgencia ni deseo específico. Sin CTA claro hacia WhatsApp. Creativo a pausar de inmediato.</p></div>
      <div class="camp-card bot"><div class="c-tag">🔴 Bottom 2 — Fast Food sin conversión</div><div class="c-name">Reel Pizza Sweet Bacon · Jul 2025</div><div class="c-stats"><div class="c-stat"><label>CPA</label><span>$2.43</span></div><div class="c-stat"><label>Conv.</label><span>5</span></div><div class="c-stat"><label>Tasa WA</label><span>9.8%</span></div><div class="c-stat"><label>CTR</label><span>195%</span></div></div><p class="c-why"><strong>¿Por qué falla?</strong> Creativo antiguo (Jul 2025) con fatiga severa. La pizza no diferencia a Casadana. Alto CTR pero bajísima conversión WA = desconexión anuncio/oferta.</p></div>
      <div class="camp-card bot"><div class="c-tag">🔴 Bottom 3 — Baja tasa conversión</div><div class="c-name">Reel Mil Hojas Nov 2025 (Febrero)</div><div class="c-stats"><div class="c-stat"><label>CPA</label><span>$1.87</span></div><div class="c-stat"><label>Conv.</label><span>18</span></div><div class="c-stat"><label>Tasa WA</label><span>21.4%</span></div><div class="c-stat"><label>CTR</label><span>122%</span></div></div><p class="c-why"><strong>¿Por qué falla?</strong> Creativo de Nov 2025 corriendo en Febrero — fatiga de audiencia. Postre menos aspiracional. Renovar creativos para esta categoría.</p></div>
    </div>
  </div>

  <!-- INSIGHTS -->
  <div class="i-slide">
    <span class="slide-badge gold">Insights Estratégicos</span>
    <div class="slide-h2">Lo Que Los Datos Nos Dicen</div>
    <div class="ins-grid">
      <div class="ins-box"><div class="ins-top" style="background:var(--blue)"></div><h4>Interacción > Tráfico para conversión</h4><p>MOFU genera conversaciones directas a CPA <strong>$0.87 USD</strong>. TOFU tiene CPM más bajo pero no contribuye directamente a leads. La inversión MOFU tiene ROI más trazable y debe priorizarse.</p></div>
      <div class="ins-box"><div class="ins-top" style="background:var(--red)"></div><h4>Fatiga de audiencia en Marzo</h4><p>CPM saltó de <strong>$1.49 → $3.04 (+104%)</strong> y el alcance cayó 54%. Con misma segmentación y creativos repetidos, Meta eleva costos al saturar la audiencia disponible.</p></div>
      <div class="ins-box"><div class="ins-top" style="background:var(--caramel)"></div><h4>Postres & Árabe = motor de conversión</h4><p>Estas dos categorías concentran el <strong>80% de las conversaciones WA eficientes</strong>. Son los productos con mayor deseo visual y diferenciación competitiva.</p></div>
      <div class="ins-box"><div class="ins-top" style="background:var(--red)"></div><h4>Riesgo de estrategia repetida</h4><p>La misma segmentación + mismos creativos mes a mes genera <strong>deterioro predecible</strong>. El patrón de caída en Marzo es consecuencia directa de no rotar creativos.</p></div>
      <div class="ins-box"><div class="ins-top" style="background:var(--caramel)"></div><h4>Distribución de presupuesto subóptima</h4><p>Fasto Food recibe el mismo presupuesto que Postres/Beirut pero genera <strong>37% menos conversaciones</strong>. Se desperdicia inversión en la categoría de menor rendimiento.</p></div>
      <div class="ins-box"><div class="ins-top" style="background:var(--sage)"></div><h4>Especias y condimentos: oportunidad</h4><p>Casadana tiene <strong>alto potencial en maricería/especias</strong> pero no hay campañas para este segmento. Audiencias nichadas con CPA potencialmente muy bajo y alta lealtad.</p></div>
    </div>
  </div>

  <!-- RECOMENDACIONES -->
  <div class="i-slide">
    <span class="slide-badge red">Acción Requerida</span>
    <div class="slide-h2">Recomendaciones Accionables</div>
    <div class="rec-list">
      <div class="rec-item"><div class="rec-num">1</div><div class="rec-content"><h4>Redistribuir presupuesto: –30% Fasto → +15% Postres + +15% Beirut <span class="pr-badge pr-high">Alta Prioridad</span></h4><p>Reasignar <strong>$130–140 USD/mes</strong> de Fasto a categorías ganadoras incrementaría ~150 conversaciones adicionales mensuales sin aumentar la inversión total.</p></div></div>
      <div class="rec-item"><div class="rec-num">2</div><div class="rec-content"><h4>Renovar creativos cada 30 días — regla de no repetición <span class="pr-badge pr-high">Alta Prioridad</span></h4><p>Ningún creativo activo por más de <strong>30 días en MOFU</strong>. Mínimo 2 nuevos reels por categoría mensualmente. Priorizar bebidas frías, platillos aromáticos y postres con textura visible.</p></div></div>
      <div class="rec-item"><div class="rec-num">3</div><div class="rec-content"><h4>Lanzar campaña piloto de Especias & Condimentos <span class="pr-badge pr-med">Media Prioridad</span></h4><p>Nueva campaña MOFU para especias y salsas propias. Segmentación: cocina casera, foodies, gastronomía. Inversión inicial <strong>$100–120 USD/mes</strong> para testear demanda.</p></div></div>
      <div class="rec-item"><div class="rec-num">4</div><div class="rec-content"><h4>Test A/B de segmentación en MOFU <span class="pr-badge pr-med">Media Prioridad</span></h4><p><strong>50% segmentación amplia (actual) vs 50% intereses específicos</strong>. Si intereses supera amplia en CPA por más del 20%, migrar toda la inversión MOFU.</p></div></div>
      <div class="rec-item"><div class="rec-num">5</div><div class="rec-content"><h4>Optimizar el funnel de WhatsApp post-clic <span class="pr-badge pr-high">Alta Prioridad</span></h4><p>Mensaje de bienvenida automático (&lt;3 seg), catálogo visual con precios, respuesta máx. <strong>30 min en horarios activos</strong>, etiquetado de conversaciones para medir tasa de pedido real.</p></div></div>
    </div>
  </div>

  <!-- COMPARACIÓN MENSUAL -->
  <div class="i-slide">
    <span class="slide-badge blue">Comparación Mensual</span>
    <div class="slide-h2">Evolución Mensual — Solo MOFU (Interacción)</div>
    <div class="month-cols">
      <div class="month-col">
        <h3>Enero</h3>
        <div class="m-row"><span class="ml">Gasto</span><span class="mv">$464.81</span></div>
        <div class="m-row"><span class="ml">Resultados WA</span><span class="mv">584</span></div>
        <div class="m-row"><span class="ml">CPA</span><span class="mv">$0.796</span></div>
        <div class="m-row"><span class="ml">Tasa WA</span><span class="mv">27.1%</span></div>
        <div class="m-row"><span class="ml">CPM</span><span class="mv">$1.49</span></div>
        <div class="m-row"><span class="ml">Alcance</span><span class="mv">179,824</span></div>
        <div class="m-row"><span class="ml">Frecuencia</span><span class="mv">1.89x</span></div>
      </div>
      <div class="month-col best">
        <div class="best-crown">🏆 Mejor Mes</div>
        <h3>Febrero</h3>
        <div class="m-row"><span class="ml">Gasto</span><span class="mv">$503.25</span></div>
        <div class="m-row"><span class="ml">Resultados WA</span><span class="mv">636</span></div>
        <div class="m-row"><span class="ml">CPA</span><span class="mv">$0.791</span></div>
        <div class="m-row"><span class="ml">Tasa WA</span><span class="mv">34.1%</span></div>
        <div class="m-row"><span class="ml">CPM</span><span class="mv">$1.71</span></div>
        <div class="m-row"><span class="ml">Alcance</span><span class="mv">143,888</span></div>
        <div class="m-row"><span class="ml">Frecuencia</span><span class="mv">1.87x</span></div>
      </div>
      <div class="month-col">
        <h3>Marzo ⚠️</h3>
        <div class="m-row"><span class="ml">Gasto</span><span class="mv">$417.76</span></div>
        <div class="m-row"><span class="ml">Resultados WA</span><span class="mv warn">396</span></div>
        <div class="m-row"><span class="ml">CPA</span><span class="mv warn">$1.055</span></div>
        <div class="m-row"><span class="ml">Tasa WA</span><span class="mv">32.9%</span></div>
        <div class="m-row"><span class="ml">CPM</span><span class="mv warn">$3.04</span></div>
        <div class="m-row"><span class="ml">Alcance</span><span class="mv warn">81,998</span></div>
        <div class="m-row"><span class="ml">Frecuencia</span><span class="mv">1.75x</span></div>
      </div>
    </div>
    <div class="trend-row">
      <div class="trend-box keep"><label>✅ Mantener</label><ul>
        <li>Creativos de frapuchinos y bebidas frías (top performers)</li>
        <li>Campaña Beirut/Shawarma — alta conversión sostenida</li>
        <li>TOFU con segmentación amplia para reconocimiento</li>
        <li>Reels como formato principal (mejor FTIR y CTR)</li>
      </ul></div>
      <div class="trend-box change"><label>🔄 Cambiar / Optimizar</label><ul>
        <li>Pausar creativos con más de 4 semanas activos en MOFU</li>
        <li>Reducir inversión Fasto Food o renovar completamente creativos</li>
        <li>Testear segmentación por intereses específicos en MOFU</li>
        <li>KPI de cierre en WA, no solo conversación iniciada</li>
      </ul></div>
    </div>
  </div>

  <!-- CONCLUSIÓN -->
  <div class="slide-conc">
    <div class="c-header">Síntesis Estratégica · Q1 2026</div>
    <h2>La Base Es Sólida.<br><span>El Potencial, Mayor.</span></h2>
    <div class="conc-cards">
      <div class="conc-card"><div class="conc-num">$0.87</div><h4>CPA Promedio MOFU — Eficiente</h4><p>1,616 conversaciones de WhatsApp a costo muy competitivo. La estrategia MOFU funciona. El trabajo es escalar lo que funciona y eliminar lo que no.</p></div>
      <div class="conc-card"><div class="conc-num" style="color:var(--blush)">–33%</div><h4>Caída de Resultados en Marzo</h4><p>La señal más clara del trimestre: misma estrategia + mismos creativos = rendimientos decrecientes. La rotación creativa es estructural, no opcional.</p></div>
      <div class="conc-card"><div class="conc-num">3×</div><h4>Potencial de Escala en Top Categorías</h4><p>Postres y Beirut demuestran demanda activa. Con más presupuesto, nuevos creativos y mejor WA, estos segmentos pueden triplicar su impacto.</p></div>
    </div>
    <div style="margin-top:20px;background:rgba(255,255,255,0.06);border:1px solid rgba(196,124,63,0.2);border-radius:8px;padding:16px 20px;">
      <p style="font-size:12px;color:rgba(250,246,239,0.65);line-height:1.7;"><strong style="color:var(--cream)">Prioridades Q2 2026:</strong> (1) Rotar creativos mensualmente · (2) Redistribuir presupuesto hacia Postres + Beirut · (3) Lanzar piloto Especias · (4) Test A/B segmentación MOFU · (5) Activar seguimiento de pedidos en WhatsApp Business</p>
    </div>
    <div class="conc-footer">
      <p>Meta Ads Q1 2026 · Análisis Estratégico para @Casadana · Confidencial</p>
      <span class="conc-brand">Casadana</span>
    </div>
  </div>

</div>
</div>

<script>
function showSection(id){
  document.querySelectorAll('.section').forEach(s=>s.classList.remove('active'));
  document.getElementById('sec-'+id).classList.add('active');
  document.querySelectorAll('.nav-tab').forEach(t=>t.classList.remove('active'));
  event.target.classList.add('active');
}

const DATA={
  all:{gasto:1385.82,resultados:1616,cpa:0.87,cpm:2.09,tasa_wa:31.5,alcance:405710,frecuencia:1.84},
  Enero:{gasto:464.81,resultados:584,cpa:0.796,cpm:1.49,tasa_wa:27.1,alcance:179824,frecuencia:1.89},
  Febrero:{gasto:503.25,resultados:636,cpa:0.791,cpm:1.71,tasa_wa:34.1,alcance:143888,frecuencia:1.87,gasto_delta:'+8.3%',res_delta:'+8.9%',cpa_delta:'-0.6%'},
  Marzo:{gasto:417.76,resultados:396,cpa:1.055,cpm:3.04,tasa_wa:32.9,alcance:81998,frecuencia:1.75,gasto_delta:'-17%',res_delta:'-37.7%',cpa_delta:'+33.4%'},
};
const months=['Enero','Febrero','Marzo'];
const cMain='#C47C3F',cGreen='#5C7A5A',cBlue='#4A6FA5',cRed='#B94040',cGray='#888780';
const tick='#8C7B6B',grid='rgba(140,123,107,0.12)';
let charts={};

function setMonth(m,btn){
  document.querySelectorAll('.mtab').forEach(t=>t.classList.remove('active'));
  btn.classList.add('active');
  renderMetrics(m); renderCharts(m); renderRankings(m);
}

function renderMetrics(m){
  const d=DATA[m==='all'?'all':m];
  const cards=[
    {label:'Inversión MOFU',val:'$'+d.gasto.toLocaleString('es',{maximumFractionDigits:0}),delta:d.gasto_delta,accent:true},
    {label:'Conv. WhatsApp',val:d.resultados.toLocaleString('es'),delta:d.res_delta,dir:d.res_delta&&d.res_delta.includes('+')?'up':'down'},
    {label:'CPA promedio',val:'$'+d.cpa.toFixed(3),delta:d.cpa_delta,dir:d.cpa_delta&&d.cpa_delta.includes('-')?'up':'down'},
    {label:'Tasa conv. WA',val:d.tasa_wa.toFixed(1)+'%',delta:null},
    {label:'Alcance MOFU',val:Math.round(d.alcance/1000)+'K',delta:null},
  ];
  document.getElementById('metricsGrid').innerHTML=cards.map(c=>`
    <div class="m-card${c.accent?' accent':''}">
      <div class="m-label">${c.label}</div>
      <div class="m-value">${c.val}</div>
      <div class="m-delta ${c.delta?c.dir||'neu':'neu'}">${c.delta?c.delta+' vs ant.':'&nbsp;'}</div>
    </div>`).join('');
}

function mk(id,cfg){if(charts[id])charts[id].destroy();charts[id]=new Chart(document.getElementById(id),cfg);}

function renderCharts(m){
  const isAll=m==='all';
  const labels=isAll?months:[m];
  const gastoV=isAll?[464.81,503.25,417.76]:[DATA[m].gasto];
  const resV=isAll?[584,636,396]:[DATA[m].resultados];
  const cpaV=isAll?[0.796,0.791,1.055]:[DATA[m].cpa];
  const cpmMV=isAll?[1.49,1.71,3.04]:[DATA[m].cpm];
  const cpmTV=isAll?[0.65,0.58,0.52]:[m==='Enero'?0.65:m==='Febrero'?0.58:0.52];
  const tasaV=isAll?[27.1,34.1,32.9]:[DATA[m].tasa_wa];
  const alcV=isAll?[179824,143888,81998]:[DATA[m].alcance];
  const freqV=isAll?[1.89,1.87,1.75]:[DATA[m].frecuencia];
  const ax=()=>({ticks:{color:tick,font:{size:11}},grid:{color:grid},border:{display:false}});
  const opts=(y2=false)=>({responsive:true,maintainAspectRatio:false,plugins:{legend:{display:false},tooltip:{mode:'index',intersect:false}},scales:y2?{x:ax(),y:{...ax(),position:'left'},y2:{...ax(),grid:{display:false},position:'right'}}:{x:ax(),y:ax()}});

  mk('c1',{type:'bar',data:{labels,datasets:[
    {label:'Gasto USD',data:gastoV,backgroundColor:cMain,yAxisID:'y',borderRadius:4},
    {label:'Conv. WA',data:resV,backgroundColor:cGreen,yAxisID:'y2',borderRadius:4}
  ]},options:{...opts(true),scales:{x:ax(),y:{...ax(),position:'left',ticks:{...ax().ticks,callback:v=>'$'+v}},y2:{...ax(),grid:{display:false},position:'right'}}}});

  mk('c2',{type:'line',data:{labels,datasets:[{label:'CPA',data:cpaV,borderColor:cBlue,backgroundColor:cBlue+'22',fill:true,tension:0.3,pointRadius:5,pointBackgroundColor:cBlue}]},options:{...opts(),scales:{x:ax(),y:{...ax(),ticks:{...ax().ticks,callback:v=>'$'+v.toFixed(3)}}}}});

  mk('c3',{type:'bar',data:{labels,datasets:[{label:'MOFU',data:cpmMV,backgroundColor:cRed,borderRadius:4},{label:'TOFU',data:cpmTV,backgroundColor:cMain,borderRadius:4}]},options:{...opts(),scales:{x:ax(),y:{...ax(),ticks:{...ax().ticks,callback:v=>'$'+v.toFixed(2)}}}}});

  mk('c4',{type:'bar',data:{labels,datasets:[{label:'Tasa WA',data:tasaV,backgroundColor:labels.map(l=>l==='Febrero'?cGreen:cGreen+'99'),borderRadius:4}]},options:{...opts(),scales:{x:ax(),y:{...ax(),ticks:{...ax().ticks,callback:v=>v+'%'},max:50}}}});

  mk('c5',{type:'bar',data:{labels,datasets:[{label:'Alcance',data:alcV,backgroundColor:cMain+'cc',yAxisID:'y',borderRadius:4},{label:'Freq.',data:freqV,backgroundColor:cBlue+'bb',yAxisID:'y2',borderRadius:4}]},options:{responsive:true,maintainAspectRatio:false,plugins:{legend:{display:false},tooltip:{mode:'index',intersect:false}},scales:{x:ax(),y:{...ax(),position:'left',ticks:{...ax().ticks,callback:v=>Math.round(v/1000)+'K'}},y2:{...ax(),grid:{display:false},position:'right',min:0,max:3,ticks:{...ax().ticks,callback:v=>v.toFixed(2)+'x'}}}}});

  const catD={all:{b:[0.50,0.68,1.24],p:[0.62,0.73,1.03],f:[1.60,1.87,5.25]},Enero:{b:[0.50],p:[0.62],f:[1.60]},Febrero:{b:[0.68],p:[0.73],f:[1.87]},Marzo:{b:[1.24],p:[1.03],f:[5.25]}};
  const cd=catD[m==='all'?'all':m];
  mk('c6',{type:'bar',data:{labels,datasets:[{label:'Beirut',data:cd.b,backgroundColor:cGreen,borderRadius:4},{label:'Postres',data:cd.p,backgroundColor:cMain,borderRadius:4},{label:'Fast Food',data:cd.f,backgroundColor:cRed,borderRadius:4}]},options:{...opts(),scales:{x:ax(),y:{...ax(),ticks:{...ax().ticks,callback:v=>'$'+v.toFixed(2)}}}}});

  const sp=isAll?[1385.82,684.59,352.29]:m==='Enero'?[464.81,220,120]:m==='Febrero'?[503.25,230,115]:[417.76,235,117];
  const total=sp.reduce((a,b)=>a+b,0);
  mk('c7',{type:'doughnut',data:{labels:['MOFU','TOFU Tráfico','Reconocimiento'],datasets:[{data:sp,backgroundColor:[cMain,cBlue,cGray],borderWidth:0}]},options:{responsive:true,maintainAspectRatio:false,plugins:{legend:{display:false},tooltip:{callbacks:{label:ctx=>' $'+ctx.raw.toFixed(0)+' ('+Math.round(ctx.raw/total*100)+'%)'}}}}});
  document.getElementById('spendSummary').innerHTML=[{l:'MOFU',v:sp[0],c:cMain},{l:'TOFU',v:sp[1],c:cBlue},{l:'Recono.',v:sp[2],c:cGray}].map(s=>`<div style="display:flex;justify-content:space-between;font-size:11px;padding:3px 0;border-bottom:1px solid var(--light-caramel)"><span style="color:var(--muted)">${s.l}</span><span style="color:${s.c};font-weight:600">$${s.v.toFixed(0)} (${Math.round(s.v/total*100)}%)</span></div>`).join('');
}

function renderRankings(m){
  const allTop=[{n:'Frapuchino 30Ene · Postres',mes:'Feb',cpa:0.494},{n:'Shawarma Libanés · Beirut',mes:'Ene',cpa:0.497},{n:'Beirut Reel 07Dic · Beirut',mes:'Ene',cpa:0.504},{n:'Torta 16Nov · Postres',mes:'Ene',cpa:0.622},{n:'Frapuccino Fresa · Postres',mes:'Mar',cpa:0.672}];
  const allBot=[{n:'Tantas Formas Desayunar · Fasto',mes:'Mar',cpa:5.25},{n:'Pizza Sweet Bacon · Fasto',mes:'Ene',cpa:2.43},{n:'Pizzas Perfectas · Fasto',mes:'Feb',cpa:2.12},{n:'Crispy Fasto Carrusel',mes:'Ene',cpa:2.01},{n:'Mil Hojas Nov · Postres',mes:'Feb',cpa:1.87}];
  const mMap={'Enero':'Ene','Febrero':'Feb','Marzo':'Mar'};
  const f=m==='all'?()=>true:d=>d.mes===mMap[m];
  const rnd=(arr,g)=>arr.filter(f).slice(0,5).map((a,i)=>`<div class="rank-item"><span class="rank-n">${i+1}</span><span class="rank-name">${a.n}</span><span class="rank-val ${g?'g':'r'}">$${a.cpa.toFixed(3)}</span></div>`).join('');
  document.getElementById('topAds').innerHTML=rnd(allTop,true)||'<p style="font-size:11px;color:var(--muted);padding:8px 0">Sin datos para este mes</p>';
  document.getElementById('botAds').innerHTML=rnd(allBot,false)||'<p style="font-size:11px;color:var(--muted);padding:8px 0">Sin datos para este mes</p>';
}

renderMetrics('all'); renderCharts('all'); renderRankings('all');
</script>
</body>
</html>
[Casadana_Meta_Ads_Netlify (2).html](https://github.com/user-attachments/files/26391197/Casadana_Meta_Ads_Netlify.2.html)
a
