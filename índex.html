<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Lumière Studio</title>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/fontsource/fonts/inter@latest/latin-400-normal.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/fontsource/fonts/inter@latest/latin-600-normal.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/fontsource/fonts/inter@latest/latin-700-normal.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/fontsource/fonts/playfair-display@latest/latin-700-normal.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/fontsource/fonts/playfair-display@latest/latin-400-italic.css">
<style>
*{margin:0;padding:0;box-sizing:border-box}
:root{
  --bg:#0a0a0b;--bg2:#111113;--bg3:#1a1a1d;--bg4:#232327;
  --text:#f5f5f7;--text2:#a1a1aa;--text3:#71717a;
  --accent:#c9a96e;--accent2:#e8d5a8;--accent-dark:#8b7340;
  --border:#27272a;--danger:#ef4444;--success:#22c55e;--info:#3b82f6;
  --radius:12px;--radius-lg:20px;
}
body{font-family:'Inter',sans-serif;background:var(--bg);color:var(--text);min-height:100vh;overflow-x:hidden}
::-webkit-scrollbar{width:6px}
::-webkit-scrollbar-track{background:var(--bg2)}
::-webkit-scrollbar-thumb{background:var(--bg4);border-radius:3px}
::-webkit-scrollbar-thumb:hover{background:var(--accent-dark)}

nav{position:fixed;top:0;left:0;right:0;z-index:100;padding:1rem 2rem;display:flex;align-items:center;justify-content:space-between;backdrop-filter:blur(20px);background:rgba(10,10,11,.85);border-bottom:1px solid rgba(255,255,255,.05)}
.nav-left{display:flex;align-items:center;gap:1rem}
.logo-img{height:40px;width:auto}
.logo-text{font-family:'Playfair Display',serif;font-size:1.4rem;font-weight:700;color:var(--accent);letter-spacing:1px}
.nav-links{display:flex;gap:.5rem;align-items:center}
.nav-links button{background:none;border:none;color:var(--text2);font-size:.88rem;cursor:pointer;text-decoration:none;transition:all .3s;font-family:inherit;padding:.5rem .9rem;border-radius:8px}
.nav-links button:hover{color:var(--accent);background:rgba(201,169,110,.08)}
.btn-login{padding:.5rem 1.2rem!important;border:1px solid var(--accent)!important;color:var(--accent)!important;border-radius:50px!important;font-weight:600!important}
.btn-login:hover{background:var(--accent)!important;color:var(--bg)!important}
.btn-admin-active{background:var(--accent)!important;color:var(--bg)!important}
.user-badge{display:flex;align-items:center;gap:.5rem;padding:.4rem .8rem;background:rgba(201,169,110,.15);border-radius:50px;font-size:.8rem;color:var(--accent)}

.hero{min-height:100vh;display:flex;align-items:center;justify-content:center;position:relative;overflow:hidden;background-size:cover;background-position:center;background-attachment:fixed}
.hero::before{content:'';position:absolute;inset:0;background:linear-gradient(to bottom,rgba(10,10,11,.3) 0%,rgba(10,10,11,.7) 50%,rgba(10,10,11,1) 100%)}
.hero-content{text-align:center;z-index:1;animation:fadeUp 1s ease;padding:2rem;max-width:800px}
.hero h1{font-family:'Playfair Display',serif;font-size:clamp(2.5rem,6vw,5rem);font-weight:700;line-height:1.1;margin-bottom:1rem}
.hero h1 em{font-style:italic;color:var(--accent)}
.hero p{color:var(--text2);font-size:1.1rem;max-width:550px;margin:0 auto 2rem;line-height:1.7}
.hero-btn{display:inline-block;padding:.9rem 2.5rem;background:var(--accent);color:var(--bg);border:none;border-radius:50px;font-size:1rem;font-weight:600;cursor:pointer;transition:all .3s;text-decoration:none;font-family:inherit}
.hero-btn:hover{transform:translateY(-2px);box-shadow:0 10px 30px rgba(201,169,110,.3)}
@keyframes fadeUp{from{opacity:0;transform:translateY(30px)}to{opacity:1;transform:translateY(0)}}

.section{padding:5rem 2rem;max-width:1400px;margin:0 auto}
.section-title{font-family:'Playfair Display',serif;font-size:2.2rem;margin-bottom:.5rem}
.section-subtitle{color:var(--text2);margin-bottom:3rem;font-size:1rem}

.albums-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(320px,1fr));gap:1.5rem}
.album-card{position:relative;border-radius:var(--radius-lg);overflow:hidden;cursor:pointer;aspect-ratio:4/3;background:var(--bg3);transition:all .4s;border:1px solid var(--border)}
.album-card:hover{transform:translateY(-5px);border-color:var(--accent-dark);box-shadow:0 20px 40px rgba(0,0,0,.4)}
.album-card img{width:100%;height:100%;object-fit:cover;transition:transform .6s}
.album-card:hover img{transform:scale(1.05)}
.album-overlay{position:absolute;inset:0;background:linear-gradient(to top,rgba(0,0,0,.85) 0%,transparent 60%);display:flex;flex-direction:column;justify-content:flex-end;padding:1.5rem}
.album-overlay h3{font-family:'Playfair Display',serif;font-size:1.3rem;margin-bottom:.3rem}
.album-overlay p{color:var(--text2);font-size:.82rem}
.album-badge{position:absolute;top:1rem;right:1rem;padding:.3rem .7rem;border-radius:50px;font-size:.7rem;font-weight:600;text-transform:uppercase;letter-spacing:.5px;backdrop-filter:blur(10px)}
.badge-public{background:rgba(34,197,94,.2);color:var(--success);border:1px solid rgba(34,197,94,.3)}
.badge-private{background:rgba(201,169,110,.2);color:var(--accent);border:1px solid rgba(201,169,110,.3)}
.badge-free{background:rgba(59,130,246,.2);color:var(--info);border:1px solid rgba(59,130,246,.3)}
.badge-paid{background:rgba(201,169,110,.2);color:var(--accent);border:1px solid rgba(201,169,110,.3)}
.album-count{position:absolute;top:1rem;left:1rem;background:rgba(0,0,0,.6);backdrop-filter:blur(10px);padding:.3rem .7rem;border-radius:50px;font-size:.75rem;color:var(--text2)}
.album-client-tag{position:absolute;bottom:3.5rem;left:1rem;background:rgba(0,0,0,.6);backdrop-filter:blur(10px);padding:.2rem .6rem;border-radius:50px;font-size:.7rem;color:var(--accent)}

.gallery-view{display:none;min-height:100vh;padding-top:5rem}
.gallery-header{padding:2rem;display:flex;align-items:center;gap:1rem;flex-wrap:wrap;border-bottom:1px solid var(--border)}
.back-btn{background:none;border:1px solid var(--border);color:var(--text);padding:.6rem 1.2rem;border-radius:50px;cursor:pointer;font-family:inherit;font-size:.9rem;transition:all .3s;display:flex;align-items:center;gap:.5rem}
.back-btn:hover{border-color:var(--accent);color:var(--accent)}
.gallery-header h2{font-family:'Playfair Display',serif;font-size:1.8rem;flex:1}
.gallery-info{color:var(--text2);font-size:.9rem}
.photos-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(220px,1fr));gap:1rem;padding:1.5rem 2rem 2rem}
.photo-card{position:relative;border-radius:var(--radius);overflow:hidden;cursor:pointer;aspect-ratio:1;background:var(--bg3);transition:all .3s;border:1px solid transparent}
.photo-card:hover{border-color:var(--accent-dark);transform:scale(1.02)}
.photo-card img{width:100%;height:100%;object-fit:cover;transition:transform .4s}
.photo-card:hover img{transform:scale(1.08)}
.photo-overlay{position:absolute;inset:0;background:rgba(0,0,0,.6);opacity:0;transition:opacity .3s;display:flex;align-items:center;justify-content:center;gap:.6rem}
.photo-card:hover .photo-overlay{opacity:1}
.photo-overlay button{width:38px;height:38px;border-radius:50%;border:none;background:rgba(255,255,255,.15);backdrop-filter:blur(10px);color:white;cursor:pointer;display:flex;align-items:center;justify-content:center;transition:all .2s;font-size:.9rem}
.photo-overlay button:hover{background:var(--accent);color:var(--bg)}

.lightbox{display:none;position:fixed;inset:0;z-index:200;background:rgba(0,0,0,.97);backdrop-filter:blur(20px);align-items:center;justify-content:center;flex-direction:column}
.lightbox.active{display:flex}
.lightbox img{max-width:90vw;max-height:75vh;object-fit:contain;border-radius:var(--radius)}
.lightbox-close{position:absolute;top:1.5rem;right:1.5rem;width:44px;height:44px;border-radius:50%;border:1px solid rgba(255,255,255,.2);background:rgba(255,255,255,.1);color:white;font-size:1.2rem;cursor:pointer;display:flex;align-items:center;justify-content:center;transition:all .3s;z-index:10}
.lightbox-close:hover{background:var(--accent);color:var(--bg);border-color:var(--accent)}
.lightbox-nav{position:absolute;top:50%;transform:translateY(-50%);width:48px;height:48px;border-radius:50%;border:1px solid rgba(255,255,255,.2);background:rgba(255,255,255,.1);color:white;font-size:1.2rem;cursor:pointer;display:flex;align-items:center;justify-content:center;transition:all .3s;z-index:10}
.lightbox-nav:hover{background:var(--accent);color:var(--bg);border-color:var(--accent)}
.lightbox-prev{left:1.5rem}
.lightbox-next{right:1.5rem}
.lightbox-actions{display:flex;gap:.6rem;margin-top:1.5rem;flex-wrap:wrap;justify-content:center}
.lightbox-actions button{padding:.6rem 1rem;border-radius:50px;border:1px solid rgba(255,255,255,.2);background:rgba(255,255,255,.1);color:white;cursor:pointer;font-family:inherit;font-size:.85rem;display:flex;align-items:center;gap:.4rem;transition:all .3s}
.lightbox-actions button:hover{background:var(--accent);color:var(--bg);border-color:var(--accent)}
.lightbox-info{color:var(--text2);font-size:.8rem;margin-top:.8rem}

