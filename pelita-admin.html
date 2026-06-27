<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>PELITA Admin — Dasbor Fakultas Psikologi</title>
<link rel="preconnect" href="https://fonts.googleapis.com"/>
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin/>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=DM+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet"/>
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.min.js"></script>
<style>
/* ── RESET & TOKENS ─────────────────────────────────── */
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{
  --navy:       #1B2A4A;
  --navy-dk:    #111D35;
  --navy-lt:    #243656;
  --indigo:     #3D52A0;
  --indigo-lt:  #5C72C4;
  --indigo-dim: #EEF2FF;
  --bg:         #F7F8FC;
  --surface:    #FFFFFF;
  --border:     #E4E8F0;
  --border-dk:  #D0D6E2;
  --txt-hd:     #0F172A;
  --txt-bd:     #334155;
  --txt-sm:     #64748B;
  --txt-xs:     #94A3B8;
  --red:        #DC2626;
  --red-lt:     #FEF2F2;
  --red-bd:     #FECACA;
  --amber:      #D97706;
  --amber-lt:   #FFFBEB;
  --amber-bd:   #FDE68A;
  --green:      #059669;
  --green-lt:   #ECFDF5;
  --green-bd:   #A7F3D0;
  --sidebar-w:  220px;
  --top-h:      60px;
  --radius:     10px;
  --radius-lg:  16px;
  --shadow:     0 1px 4px rgba(15,23,42,.07), 0 4px 16px rgba(15,23,42,.05);
  --shadow-md:  0 4px 20px rgba(15,23,42,.12);
  --transition: .2s cubic-bezier(.4,0,.2,1);
}
html{font-size:14px;scroll-behavior:smooth}
body{font-family:'Inter',sans-serif;background:var(--bg);color:var(--txt-bd);min-height:100vh;display:flex;overflow-x:hidden}
::-webkit-scrollbar{width:5px;height:5px}
::-webkit-scrollbar-track{background:transparent}
::-webkit-scrollbar-thumb{background:var(--border-dk);border-radius:99px}