.modal-overlay{display:none;position:fixed;inset:0;z-index:150;background:rgba(0,0,0,.75);backdrop-filter:blur(10px);align-items:center;justify-content:center;padding:1rem}
.modal-overlay.active{display:flex}
.modal{background:var(--bg2);border:1px solid var(--border);border-radius:var(--radius-lg);padding:2rem;max-width:550px;width:100%;max-height:90vh;overflow-y:auto;animation:modalIn .3s ease}
@keyframes modalIn{from{opacity:0;transform:scale(.95)}to{opacity:1;transform:scale(1)}}
.modal h2{font-family:'Playfair Display',serif;font-size:1.5rem;margin-bottom:1.5rem}
.modal label{display:block;color:var(--text2);font-size:.82rem;margin-bottom:.4rem;margin-top:1rem;font-weight:600}
.modal input,.modal textarea,.modal select{width:100%;padding:.7rem 1rem;background:var(--bg3);border:1px solid var(--border);border-radius:var(--radius);color:var(--text);font-family:inherit;font-size:.9rem;transition:border-color .3s}
.modal input:focus,.modal textarea:focus,.modal select:focus{outline:none;border-color:var(--accent)}
.modal textarea{resize:vertical;min-height:80px}
.modal-actions{display:flex;gap:.8rem;margin-top:1.5rem;justify-content:flex-end;flex-wrap:wrap}
.btn{padding:.7rem 1.3rem;border-radius:50px;border:none;cursor:pointer;font-family:inherit;font-size:.88rem;font-weight:600;transition:all .3s;display:inline-flex;align-items:center;gap:.4rem}
.btn-primary{background:var(--accent);color:var(--bg)}
.btn-primary:hover{background:var(--accent2)}
.btn-secondary{background:var(--bg3);color:var(--text);border:1px solid var(--border)}
.btn-secondary:hover{border-color:var(--accent);color:var(--accent)}
.btn-danger{background:rgba(239,68,68,.15);color:var(--danger);border:1px solid rgba(239,68,68,.3)}
.btn-danger:hover{background:var(--danger);color:white}
.btn-info{background:rgba(59,130,246,.15);color:var(--info);border:1px solid rgba(59,130,246,.3)}
.btn-info:hover{background:var(--info);color:white}
.btn-warning{background:rgba(251,191,36,.15);color:#fbbf24;border:1px solid rgba(251,191,36,.3)}
.btn-warning:hover{background:#fbbf24;color:var(--bg)}
.btn-sm{padding:.4rem .8rem;font-size:.8rem}

.upload-zone{border:2px dashed var(--border);border-radius:var(--radius);padding:2.5rem 2rem;text-align:center;cursor:pointer;transition:all .3s;margin-top:.5rem}
.upload-zone:hover,.upload-zone.dragover{border-color:var(--accent);background:rgba(201,169,110,.05)}
.upload-zone svg{width:42px;height:42px;stroke:var(--text3);margin-bottom:.8rem}
.upload-zone p{color:var(--text2);font-size:.88rem}
.upload-zone .highlight{color:var(--accent);font-weight:600}
.upload-preview{display:grid;grid-template-columns:repeat(auto-fill,minmax(70px,1fr));gap:.5rem;margin-top:1rem;max-height:200px;overflow-y:auto}
.upload-preview img{width:100%;aspect-ratio:1;object-fit:cover;border-radius:8px;border:1px solid var(--border)}

.admin-panel{display:none;padding-top:5rem;min-height:100vh}
.admin-panel.active{display:block}
.admin-tabs{display:flex;gap:.5rem;padding:1rem 2rem;border-bottom:1px solid var(--border);background:var(--bg2);overflow-x:auto;position:sticky;top:65px;z-index:50}
.admin-tab{padding:.7rem 1.2rem;border:none;background:none;color:var(--text2);cursor:pointer;font-family:inherit;font-size:.88rem;border-radius:8px;transition:all .3s;white-space:nowrap;font-weight:600}
.admin-tab:hover{color:var(--accent);background:rgba(201,169,110,.08)}
.admin-tab.active{background:var(--accent);color:var(--bg)}
.admin-content{padding:2rem;max-width:1400px;margin:0 auto}
.admin-section{display:none}
.admin-section.active{display:block;animation:fadeUp .3s ease}

.stats-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:1rem;margin-bottom:2rem}
.stat-card{background:var(--bg2);border:1px solid var(--border);border-radius:var(--radius);padding:1.5rem}
.stat-card h4{color:var(--text2);font-size:.8rem;text-transform:uppercase;letter-spacing:1px;margin-bottom:.5rem}
.stat-card .stat-value{font-family:'Playfair Display',serif;font-size:2rem;color:var(--accent)}
.stat-card .stat-label{color:var(--text3);font-size:.78rem;margin-top:.3rem}

.data-table{width:100%;border-collapse:collapse;background:var(--bg2);border-radius:var(--radius);overflow:hidden;border:1px solid var(--border)}
.data-table th{background:var(--bg3);padding:.8rem 1rem;text-align:left;font-size:.78rem;text-transform:uppercase;letter-spacing:.5px;color:var(--text2);font-weight:600}
.data-table td{padding:.8rem 1rem;border-top:1px solid var(--border);font-size:.88rem}
.data-table tr:hover td{background:rgba(201,169,110,.03)}

.config-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:1.5rem}
.config-card{background:var(--bg2);border:1px solid var(--border);border-radius:var(--radius);padding:1.5rem}
.config-card h3{font-family:'Playfair Display',serif;font-size:1.2rem;margin-bottom:1rem;color:var(--accent)}
.color-input-wrap{display:flex;align-items:center;gap:.8rem}
.color-input-wrap input[type=color]{width:50px;height:40px;border:none;border-radius:8px;cursor:pointer;background:none}
.color-input-wrap input[type=text]{flex:1}
.toggle{position:relative;display:inline-block;width:50px;height:26px}
.toggle input{opacity:0;width:0;height:0}
.toggle-slider{position:absolute;cursor:pointer;inset:0;background:var(--bg4);border-radius:26px;transition:.3s}
.toggle-slider:before{content:'';position:absolute;height:20px;width:20px;left:3px;bottom:3px;background:white;border-radius:50%;transition:.3s}
.toggle input:checked+.toggle-slider{background:var(--accent)}
.toggle input:checked+.toggle-slider:before{transform:translateX(24px)}
.toggle-label{display:flex;align-items:center;gap:.8rem;cursor:pointer}
.preview-box{background:var(--bg3);border-radius:var(--radius);padding:1rem;margin-top:1rem;border:1px solid var(--border)}

.log-filters{display:flex;gap:.8rem;margin-bottom:1rem;flex-wrap:wrap}
.log-filters input,.log-filters select{padding:.5rem .8rem;background:var(--bg3);border:1px solid var(--border);border-radius:8px;color:var(--text);font-family:inherit;font-size:.85rem}

.toast{position:fixed;bottom:2rem;right:2rem;z-index:300;padding:1rem 1.5rem;background:var(--bg2);border:1px solid var(--border);border-radius:var(--radius);color:var(--text);font-size:.9rem;animation:slideIn .3s ease;box-shadow:0 10px 30px rgba(0,0,0,.5);max-width:350px}
.toast.success{border-color:var(--success)}
.toast.error{border-color:var(--danger)}
.toast.info{border-color:var(--info)}
@keyframes slideIn{from{opacity:0;transform:translateX(20px)}to{opacity:1;transform:translateX(0)}}

.empty-state{text-align:center;padding:4rem 2rem;color:var(--text3)}
.empty-state svg{width:64px;height:64px;stroke:var(--text3);margin-bottom:1rem;opacity:.5}
.empty-state p{font-size:1rem}

footer{text-align:center;padding:3rem 2rem;border-top:1px solid var(--border);color:var(--text3);font-size:.85rem;margin-top:3rem}
footer .social-links{display:flex;gap:.8rem;justify-content:center;margin-top:1rem;flex-wrap:wrap}
.social-link{display:flex;align-items:center;gap:.4rem;padding:.4rem .9rem;background:var(--bg3);border:1px solid var(--border);border-radius:50px;color:var(--text2);font-size:.82rem;text-decoration:none;transition:all .3s}
.social-link:hover{border-color:var(--accent);color:var(--accent)}

.login-help{margin-top:1.5rem;padding:1rem;background:rgba(251,191,36,.08);border:1px solid rgba(251,191,36,.25);border-radius:var(--radius)}
.login-help h4{color:#fbbf24;font-size:.85rem;margin-bottom:.5rem;display:flex;align-items:center;gap:.4rem}
.login-help p{color:var(--text2);font-size:.78rem;line-height:1.7;margin-bottom:.5rem}
.login-help code{background:var(--bg3);padding:.15rem .4rem;border-radius:4px;color:var(--accent);font-size:.8rem}
.login-help .reset-btn{margin-top:.8rem;width:100%;justify-content:center}

@media(max-width:768px){
  nav{padding:.8rem 1rem}
  .logo-text{font-size:1.1rem}
  .section{padding:3rem 1rem}
  .albums-grid{grid-template-columns:1fr}
  .photos-grid{grid-template-columns:repeat(auto-fill,minmax(140px,1fr));padding:1rem}
  .gallery-header{padding:1rem}
  .lightbox-nav{display:none}
  .admin-content{padding:1rem}
  .modal{padding:1.5rem}
  .hero h1{font-size:2.5rem}
  .nav-links button{padding:.4rem .6rem;font-size:.8rem}
}
</style>
</head>
<body>

<nav>
  <div class="nav-left">
    <img id="navLogo" class="logo-img" src="" alt="Logo" style="display:none">
    <div class="logo-text" id="navLogoText">Lumière Studio</div>
  </div>
  <div class="nav-links" id="navLinks">
    <button onclick="showHome()">🏠 Galería</button>
    <button id="clientNavBtn" style="display:none" onclick="showClientView()">📁 Mis Álbumes</button>
    <button id="adminNavBtn" style="display:none" onclick="showAdmin()">⚙️ Panel</button>
    <div id="userBadge" class="user-badge" style="display:none"></div>
    <button class="btn-login" id="loginBtn" onclick="handleLoginClick()">Acceder</button>
  </div>
</nav>

<div id="publicView">
  <section class="hero" id="heroSection">
    <div class="hero-content">
      <h1 id="heroTitle">Momentos que<br><em>perduran</em></h1>
      <p id="heroSubtitle">Una galería exclusiva donde cada imagen cuenta una historia única.</p>
      <button class="hero-btn" onclick="document.getElementById('albumsSection').scrollIntoView({behavior:'smooth'})">Explorar Galería</button>
    </div>
  </section>
  <section class="section" id="albumsSection">
    <h2 class="section-title">Colecciones</h2>
    <p class="section-subtitle">Explora nuestras galerías fotográficas</p>
    <div class="albums-grid" id="publicAlbumsGrid"></div>
    <div class="empty-state" id="emptyPublic" style="display:none">
      <svg viewBox="0 0 24 24" fill="none" stroke-width="1.5"><rect x="3" y="3" width="18" height="18" rx="2"/><circle cx="8.5" cy="8.5" r="1.5"/><path d="M21 15l-5-5L5 21"/></svg>
      <p>No hay álbumes públicos todavía</p>
    </div>
  </section>
  <footer>
    <p id="footerText">© 2026 Lumière Studio — Todos los derechos reservados</p>
    <div class="social-links" id="footerSocial"></div>
  </footer>
</div>

<div class="gallery-view" id="galleryView">
  <div class="gallery-header">
    <button class="back-btn" onclick="goBack()">← Volver</button>
    <h2 id="galleryTitle"></h2>
    <span class="gallery-info" id="galleryInfo"></span>
    <button class="btn btn-primary" onclick="downloadAllPhotos()" style="font-size:.82rem;padding:.5rem 1rem">⬇ Descargar todo</button>
  </div>
  <div class="photos-grid" id="photosGrid"></div>
  <div class="empty-state" id="emptyPhotos" style="display:none">
    <svg viewBox="0 0 24 24" fill="none" stroke-width="1.5"><rect x="3" y="3" width="18" height="18" rx="2"/><circle cx="8.5" cy="8.5" r="1.5"/><path d="M21 15l-5-5L5 21"/></svg>
    <p>Este álbum no tiene fotos todavía</p>
  </div>
</div>

<div class="admin-panel" id="adminPanel">
  <div class="admin-tabs">
    <button class="admin-tab active" onclick="showAdminTab('dashboard',this)">📊 Dashboard</button>
    <button class="admin-tab" onclick="showAdminTab('albums',this)">📁 Álbumes</button>
    <button class="admin-tab" onclick="showAdminTab('clients',this)">👥 Clientes</button>
    <button class="admin-tab" onclick="showAdminTab('config',this)">⚙️ Configuración</button>
    <button class="admin-tab" onclick="showAdminTab('logs',this)">📋 Historial</button>
  </div>
  <div class="admin-content">
    <div class="admin-section active" id="tab-dashboard">
      <h2 style="font-family:'Playfair Display',serif;margin-bottom:1.5rem">Dashboard</h2>
      <div class="stats-grid" id="statsGrid"></div>
      <div class="config-card" style="margin-top:1rem">
        <h3>Actividad reciente</h3>
        <div id="recentActivity"></div>
      </div>
    </div>
    <div class="admin-section" id="tab-albums">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:1.5rem;flex-wrap:wrap;gap:1rem">
        <h2 style="font-family:'Playfair Display',serif">Gestión de Álbumes</h2>
        <button class="btn btn-primary" onclick="openCreateAlbum()">＋ Nuevo Álbum</button>
      </div>
      <div id="adminAlbumsList"></div>
    </div>
    <div class="admin-section" id="tab-clients">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:1.5rem;flex-wrap:wrap;gap:1rem">
        <h2 style="font-family:'Playfair Display',serif">Gestión de Clientes</h2>
        <button class="btn btn-primary" onclick="openCreateClient()">＋ Nuevo Cliente</button>
      </div>
      <div id="adminClientsList"></div>
    </div>
    <div class="admin-section" id="tab-config">
      <h2 style="font-family:'Playfair Display',serif;margin-bottom:1.5rem">Configuración del Sitio</h2>
      <div class="config-grid">
        <div class="config-card">
          <h3>🏷️ Identidad</h3>
          <label>Nombre del sitio</label>
          <input type="text" id="cfgSiteName" oninput="updateConfig()">
          <label>Logo (imagen)</label>
          <div class="upload-zone" onclick="document.getElementById('cfgLogoInput').click()" style="padding:1.5rem">
            <p id="cfgLogoText">Haz clic para subir logo</p>
          </div>
          <input type="file" id="cfgLogoInput" accept="image/*" style="display:none" onchange="handleLogoUpload(event)">
          <div id="cfgLogoPreview" style="margin-top:.8rem"></div>
          <button class="btn btn-secondary btn-sm" onclick="clearLogo()" style="margin-top:.5rem">Quitar logo</button>
        </div>
        <div class="config-card">
          <h3>🎨 Colores</h3>
          <label>Color principal (acento)</label>
          <div class="color-input-wrap">
            <input type="color" id="cfgAccent" oninput="updateConfig()">
            <input type="text" id="cfgAccentText" oninput="syncColor('cfgAccent',this.value)">
          </div>
          <label>Color de fondo</label>
          <div class="color-input-wrap">
            <input type="color" id="cfgBg" oninput="updateConfig()">
            <input type="text" id="cfgBgText" oninput="syncColor('cfgBg',this.value)">
          </div>
          <label>Color de texto</label>
          <div class="color-input-wrap">
            <input type="color" id="cfgText" oninput="updateConfig()">
            <input type="text" id="cfgTextText" oninput="syncColor('cfgText',this.value)">
          </div>
          <button class="btn btn-secondary btn-sm" onclick="resetColors()" style="margin-top:1rem">Restaurar colores por defecto</button>
        </div>
        <div class="config-card">
          <h3>🖼️ Hero / Portada</h3>
          <label>Imagen de fondo</label>
          <div class="upload-zone" onclick="document.getElementById('cfgHeroInput').click()" style="padding:1.5rem">
            <p id="cfgHeroText">Haz clic para subir imagen</p>
          </div>
          <input type="file" id="cfgHeroInput" accept="image/*" style="display:none" onchange="handleHeroUpload(event)">
          <div id="cfgHeroPreview" style="margin-top:.8rem"></div>
          <label>Título principal</label>
          <input type="text" id="cfgHeroTitle" oninput="updateConfig()">
          <label>Subtítulo</label>
          <textarea id="cfgHeroSubtitle" oninput="updateConfig()"></textarea>
        </div>
        <div class="config-card">
          <h3>🌐 Redes Sociales</h3>
          <label>Instagram URL</label>
          <input type="text" id="cfgInstagram" placeholder="https://instagram.com/..." oninput="updateConfig()">
          <label>Facebook URL</label>
          <input type="text" id="cfgFacebook" placeholder="https://facebook.com/..." oninput="updateConfig()">
          <label>Twitter/X URL</label>
          <input type="text" id="cfgTwitter" placeholder="https://twitter.com/..." oninput="updateConfig()">
          <label>WhatsApp (número)</label>
          <input type="text" id="cfgWhatsapp" placeholder="+34 600 000 000" oninput="updateConfig()">
        </div>
        <div class="config-card">
          <h3>💧 Marca de Agua</h3>
          <label class="toggle-label">
            <label class="toggle">
              <input type="checkbox" id="cfgWatermarkEnabled" onchange="updateConfig()">
              <span class="toggle-slider"></span>
            </label>
            <span>Activar marca de agua</span>
          </label>
          <label>Texto de la marca de agua</label>
          <input type="text" id="cfgWatermarkText" placeholder="© Lumière Studio" oninput="updateConfig()">
          <label>Opacidad (0-100%)</label>
          <input type="range" id="cfgWatermarkOpacity" min="10" max="80" value="40" oninput="updateConfig()" style="width:100%">
          <label>Tamaño de fuente</label>
          <input type="range" id="cfgWatermarkSize" min="10" max="60" value="30" oninput="updateConfig()" style="width:100%">
          <div class="preview-box">
            <p style="color:var(--text2);font-size:.8rem;margin-bottom:.5rem">Vista previa:</p>
            <div id="watermarkPreview" style="background:#222;height:100px;border-radius:8px;display:flex;align-items:center;justify-content:center;position:relative;overflow:hidden">
              <span style="color:#888;font-size:.9rem">Imagen de ejemplo</span>
            </div>
          </div>
        </div>
        <div class="config-card">
          <h3>🔐 Seguridad</h3>
          <label>Contraseña de administrador</label>
          <input type="password" id="cfgAdminPass" placeholder="Nueva contraseña">
          <button class="btn btn-primary btn-sm" onclick="changeAdminPass()" style="margin-top:.8rem">Cambiar contraseña</button>
          <p style="color:var(--text3);font-size:.75rem;margin-top:.8rem">⚠️ Guarda bien esta contraseña. No hay recuperación.</p>
        </div>
      </div>
      <div style="margin-top:2rem;text-align:center">
        <button class="btn btn-primary" onclick="saveConfig()" style="padding:.9rem 2rem;font-size:1rem">💾 Guardar Configuración</button>
      </div>
    </div>
    <div class="admin-section" id="tab-logs">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:1.5rem;flex-wrap:wrap;gap:1rem">
        <h2 style="font-family:'Playfair Display',serif">Historial de Actividad</h2>
        <div style="display:flex;gap:.5rem">
          <button class="btn btn-secondary btn-sm" onclick="exportLogs()">📥 Exportar CSV</button>
          <button class="btn btn-danger btn-sm" onclick="clearLogs()">🗑 Limpiar</button>
        </div>
      </div>
      <div class="log-filters">
        <input type="text" id="logSearch" placeholder="🔍 Buscar por email, álbum..." oninput="renderLogs()">
        <select id="logFilterAction" onchange="renderLogs()">
          <option value="">Todas las acciones</option>
          <option value="view">Vistas</option>
          <option value="download">Descargas</option>
          <option value="login">Logins</option>
        </select>
      </div>
      <div id="logsTable"></div>
    </div>
  </div>
</div>

<div class="lightbox" id="lightbox">
  <button class="lightbox-close" onclick="closeLightbox()">✕</button>
  <button class="lightbox-nav lightbox-prev" onclick="navLightbox(-1)">‹</button>
  <button class="lightbox-nav lightbox-next" onclick="navLightbox(1)">›</button>
  <img id="lightboxImg" src="" alt="">
  <div class="lightbox-info" id="lightboxInfo"></div>
  <div class="lightbox-actions" id="lightboxActions"></div>
</div>

<div class="modal-overlay" id="loginModal">
  <div class="modal">
    <h2>Acceder a tu cuenta</h2>
    <p style="color:var(--text2);font-size:.88rem;margin-bottom:1rem">Introduce tus credenciales para acceder a tus álbumes privados.</p>
    <label>Email</label>
    <input type="email" id="loginEmail" placeholder="tu@email.com" autocomplete="email">
    <label>Contraseña</label>
    <input type="password" id="loginPassword" placeholder="Contraseña" onkeypress="if(event.key==='Enter')doLogin()" autocomplete="current-password">
    <div id="loginError" style="display:none;margin-top:1rem;padding:.8rem;background:rgba(239,68,68,.1);border:1px solid rgba(239,68,68,.3);border-radius:8px;color:var(--danger);font-size:.85rem"></div>
    <div class="modal-actions">
      <button class="btn btn-secondary" onclick="closeModal('loginModal')">Cancelar</button>
      <button class="btn btn-primary" onclick="doLogin()">Entrar</button>
    </div>
    <div class="login-help">
      <h4>🔑 ¿No puedes acceder?</h4>
      <p><strong style="color:var(--accent)">Credenciales por defecto:</strong><br>
        Admin: <code>admin@lumiere.com</code> / <code>admin123</code><br>
        Cliente: <code>maria@demo.com</code> / <code>maria2026</code>
      </p>
      <p style="margin-top:.5rem">Si cambiaste la contraseña de admin y no la recuerdas, usa este botón de emergencia:</p>
      <button class="btn btn-warning btn-sm reset-btn" onclick="resetAdminPassword()">🔓 Restablecer contraseña admin a "admin123"</button>
    </div>
  </div>
</div>

<div class="modal-overlay" id="createAlbumModal">
  <div class="modal">
    <h2 id="albumModalTitle">Nuevo Álbum</h2>
    <label>Nombre del álbum</label>
    <input type="text" id="albumName" placeholder="Ej: Sesión María - Octubre 2026">
    <label>Descripción</label>
    <textarea id="albumDesc" placeholder="Descripción del álbum..."></textarea>
    <div style="display:grid;grid-template-columns:1fr 1fr;gap:1rem">
      <div>
        <label>Tipo</label>
        <select id="albumType">
          <option value="free">🆓 Gratuito</option>
          <option value="paid">💎 De pago</option>
        </select>
      </div>
      <div>
        <label>Visibilidad</label>
        <select id="albumVisibility">
          <option value="public">🌐 Público</option>
          <option value="private">🔒 Privado</option>
        </select>
      </div>
    </div>
    <label>Asignar a cliente (opcional)</label>
    <select id="albumClient">
      <option value="">— Sin asignar —</option>
    </select>
    <label>Imagen de portada</label>
    <div class="upload-zone" onclick="document.getElementById('coverInput').click()" style="padding:1.5rem">
      <p id="coverText">Haz clic para subir portada</p>
    </div>
    <input type="file" id="coverInput" accept="image/*" style="display:none" onchange="handleCoverUpload(event)">
    <div id="coverPreview" style="margin-top:.5rem"></div>
    <div class="modal-actions">
      <button class="btn btn-secondary" onclick="closeModal('createAlbumModal')">Cancelar</button>
      <button class="btn btn-primary" onclick="saveAlbum()">Guardar</button>
    </div>
  </div>
</div>

<div class="modal-overlay" id="uploadModal">
  <div class="modal">
    <h2>Subir Fotos</h2>
    <p style="color:var(--text2);font-size:.85rem;margin-bottom:1rem">Álbum: <strong id="uploadAlbumName" style="color:var(--accent)"></strong></p>
    <div class="upload-zone" id="photoUploadZone" onclick="document.getElementById('photoInput').click()">
      <svg viewBox="0 0 24 24" fill="none" stroke-width="1.5"><path d="M21 15v4a2 2 0 01-2 2H5a2 2 0 01-2-2v-4"/><polyline points="17 8 12 3 7 8"/><line x1="12" y1="3" x2="12" y2="15"/></svg>
      <p>Arrastra fotos aquí o <span class="highlight">haz clic para seleccionar</span></p>
      <p style="font-size:.75rem;margin-top:.5rem">JPG, PNG, WEBP — Máx 5MB</p>
    </div>
    <input type="file" id="photoInput" accept="image/*" multiple style="display:none" onchange="handlePhotoUpload(event)">
    <div class="upload-preview" id="uploadPreview"></div>
    <div class="modal-actions">
      <button class="btn btn-secondary" onclick="closeModal('uploadModal')">Cancelar</button>
      <button class="btn btn-primary" onclick="savePhotos()">Guardar Fotos</button>
    </div>
  </div>
</div>

<div class="modal-overlay" id="createClientModal">
  <div class="modal">
    <h2 id="clientModalTitle">Nuevo Cliente</h2>
    <label>Nombre completo</label>
    <input type="text" id="clientName" placeholder="María García">
    <label>Email (obligatorio para descargas)</label>
    <input type="email" id="clientEmail" placeholder="maria@email.com">
    <label>Contraseña (la que le darás al cliente)</label>
    <input type="text" id="clientPassword" placeholder="Contraseña para el cliente">
    <button class="btn btn-secondary btn-sm" onclick="generatePassword()" style="margin-top:.5rem">🎲 Generar contraseña aleatoria</button>
    <div class="modal-actions">
      <button class="btn btn-secondary" onclick="closeModal('createClientModal')">Cancelar</button>
      <button class="btn btn-primary" onclick="saveClient()">Guardar</button>
    </div>
  </div>
</div>

<div class="modal-overlay" id="downloadModal">
  <div class="modal">
    <h2>Descargar Foto</h2>
    <p style="color:var(--text2);font-size:.88rem;margin-bottom:1rem">Para descargar esta foto necesitamos tu email (registro de seguridad).</p>
    <label>Tu email</label>
    <input type="email" id="downloadEmail" placeholder="tu@email.com">
    <label>Calidad de descarga</label>
    <select id="downloadQuality">
      <option value="thumb">📱 Miniatura (web, rápida)</option>
      <option value="full">🖼️ Máxima calidad (impresión)</option>
    </select>
    <div class="modal-actions">
      <button class="btn btn-secondary" onclick="closeModal('downloadModal')">Cancelar</button>
      <button class="btn btn-primary" onclick="confirmDownload()">⬇ Descargar</button>
    </div>
  </div>
</div>

<script>
const DEFAULT_CONFIG = {
  siteName: 'Lumière Studio',
  logo: '',
  heroImage: '',
  heroTitle: 'Momentos que<br><em>perduran</em>',
  heroSubtitle: 'Una galería exclusiva donde cada imagen cuenta una historia única.',
  accent: '#c9a96e',
  bg: '#0a0a0b',
  text: '#f5f5f7',
  instagram: '',
  facebook: '',
  twitter: '',
  whatsapp: '',
  watermarkEnabled: false,
  watermarkText: '© Lumière Studio',
  watermarkOpacity: 40,
  watermarkSize: 30
};

let config = JSON.parse(localStorage.getItem('lumiere_config') || 'null') || {...DEFAULT_CONFIG};
let adminPass = localStorage.getItem('lumiere_admin_pass') || 'admin123';
let albums = JSON.parse(localStorage.getItem('lumiere_albums') || '[]');
let clients = JSON.parse(localStorage.getItem('lumiere_clients') || '[]');
let logs = JSON.parse(localStorage.getItem('lumiere_logs') || '[]');

let currentUser = null;
let currentAlbum = null;
let currentPhotoIndex = 0;
let pendingPhotos = [];
let coverData = null;
let editingAlbumId = null;
let editingClientId = null;
let pendingDownloadPhoto = null;
let previousView = 'public';

function saveData() {
  localStorage.setItem('lumiere_config', JSON.stringify(config));
  localStorage.setItem('lumiere_admin_pass', adminPass);
  try {
    localStorage.setItem('lumiere_albums', JSON.stringify(albums));
    localStorage.setItem('lumiere_clients', JSON.stringify(clients));
    localStorage.setItem('lumiere_logs', JSON.stringify(logs));
  } catch(e) {
    showToast('⚠️ Almacenamiento lleno. Usa imágenes más pequeñas.', 'error');
  }
}

function resetAdminPassword() {
  if (!confirm('¿Restablecer la contraseña de administrador a "admin123"?\n\nEsto NO afecta a tus álbumes, clientes ni fotos. Solo cambia la contraseña de admin.')) return;
  adminPass = 'admin123';
  localStorage.setItem('lumiere_admin_pass', adminPass);
  const errorBox = document.getElementById('loginError');
  errorBox.style.display = 'block';
  errorBox.style.background = 'rgba(34,197,94,.1)';
  errorBox.style.borderColor = 'rgba(34,197,94,.3)';
  errorBox.style.color = 'var(--success)';
  errorBox.innerHTML = '✅ Contraseña restablecida correctamente. Ahora usa:<br><strong>admin@lumiere.com</strong> / <strong>admin123</strong>';
  showToast('✅ Contraseña admin restablecida a "admin123"', 'success');
  document.getElementById('loginEmail').value = '';
  document.getElementById('loginPassword').value = '';
  document.getElementById('loginEmail').focus();
}

function createPlaceholder(text, c1, c2) {
  const canvas = document.createElement('canvas');
  canvas.width = 800; canvas.height = 600;
  const ctx = canvas.getContext('2d');
  const grad = ctx.createLinearGradient(0, 0, 800, 600);
  grad.addColorStop(0, c1);
  grad.addColorStop(1, c2);
  ctx.fillStyle = grad;
  ctx.fillRect(0, 0, 800, 600);
  ctx.fillStyle = 'rgba(255,255,255,0.9)';
  ctx.font = 'bold 36px Arial';
  ctx.textAlign = 'center';
  ctx.textBaseline = 'middle';
  ctx.fillText(text, 400, 300);
  ctx.font = '16px Arial';
  ctx.fillStyle = 'rgba(255,255,255,0.5)';
  ctx.fillText('Lumière Studio', 400, 350);
  return canvas.toDataURL('image/jpeg', 0.85);
}

function createThumbnail(imgSrc, maxSize = 400) {
  return new Promise(resolve => {
    const img = new Image();
    img.onload = () => {
      const canvas = document.createElement('canvas');
      const ratio = Math.min(maxSize/img.width, maxSize/img.height, 1);
      canvas.width = img.width * ratio;
      canvas.height = img.height * ratio;
      canvas.getContext('2d').drawImage(img, 0, 0, canvas.width, canvas.height);
      resolve(canvas.toDataURL('image/jpeg', 0.85));
    };
    img.onerror = () => resolve(imgSrc);
    img.src = imgSrc;
  });
}

function applyWatermark(imgSrc, text) {
  return new Promise(resolve => {
    if (!config.watermarkEnabled || !text) { resolve(imgSrc); return; }
    const img = new Image();
    img.onload = () => {
      const canvas = document.createElement('canvas');
      canvas.width = img.width;
      canvas.height = img.height;
      const ctx = canvas.getContext('2d');
      ctx.drawImage(img, 0, 0);
      const fontSize = Math.max(20, (img.width * config.watermarkSize) / 100);
      ctx.font = `bold ${fontSize}px Arial`;
      ctx.fillStyle = `rgba(255,255,255,${config.watermarkOpacity/100})`;
      ctx.textAlign = 'center';
      ctx.textBaseline = 'middle';
      const spacingX = fontSize * 8;
      const spacingY = fontSize * 4;
      ctx.save();
      ctx.rotate(-Math.PI/6);
      for (let y = -canvas.height; y < canvas.height * 2; y += spacingY) {
        for (let x = -canvas.width; x < canvas.width * 2; x += spacingX) {
          ctx.fillText(text, x, y);
        }
      }
      ctx.restore();
      resolve(canvas.toDataURL('image/jpeg', 0.9));
    };
    img.onerror = () => resolve(imgSrc);
    img.src = imgSrc;
  });
}

function logAction(action, details = {}) {
  logs.unshift({
    id: 'log_' + Date.now() + '_' + Math.random().toString(36).substr(2,5),
    timestamp: new Date().toISOString(),
    action,
    userEmail: currentUser ? currentUser.email : (details.email || 'anonimo'),
    userName: currentUser ? currentUser.name : (details.name || 'Anónimo'),
    albumName: details.albumName || '',
    photoName: details.photoName || '',
    resolution: details.resolution || '',
    ip: 'local'
  });
  if (logs.length > 500) logs = logs.slice(0, 500);
  saveData();
}

function applyConfig() {
  document.documentElement.style.setProperty('--accent', config.accent);
  document.documentElement.style.setProperty('--accent2', lightenColor(config.accent, 30));
  document.documentElement.style.setProperty('--accent-dark', darkenColor(config.accent, 30));
  document.documentElement.style.setProperty('--bg', config.bg);
  document.documentElement.style.setProperty('--text', config.text);
  document.getElementById('navLogoText').textContent = config.siteName;
  document.title = config.siteName;
  document.getElementById('footerText').textContent = `© ${new Date().getFullYear()} ${config.siteName} — Todos los derechos reservados`;
  const logoImg = document.getElementById('navLogo');
  if (config.logo) {
    logoImg.src = config.logo;
    logoImg.style.display = 'block';
  } else {
    logoImg.style.display = 'none';
  }
  const hero = document.getElementById('heroSection');
  if (config.heroImage) {
    hero.style.backgroundImage = `url('${config.heroImage}')`;
  }
  document.getElementById('heroTitle').innerHTML = config.heroTitle;
  document.getElementById('heroSubtitle').textContent = config.heroSubtitle;
  renderSocialLinks();
}

function lightenColor(hex, percent) {
  const num = parseInt(hex.replace('#',''), 16);
  const r = Math.min(255, (num >> 16) + percent);
  const g = Math.min(255, ((num >> 8) & 0x00FF) + percent);
  const b = Math.min(255, (num & 0x0000FF) + percent);
  return `#${(0x1000000 + r*0x10000 + g*0x100 + b).toString(16).slice(1)}`;
}

function darkenColor(hex, percent) {
  const num = parseInt(hex.replace('#',''), 16);
  const r = Math.max(0, (num >> 16) - percent);
  const g = Math.max(0, ((num >> 8) & 0x00FF) - percent);
  const b = Math.max(0, (num & 0x0000FF) - percent);
  return `#${(0x1000000 + r*0x10000 + g*0x100 + b).toString(16).slice(1)}`;
}

function renderSocialLinks() {
  const container = document.getElementById('footerSocial');
  const links = [];
  if (config.instagram) links.push(`<a href="${config.instagram}" target="_blank" class="social-link">📷 Instagram</a>`);
  if (config.facebook) links.push(`<a href="${config.facebook}" target="_blank" class="social-link">📘 Facebook</a>`);
  if (config.twitter) links.push(`<a href="${config.twitter}" target="_blank" class="social-link">🐦 Twitter</a>`);
  if (config.whatsapp) links.push(`<a href="https://wa.me/${config.whatsapp.replace(/\D/g,'')}" target="_blank" class="social-link">💬 WhatsApp</a>`);
  container.innerHTML = links.join('');
}

function updateConfig() {
  config.siteName = document.getElementById('cfgSiteName').value;
  config.accent = document.getElementById('cfgAccent').value;
  document.getElementById('cfgAccentText').value = config.accent;
  config.bg = document.getElementById('cfgBg').value;
  document.getElementById('cfgBgText').value = config.bg;
  config.text = document.getElementById('cfgText').value;
  document.getElementById('cfgTextText').value = config.text;
  config.heroTitle = document.getElementById('cfgHeroTitle').value;
  config.heroSubtitle = document.getElementById('cfgHeroSubtitle').value;
  config.instagram = document.getElementById('cfgInstagram').value;
  config.facebook = document.getElementById('cfgFacebook').value;
  config.twitter = document.getElementById('cfgTwitter').value;
  config.whatsapp = document.getElementById('cfgWhatsapp').value;
  config.watermarkEnabled = document.getElementById('cfgWatermarkEnabled').checked;
  config.watermarkText = document.getElementById('cfgWatermarkText').value;
  config.watermarkOpacity = parseInt(document.getElementById('cfgWatermarkOpacity').value);
  config.watermarkSize = parseInt(document.getElementById('cfgWatermarkSize').value);
  applyConfig();
  updateWatermarkPreview();
}

function syncColor(id, val) {
  if (/^#[0-9A-F]{6}$/i.test(val)) {
    document.getElementById(id).value = val;
    updateConfig();
  }
}

function updateWatermarkPreview() {
  const preview = document.getElementById('watermarkPreview');
  if (!config.watermarkEnabled) {
    preview.innerHTML = '<span style="color:#888;font-size:.9rem">Marca de agua desactivada</span>';
    return;
  }
  const fontSize = Math.max(12, config.watermarkSize * 0.6);
  preview.innerHTML = `<span style="color:rgba(255,255,255,${config.watermarkOpacity/100});font-size:${fontSize}px;font-weight:bold;position:absolute">${config.watermarkText || '© Marca'}</span>`;
}

function handleLogoUpload(e) {
  const file = e.target.files[0];
  if (!file) return;
  const reader = new FileReader();
  reader.onload = ev => {
    config.logo = ev.target.result;
    document.getElementById('cfgLogoPreview').innerHTML = `<img src="${config.logo}" style="max-height:80px;border-radius:8px">`;
    document.getElementById('cfgLogoText').textContent = 'Logo cargado ✓';
    applyConfig();
  };
  reader.readAsDataURL(file);
}

function clearLogo() {
  config.logo = '';
  document.getElementById('cfgLogoPreview').innerHTML = '';
  document.getElementById('cfgLogoText').textContent = 'Haz clic para subir logo';
  applyConfig();
}

function handleHeroUpload(e) {
  const file = e.target.files[0];
  if (!file) return;
  const reader = new FileReader();
  reader.onload = ev => {
    config.heroImage = ev.target.result;
    document.getElementById('cfgHeroPreview').innerHTML = `<img src="${config.heroImage}" style="width:100%;max-height:150px;object-fit:cover;border-radius:8px">`;
    document.getElementById('cfgHeroText').textContent = 'Imagen cargada ✓';
    applyConfig();
  };
  reader.readAsDataURL(file);
}

function resetColors() {
  config.accent = DEFAULT_CONFIG.accent;
  config.bg = DEFAULT_CONFIG.bg;
  config.text = DEFAULT_CONFIG.text;
  document.getElementById('cfgAccent').value = config.accent;
  document.getElementById('cfgBg').value = config.bg;
  document.getElementById('cfgText').value = config.text;
  updateConfig();
}

function saveConfig() {
  saveData();
  showToast('✅ Configuración guardada', 'success');
}

function changeAdminPass() {
  const newPass = document.getElementById('cfgAdminPass').value.trim();
  if (newPass.length < 4) { showToast('Mínimo 4 caracteres', 'error'); return; }
  adminPass = newPass;
  document.getElementById('cfgAdminPass').value = '';
  saveData();
  showToast('✅ Contraseña de admin actualizada', 'success');
}

function loadConfigUI() {
  document.getElementById('cfgSiteName').value = config.siteName;
  document.getElementById('cfgAccent').value = config.accent;
  document.getElementById('cfgAccentText').value = config.accent;
  document.getElementById('cfgBg').value = config.bg;
  document.getElementById('cfgBgText').value = config.bg;
  document.getElementById('cfgText').value = config.text;
  document.getElementById('cfgTextText').value = config.text;
  document.getElementById('cfgHeroTitle').value = config.heroTitle.replace(/<br>/g,'\n').replace(/<em>/g,'').replace(/<\/em>/g,'');
  document.getElementById('cfgHeroSubtitle').value = config.heroSubtitle;
  document.getElementById('cfgInstagram').value = config.instagram || '';
  document.getElementById('cfgFacebook').value = config.facebook || '';
  document.getElementById('cfgTwitter').value = config.twitter || '';
  document.getElementById('cfgWhatsapp').value = config.whatsapp || '';
  document.getElementById('cfgWatermarkEnabled').checked = config.watermarkEnabled;
  document.getElementById('cfgWatermarkText').value = config.watermarkText;
  document.getElementById('cfgWatermarkOpacity').value = config.watermarkOpacity;
  document.getElementById('cfgWatermarkSize').value = config.watermarkSize;
  if (config.logo) {
    document.getElementById('cfgLogoPreview').innerHTML = `<img src="${config.logo}" style="max-height:80px;border-radius:8px">`;
    document.getElementById('cfgLogoText').textContent = 'Logo cargado ✓';
  }
  if (config.heroImage && !config.heroImage.startsWith('http')) {
    document.getElementById('cfgHeroPreview').innerHTML = `<img src="${config.heroImage}" style="width:100%;max-height:150px;object-fit:cover;border-radius:8px">`;
    document.getElementById('cfgHeroText').textContent = 'Imagen cargada ✓';
  }
  updateWatermarkPreview();
}

function handleLoginClick() {
  if (currentUser) {
    const name = currentUser.name || currentUser.email;
    if (confirm(`¿Cerrar sesión de ${name}?`)) {
      currentUser = null;
      updateNav();
      showHome();
      showToast('Sesión cerrada');
    }
    return;
  }
  document.getElementById('loginEmail').value = '';
  document.getElementById('loginPassword').value = '';
  document.getElementById('loginError').style.display = 'none';
  document.getElementById('loginModal').classList.add('active');
  setTimeout(() => document.getElementById('loginEmail').focus(), 150);
}

function doLogin() {
  const email = document.getElementById('loginEmail').value.trim().toLowerCase();
  const pass = document.getElementById('loginPassword').value;
  const errorBox = document.getElementById('loginError');
  errorBox.style.background = 'rgba(239,68,68,.1)';
  errorBox.style.borderColor = 'rgba(239,68,68,.3)';
  errorBox.style.color = 'var(--danger)';
  if (!email || !pass) {
    errorBox.style.display = 'block';
    errorBox.innerHTML = '⚠️ Por favor, completa el email y la contraseña.';
    return;
  }
  if (email === 'admin@lumiere.com') {
    if (pass === adminPass) {
      currentUser = { type: 'admin', email, name: 'Administrador' };
      logAction('login', { albumName: 'Admin login' });
      closeModal('loginModal');
      updateNav();
      showAdmin();
      showToast('✨ Bienvenido, administrador', 'success');
      return;
    } else {
      errorBox.style.display = 'block';
      errorBox.innerHTML = `❌ Contraseña incorrecta para <strong>admin@lumiere.com</strong>.<br><small style="opacity:.8">Si no la recuerdas, usa el botón "Restablecer contraseña" de abajo.</small>`;
      return;
    }
  }
  const client = clients.find(c => c.email.toLowerCase() === email && c.password === pass);
  if (client) {
    currentUser = { type: 'client', id: client.id, email: client.email, name: client.name };
    logAction('login', { albumName: 'Client login: ' + client.name });
    closeModal('loginModal');
    updateNav();
    showClientView();
    showToast(`✨ Bienvenido, ${client.name}`, 'success');
    return;
  }
  const existingClient = clients.find(c => c.email.toLowerCase() === email);
  if (existingClient) {
    errorBox.style.display = 'block';
    errorBox.innerHTML = `❌ Contraseña incorrecta para <strong>${email}</strong>.<br><small style="opacity:.8">Contacta con el fotógrafo si no recuerdas tu contraseña.</small>`;
  } else {
    errorBox.style.display = 'block';
    errorBox.innerHTML = `❌ No existe ninguna cuenta con <strong>${email}</strong>.<br><small style="opacity:.8">Verifica el email o contacta con el fotógrafo.</small>`;
  }
}

function updateNav() {
  const loginBtn = document.getElementById('loginBtn');
  const adminBtn = document.getElementById('adminNavBtn');
  const clientBtn = document.getElementById('clientNavBtn');
  const badge = document.getElementById('userBadge');
  if (!currentUser) {
    loginBtn.textContent = 'Acceder';
    loginBtn.classList.remove('btn-admin-active');
    adminBtn.style.display = 'none';
    clientBtn.style.display = 'none';
    badge.style.display = 'none';
  } else if (currentUser.type === 'admin') {
    loginBtn.textContent = 'Cerrar Sesión';
    loginBtn.classList.add('btn-admin-active');
    adminBtn.style.display = 'inline-block';
    clientBtn.style.display = 'none';
    badge.style.display = 'flex';
    badge.innerHTML = '👑 Admin';
  } else {
    loginBtn.textContent = 'Cerrar Sesión';
    loginBtn.classList.add('btn-admin-active');
    adminBtn.style.display = 'none';
    clientBtn.style.display = 'inline-block';
    badge.style.display = 'flex';
    badge.innerHTML = `👤 ${currentUser.name}`;
  }
}

function showHome() {
  document.getElementById('publicView').style.display = 'block';
  document.getElementById('galleryView').style.display = 'none';
  document.getElementById('adminPanel').classList.remove('active');
  previousView = 'public';
  renderPublicAlbums();
  window.scrollTo(0, 0);
}

function showClientView() {
  if (!currentUser || currentUser.type !== 'client') { handleLoginClick(); return; }
  document.getElementById('publicView').style.display = 'block';
  document.getElementById('galleryView').style.display = 'none';
  document.getElementById('adminPanel').classList.remove('active');
  previousView = 'client';
  renderClientAlbums();
  window.scrollTo(0, 0);
}

function showAdmin() {
  if (!currentUser || currentUser.type !== 'admin') { handleLoginClick(); return; }
  document.getElementById('publicView').style.display = 'none';
  document.getElementById('galleryView').style.display = 'none';
  document.getElementById('adminPanel').classList.add('active');
  previousView = 'admin';
  showAdminTab('dashboard', document.querySelector('.admin-tab'));
  window.scrollTo(0, 0);
}

function showAdminTab(tab, btn) {
  document.querySelectorAll('.admin-tab').forEach(t => t.classList.remove('active'));
  document.querySelectorAll('.admin-section').forEach(s => s.classList.remove('active'));
  if (btn) btn.classList.add('active');
  else document.querySelector(`.admin-tab[onclick*="${tab}"]`)?.classList.add('active');
  document.getElementById('tab-' + tab).classList.add('active');
  if (tab === 'dashboard') renderDashboard();
  if (tab === 'albums') renderAdminAlbums();
  if (tab === 'clients') renderAdminClients();
  if (tab === 'config') loadConfigUI();
  if (tab === 'logs') renderLogs();
}

function goBack() {
  if (previousView === 'admin') showAdmin();
  else if (previousView === 'client') showClientView();
  else showHome();
}

function renderPublicAlbums() {
  const grid = document.getElementById('publicAlbumsGrid');
  const empty = document.getElementById('emptyPublic');
  const visible = albums.filter(a => a.visibility === 'public');
  if (visible.length === 0) {
    grid.innerHTML = '';
    empty.style.display = 'block';
    return;
  }
  empty.style.display = 'none';
  grid.innerHTML = visible.map(album => renderAlbumCard(album)).join('');
}

function renderClientAlbums() {
  document.getElementById('albumsSection').style.display = 'block';
  document.querySelector('.section-title').textContent = 'Mis Álbumes';
  document.querySelector('.section-subtitle').textContent = `Álbumes asignados a ${currentUser.name}`;
  const grid = document.getElementById('publicAlbumsGrid');
  const empty = document.getElementById('emptyPublic');
  const visible = albums.filter(a => a.clientId === currentUser.id);
  if (visible.length === 0) {
    grid.innerHTML = '';
    empty.style.display = 'block';
    empty.querySelector('p').textContent = 'No tienes álbumes asignados todavía';
    return;
  }
  empty.style.display = 'none';
  empty.querySelector('p').textContent = 'No hay álbumes todavía';
  grid.innerHTML = visible.map(album => renderAlbumCard(album)).join('');
}

function renderAlbumCard(album) {
  const cover = album.cover || (album.photos && album.photos.length > 0 ? album.photos[0].thumb : '');
  const photoCount = album.photos ? album.photos.length : 0;
  const client = album.clientId ? clients.find(c => c.id === album.clientId) : null;
  return `
    <div class="album-card" onclick="openAlbum('${album.id}')">
      ${cover ? `<img src="${cover}" alt="${album.name}">` : `<div style="width:100%;height:100%;display:flex;align-items:center;justify-content:center;color:var(--text3);font-size:3rem">📷</div>`}
      <div class="album-overlay">
        <h3>${album.name}</h3>
        <p>${album.description || 'Sin descripción'}</p>
      </div>
      <span class="album-count">${photoCount} foto${photoCount !== 1 ? 's' : ''}</span>
      <span class="album-badge ${album.visibility === 'public' ? 'badge-public' : 'badge-private'}">${album.visibility === 'public' ? '🌐 Público' : '🔒 Privado'}</span>
      <span class="album-badge ${album.type === 'free' ? 'badge-free' : 'badge-paid'}" style="top:3rem">${album.type === 'free' ? '🆓 Gratis' : '💎 Pago'}</span>
      ${client ? `<span class="album-client-tag">👤 ${client.name}</span>` : ''}
    </div>
  `;
}

function openAlbum(id) {
  const album = albums.find(a => a.id === id);
  if (!album) return;
  if (album.visibility === 'private' && (!currentUser || (currentUser.type !== 'admin' && album.clientId !== currentUser.id))) {
    showToast('🔒 Este álbum es privado', 'error');
    return;
  }
  currentAlbum = album;
  logAction('view', { albumName: album.name });
  document.getElementById('publicView').style.display = 'none';
  document.getElementById('adminPanel').classList.remove('active');
  document.getElementById('galleryView').style.display = 'block';
  document.getElementById('galleryTitle').textContent = album.name;
  document.getElementById('galleryInfo').textContent = `${album.photos ? album.photos.length : 0} fotos • ${album.type === 'free' ? '🆓 Gratuito' : '💎 De pago'} • ${album.visibility === 'public' ? '🌐 Público' : '🔒 Privado'}`;
  renderPhotos();
  window.scrollTo(0, 0);
}

function renderPhotos() {
  const grid = document.getElementById('photosGrid');
  const empty = document.getElementById('emptyPhotos');
  if (!currentAlbum.photos || currentAlbum.photos.length === 0) {
    grid.innerHTML = '';
    empty.style.display = 'block';
    return;
  }
  empty.style.display = 'none';
  grid.innerHTML = currentAlbum.photos.map((photo, i) => `
    <div class="photo-card" onclick="openLightbox(${i})">
      <img src="${photo.thumb}" alt="${photo.name}" loading="lazy">
      <div class="photo-overlay">
        <button onclick="event.stopPropagation();openLightbox(${i})" title="Ver">🔍</button>
        <button onclick="event.stopPropagation();requestDownload(${i})" title="Descargar">⬇</button>
      </div>
    </div>
  `).join('');
}

function openLightbox(index) {
  currentPhotoIndex = index;
  const photo = currentAlbum.photos[index];
  document.getElementById('lightboxImg').src = photo.thumb;
  document.getElementById('lightboxInfo').textContent = `${photo.name} — ${currentAlbum.name} (${index + 1}/${currentAlbum.photos.length})`;
  const actions = document.getElementById('lightboxActions');
  actions.innerHTML = `
    <button onclick="requestDownload(${index})">⬇ Descargar</button>
    <button onclick="sharePhoto('facebook')">📘 Facebook</button>
    <button onclick="sharePhoto('twitter')">🐦 Twitter</button>
    <button onclick="sharePhoto('whatsapp')">💬 WhatsApp</button>
  `;
  document.getElementById('lightbox').classList.add('active');
  document.body.style.overflow = 'hidden';
}

function closeLightbox() {
  document.getElementById('lightbox').classList.remove('active');
  document.body.style.overflow = '';
}

function navLightbox(dir) {
  if (!currentAlbum || !currentAlbum.photos) return;
  currentPhotoIndex += dir;
  if (currentPhotoIndex < 0) currentPhotoIndex = currentAlbum.photos.length - 1;
  if (currentPhotoIndex >= currentAlbum.photos.length) currentPhotoIndex = 0;
  openLightbox(currentPhotoIndex);
}

document.addEventListener('keydown', e => {
  if (!document.getElementById('lightbox').classList.contains('active')) return;
  if (e.key === 'Escape') closeLightbox();
  if (e.key === 'ArrowLeft') navLightbox(-1);
  if (e.key === 'ArrowRight') navLightbox(1);
});

function requestDownload(index) {
  if (!currentAlbum || !currentAlbum.photos) return;
  pendingDownloadPhoto = index;
  const emailField = document.getElementById('downloadEmail');
  if (currentUser) {
    emailField.value = currentUser.email || '';
  } else {
    emailField.value = '';
  }
  document.getElementById('downloadModal').classList.add('active');
  setTimeout(() => emailField.focus(), 150);
}

async function confirmDownload() {
  const email = document.getElementById('downloadEmail').value.trim();
  const quality = document.getElementById('downloadQuality').value;
  if (!email || !email.includes('@')) {
    showToast('⚠️ Email válido requerido', 'error');
    return;
  }
  if (pendingDownloadPhoto === null) return;
  const photo = currentAlbum.photos[pendingDownloadPhoto];
  const imgSrc = quality === 'full' ? photo.full : photo.thumb;
  let finalSrc = imgSrc;
  if (config.watermarkEnabled && currentAlbum.type === 'paid') {
    finalSrc = await applyWatermark(imgSrc, config.watermarkText);
  }
  const link = document.createElement('a');
  link.href = finalSrc;
  link.download = `${currentAlbum.name}_${photo.name}_${quality}.jpg`;
  link.click();
  logAction('download', {
    albumName: currentAlbum.name,
    photoName: photo.name,
    resolution: quality,
    email
  });
  closeModal('downloadModal');
  showToast(`✅ Foto descargada (${quality === 'full' ? 'máxima calidad' : 'miniatura'})`, 'success');
}

function downloadAllPhotos() {
  if (!currentAlbum || !currentAlbum.photos || currentAlbum.photos.length === 0) return;
  const email = currentUser ? currentUser.email : '';
  if (!email) {
    showToast('⚠️ Inicia sesión para descargar todo', 'info');
    handleLoginClick();
    return;
  }
  currentAlbum.photos.forEach((photo, i) => {
    setTimeout(async () => {
      let src = photo.full;
      if (config.watermarkEnabled && currentAlbum.type === 'paid') {
        src = await applyWatermark(photo.full, config.watermarkText);
      }
      const link = document.createElement('a');
      link.href = src;
      link.download = `${currentAlbum.name}_${photo.name}_full.jpg`;
      link.click();
    }, i * 500);
  });
  logAction('download', { albumName: currentAlbum.name, photoName: 'TODAS', resolution: 'full', email });
  showToast(`⬇ Descargando ${currentAlbum.photos.length} fotos...`, 'success');
}

function sharePhoto(platform) {
  const photo = currentAlbum.photos[currentPhotoIndex];
  const text = encodeURIComponent(`Mira esta foto de ${config.siteName}`);
  const url = encodeURIComponent(window.location.href);
  let shareUrl = '';
  switch(platform) {
    case 'facebook': shareUrl = `https://www.facebook.com/sharer/sharer.php?u=${url}`; break;
    case 'twitter': shareUrl = `https://twitter.com/intent/tweet?text=${text}&url=${url}`; break;
    case 'whatsapp': shareUrl = `https://wa.me/?text=${text}%20${url}`; break;
  }
  if (shareUrl) window.open(shareUrl, '_blank', 'width=600,height=400');
  logAction('share', { albumName: currentAlbum.name, photoName: photo.name });
}

function openCreateAlbum() {
  editingAlbumId = null;
  coverData = null;
  document.getElementById('albumModalTitle').textContent = 'Nuevo Álbum';
  document.getElementById('albumName').value = '';
  document.getElementById('albumDesc').value = '';
  document.getElementById('albumType').value = 'free';
  document.getElementById('albumVisibility').value = 'public';
  document.getElementById('coverPreview').innerHTML = '';
  document.getElementById('coverText').textContent = 'Haz clic para subir portada';
  const select = document.getElementById('albumClient');
  select.innerHTML = '<option value="">— Sin asignar —</option>' + clients.map(c => `<option value="${c.id}">${c.name} (${c.email})</option>`).join('');
  document.getElementById('createAlbumModal').classList.add('active');
}

function openEditAlbum(id) {
  const album = albums.find(a => a.id === id);
  if (!album) return;
  editingAlbumId = id;
  coverData = album.cover;
  document.getElementById('albumModalTitle').textContent = 'Editar Álbum';
  document.getElementById('albumName').value = album.name;
  document.getElementById('albumDesc').value = album.description || '';
  document.getElementById('albumType').value = album.type || 'free';
  document.getElementById('albumVisibility').value = album.visibility;
  const select = document.getElementById('albumClient');
  select.innerHTML = '<option value="">— Sin asignar —</option>' + clients.map(c => `<option value="${c.id}" ${c.id === album.clientId ? 'selected' : ''}>${c.name} (${c.email})</option>`).join('');
  if (album.cover) {
    document.getElementById('coverPreview').innerHTML = `<img src="${album.cover}" style="width:100%;max-height:150px;object-fit:cover;border-radius:8px">`;
    document.getElementById('coverText').textContent = 'Portada cargada ✓';
  } else {
    document.getElementById('coverPreview').innerHTML = '';
    document.getElementById('coverText').textContent = 'Haz clic para subir portada';
  }
  document.getElementById('createAlbumModal').classList.add('active');
}

function handleCoverUpload(e) {
  const file = e.target.files[0];
  if (!file) return;
  const reader = new FileReader();
  reader.onload = ev => {
    coverData = ev.target.result;
    document.getElementById('coverPreview').innerHTML = `<img src="${coverData}" style="width:100%;max-height:150px;object-fit:cover;border-radius:8px">`;
    document.getElementById('coverText').textContent = 'Portada cargada ✓';
  };
  reader.readAsDataURL(file);
}

async function saveAlbum() {
  const name = document.getElementById('albumName').value.trim();
  if (!name) { showToast('El nombre es obligatorio', 'error'); return; }
  const albumData = {
    name,
    description: document.getElementById('albumDesc').value.trim(),
    type: document.getElementById('albumType').value,
    visibility: document.getElementById('albumVisibility').value,
    clientId: document.getElementById('albumClient').value || null,
    cover: coverData
  };
  if (editingAlbumId) {
    const album = albums.find(a => a.id === editingAlbumId);
    if (album) Object.assign(album, albumData);
    showToast('✅ Álbum actualizado', 'success');
  } else {
    albums.unshift({
      id: 'album_' + Date.now(),
      ...albumData,
      photos: [],
      createdAt: new Date().toISOString()
    });
    showToast('✅ Álbum creado', 'success');
  }
  saveData();
  closeModal('createAlbumModal');
  renderAdminAlbums();
}

function deleteAlbum(id) {
  if (!confirm('¿Eliminar este álbum y todas sus fotos? Esta acción no se puede deshacer.')) return;
  albums = albums.filter(a => a.id !== id);
  saveData();
  renderAdminAlbums();
  showToast('Álbum eliminado');
}

function openUploadForAlbum(id) {
  const album = albums.find(a => a.id === id);
  if (!album) return;
  editingAlbumId = id;
  pendingPhotos = [];
  document.getElementById('uploadAlbumName').textContent = album.name;
  document.getElementById('uploadPreview').innerHTML = '';
  document.getElementById('uploadModal').classList.add('active');
}

function handlePhotoUpload(e) {
  const files = Array.from(e.target.files);
  files.forEach(file => {
    if (file.size > 5 * 1024 * 1024) {
      showToast(`${file.name} es demasiado grande (máx 5MB)`, 'error');
      return;
    }
    const reader = new FileReader();
    reader.onload = async ev => {
      const full = ev.target.result;
      const thumb = await createThumbnail(full, 400);
      pendingPhotos.push({ name: file.name.replace(/\.[^.]+$/,''), thumb, full });
      renderUploadPreview();
    };
    reader.readAsDataURL(file);
  });
  e.target.value = '';
}

function renderUploadPreview() {
  const container = document.getElementById('uploadPreview');
  container.innerHTML = pendingPhotos.map((p, i) => `
    <div style="position:relative">
      <img src="${p.thumb}" alt="Preview">
      <button onclick="removePendingPhoto(${i})" style="position:absolute;top:-5px;right:-5px;width:20px;height:20px;border-radius:50%;border:none;background:var(--danger);color:white;font-size:.7rem;cursor:pointer;display:flex;align-items:center;justify-content:center">✕</button>
    </div>
  `).join('');
}

function removePendingPhoto(i) {
  pendingPhotos.splice(i, 1);
  renderUploadPreview();
}

function savePhotos() {
  if (pendingPhotos.length === 0) { showToast('Selecciona al menos una foto', 'error'); return; }
  const album = albums.find(a => a.id === editingAlbumId);
  if (!album) return;
  if (!album.photos) album.photos = [];
  album.photos.push(...pendingPhotos);
  if (!album.cover && pendingPhotos.length > 0) album.cover = pendingPhotos[0].thumb;
  saveData();
  closeModal('uploadModal');
  showToast(`✅ ${pendingPhotos.length} foto(s) añadidas`, 'success');
  pendingPhotos = [];
  renderAdminAlbums();
}

function deletePhoto(albumId, photoIndex) {
  if (!confirm('¿Eliminar esta foto?')) return;
  const album = albums.find(a => a.id === albumId);
  if (!album) return;
  album.photos.splice(photoIndex, 1);
  if (album.photos.length === 0) album.cover = null;
  saveData();
  renderAdminAlbums();
  showToast('Foto eliminada');
}

function renderAdminAlbums() {
  const container = document.getElementById('adminAlbumsList');
  if (albums.length === 0) {
    container.innerHTML = '<div class="empty-state"><p>No hay álbumes todavía. Crea el primero.</p></div>';
    return;
  }
  container.innerHTML = albums.map(album => {
    const client = album.clientId ? clients.find(c => c.id === album.clientId) : null;
    const photoCount = album.photos ? album.photos.length : 0;
    return `
      <div class="config-card" style="margin-bottom:1rem">
        <div style="display:flex;gap:1rem;align-items:flex-start;flex-wrap:wrap">
          ${album.cover ? `<img src="${album.cover}" style="width:100px;height:100px;object-fit:cover;border-radius:8px">` : '<div style="width:100px;height:100px;background:var(--bg3);border-radius:8px;display:flex;align-items:center;justify-content:center">📷</div>'}
          <div style="flex:1;min-width:200px">
            <h3 style="font-family:'Playfair Display',serif;margin-bottom:.3rem">${album.name}</h3>
            <p style="color:var(--text2);font-size:.85rem;margin-bottom:.5rem">${album.description || 'Sin descripción'}</p>
            <div style="display:flex;gap:.5rem;flex-wrap:wrap;font-size:.75rem">
              <span class="album-badge ${album.visibility === 'public' ? 'badge-public' : 'badge-private'}" style="position:static">${album.visibility === 'public' ? '🌐 Público' : '🔒 Privado'}</span>
              <span class="album-badge ${album.type === 'free' ? 'badge-free' : 'badge-paid'}" style="position:static">${album.type === 'free' ? '🆓 Gratis' : '💎 Pago'}</span>
              <span style="color:var(--text3);font-size:.75rem">📷 ${photoCount} fotos</span>
              ${client ? `<span style="color:var(--accent);font-size:.75rem">👤 ${client.name}</span>` : ''}
            </div>
          </div>
          <div style="display:flex;gap:.4rem;flex-wrap:wrap">
            <button class="btn btn-primary btn-sm" onclick="openUploadForAlbum('${album.id}')">⬆ Subir</button>
            <button class="btn btn-secondary btn-sm" onclick="openEditAlbum('${album.id}')">✏️ Editar</button>
            <button class="btn btn-info btn-sm" onclick="openAlbum('${album.id}')">👁 Ver</button>
            <button class="btn btn-danger btn-sm" onclick="deleteAlbum('${album.id}')">🗑</button>
          </div>
        </div>
        ${album.photos && album.photos.length > 0 ? `
          <div style="margin-top:1rem;display:grid;grid-template-columns:repeat(auto-fill,minmax(60px,1fr));gap:.4rem">
            ${album.photos.map((p, i) => `
              <div style="position:relative">
                <img src="${p.thumb}" style="width:100%;aspect-ratio:1;object-fit:cover;border-radius:6px;border:1px solid var(--border)">
                <button onclick="deletePhoto('${album.id}',${i})" style="position:absolute;top:-4px;right:-4px;width:18px;height:18px;border-radius:50%;border:none;background:var(--danger);color:white;font-size:.6rem;cursor:pointer">✕</button>
              </div>
            `).join('')}
          </div>
        ` : ''}
      </div>
    `;
  }).join('');
}

function openCreateClient() {
  editingClientId = null;
  document.getElementById('clientModalTitle').textContent = 'Nuevo Cliente';
  document.getElementById('clientName').value = '';
  document.getElementById('clientEmail').value = '';
  document.getElementById('clientPassword').value = '';
  document.getElementById('createClientModal').classList.add('active');
}

function openEditClient(id) {
  const client = clients.find(c => c.id === id);
  if (!client) return;
  editingClientId = id;
  document.getElementById('clientModalTitle').textContent = 'Editar Cliente';
  document.getElementById('clientName').value = client.name;
  document.getElementById('clientEmail').value = client.email;
  document.getElementById('clientPassword').value = client.password;
  document.getElementById('createClientModal').classList.add('active');
}

function generatePassword() {
  const chars = 'ABCDEFGHJKLMNPQRSTUVWXYZabcdefghijkmnpqrstuvwxyz23456789';
  let pass = '';
  for (let i = 0; i < 10; i++) pass += chars.charAt(Math.floor(Math.random() * chars.length));
  document.getElementById('clientPassword').value = pass;
}

function saveClient() {
  const name = document.getElementById('clientName').value.trim();
  const email = document.getElementById('clientEmail').value.trim().toLowerCase();
  const password = document.getElementById('clientPassword').value.trim();
  if (!name || !email || !password) { showToast('Todos los campos son obligatorios', 'error'); return; }
  if (!email.includes('@')) { showToast('Email no válido', 'error'); return; }
  if (editingClientId) {
    const client = clients.find(c => c.id === editingClientId);
    if (client) { client.name = name; client.email = email; client.password = password; }
    showToast('✅ Cliente actualizado', 'success');
  } else {
    if (clients.find(c => c.email === email)) { showToast('Ya existe un cliente con ese email', 'error'); return; }
    clients.push({
      id: 'client_' + Date.now(),
      name, email, password,
      createdAt: new Date().toISOString()
    });
    showToast('✅ Cliente creado', 'success');
  }
  saveData();
  closeModal('createClientModal');
  renderAdminClients();
}

function deleteClient(id) {
  if (!confirm('¿Eliminar este cliente? Los álbumes asignados quedarán sin cliente.')) return;
  clients = clients.filter(c => c.id !== id);
  albums.forEach(a => { if (a.clientId === id) a.clientId = null; });
  saveData();
  renderAdminClients();
  showToast('Cliente eliminado');
}

function renderAdminClients() {
  const container = document.getElementById('adminClientsList');
  if (clients.length === 0) {
    container.innerHTML = '<div class="empty-state"><p>No hay clientes todavía. Crea el primero para asignarle álbumes privados.</p></div>';
    return;
  }
  container.innerHTML = `<table class="data-table">
    <thead><tr><th>Nombre</th><th>Email</th><th>Contraseña</th><th>Álbumes</th><th>Acciones</th></tr></thead>
    <tbody>
      ${clients.map(c => {
        const albumCount = albums.filter(a => a.clientId === c.id).length;
        return `<tr>
          <td><strong>${c.name}</strong></td>
          <td>${c.email}</td>
          <td><code style="background:var(--bg3);padding:.2rem .5rem;border-radius:4px;font-size:.8rem">${c.password}</code></td>
          <td>${albumCount} álbum(es)</td>
          <td>
            <button class="btn btn-secondary btn-sm" onclick="openEditClient('${c.id}')">✏️</button>
            <button class="btn btn-danger btn-sm" onclick="deleteClient('${c.id}')">🗑</button>
          </td>
        </tr>`;
      }).join('')}
    </tbody>
  </table>`;
}

function renderDashboard() {
  const totalAlbums = albums.length;
  const totalPhotos = albums.reduce((sum, a) => sum + (a.photos ? a.photos.length : 0), 0);
  const totalClients = clients.length;
  const totalDownloads = logs.filter(l => l.action === 'download').length;
  const totalViews = logs.filter(l => l.action === 'view').length;
  const paidAlbums = albums.filter(a => a.type === 'paid').length;
  document.getElementById('statsGrid').innerHTML = `
    <div class="stat-card"><h4>Álbumes</h4><div class="stat-value">${totalAlbums}</div><div class="stat-label">${paidAlbums} de pago</div></div>
    <div class="stat-card"><h4>Fotos</h4><div class="stat-value">${totalPhotos}</div><div class="stat-label">en total</div></div>
    <div class="stat-card"><h4>Clientes</h4><div class="stat-value">${totalClients}</div><div class="stat-label">registrados</div></div>
    <div class="stat-card"><h4>Descargas</h4><div class="stat-value">${totalDownloads}</div><div class="stat-label">registradas</div></div>
    <div class="stat-card"><h4>Vistas</h4><div class="stat-value">${totalViews}</div><div class="stat-label">de álbumes</div></div>
  `;
  const recent = logs.slice(0, 10);
  document.getElementById('recentActivity').innerHTML = recent.length === 0 
    ? '<p style="color:var(--text3);font-size:.88rem">Sin actividad todavía</p>'
    : `<table class="data-table">
        <thead><tr><th>Hora</th><th>Acción</th><th>Usuario</th><th>Detalle</th></tr></thead>
        <tbody>
          ${recent.map(l => `<tr>
            <td style="font-size:.8rem;color:var(--text3)">${new Date(l.timestamp).toLocaleString('es-ES')}</td>
            <td><span class="album-badge ${l.action === 'download' ? 'badge-paid' : l.action === 'view' ? 'badge-public' : 'badge-free'}" style="position:static">${l.action}</span></td>
            <td>${l.userEmail}</td>
            <td style="font-size:.85rem">${l.albumName} ${l.photoName ? '→ ' + l.photoName : ''}</td>
          </tr>`).join('')}
        </tbody>
      </table>`;
}

function renderLogs() {
  const search = document.getElementById('logSearch').value.toLowerCase();
  const filterAction = document.getElementById('logFilterAction').value;
  let filtered = logs.filter(l => {
    const matchSearch = !search || l.userEmail.toLowerCase().includes(search) || l.albumName.toLowerCase().includes(search) || (l.userName && l.userName.toLowerCase().includes(search));
    const matchAction = !filterAction || l.action === filterAction;
    return matchSearch && matchAction;
  });
  const container = document.getElementById('logsTable');
  if (filtered.length === 0) {
    container.innerHTML = '<div class="empty-state"><p>No hay registros</p></div>';
    return;
  }
  container.innerHTML = `<table class="data-table">
    <thead><tr><th>Fecha/Hora</th><th>Acción</th><th>Email</th><th>Nombre</th><th>Álbum</th><th>Foto</th><th>Resolución</th></tr></thead>
    <tbody>
      ${filtered.map(l => `<tr>
        <td style="font-size:.8rem;color:var(--text3);white-space:nowrap">${new Date(l.timestamp).toLocaleString('es-ES')}</td>
        <td><span class="album-badge ${l.action === 'download' ? 'badge-paid' : l.action === 'view' ? 'badge-public' : 'badge-free'}" style="position:static">${l.action}</span></td>
        <td>${l.userEmail}</td>
        <td>${l.userName || '-'}</td>
        <td>${l.albumName || '-'}</td>
        <td>${l.photoName || '-'}</td>
        <td>${l.resolution || '-'}</td>
      </tr>`).join('')}
    </tbody>
  </table>`;
}

function exportLogs() {
  if (logs.length === 0) { showToast('No hay logs para exportar', 'error'); return; }
  const headers = ['Fecha','Acción','Email','Nombre','Álbum','Foto','Resolución'];
  const rows = logs.map(l => [
    new Date(l.timestamp).toLocaleString('es-ES'),
    l.action, l.userEmail, l.userName || '', l.albumName || '', l.photoName || '', l.resolution || ''
  ]);
  const csv = [headers, ...rows].map(r => r.map(c => `"${String(c).replace(/"/g,'""')}"`).join(',')).join('\n');
  const blob = new Blob(['\ufeff' + csv], { type: 'text/csv;charset=utf-8;' });
  const link = document.createElement('a');
  link.href = URL.createObjectURL(blob);
  link.download = `lumiere_logs_${new Date().toISOString().split('T')[0]}.csv`;
  link.click();
  showToast('📥 CSV exportado', 'success');
}

function clearLogs() {
  if (!confirm('¿Eliminar todo el historial? Esta acción no se puede deshacer.')) return;
  logs = [];
  saveData();
  renderLogs();
  showToast('Historial limpiado');
}

function closeModal(id) {
  document.getElementById(id).classList.remove('active');
}
document.querySelectorAll('.modal-overlay').forEach(overlay => {
  overlay.addEventListener('click', e => { if (e.target === overlay) overlay.classList.remove('active'); });
});

const uploadZone = document.getElementById('photoUploadZone');
['dragenter', 'dragover'].forEach(evt => {
  uploadZone.addEventListener(evt, e => { e.preventDefault(); uploadZone.classList.add('dragover'); });
});
['dragleave', 'drop'].forEach(evt => {
  uploadZone.addEventListener(evt, e => { e.preventDefault(); uploadZone.classList.remove('dragover'); });
});
uploadZone.addEventListener('drop', e => {
  const files = Array.from(e.dataTransfer.files).filter(f => f.type.startsWith('image/'));
  files.forEach(file => {
    if (file.size > 5 * 1024 * 1024) { showToast(`${file.name} es demasiado grande`, 'error'); return; }
    const reader = new FileReader();
    reader.onload = async ev => {
      const full = ev.target.result;
      const thumb = await createThumbnail(full, 400);
      pendingPhotos.push({ name: file.name.replace(/\.[^.]+$/,''), thumb, full });
      renderUploadPreview();
    };
    reader.readAsDataURL(file);
  });
});

function showToast(msg, type = '') {
  const existing = document.querySelector('.toast');
  if (existing) existing.remove();
  const toast = document.createElement('div');
  toast.className = `toast ${type}`;
  toast.textContent = msg;
  document.body.appendChild(toast);
  setTimeout(() => toast.remove(), 3500);
}

// ============ DEMO DATA ============
if (albums.length === 0 && clients.length === 0) {
  const demoClient1 = {
    id: 'client_demo_1',
    name: 'María García',
    email: 'maria@demo.com',
    password: 'maria2026',
    createdAt: new Date().toISOString()
  };
  const demoClient2 = {
    id: 'client_demo_2',
    name: 'Familia Rodríguez',
    email: 'rodriguez@demo.com',
    password: 'familia2026',
    createdAt: new Date().toISOString()
  };
  clients.push(demoClient1, demoClient2);
  
  albums = [
    {
      id: 'demo_1',
      name: 'Boda María & Carlos',
      description: 'Un día mágico capturado en cada instante — Jardín Botánico, Septiembre 2026',
      visibility: 'public',
      type: 'free',
      clientId: null,
      cover: createPlaceholder('Boda María & Carlos', '#c9a96e', '#8b7340'),
      photos: [
        { name: 'ceremonia_jardin', thumb: createPlaceholder('Ceremonia Jardín', '#d4b87a', '#9b8350'), full: createPlaceholder('Ceremonia Jardín', '#d4b87a', '#9b8350') },
        { name: 'pareja_atardecer', thumb: createPlaceholder('Pareja Atardecer', '#bfa060', '#7a6030'), full: createPlaceholder('Pareja Atardecer', '#bfa060', '#7a6030') },
        { name: 'recepcion_baile', thumb: createPlaceholder('Recepción Baile', '#a08050', '#604020'), full: createPlaceholder('Recepción Baile', '#a08050', '#604020') },
      ],
      createdAt: new Date().toISOString()
    },
    {
      id: 'demo_2',
      name: 'Retrato Editorial — Laura',
      description: 'Sesión de retrato en estudio con iluminación dramática',
      visibility: 'public',
      type: 'free',
      clientId: null,
      cover: createPlaceholder('Retrato Editorial', '#4a4a5a', '#2a2a3a'),
      photos: [
        { name: 'retrato_estudio_1', thumb: createPlaceholder('Retrato Estudio 1', '#5a5a6a', '#3a3a4a'), full: createPlaceholder('Retrato Estudio 1', '#5a5a6a', '#3a3a4a') },
        { name: 'retrato_editorial', thumb: createPlaceholder('Retrato Editorial', '#3a3a4a', '#1a1a2a'), full: createPlaceholder('Retrato Editorial', '#3a3a4a', '#1a1a2a') },
      ],
      createdAt: new Date().toISOString()
    },
    {
      id: 'demo_3',
      name: 'Evento TechSummit 2026',
      description: 'Cobertura completa del evento corporativo anual',
      visibility: 'private',
      type: 'paid',
      clientId: demoClient1.id,
      cover: createPlaceholder('TechSummit 2026', '#1a3a5a', '#0a2a4a'),
      photos: [
        { name: 'conferencia_principal', thumb: createPlaceholder('Conferencia', '#2a4a6a', '#1a3a5a'), full: createPlaceholder('Conferencia', '#2a4a6a', '#1a3a5a') },
      ],
      createdAt: new Date().toISOString()
    },
    {
      id: 'demo_4',
      name: 'Naturaleza — Amanecer en la Montaña',
      description: 'Colección de paisajes naturales en alta montaña',
      visibility: 'public',
      type: 'free',
      clientId: null,
      cover: createPlaceholder('Amanecer Montaña', '#2a5a4a', '#1a3a2a'),
      photos: [
        { name: 'lago_montana', thumb: createPlaceholder('Lago Montaña', '#3a6a5a', '#2a5a4a'), full: createPlaceholder('Lago Montaña', '#3a6a5a', '#2a5a4a') },
      ],
      createdAt: new Date().toISOString()
    },
    {
      id: 'demo_5',
      name: 'Recién Nacido — Familia Rodríguez',
      description: 'Sesión newborn — Álbum privado para la familia',
      visibility: 'private',
      type: 'free',
      clientId: demoClient2.id,
      cover: createPlaceholder('Newborn Familia', '#6a5a7a', '#4a3a5a'),
      photos: [
        { name: 'bebe_dormido', thumb: createPlaceholder('Bebé Dormido', '#7a6a8a', '#5a4a6a'), full: createPlaceholder('Bebé Dormido', '#7a6a8a', '#5a4a6a') },
      ],
      createdAt: new Date().toISOString()
    }
  ];
  saveData();
}

applyConfig();
updateNav();
renderPublicAlbums();
</script>
</body>
</html>