/* ── SIDEBAR ────────────────────────────────────────── */
#sidebar{
  width:var(--sidebar-w);min-height:100vh;
  background:var(--navy-dk);
  display:flex;flex-direction:column;
  position:fixed;left:0;top:0;z-index:200;
  transition:transform var(--transition);
}
.sb-brand{
  padding:20px 18px 16px;
  border-bottom:1px solid rgba(255,255,255,.07);
  display:flex;align-items:center;gap:10px;
}
.sb-brand-icon{
  width:36px;height:36px;
  background:var(--indigo);
  border-radius:9px;
  display:flex;align-items:center;justify-content:center;
  font-size:17px;flex-shrink:0;
}
.sb-brand-name{font-family:'DM Sans',sans-serif;font-size:15px;font-weight:700;color:#fff;line-height:1.1}
.sb-brand-sub{font-size:9.5px;color:rgba(255,255,255,.35);font-weight:500;letter-spacing:.4px;margin-top:2px}
.sb-role-badge{
  margin:12px 14px;
  padding:7px 12px;
  background:rgba(61,82,160,.35);
  border:1px solid rgba(61,82,160,.5);
  border-radius:8px;
  display:flex;align-items:center;gap:8px;
}
.sb-role-dot{width:7px;height:7px;border-radius:50%;background:#34D399;flex-shrink:0;box-shadow:0 0 0 2px rgba(52,211,153,.25)}
.sb-role-lbl{font-size:11px;color:rgba(255,255,255,.75);font-weight:600}
.sb-nav{padding:6px 10px;flex:1}
.sb-sec-lbl{
  font-size:9px;color:rgba(255,255,255,.25);
  text-transform:uppercase;letter-spacing:1.2px;font-weight:700;
  padding:12px 8px 5px;
}
.sb-item{
  display:flex;align-items:center;gap:10px;
  padding:9px 12px;
  border-radius:8px;
  color:rgba(255,255,255,.55);
  font-size:13px;font-weight:500;
  cursor:pointer;
  transition:background var(--transition),color var(--transition);
  margin-bottom:2px;user-select:none;
  position:relative;
}
.sb-item:hover{background:rgba(255,255,255,.07);color:rgba(255,255,255,.85)}
.sb-item.active{background:var(--indigo);color:#fff;font-weight:600}
.sb-item .sb-icon{font-size:15px;width:18px;text-align:center;flex-shrink:0}
.sb-badge{
  margin-left:auto;
  background:var(--red);color:#fff;
  font-size:10px;font-weight:700;
  padding:1px 7px;border-radius:99px;
  min-width:20px;text-align:center;
}
.sb-footer{
  padding:12px 14px 18px;
  border-top:1px solid rgba(255,255,255,.07);
}
.sb-user{display:flex;align-items:center;gap:10px}
.sb-avatar{
  width:32px;height:32px;border-radius:50%;
  background:var(--indigo);
  display:flex;align-items:center;justify-content:center;
  font-size:12px;font-weight:700;color:#fff;flex-shrink:0;
}
.sb-user-name{font-size:12px;color:rgba(255,255,255,.75);font-weight:600;line-height:1.3}
.sb-user-role{font-size:10px;color:rgba(255,255,255,.35)}

/* ── TOPBAR ─────────────────────────────────────────── */
#main{margin-left:var(--sidebar-w);flex:1;display:flex;flex-direction:column;min-height:100vh}
#topbar{
  height:var(--top-h);
  background:var(--surface);
  border-bottom:1px solid var(--border);
  display:flex;align-items:center;justify-content:space-between;
  padding:0 28px;
  position:sticky;top:0;z-index:100;
}
.topbar-left{display:flex;align-items:center;gap:12px}
.hamburger{display:none;background:none;border:none;font-size:20px;cursor:pointer;color:var(--txt-sm);padding:4px}
#topbar-breadcrumb{font-size:13px;color:var(--txt-sm)}
#topbar-breadcrumb strong{color:var(--txt-hd);font-weight:600}
.topbar-right{display:flex;align-items:center;gap:12px}
.topbar-time{font-size:12px;color:var(--txt-xs);font-weight:500}
.notif-btn{
  position:relative;background:none;border:1px solid var(--border);
  border-radius:8px;padding:6px 9px;cursor:pointer;
  font-size:16px;transition:background var(--transition);
}
.notif-btn:hover{background:var(--indigo-dim)}
.notif-pip{
  position:absolute;top:4px;right:4px;
  width:8px;height:8px;border-radius:50%;
  background:var(--red);border:1.5px solid var(--surface);
}
.export-btn{
  padding:7px 14px;
  background:var(--indigo);color:#fff;
  border:none;border-radius:8px;
  font-family:'Inter',sans-serif;font-size:12px;font-weight:600;
  cursor:pointer;transition:opacity var(--transition),transform var(--transition);
  display:flex;align-items:center;gap:6px;
}
.export-btn:hover{opacity:.88;transform:translateY(-1px)}

/* ── CONTENT ────────────────────────────────────────── */
#content{padding:24px 28px 48px;flex:1}
.page{display:none;animation:fadeIn .25s ease}
.page.active{display:block}
@keyframes fadeIn{from{opacity:0;transform:translateY(5px)}to{opacity:1;transform:translateY(0)}}

/* ── PAGE HEADER ────────────────────────────────────── */
.pg-header{margin-bottom:22px;display:flex;align-items:flex-start;justify-content:space-between;gap:12px;flex-wrap:wrap}
.pg-title{font-family:'DM Sans',sans-serif;font-size:20px;font-weight:800;color:var(--txt-hd);line-height:1.2}
.pg-sub{font-size:12.5px;color:var(--txt-sm);margin-top:3px}
.pg-actions{display:flex;gap:8px;flex-wrap:wrap}

/* ── STAT CARDS ─────────────────────────────────────── */
.stats-row{display:grid;grid-template-columns:repeat(auto-fill,minmax(190px,1fr));gap:16px;margin-bottom:24px}
.stat-card{
  background:var(--surface);border:1px solid var(--border);
  border-radius:var(--radius);padding:18px 20px;
  box-shadow:var(--shadow);
  position:relative;overflow:hidden;
}
.stat-card::before{
  content:'';position:absolute;left:0;top:0;bottom:0;
  width:4px;border-radius:2px 0 0 2px;
}
.stat-card.blue::before{background:var(--indigo)}
.stat-card.red::before{background:var(--red)}
.stat-card.amber::before{background:var(--amber)}
.stat-card.green::before{background:var(--green)}
.stat-card-icon{font-size:20px;margin-bottom:10px}
.stat-card-val{font-family:'DM Sans',sans-serif;font-size:30px;font-weight:800;color:var(--txt-hd);line-height:1}
.stat-card-lbl{font-size:12px;color:var(--txt-sm);font-weight:500;margin-top:4px}
.stat-card-delta{font-size:11px;font-weight:600;margin-top:6px;display:flex;align-items:center;gap:4px}
.delta-up{color:var(--red)}
.delta-dn{color:var(--green)}
.delta-neu{color:var(--txt-xs)}

/* ── SECTION TITLE ──────────────────────────────────── */
.sec-title{
  font-family:'DM Sans',sans-serif;font-size:14px;font-weight:700;
  color:var(--txt-hd);margin-bottom:14px;
  display:flex;align-items:center;gap:8px;
}
.sec-title-badge{
  font-size:10px;font-weight:700;padding:2px 8px;
  border-radius:99px;font-family:'Inter',sans-serif;
}

/* ── TWO COL ────────────────────────────────────────── */
.grid-2{display:grid;grid-template-columns:1fr 1fr;gap:18px;margin-bottom:22px}
.grid-3{display:grid;grid-template-columns:2fr 1fr;gap:18px;margin-bottom:22px}
@media(max-width:900px){.grid-2,.grid-3{grid-template-columns:1fr}}

/* ── CARD ───────────────────────────────────────────── */
.card{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius);box-shadow:var(--shadow)}
.card-hd{
  padding:14px 18px 11px;
  border-bottom:1px solid var(--border);
  display:flex;align-items:center;justify-content:space-between;gap:10px;
}
.card-hd-title{font-family:'DM Sans',sans-serif;font-size:13.5px;font-weight:700;color:var(--txt-hd);display:flex;align-items:center;gap:7px}
.card-hd-action{
  font-size:12px;color:var(--indigo);font-weight:600;cursor:pointer;
  background:none;border:none;font-family:'Inter',sans-serif;
  padding:4px 8px;border-radius:6px;transition:background var(--transition);
}
.card-hd-action:hover{background:var(--indigo-dim)}
.card-bd{padding:16px 18px}

/* ── CHART ──────────────────────────────────────────── */
.chart-wrap{position:relative;height:220px}
.chart-wrap.tall{height:280px}

/* ── TABLE ──────────────────────────────────────────── */
.tbl-wrap{overflow-x:auto}
table.data-table{width:100%;border-collapse:collapse;font-size:12.5px}
table.data-table thead th{
  padding:9px 14px;
  text-align:left;
  font-weight:700;color:var(--txt-sm);
  background:var(--bg);
  border-bottom:1px solid var(--border);
  white-space:nowrap;font-size:11px;text-transform:uppercase;letter-spacing:.5px;
}
table.data-table tbody tr{
  border-bottom:1px solid var(--border);
  transition:background var(--transition);
  cursor:pointer;
}
table.data-table tbody tr:last-child{border-bottom:none}
table.data-table tbody tr:hover{background:#F8FAFF}
table.data-table tbody td{padding:11px 14px;vertical-align:middle}
.td-name{font-weight:600;color:var(--txt-hd);font-size:13px}
.td-nim{color:var(--txt-xs);font-size:11.5px;margin-top:1px}

/* ── STATUS BADGE ───────────────────────────────────── */
.badge{
  display:inline-flex;align-items:center;gap:5px;
  padding:3px 10px;border-radius:99px;
  font-size:11px;font-weight:700;white-space:nowrap;
}
.badge-red{background:var(--red-lt);color:var(--red);border:1px solid var(--red-bd)}
.badge-amber{background:var(--amber-lt);color:var(--amber);border:1px solid var(--amber-bd)}
.badge-green{background:var(--green-lt);color:var(--green);border:1px solid var(--green-bd)}
.badge-blue{background:var(--indigo-dim);color:var(--indigo);border:1px solid #C7D2F9}
.badge-gray{background:#F1F5F9;color:var(--txt-sm);border:1px solid var(--border)}
.badge-dot{width:6px;height:6px;border-radius:50%;flex-shrink:0}
.dot-red{background:var(--red)}
.dot-amber{background:var(--amber)}
.dot-green{background:var(--green)}

/* ── PULSE ANIM (kritis) ────────────────────────────── */
@keyframes pulse-ring{
  0%,100%{box-shadow:0 0 0 0 rgba(220,38,38,.45)}
  50%{box-shadow:0 0 0 5px rgba(220,38,38,0)}
}
.pulse-dot{animation:pulse-ring 1.8s ease infinite}

/* ── STRESS BAR ─────────────────────────────────────── */
.stress-bar-wrap{display:flex;align-items:center;gap:8px;min-width:120px}
.stress-bar-track{flex:1;height:6px;background:var(--border);border-radius:99px;overflow:hidden}
.stress-bar-fill{height:100%;border-radius:99px;transition:width .6s ease}
.stress-bar-val{font-size:11px;font-weight:700;min-width:24px;text-align:right}

/* ── TAG CHIPS ──────────────────────────────────────── */
.tag-wrap{display:flex;flex-wrap:wrap;gap:4px}
.tag{
  font-size:10px;font-weight:600;padding:2px 7px;
  border-radius:99px;background:#F1F5F9;color:var(--txt-sm);
  border:1px solid var(--border);white-space:nowrap;
}
.tag-red{background:#FFF1F2;color:#9F1239;border-color:#FECDD3}
.tag-amber{background:#FFFBEB;color:#92400E;border-color:#FDE68A}

/* ── ACTION BUTTONS ─────────────────────────────────── */
.btn{
  display:inline-flex;align-items:center;gap:5px;
  padding:6px 13px;border-radius:7px;
  font-family:'Inter',sans-serif;font-size:12px;font-weight:600;
  cursor:pointer;border:none;transition:all var(--transition);white-space:nowrap;
}
.btn:active{transform:scale(.97)}
.btn-primary{background:var(--indigo);color:#fff}
.btn-primary:hover{background:var(--indigo-lt)}
.btn-danger{background:var(--red-lt);color:var(--red);border:1px solid var(--red-bd)}
.btn-danger:hover{background:#FECACA}
.btn-ghost{background:transparent;color:var(--txt-sm);border:1px solid var(--border)}
.btn-ghost:hover{background:var(--bg)}
.btn-success{background:var(--green-lt);color:var(--green);border:1px solid var(--green-bd)}
.btn-success:hover{background:#A7F3D0}
.btn-amber{background:var(--amber-lt);color:var(--amber);border:1px solid var(--amber-bd)}
.btn-amber:hover{background:#FDE68A}
.btn-sm{padding:4px 10px;font-size:11px}

/* ── WARNING INBOX ──────────────────────────────────── */
.warning-list{display:flex;flex-direction:column;gap:10px}
.warning-item{
  display:flex;align-items:flex-start;gap:14px;
  padding:14px 16px;
  background:var(--red-lt);
  border:1px solid var(--red-bd);
  border-left:4px solid var(--red);
  border-radius:var(--radius);
  transition:opacity var(--transition),transform var(--transition);
}
.warning-item.resolved{
  opacity:0;transform:translateX(20px);pointer-events:none;height:0;padding:0;margin:0;border:none;overflow:hidden;
}
.warning-avatar{
  width:36px;height:36px;border-radius:50%;
  display:flex;align-items:center;justify-content:center;
  font-size:13px;font-weight:700;color:#fff;flex-shrink:0;
}
.warning-body{flex:1;min-width:0}
.warning-name{font-size:13px;font-weight:700;color:var(--txt-hd)}
.warning-meta{font-size:11.5px;color:var(--txt-sm);margin-top:2px;line-height:1.5}
.warning-meta b{color:var(--red);font-weight:700}
.warning-time{font-size:10.5px;color:var(--txt-xs);margin-top:4px}
.warning-actions{display:flex;gap:6px;flex-shrink:0;flex-wrap:wrap;align-items:flex-start}

/* ── KONSELING TABLE ────────────────────────────────── */
.sesi-status-select{
  padding:4px 8px;border:1px solid var(--border);border-radius:6px;
  font-family:'Inter',sans-serif;font-size:11.5px;font-weight:600;
  background:var(--surface);cursor:pointer;outline:none;
  transition:border-color var(--transition);color:var(--txt-bd);
}
.sesi-status-select:focus{border-color:var(--indigo)}

/* ── MODAL ──────────────────────────────────────────── */
#modal-overlay{
  position:fixed;inset:0;
  background:rgba(15,23,42,.55);
  backdrop-filter:blur(4px);
  -webkit-backdrop-filter:blur(4px);
  z-index:1000;
  display:flex;align-items:center;justify-content:center;
  padding:20px;
  opacity:0;pointer-events:none;
  transition:opacity .3s ease;
}
#modal-overlay.open{opacity:1;pointer-events:all}
#modal-box{
  background:var(--surface);border-radius:var(--radius-lg);
  padding:28px;max-width:480px;width:100%;
  box-shadow:var(--shadow-md);
  transform:translateY(16px) scale(.98);
  transition:transform .3s cubic-bezier(.34,1.56,.64,1);
}
#modal-overlay.open #modal-box{transform:translateY(0) scale(1)}
.modal-hd{display:flex;align-items:flex-start;justify-content:space-between;margin-bottom:20px}
.modal-title{font-family:'DM Sans',sans-serif;font-size:17px;font-weight:800;color:var(--txt-hd)}
.modal-close{background:none;border:none;font-size:20px;cursor:pointer;color:var(--txt-xs);line-height:1;padding:2px}
.modal-close:hover{color:var(--txt-hd)}
.modal-section-lbl{font-size:11px;font-weight:700;text-transform:uppercase;letter-spacing:.7px;color:var(--txt-xs);margin-bottom:8px}
.modal-hormone-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:18px}
.mh-item{background:var(--bg);border-radius:8px;padding:10px 12px;border:1px solid var(--border)}
.mh-label{font-size:10.5px;font-weight:700;color:var(--txt-sm);display:flex;align-items:center;gap:5px}
.mh-val{font-size:22px;font-weight:800;color:var(--txt-hd);margin-top:3px}
.mh-bar{height:4px;border-radius:99px;margin-top:5px;background:var(--border)}
.mh-bar-fill{height:100%;border-radius:99px}
.modal-diary{
  background:var(--bg);border-radius:8px;padding:12px;
  font-size:13px;color:var(--txt-bd);line-height:1.65;
  border:1px solid var(--border);margin-bottom:18px;
  max-height:100px;overflow-y:auto;
}
.modal-tag-wrap{display:flex;flex-wrap:wrap;gap:5px;margin-bottom:20px}
.modal-actions{display:flex;gap:8px;justify-content:flex-end;flex-wrap:wrap}

/* ── TOAST ──────────────────────────────────────────── */
#toast{
  position:fixed;bottom:24px;left:50%;
  transform:translateX(-50%) translateY(60px);
  background:var(--navy-dk);color:#fff;
  padding:10px 22px;border-radius:99px;
  font-size:13px;font-weight:600;z-index:2000;
  transition:transform .35s cubic-bezier(.34,1.56,.64,1);
  box-shadow:var(--shadow-md);white-space:nowrap;
  display:flex;align-items:center;gap:7px;
}
#toast.show{transform:translateX(-50%) translateY(0)}

/* ── EMPTY STATE ────────────────────────────────────── */
.empty{text-align:center;padding:32px 16px;color:var(--txt-xs)}
.empty-icon{font-size:36px;margin-bottom:8px}
.empty-txt{font-size:13px}

/* ── RESPONSIVE ─────────────────────────────────────── */
@media(max-width:768px){
  :root{--sidebar-w:0px}
  #sidebar{width:220px;transform:translateX(-220px)}
  #sidebar.open{transform:translateX(0)}
  #main{margin-left:0}
  .hamburger{display:block}
  #content{padding:18px 16px 48px}
  #topbar{padding:0 16px}
  .stats-row{grid-template-columns:1fr 1fr}
}
@media(max-width:480px){
  .stats-row{grid-template-columns:1fr}
  .warning-actions{flex-direction:column}
}
</style>
</head>
<body>

<!-- ══════════ SIDEBAR ══════════════════════════════ -->
<nav id="sidebar">
  <div class="sb-brand">
    <div class="sb-brand-icon">🕯️</div>
    <div>
      <div class="sb-brand-name">PELITA Admin</div>
      <div class="sb-brand-sub">Dasbor Fakultas Psikologi</div>
    </div>
  </div>

  <div class="sb-role-badge">
    <div class="sb-role-dot"></div>
    <div class="sb-role-lbl">Satgas Kesehatan Mental</div>
  </div>

  <div class="sb-nav">
    <div class="sb-sec-lbl">Pemantauan</div>
    <div class="sb-item active" onclick="nav('ringkasan')" id="nav-ringkasan">
      <span class="sb-icon">📊</span> Ringkasan Dasbor
    </div>
    <div class="sb-item" onclick="nav('radar')" id="nav-radar">
      <span class="sb-icon">📡</span> Radar Mahasiswa
    </div>

    <div class="sb-sec-lbl">Intervensi</div>
    <div class="sb-item" onclick="nav('peringatan')" id="nav-peringatan">
      <span class="sb-icon">🚨</span> Peringatan Dini
      <span class="sb-badge" id="sb-badge-warn">3</span>
    </div>

    <div class="sb-sec-lbl">Konseling</div>
    <div class="sb-item" onclick="nav('konseling')" id="nav-konseling">
      <span class="sb-icon">🗓️</span> Manajemen Jadwal
    </div>
  </div>

  <div class="sb-footer">
    <div class="sb-user">
      <div class="sb-avatar">SW</div>
      <div>
        <div class="sb-user-name">Dr. Sari Wulandari</div>
        <div class="sb-user-role">Koordinator SDM</div>
      </div>
    </div>
  </div>
</nav>
<div id="sidebar-overlay" onclick="closeSidebar()"
     style="display:none;position:fixed;inset:0;background:rgba(0,0,0,.4);z-index:199"></div>

<!-- ══════════ MAIN ═════════════════════════════════ -->
<div id="main">

  <!-- TOPBAR -->
  <div id="topbar">
    <div class="topbar-left">
      <button class="hamburger" onclick="toggleSidebar()">☰</button>
      <div id="topbar-breadcrumb">PELITA / <strong id="topbar-bc-text">Ringkasan Dasbor</strong></div>
    </div>
    <div class="topbar-right">
      <div class="topbar-time" id="topbar-clock"></div>
      <button class="notif-btn" onclick="nav('peringatan')">
        🔔<span class="notif-pip" id="notif-pip"></span>
      </button>
      <button class="export-btn" onclick="showToast('📤 Data diekspor ke PDF — fitur segera hadir.')">
        ↑ Ekspor Laporan
      </button>
    </div>
  </div>

  <div id="content">

    <!-- ══ PAGE: RINGKASAN ══════════════════════════ -->
    <div class="page active" id="page-ringkasan">
      <div class="pg-header">
        <div>
          <div class="pg-title">Ringkasan Dasbor</div>
          <div class="pg-sub">Pembaruan terakhir: <span id="last-update"></span> · Semester Genap 2024/2025</div>
        </div>
        <div class="pg-actions">
          <button class="btn btn-ghost" onclick="showToast('🔄 Data diperbarui.')">↻ Perbarui</button>
        </div>
      </div>

      <div class="stats-row">
        <div class="stat-card blue">
          <div class="stat-card-icon">🎓</div>
          <div class="stat-card-val">128</div>
          <div class="stat-card-lbl">Mahasiswa Aktif Terdaftar</div>
          <div class="stat-card-delta delta-dn">▲ 4 mahasiswa baru minggu ini</div>
        </div>
        <div class="stat-card red">
          <div class="stat-card-icon">🚨</div>
          <div class="stat-card-val" id="stat-kritis">3</div>
          <div class="stat-card-lbl">Peringatan Dini Kritis</div>
          <div class="stat-card-delta delta-up">▲ 1 dari kemarin</div>
        </div>
        <div class="stat-card amber">
          <div class="stat-card-icon">⚠️</div>
          <div class="stat-card-val">9</div>
          <div class="stat-card-lbl">Mahasiswa Status Waspada</div>
          <div class="stat-card-delta delta-up">▲ 2 dari minggu lalu</div>
        </div>
        <div class="stat-card green">
          <div class="stat-card-icon">🗓️</div>
          <div class="stat-card-val" id="stat-konseling">7</div>
          <div class="stat-card-lbl">Jadwal Konseling Minggu Ini</div>
          <div class="stat-card-delta delta-neu">3 menunggu konfirmasi</div>
        </div>
      </div>

      <div class="grid-3">
        <!-- Tren Kortisol -->
        <div class="card">
          <div class="card-hd">
            <div class="card-hd-title">📉 Tren Rata-rata Kortisol — 14 Hari Terakhir</div>
            <button class="card-hd-action" onclick="nav('radar')">Lihat semua →</button>
          </div>
          <div class="card-bd">
            <div class="chart-wrap tall"><canvas id="chart-tren"></canvas></div>
          </div>
        </div>
        <!-- Distribusi Status -->
        <div class="card">
          <div class="card-hd">
            <div class="card-hd-title">🥧 Distribusi Status Wellbeing</div>
          </div>
          <div class="card-bd" style="display:flex;flex-direction:column;align-items:center;gap:16px">
            <div class="chart-wrap" style="height:180px;width:180px;flex-shrink:0">
              <canvas id="chart-donut"></canvas>
            </div>
            <div style="width:100%;display:flex;flex-direction:column;gap:8px">
              <div style="display:flex;align-items:center;justify-content:space-between">
                <span style="display:flex;align-items:center;gap:7px;font-size:12px;font-weight:600"><span style="width:10px;height:10px;border-radius:2px;background:#DC2626;display:inline-block"></span>Kritis/Burnout</span>
                <span style="font-size:13px;font-weight:800;color:var(--red)">3 mhs</span>
              </div>
              <div style="display:flex;align-items:center;justify-content:space-between">
                <span style="display:flex;align-items:center;gap:7px;font-size:12px;font-weight:600"><span style="width:10px;height:10px;border-radius:2px;background:#D97706;display:inline-block"></span>Waspada</span>
                <span style="font-size:13px;font-weight:800;color:var(--amber)">9 mhs</span>
              </div>
              <div style="display:flex;align-items:center;justify-content:space-between">
                <span style="display:flex;align-items:center;gap:7px;font-size:12px;font-weight:600"><span style="width:10px;height:10px;border-radius:2px;background:#059669;display:inline-block"></span>Stabil</span>
                <span style="font-size:13px;font-weight:800;color:var(--green)">116 mhs</span>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Top Pemicu Stres -->
      <div class="card" style="margin-bottom:22px">
        <div class="card-hd">
          <div class="card-hd-title">🏷️ Top Pemicu Stres yang Dilaporkan Minggu Ini</div>
        </div>
        <div class="card-bd">
          <div id="trigger-bars"></div>
        </div>
      </div>

      <!-- Mahasiswa Kritis Cepat -->
      <div class="card">
        <div class="card-hd">
          <div class="card-hd-title">🚨 Mahasiswa Kritis — Butuh Tindak Lanjut Segera
            <span class="sec-title-badge badge badge-red">3 aktif</span>
          </div>
          <button class="card-hd-action" onclick="nav('peringatan')">Lihat semua →</button>
        </div>
        <div class="card-bd" style="padding:12px 16px">
          <div id="quick-warning-list"></div>
        </div>
      </div>
    </div>

    <!-- ══ PAGE: RADAR ══════════════════════════════ -->
    <div class="page" id="page-radar">
      <div class="pg-header">
        <div>
          <div class="pg-title">Radar Mahasiswa</div>
          <div class="pg-sub">Pantau kondisi seluruh mahasiswa berdasarkan data jurnal harian mereka</div>
        </div>
        <div class="pg-actions">
          <select id="filter-status" onchange="renderRadarTable()"
            style="padding:7px 12px;border:1px solid var(--border);border-radius:8px;font-family:'Inter',sans-serif;font-size:12px;background:var(--surface);color:var(--txt-bd);outline:none;cursor:pointer">
            <option value="semua">Semua Status</option>
            <option value="kritis">Kritis</option>
            <option value="waspada">Waspada</option>
            <option value="stabil">Stabil</option>
          </select>
          <input id="search-mhs" type="text" placeholder="🔍  Cari nama / NIM…" oninput="renderRadarTable()"
            style="padding:7px 12px;border:1px solid var(--border);border-radius:8px;font-family:'Inter',sans-serif;font-size:12px;outline:none;width:180px;transition:border-color var(--transition)"
            onfocus="this.style.borderColor='var(--indigo)'" onblur="this.style.borderColor='var(--border)'"/>
        </div>
      </div>

      <div class="card">
        <div class="tbl-wrap">
          <table class="data-table">
            <thead>
              <tr>
                <th>Mahasiswa</th>
                <th>NIM</th>
                <th>Semester</th>
                <th>Status</th>
                <th>Kortisol (Terkini)</th>
                <th>Pemicu Stres</th>
                <th>Entri Terakhir</th>
                <th>Aksi</th>
              </tr>
            </thead>
            <tbody id="radar-tbody"></tbody>
          </table>
        </div>
      </div>
    </div>

    <!-- ══ PAGE: PERINGATAN ═════════════════════════ -->
    <div class="page" id="page-peringatan">
      <div class="pg-header">
        <div>
          <div class="pg-title">Peringatan Dini — Kotak Masuk Intervensi</div>
          <div class="pg-sub">Mahasiswa dengan Kortisol &gt; 80 atau kombinasi stres tinggi terdeteksi otomatis</div>
        </div>
      </div>

      <div style="padding:10px 14px;background:var(--red-lt);border:1px solid var(--red-bd);border-radius:var(--radius);margin-bottom:18px;display:flex;align-items:center;gap:10px">
        <span style="font-size:18px">⚠️</span>
        <div>
          <div style="font-size:13px;font-weight:700;color:var(--red)">Sistem Jemput Bola Aktif</div>
          <div style="font-size:12px;color:var(--txt-sm);margin-top:1px">Notifikasi dikirim otomatis ke Dosen Wali saat nilai Kortisol mahasiswa melebihi ambang batas kritis (>80) atau kombinasi Kortisol >70 dan Dopamin &lt;30.</div>
        </div>
      </div>

      <div class="grid-2">
        <div>
          <div class="sec-title">
            🔴 Belum Ditindaklanjuti
            <span class="sec-title-badge badge badge-red" id="unresolved-count-badge">3</span>
          </div>
          <div class="warning-list" id="warning-unresolved"></div>
          <div class="empty" id="warning-empty" style="display:none">
            <div class="empty-icon">✅</div>
            <div class="empty-txt">Semua peringatan telah ditindaklanjuti.</div>
          </div>
        </div>
        <div>
          <div class="sec-title">🟢 Sudah Ditangani</div>
          <div class="warning-list" id="warning-resolved"></div>
          <div class="empty" id="resolved-empty">
            <div class="empty-icon">📭</div>
            <div class="empty-txt">Belum ada yang ditandai selesai.</div>
          </div>
        </div>
      </div>
    </div>

    <!-- ══ PAGE: KONSELING ══════════════════════════ -->
    <div class="page" id="page-konseling">
      <div class="pg-header">
        <div>
          <div class="pg-title">Manajemen Jadwal Konseling</div>
          <div class="pg-sub">Setujui permintaan, alokasikan konselor, dan pantau status sesi</div>
        </div>
        <div class="pg-actions">
          <button class="btn btn-primary" onclick="showToast('📋 Form pengajuan jadwal manual dibuka — segera hadir.')">+ Jadwal Manual</button>
        </div>
      </div>

      <!-- Summary row -->
      <div class="stats-row" style="margin-bottom:20px">
        <div class="stat-card amber">
          <div class="stat-card-icon">⏳</div>
          <div class="stat-card-val" id="konseling-menunggu-val">3</div>
          <div class="stat-card-lbl">Menunggu Persetujuan</div>
        </div>
        <div class="stat-card blue">
          <div class="stat-card-icon">✅</div>
          <div class="stat-card-val" id="konseling-disetujui-val">3</div>
          <div class="stat-card-lbl">Sesi Disetujui</div>
        </div>
        <div class="stat-card green">
          <div class="stat-card-icon">🎯</div>
          <div class="stat-card-val" id="konseling-selesai-val">1</div>
          <div class="stat-card-lbl">Sesi Selesai Minggu Ini</div>
        </div>
      </div>

      <!-- Konselor availability -->
      <div class="card" style="margin-bottom:20px">
        <div class="card-hd">
          <div class="card-hd-title">👥 Ketersediaan Konselor Hari Ini</div>
        </div>
        <div class="card-bd">
          <div id="konselor-availability"></div>
        </div>
      </div>

      <!-- Jadwal table -->
      <div class="card">
        <div class="card-hd">
          <div class="card-hd-title">📋 Semua Permintaan Sesi</div>
          <div style="display:flex;gap:8px">
            <button class="card-hd-action" onclick="filterKonseling('semua')">Semua</button>
            <button class="card-hd-action" onclick="filterKonseling('menunggu')">Menunggu</button>
            <button class="card-hd-action" onclick="filterKonseling('disetujui')">Disetujui</button>
          </div>
        </div>
        <div class="tbl-wrap">
          <table class="data-table">
            <thead>
              <tr>
                <th>Mahasiswa</th>
                <th>Tanggal Diajukan</th>
                <th>Jadwal Sesi</th>
                <th>Topik</th>
                <th>Konselor</th>
                <th>Status</th>
                <th>Aksi</th>
              </tr>
            </thead>
            <tbody id="konseling-tbody"></tbody>
          </table>
        </div>
      </div>
    </div>

  </div><!-- /#content -->
</div><!-- /#main -->

<!-- ══ MODAL: DETAIL MAHASISWA ══════════════════════ -->
<div id="modal-overlay" role="dialog" aria-modal="true">
  <div id="modal-box">
    <div class="modal-hd">
      <div class="modal-title" id="modal-title">Detail Kondisi Mahasiswa</div>
      <button class="modal-close" onclick="closeModal()">✕</button>
    </div>
    <div id="modal-body"></div>
  </div>
</div>

<!-- ══ TOAST ═══════════════════════════════════════ -->
<div id="toast"></div>

<script>
/* ════════════════════════════════════════════════════
   DATA LAYER
════════════════════════════════════════════════════ */
const AVATARS = ['#3D52A0','#059669','#D97706','#7C3AED','#DB2777','#0891B2','#65A30D','#C2410C'];

const mahasiswaData = [
  { id:1,  nama:'Anisa Rahma Dewi',     nim:'2210101001', sem:7,  kortisol:88, dopamin:22, serotonin:30, oksitosin:35, mood:'Buruk',      tags:['Skripsi','Revisi Proposal','Analisis Data'],    lastEntry:'2 jam lalu',    status:'kritis',  diary:'Bab 3 diminta revisi total. Nggak tau harus mulai dari mana lagi. Capek banget.',  color:'#DC2626' },
  { id:2,  nama:'Bimo Satrio Nugroho',  nim:'2210101002', sem:7,  kortisol:82, dopamin:28, serotonin:35, oksitosin:40, mood:'Buruk',      tags:['Skripsi','Sidang Skripsi','Deadline Tugas'],    lastEntry:'5 jam lalu',    status:'kritis',  diary:'Pembimbing susah dihubungi. Deadline sidang 2 minggu lagi. Panik.',               color:'#7C3AED' },
  { id:3,  nama:'Citra Maharani',       nim:'2210101003', sem:5,  kortisol:81, dopamin:25, serotonin:28, oksitosin:30, mood:'Buruk',      tags:['UTS','Tugas Kelompok','Analisis Data'],          lastEntry:'Kemarin',       status:'kritis',  diary:'Empat UTS dalam seminggu. Tim kelompok nggak kooperatif. Mau nangis.',            color:'#DB2777' },
  { id:4,  nama:'Deni Prasetyo',        nim:'2210101004', sem:6,  kortisol:72, dopamin:38, serotonin:45, oksitosin:50, mood:'Kurang',     tags:['Skripsi','Proposal'],                            lastEntry:'Kemarin',       status:'waspada', diary:'Lagi banyak revisi minor. Masih cukup terkontrol.',                              color:'#0891B2' },
  { id:5,  nama:'Elisa Purnama Sari',   nim:'2210101005', sem:4,  kortisol:68, dopamin:42, serotonin:55, oksitosin:58, mood:'Netral',     tags:['Tugas Kelompok','Deadline Tugas'],               lastEntry:'2 hari lalu',   status:'waspada', diary:'Ada konflik kecil di grup, tapi masih bisa diatasi.',                            color:'#65A30D' },
  { id:6,  nama:'Fajar Alamsyah',       nim:'2210101006', sem:3,  kortisol:65, dopamin:48, serotonin:55, oksitosin:62, mood:'Netral',     tags:['UTS'],                                           lastEntry:'3 hari lalu',   status:'waspada', diary:'UTS minggu depan, mulai agak cemas.',                                            color:'#C2410C' },
  { id:7,  nama:'Gita Permata',         nim:'2210101007', sem:6,  kortisol:40, dopamin:70, serotonin:72, oksitosin:75, mood:'Baik',       tags:['Seminar Tamu'],                                  lastEntry:'Hari ini',      status:'stabil',  diary:'Seminar tadi sangat inspiratif. Dapat banyak insight.',                          color:'#059669' },
  { id:8,  nama:'Hendra Kusuma',        nim:'2210101008', sem:5,  kortisol:35, dopamin:75, serotonin:68, oksitosin:70, mood:'Baik',       tags:['Pencapaian Hari Ini'],                           lastEntry:'Hari ini',      status:'stabil',  diary:'Berhasil finishing draft bab 2. Senang.',                                        color:'#3D52A0' },
  { id:9,  nama:'Indah Setiawati',      nim:'2210101009', sem:7,  kortisol:30, dopamin:80, serotonin:78, oksitosin:82, mood:'Sangat Baik',tags:['Pencapaian Hari Ini'],                           lastEntry:'Hari ini',      status:'stabil',  diary:'Acc BAB 4! Akhirnya bisa lanjut ke bab penutup.',                                color:'#7C3AED' },
  { id:10, nama:'Joko Prasetya Wibowo', nim:'2210101010', sem:4,  kortisol:55, dopamin:52, serotonin:60, oksitosin:55, mood:'Netral',     tags:['Tugas Kelompok','Deadline Tugas'],               lastEntry:'Kemarin',       status:'waspada', diary:'Agak kelelahan tapi masih oke.',                                                 color:'#DB2777' },
  { id:11, nama:'Kartika Rindiani',     nim:'2210101011', sem:2,  kortisol:28, dopamin:82, serotonin:80, oksitosin:85, mood:'Sangat Baik',tags:['Seminar Tamu'],                                  lastEntry:'Hari ini',      status:'stabil',  diary:'Suka banget semester ini. Banyak belajar hal baru.',                             color:'#D97706' },
  { id:12, nama:'Lukman Hakim',         nim:'2210101012', sem:8,  kortisol:75, dopamin:32, serotonin:38, oksitosin:42, mood:'Kurang',     tags:['Skripsi','Sidang Skripsi'],                      lastEntry:'4 jam lalu',    status:'waspada', diary:'Nunggu jadwal sidang bikin was-was terus.',                                      color:'#0891B2' },
];

const konselingData = [
  { id:1,  mhs:'Anisa Rahma Dewi',  nim:'2210101001', diajukan:'18 Jun 2025', jadwal:'20 Jun 2025 — 10:00', topik:'Stres skripsi & kelelahan',      konselor:'Dr. Sari Wulandari', status:'menunggu'  },
  { id:2,  mhs:'Bimo Satrio Nugroho',nim:'2210101002', diajukan:'18 Jun 2025', jadwal:'20 Jun 2025 — 13:00', topik:'Kecemasan sidang skripsi',        konselor:'Rizky Pratama, M.Psi.', status:'menunggu' },
  { id:3,  mhs:'Citra Maharani',    nim:'2210101003', diajukan:'17 Jun 2025', jadwal:'19 Jun 2025 — 11:00', topik:'Beban UTS & dinamika kelompok',   konselor:'— belum dialokasi —', status:'menunggu'  },
  { id:4,  mhs:'Deni Prasetyo',     nim:'2210101004', diajukan:'15 Jun 2025', jadwal:'18 Jun 2025 — 09:00', topik:'Manajemen waktu skripsi',         konselor:'Dr. Ayu Rahayu',     status:'disetujui' },
  { id:5,  mhs:'Elisa Purnama Sari',nim:'2210101005', diajukan:'14 Jun 2025', jadwal:'17 Jun 2025 — 14:00', topik:'Konflik tugas kelompok',          konselor:'Rizky Pratama, M.Psi.', status:'disetujui' },
  { id:6,  mhs:'Lukman Hakim',      nim:'2210101012', diajukan:'16 Jun 2025', jadwal:'18 Jun 2025 — 15:00', topik:'Kecemasan menunggu jadwal sidang', konselor:'Dr. Sari Wulandari', status:'disetujui' },
  { id:7,  mhs:'Gita Permata',      nim:'2210101007', diajukan:'10 Jun 2025', jadwal:'13 Jun 2025 — 10:00', topik:'Eksplorasi karier pasca kampus',  konselor:'Dr. Ayu Rahayu',     status:'selesai'   },
];

const konselorList = [
  { nama:'Dr. Sari Wulandari',    keahlian:'Burnout & Stres Akademik', status:'Tersedia', slot:3, emoji:'👩‍💼', color:'#EEF2FF' },
  { nama:'Rizky Pratama, M.Psi.', keahlian:'Kecemasan & Identitas',    status:'Sibuk — 1 sesi',    slot:1, emoji:'👨‍⚕️', color:'#ECFDF5' },
  { nama:'Dr. Ayu Rahayu',        keahlian:'Relasi & Adaptasi',         status:'Tersedia', slot:4, emoji:'👩‍🏫', color:'#FFFBEB' },
];

const trenData = {
  labels: ['5 Jun','6 Jun','7 Jun','8 Jun','9 Jun','10 Jun','11 Jun','12 Jun','13 Jun','14 Jun','15 Jun','16 Jun','17 Jun','18 Jun'],
  avg:    [52,55,58,54,60,63,61,65,68,66,70,72,74,76],
  kritis: [0,0,1,0,1,1,1,2,2,2,2,3,3,3]
};

const triggerData = [
  { label:'Skripsi / Revisi',         pct:78, color:'#DC2626' },
  { label:'Deadline Tugas',           pct:62, color:'#D97706' },
  { label:'UTS / UAS',                pct:55, color:'#D97706' },
  { label:'Tugas Kelompok',           pct:41, color:'#3D52A0' },
  { label:'Sidang Skripsi',           pct:35, color:'#DC2626' },
  { label:'Analisis Data (SPSS/SEM)', pct:29, color:'#7C3AED' },
];

/* ════════════════════════════════════════════════════
   NAV
════════════════════════════════════════════════════ */
const breadcrumbs = { ringkasan:'Ringkasan Dasbor', radar:'Radar Mahasiswa', peringatan:'Peringatan Dini', konseling:'Manajemen Jadwal Konseling' };

function nav(id) {
  document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
  document.querySelectorAll('.sb-item').forEach(s => s.classList.remove('active'));
  document.getElementById('page-' + id).classList.add('active');
  document.getElementById('nav-' + id).classList.add('active');
  document.getElementById('topbar-bc-text').textContent = breadcrumbs[id];
  if (id === 'ringkasan')  renderRingkasan();
  if (id === 'radar')      renderRadarTable();
  if (id === 'peringatan') renderPeringatan();
  if (id === 'konseling')  renderKonseling();
  closeSidebar();
}

function toggleSidebar() {
  const sb = document.getElementById('sidebar');
  const ov = document.getElementById('sidebar-overlay');
  if (sb.classList.toggle('open')) ov.style.display = 'block';
  else ov.style.display = 'none';
}
function closeSidebar() {
  document.getElementById('sidebar').classList.remove('open');
  document.getElementById('sidebar-overlay').style.display = 'none';
}

/* ════════════════════════════════════════════════════
   CLOCK
════════════════════════════════════════════════════ */
function updateClock() {
  const now = new Date();
  const pad = n => String(n).padStart(2,'0');
  document.getElementById('topbar-clock').textContent =
    `${pad(now.getHours())}:${pad(now.getMinutes())}:${pad(now.getSeconds())} WIB`;
}
setInterval(updateClock, 1000);
updateClock();

(function setLastUpdate() {
  const now = new Date();
  const opts = { day:'numeric', month:'long', year:'numeric', hour:'2-digit', minute:'2-digit' };
  document.getElementById('last-update').textContent = now.toLocaleDateString('id-ID', opts);
})();

/* ════════════════════════════════════════════════════
   CHARTS
════════════════════════════════════════════════════ */
let chartTren = null, chartDonut = null;

function buildCharts() {
  // Tren Kortisol
  if (chartTren) chartTren.destroy();
  chartTren = new Chart(document.getElementById('chart-tren'), {
    type: 'line',
    data: {
      labels: trenData.labels,
      datasets: [
        {
          label: 'Rata-rata Kortisol',
          data: trenData.avg,
          borderColor: '#3D52A0', backgroundColor: 'rgba(61,82,160,.1)',
          fill: true, tension: 0.4, borderWidth: 2.5, pointRadius: 3, pointBackgroundColor: '#3D52A0',
          yAxisID: 'y'
        },
        {
          label: 'Kasus Kritis',
          data: trenData.kritis,
          borderColor: '#DC2626', backgroundColor: 'rgba(220,38,38,.08)',
          fill: false, tension: 0.3, borderWidth: 2, borderDash: [5,4],
          pointRadius: 4, pointBackgroundColor: '#DC2626',
          yAxisID: 'y2'
        }
      ]
    },
    options: {
      responsive: true, maintainAspectRatio: false,
      interaction: { mode: 'index', intersect: false },
      plugins: {
        legend: { display: true, position: 'bottom', labels: { font: { family: 'Inter', size: 11 }, usePointStyle: true, padding: 12 } },
        tooltip: { bodyFont: { family: 'Inter' }, titleFont: { family: 'Inter', weight: '700' } }
      },
      scales: {
        x: { grid: { display: false }, ticks: { font: { family: 'Inter', size: 11 }, color: '#94A3B8', maxRotation: 45 } },
        y: {
          min: 0, max: 100, position: 'left',
          grid: { color: 'rgba(228,232,240,.6)' },
          ticks: { font: { family: 'Inter', size: 11 }, color: '#94A3B8', stepSize: 20 },
          title: { display: true, text: 'Kortisol', font: { family: 'Inter', size: 10 }, color: '#94A3B8' }
        },
        y2: {
          min: 0, max: 8, position: 'right',
          grid: { display: false },
          ticks: { font: { family: 'Inter', size: 11 }, color: '#94A3B8', stepSize: 1 },
          title: { display: true, text: 'Kasus', font: { family: 'Inter', size: 10 }, color: '#94A3B8' }
        }
      }
    }
  });

  // Donut
  if (chartDonut) chartDonut.destroy();
  chartDonut = new Chart(document.getElementById('chart-donut'), {
    type: 'doughnut',
    data: {
      labels: ['Kritis','Waspada','Stabil'],
      datasets: [{ data: [3, 9, 116], backgroundColor: ['#DC2626','#D97706','#059669'], borderWidth: 0, hoverOffset: 4 }]
    },
    options: {
      responsive: true, maintainAspectRatio: false, cutout: '70%',
      plugins: {
        legend: { display: false },
        tooltip: { bodyFont: { family: 'Inter' }, titleFont: { family: 'Inter', weight: '700' } }
      }
    }
  });
}

/* ════════════════════════════════════════════════════
   RINGKASAN PAGE
════════════════════════════════════════════════════ */
function renderRingkasan() {
  buildCharts();
  renderTriggerBars();
  renderQuickWarnings();
}

function renderTriggerBars() {
  document.getElementById('trigger-bars').innerHTML = triggerData.map(t => `
    <div style="margin-bottom:12px">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:4px">
        <span style="font-size:12.5px;font-weight:600;color:var(--txt-bd)">${t.label}</span>
        <span style="font-size:12px;font-weight:800;color:var(--txt-hd)">${t.pct}%</span>
      </div>
      <div style="height:7px;background:var(--border);border-radius:99px;overflow:hidden">
        <div style="height:100%;width:${t.pct}%;background:${t.color};border-radius:99px;transition:width .7s ease"></div>
      </div>
    </div>
  `).join('');
}

function renderQuickWarnings() {
  const kritis = mahasiswaData.filter(m => m.status === 'kritis');
  document.getElementById('quick-warning-list').innerHTML = kritis.map(m => `
    <div style="display:flex;align-items:center;gap:12px;padding:10px 0;border-bottom:1px solid var(--border);flex-wrap:wrap" id="qw-${m.id}">
      <div style="width:36px;height:36px;border-radius:50%;background:${m.color};display:flex;align-items:center;justify-content:center;font-size:12px;font-weight:700;color:#fff;flex-shrink:0">${initials(m.nama)}</div>
      <div style="flex:1;min-width:0">
        <div style="font-size:13px;font-weight:700;color:var(--txt-hd)">${m.nama}</div>
        <div style="font-size:11.5px;color:var(--txt-sm)">NIM ${m.nim} · Sem. ${m.sem} · Kortisol <b style="color:var(--red)">${m.kortisol}</b> · ${m.lastEntry}</div>
      </div>
      <div style="display:flex;gap:6px;flex-wrap:wrap">
        <button class="btn btn-danger btn-sm" onclick="openModal(${m.id})">🔍 Lihat Detail</button>
        <button class="btn btn-primary btn-sm" onclick="hubungiMhs(${m.id}, this)">📞 Hubungi</button>
      </div>
    </div>
  `).join('');
}

/* ════════════════════════════════════════════════════
   RADAR TABLE
════════════════════════════════════════════════════ */
function renderRadarTable() {
  const filter = document.getElementById('filter-status')?.value || 'semua';
  const q      = (document.getElementById('search-mhs')?.value || '').toLowerCase();
  let data     = mahasiswaData.filter(m =>
    (filter === 'semua' || m.status === filter) &&
    (m.nama.toLowerCase().includes(q) || m.nim.includes(q))
  );

  document.getElementById('radar-tbody').innerHTML = data.map(m => {
    const statusBadge = m.status === 'kritis'
      ? `<span class="badge badge-red"><span class="badge-dot dot-red pulse-dot"></span>Kritis</span>`
      : m.status === 'waspada'
      ? `<span class="badge badge-amber"><span class="badge-dot dot-amber"></span>Waspada</span>`
      : `<span class="badge badge-green"><span class="badge-dot dot-green"></span>Stabil</span>`;
    const barColor = m.kortisol > 80 ? '#DC2626' : m.kortisol > 65 ? '#D97706' : '#059669';
    return `
      <tr onclick="openModal(${m.id})">
        <td>
          <div style="display:flex;align-items:center;gap:10px">
            <div style="width:32px;height:32px;border-radius:50%;background:${m.color};display:flex;align-items:center;justify-content:center;font-size:11px;font-weight:700;color:#fff;flex-shrink:0">${initials(m.nama)}</div>
            <div>
              <div class="td-name">${m.nama}</div>
            </div>
          </div>
        </td>
        <td><div class="td-nim" style="font-size:12px">${m.nim}</div></td>
        <td><span style="font-size:13px;font-weight:600">Sem. ${m.sem}</span></td>
        <td>${statusBadge}</td>
        <td>
          <div class="stress-bar-wrap">
            <div class="stress-bar-track"><div class="stress-bar-fill" style="width:${m.kortisol}%;background:${barColor}"></div></div>
            <div class="stress-bar-val" style="color:${barColor}">${m.kortisol}</div>
          </div>
        </td>
        <td><div class="tag-wrap">${m.tags.slice(0,2).map(t => `<span class="tag ${t.includes('Skripsi')||t.includes('Sidang')||t.includes('UTS') ? 'tag-red' : ''}">${t}</span>`).join('')}${m.tags.length > 2 ? `<span class="tag">+${m.tags.length-2}</span>` : ''}</div></td>
        <td><span style="font-size:12px;color:var(--txt-sm)">${m.lastEntry}</span></td>
        <td onclick="event.stopPropagation()">
          <div style="display:flex;gap:5px">
            <button class="btn btn-ghost btn-sm" onclick="openModal(${m.id})">Detail</button>
            ${m.status !== 'stabil' ? `<button class="btn btn-danger btn-sm" onclick="hubungiMhs(${m.id}, this)">Hubungi</button>` : ''}
          </div>
        </td>
      </tr>`;
  }).join('') || `<tr><td colspan="8"><div class="empty"><div class="empty-icon">🔍</div><div class="empty-txt">Tidak ada data sesuai filter.</div></div></td></tr>`;
}

/* ════════════════════════════════════════════════════
   WARNING / PERINGATAN
════════════════════════════════════════════════════ */
let resolvedIds = new Set();

function renderPeringatan() {
  const kritis = mahasiswaData.filter(m => m.status === 'kritis');
  const unresolved = kritis.filter(m => !resolvedIds.has(m.id));
  const resolved   = kritis.filter(m =>  resolvedIds.has(m.id));

  document.getElementById('unresolved-count-badge').textContent = unresolved.length;
  document.getElementById('sb-badge-warn').textContent = unresolved.length;
  document.getElementById('notif-pip').style.display = unresolved.length > 0 ? 'block' : 'none';
  document.getElementById('stat-kritis').textContent = unresolved.length;

  document.getElementById('warning-unresolved').innerHTML = unresolved.map(m => warningItem(m, false)).join('');
  document.getElementById('warning-empty').style.display = unresolved.length === 0 ? 'block' : 'none';

  document.getElementById('warning-resolved').innerHTML = resolved.map(m => warningItem(m, true)).join('');
  document.getElementById('resolved-empty').style.display = resolved.length === 0 ? 'block' : 'none';
}

function warningItem(m, isResolved) {
  const trigger = m.kortisol > 80 ? `Kortisol sangat tinggi (<b>${m.kortisol}</b>)` : `Kortisol <b>${m.kortisol}</b> & Dopamin rendah (<b>${m.dopamin}</b>)`;
  return `
    <div class="warning-item${isResolved ? ' resolved-rendered' : ''}" id="warn-${m.id}">
      <div style="width:38px;height:38px;border-radius:50%;background:${m.color};display:flex;align-items:center;justify-content:center;font-size:13px;font-weight:700;color:#fff;flex-shrink:0">${initials(m.nama)}</div>
      <div class="warning-body">
        <div class="warning-name">${m.nama} <span style="font-size:10.5px;font-weight:500;color:var(--txt-xs)">· NIM ${m.nim} · Sem. ${m.sem}</span></div>
        <div class="warning-meta">Pemicu: ${trigger} · Mood: ${m.mood}</div>
        <div class="warning-meta" style="margin-top:2px">🏷️ ${m.tags.slice(0,3).join(', ')}</div>
        <div class="warning-time">📌 Entri terakhir: ${m.lastEntry}</div>
      </div>
      <div class="warning-actions">
        ${!isResolved ? `
          <button class="btn btn-danger btn-sm" onclick="hubungiMhs(${m.id}, this)">📞 Hubungi Mahasiswa</button>
          <button class="btn btn-ghost btn-sm" onclick="openModal(${m.id})">🔍 Detail</button>
          <button class="btn btn-success btn-sm" onclick="resolveWarning(${m.id})">✓ Tandai Ditangani</button>
        ` : `<span class="badge badge-green">✓ Ditangani</span>`}
      </div>
    </div>`;
}

function resolveWarning(id) {
  resolvedIds.add(id);
  const el = document.getElementById('warn-' + id);
  if (el) {
    el.style.opacity = '0';
    el.style.transform = 'translateX(16px)';
    setTimeout(() => renderPeringatan(), 350);
  }
  showToast('✅ Mahasiswa ditandai sudah ditangani.');
}

/* ════════════════════════════════════════════════════
   KONSELING PAGE
════════════════════════════════════════════════════ */
let konselingFilter = 'semua';

function filterKonseling(f) { konselingFilter = f; renderKonseling(); }

function renderKonseling() {
  // Stats
  const counts = { menunggu: 0, disetujui: 0, selesai: 0 };
  konselingData.forEach(k => counts[k.status]++);
  document.getElementById('konseling-menunggu-val').textContent = counts.menunggu;
  document.getElementById('konseling-disetujui-val').textContent = counts.disetujui;
  document.getElementById('konseling-selesai-val').textContent  = counts.selesai;
  document.getElementById('stat-konseling').textContent = counts.disetujui + counts.menunggu;

  // Konselor availability
  document.getElementById('konselor-availability').innerHTML = `
    <div style="display:flex;gap:12px;flex-wrap:wrap">
      ${konselorList.map(k => `
        <div style="flex:1;min-width:180px;padding:12px 14px;border:1px solid var(--border);border-radius:var(--radius);background:${k.color};display:flex;align-items:center;gap:10px">
          <div style="font-size:24px">${k.emoji}</div>
          <div>
            <div style="font-size:12.5px;font-weight:700;color:var(--txt-hd)">${k.nama}</div>
            <div style="font-size:11px;color:var(--txt-sm)">${k.keahlian}</div>
            <div style="margin-top:4px">
              <span class="badge ${k.slot > 1 ? 'badge-green' : 'badge-amber'}" style="font-size:10px">${k.status} · ${k.slot} slot tersisa</span>
            </div>
          </div>
        </div>
      `).join('')}
    </div>`;

  // Table
  const filtered = konselingData.filter(k => konselingFilter === 'semua' || k.status === konselingFilter);
  document.getElementById('konseling-tbody').innerHTML = filtered.map(k => {
    const statusBadge =
      k.status === 'menunggu'  ? `<span class="badge badge-amber">⏳ Menunggu</span>` :
      k.status === 'disetujui' ? `<span class="badge badge-blue">✅ Disetujui</span>` :
                                  `<span class="badge badge-green">🎯 Selesai</span>`;
    const konsOptions = ['— belum dialokasi —','Dr. Sari Wulandari','Rizky Pratama, M.Psi.','Dr. Ayu Rahayu']
      .map(o => `<option value="${o}" ${k.konselor === o ? 'selected' : ''}>${o}</option>`).join('');
    return `
      <tr>
        <td>
          <div class="td-name">${k.mhs}</div>
          <div class="td-nim">${k.nim}</div>
        </td>
        <td style="font-size:12px;color:var(--txt-sm)">${k.diajukan}</td>
        <td style="font-size:12.5px;font-weight:600">${k.jadwal}</td>
        <td><div class="tag-wrap"><span class="tag">${k.topik}</span></div></td>
        <td>
          <select class="sesi-status-select" onchange="updateKonselor(${k.id}, this.value)" style="max-width:160px;font-size:11px">
            ${konsOptions}
          </select>
        </td>
        <td>${statusBadge}</td>
        <td>
          <div style="display:flex;gap:5px;flex-wrap:wrap">
            ${k.status === 'menunggu' ? `
              <button class="btn btn-success btn-sm" onclick="approveKonseling(${k.id})">✓ Setujui</button>
              <button class="btn btn-ghost btn-sm" onclick="showToast('❌ Sesi dibatalkan.')">Tolak</button>
            ` : k.status === 'disetujui' ? `
              <button class="btn btn-primary btn-sm" onclick="selesaiKonseling(${k.id})">Tandai Selesai</button>
            ` : `<span style="font-size:11px;color:var(--txt-xs)">—</span>`}
          </div>
        </td>
      </tr>`;
  }).join('') || `<tr><td colspan="7"><div class="empty"><div class="empty-icon">📭</div><div class="empty-txt">Tidak ada sesi ditemukan.</div></div></td></tr>`;
}

function updateKonselor(id, val) {
  const k = konselingData.find(k => k.id === id);
  if (k) { k.konselor = val; showToast('👤 Konselor diperbarui: ' + val.replace('— belum dialokasi —','(belum dialokasi)')); }
}

function approveKonseling(id) {
  const k = konselingData.find(k => k.id === id);
  if (!k) return;
  if (k.konselor === '— belum dialokasi —') {
    showToast('⚠️ Alokasikan konselor terlebih dahulu sebelum menyetujui.');
    return;
  }
  k.status = 'disetujui';
  renderKonseling();
  showToast('✅ Jadwal konseling disetujui & notifikasi dikirim ke mahasiswa.');
}

function selesaiKonseling(id) {
  const k = konselingData.find(k => k.id === id);
  if (k) { k.status = 'selesai'; renderKonseling(); showToast('🎯 Sesi konseling ditandai selesai.'); }
}

/* ════════════════════════════════════════════════════
   MODAL: DETAIL MAHASISWA
════════════════════════════════════════════════════ */
function openModal(id) {
  const m = mahasiswaData.find(x => x.id === id);
  if (!m) return;
  document.getElementById('modal-title').textContent = `Detail Kondisi — ${m.nama}`;

  const wb = Math.round((m.dopamin + m.serotonin + m.oksitosin + (100 - m.kortisol)) / 4);
  const hormonConfig = [
    { label:'🧠 Dopamin',   val: m.dopamin,   color: m.dopamin  < 35 ? '#DC2626' : m.dopamin  < 60 ? '#D97706' : '#059669' },
    { label:'☀️ Serotonin', val: m.serotonin, color: m.serotonin< 35 ? '#DC2626' : m.serotonin< 60 ? '#D97706' : '#059669' },
    { label:'🫂 Oksitosin', val: m.oksitosin, color: m.oksitosin< 35 ? '#DC2626' : m.oksitosin< 60 ? '#D97706' : '#059669' },
    { label:'⚡ Kortisol',  val: m.kortisol,  color: m.kortisol > 80 ? '#DC2626' : m.kortisol > 60 ? '#D97706' : '#059669', invert: true },
  ];
  const statusBadge = m.status === 'kritis'
    ? `<span class="badge badge-red"><span class="badge-dot dot-red"></span>Kritis / Burnout</span>`
    : m.status === 'waspada'
    ? `<span class="badge badge-amber"><span class="badge-dot dot-amber"></span>Waspada</span>`
    : `<span class="badge badge-green"><span class="badge-dot dot-green"></span>Stabil</span>`;

  document.getElementById('modal-body').innerHTML = `
    <div style="display:flex;align-items:center;gap:12px;margin-bottom:18px;padding-bottom:16px;border-bottom:1px solid var(--border)">
      <div style="width:48px;height:48px;border-radius:50%;background:${m.color};display:flex;align-items:center;justify-content:center;font-size:16px;font-weight:700;color:#fff">${initials(m.nama)}</div>
      <div>
        <div style="font-size:15px;font-weight:800;color:var(--txt-hd)">${m.nama}</div>
        <div style="font-size:12px;color:var(--txt-sm);margin-top:2px">NIM ${m.nim} · Semester ${m.sem} · Mood: ${m.mood}</div>
        <div style="margin-top:5px;display:flex;align-items:center;gap:8px">${statusBadge}<span style="font-size:12px;color:var(--txt-xs)">Wellbeing Score: <b style="color:var(--txt-hd)">${wb}</b></span></div>
      </div>
    </div>

    <div class="modal-section-lbl">Kondisi Hormon</div>
    <div class="modal-hormone-grid">
      ${hormonConfig.map(h => `
        <div class="mh-item">
          <div class="mh-label" style="color:${h.color}">${h.label}</div>
          <div class="mh-val" style="color:${h.color}">${h.val}</div>
          <div class="mh-bar"><div class="mh-bar-fill" style="width:${h.val}%;background:${h.color}"></div></div>
        </div>
      `).join('')}
    </div>

    <div class="modal-section-lbl">Catatan Diary Terbaru</div>
    <div class="modal-diary">${m.diary || '<em style="color:var(--txt-xs)">Tidak ada catatan diary.</em>'}</div>

    <div class="modal-section-lbl">Pemicu Stres yang Dilaporkan</div>
    <div class="modal-tag-wrap">${m.tags.map(t => `<span class="tag ${t.includes('Skripsi')||t.includes('Sidang')||t.includes('UTS')||t.includes('Analisis') ? 'tag-red' : ''}">${t}</span>`).join('')}</div>

    <div class="modal-actions">
      <button class="btn btn-ghost" onclick="closeModal()">Tutup</button>
      <button class="btn btn-amber" onclick="closeModal();nav('konseling');showToast('📋 Form jadwal konseling dibuka untuk ${m.nama}.')">🗓️ Jadwalkan Konseling</button>
      <button class="btn btn-primary" onclick="hubungiMhs(${m.id}, this);closeModal()">📞 Hubungi Sekarang</button>
    </div>`;

  document.getElementById('modal-overlay').classList.add('open');
}

function closeModal() {
  document.getElementById('modal-overlay').classList.remove('open');
}

document.getElementById('modal-overlay').addEventListener('click', function(e) {
  if (e.target === this) closeModal();
});

/* ════════════════════════════════════════════════════
   ACTIONS
════════════════════════════════════════════════════ */
function hubungiMhs(id, btn) {
  const m = mahasiswaData.find(x => x.id === id);
  if (!m) return;
  if (btn) {
    const orig = btn.textContent;
    btn.textContent = '✓ Dihubungi';
    btn.classList.remove('btn-danger','btn-primary');
    btn.classList.add('btn-success');
    btn.disabled = true;
  }
  showToast(`📞 Notifikasi dikirim ke ${m.nama} — menunggu respon.`);
}

/* ════════════════════════════════════════════════════
   TOAST
════════════════════════════════════════════════════ */
let toastTimer;
function showToast(msg) {
  const t = document.getElementById('toast');
  t.textContent = msg;
  t.classList.add('show');
  if (toastTimer) clearTimeout(toastTimer);
  toastTimer = setTimeout(() => t.classList.remove('show'), 3600);
}

/* ════════════════════════════════════════════════════
   UTILS
════════════════════════════════════════════════════ */
function initials(nama) {
  return nama.split(' ').slice(0,2).map(w => w[0]).join('').toUpperCase();
}

/* ════════════════════════════════════════════════════
   INIT
════════════════════════════════════════════════════ */
(function init() {
  renderRingkasan();
  renderRadarTable();
  renderPeringatan();
  renderKonseling();
})();
</script>
</body>
</html>
