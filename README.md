<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Menuiserie Aluminium &amp; PVC | Fabrication &amp; Installation</title>
<meta name="description" content="Fabrication et installation de solutions en aluminium et PVC : fenêtres, portes, cuisines, parois de douche et réalisations sur mesure.">
<link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>🪟</text></svg>">
<style>
:root{
  --ivory:#F7F6F2;
  --graphite:#171717;
  --charcoal:#242424;
  --gray:#8A8A8A;
  --bronze:#B59A6A;
  --bg:var(--ivory);
  --fg:var(--graphite);
  --fg-soft:var(--gray);
  --surface:#ffffff;
  box-sizing:border-box;
  padding-top:env(safe-area-inset-top,0px);
  padding-bottom:env(safe-area-inset-bottom,0px);
}
*{box-sizing:border-box;margin:0;padding:0;}
html{scroll-behavior:smooth;scroll-padding-top:90px;}
body{
  font-family:'Helvetica Neue',Arial,'Segoe UI',sans-serif;
  background:var(--bg);
  color:var(--fg);
  overflow-x:hidden;
  -webkit-font-smoothing:antialiased;
}
img{max-width:100%;display:block;}
a{color:inherit;text-decoration:none;}
button{font-family:inherit;cursor:pointer;border:none;background:none;color:inherit;}
.container{max-width:1280px;margin:0 auto;padding:0 6vw;}
[data-i18n],[data-i18n-html]{transition:opacity .25s ease;}

/* ---------- NAV ---------- */
.nav{
  position:fixed;top:0;left:0;right:0;z-index:1000;
  padding:env(safe-area-inset-top,0px) 0 0;
  transition:background .4s ease,padding .4s ease,box-shadow .4s ease;
}
.nav-inner{
  display:flex;align-items:center;justify-content:space-between;
  padding:22px 6vw;
  transition:padding .4s ease;
}
.nav.scrolled{background:rgba(247,246,242,.9);backdrop-filter:blur(14px);box-shadow:0 1px 0 rgba(0,0,0,.06);}
.nav.scrolled .nav-inner{padding:14px 6vw;}
.logo{font-size:.82rem;letter-spacing:.03em;font-weight:600;line-height:1.2;}
.logo small{display:block;font-weight:400;color:var(--gray);font-size:.72rem;letter-spacing:.08em;text-transform:uppercase;margin-top:2px;}
.nav-links{display:flex;gap:2.4vw;list-style:none;}
.nav-links a{font-size:.86rem;letter-spacing:.02em;position:relative;padding:4px 0;}
.nav-links a::after{content:"";position:absolute;left:0;bottom:0;width:0;height:1px;background:var(--fg);transition:width .3s ease;}
.nav-links a:hover::after{width:100%;}
.nav-right{display:flex;align-items:center;gap:22px;}
.lang-switch{display:flex;gap:8px;font-size:.76rem;letter-spacing:.05em;}
.lang-switch button{opacity:.45;transition:opacity .25s ease;}
.lang-switch button.active{opacity:1;font-weight:700;}
.nav-cta{
  background:var(--graphite);color:var(--ivory);
  padding:10px 22px;font-size:.8rem;letter-spacing:.03em;border-radius:2px;
  transition:background .3s ease,transform .3s ease;white-space:nowrap;
}
.nav-cta:hover{background:var(--bronze);transform:translateY(-1px);}
.burger{display:none;flex-direction:column;gap:5px;width:26px;z-index:1100;}
.burger span{height:1px;background:var(--fg);width:100%;transition:.3s;}
.mobile-menu{
  position:fixed;inset:0;background:var(--graphite);color:var(--ivory);
  z-index:1050;display:flex;flex-direction:column;justify-content:center;
  padding:8vh 8vw;gap:26px;
  transform:translateY(-100%);transition:transform .5s cubic-bezier(.7,0,.3,1);
}
.mobile-menu.open{transform:translateY(0);}
.mobile-menu a{font-size:1.6rem;font-weight:300;letter-spacing:.01em;}
.mobile-menu .m-cta{margin-top:20px;display:inline-block;border:1px solid var(--ivory);padding:14px 26px;font-size:1rem;width:fit-content;}
.mobile-menu .m-lang{display:flex;gap:16px;margin-top:10px;font-size:.9rem;opacity:.7;}
.mobile-menu .m-lang button.active{opacity:1;text-decoration:underline;}

/* ---------- HERO ---------- */
.hero{position:relative;height:100vh;min-height:560px;width:100%;overflow:hidden;}
.hero img{width:100%;height:100%;object-fit:cover;transform:scale(1.08);animation:heroZoom 12s ease-out forwards;}
@keyframes heroZoom{to{transform:scale(1);}}
.hero-overlay{
  position:absolute;inset:0;
  background:linear-gradient(180deg,rgba(23,23,23,.15) 0%,rgba(23,23,23,.05) 40%,rgba(23,23,23,.65) 100%);
}
.hero-content{
  position:absolute;left:6vw;right:6vw;bottom:9vh;color:var(--ivory);
  max-width:760px;
}
.hero-content h1{
  font-size:clamp(2.3rem,6vw,4.6rem);font-weight:300;line-height:1.05;letter-spacing:-.01em;
  opacity:0;transform:translateY(24px);animation:riseIn .9s .3s ease forwards;
}
.hero-content p{
  margin-top:20px;font-size:clamp(1rem,1.6vw,1.15rem);color:rgba(247,246,242,.85);font-weight:300;
  opacity:0;transform:translateY(24px);animation:riseIn .9s .5s ease forwards;
}
.hero-cta{margin-top:38px;display:flex;gap:16px;flex-wrap:wrap;opacity:0;transform:translateY(24px);animation:riseIn .9s .7s ease forwards;}
.btn-primary{background:var(--ivory);color:var(--graphite);padding:16px 30px;font-size:.9rem;letter-spacing:.03em;border-radius:2px;transition:transform .3s ease,background .3s ease;}
.btn-primary:hover{transform:translateY(-2px);background:var(--bronze);color:var(--ivory);}
.btn-outline{border:1px solid rgba(247,246,242,.55);padding:16px 30px;font-size:.9rem;letter-spacing:.03em;border-radius:2px;transition:.3s ease;}
.btn-outline:hover{background:rgba(247,246,242,.12);border-color:var(--ivory);}
@keyframes riseIn{to{opacity:1;transform:translateY(0);}}
.scroll-hint{position:absolute;bottom:4vh;right:6vw;color:var(--ivory);font-size:.72rem;letter-spacing:.15em;text-transform:uppercase;opacity:.7;writing-mode:vertical-rl;}

/* ---------- reveal-on-scroll ---------- */
.reveal{opacity:0;transform:translateY(36px);transition:opacity .9s cubic-bezier(.2,.6,.2,1),transform .9s cubic-bezier(.2,.6,.2,1);}
.reveal.in{opacity:1;transform:translateY(0);}

/* ---------- INTRO ---------- */
.intro{padding:14vh 0 10vh;}
.intro .eyebrow{font-size:.78rem;letter-spacing:.15em;text-transform:uppercase;color:var(--bronze);margin-bottom:20px;}
.intro h2{font-size:clamp(1.9rem,3.6vw,3.1rem);font-weight:300;line-height:1.2;max-width:820px;}
.intro p{margin-top:26px;max-width:520px;color:var(--fg-soft);font-size:1.02rem;line-height:1.7;}

/* ---------- FEATURED ---------- */
.featured{padding:6vh 0 12vh;}
.featured-grid{display:grid;grid-template-columns:1.3fr 1fr;gap:0;align-items:stretch;}
.featured-img{overflow:hidden;min-height:480px;}
.featured-img img{width:100%;height:100%;object-fit:cover;transition:transform 1.1s cubic-bezier(.2,.6,.2,1);}
.featured-img:hover img{transform:scale(1.05);}
.featured-text{background:var(--graphite);color:var(--ivory);padding:8vh 5vw;display:flex;flex-direction:column;justify-content:center;}
.featured-text .num{font-size:.78rem;color:var(--bronze);letter-spacing:.15em;margin-bottom:18px;}
.featured-text h3{font-size:clamp(1.7rem,2.6vw,2.4rem);font-weight:300;line-height:1.15;}
.featured-text p{margin-top:20px;color:rgba(247,246,242,.7);line-height:1.7;font-size:.98rem;}
.featured-text .btn-outline{margin-top:34px;width:fit-content;border-color:rgba(247,246,242,.4);}

/* ---------- PRODUCTS ---------- */
.products{padding:12vh 0;}
.section-head{display:flex;justify-content:space-between;align-items:flex-end;margin-bottom:6vh;gap:20px;flex-wrap:wrap;}
.section-head h2{font-size:clamp(1.9rem,3.4vw,2.8rem);font-weight:300;}
.section-head p{color:var(--fg-soft);max-width:360px;font-size:.95rem;}
.product-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:2px;background:var(--ivory);}
.product{position:relative;aspect-ratio:3/4;overflow:hidden;}
.product img{width:100%;height:100%;object-fit:cover;transition:transform .8s cubic-bezier(.2,.6,.2,1);}
.product:hover img{transform:scale(1.08);}
.product::after{content:"";position:absolute;inset:0;background:linear-gradient(180deg,rgba(23,23,23,0) 45%,rgba(23,23,23,.78) 100%);}
.product-label{position:absolute;left:22px;right:22px;bottom:22px;color:var(--ivory);z-index:2;}
.product-label .pnum{font-size:.7rem;letter-spacing:.15em;color:var(--bronze);display:block;margin-bottom:6px;}
.product-label h4{font-size:1.05rem;font-weight:400;line-height:1.3;}

/* ---------- GALLERY ---------- */
.gallery-section{padding:12vh 0;}
.filters{display:flex;gap:10px;flex-wrap:wrap;margin-bottom:5vh;}
.filter-btn{padding:9px 20px;font-size:.8rem;letter-spacing:.04em;border:1px solid rgba(23,23,23,.18);border-radius:30px;transition:.3s ease;}
.filter-btn.active,.filter-btn:hover{background:var(--graphite);color:var(--ivory);border-color:var(--graphite);}
.masonry{
  columns:4 220px;column-gap:14px;
}
.masonry .g-item{break-inside:avoid;margin-bottom:14px;overflow:hidden;position:relative;cursor:pointer;border-radius:2px;}
.masonry .g-item img{width:100%;display:block;transition:transform .7s cubic-bezier(.2,.6,.2,1),opacity .4s ease;}
.masonry .g-item:hover img{transform:scale(1.06);}
.g-item.hide{display:none;}
.g-item .g-tag{position:absolute;left:12px;bottom:12px;color:#fff;font-size:.7rem;letter-spacing:.08em;text-transform:uppercase;opacity:0;transition:opacity .3s ease;text-shadow:0 1px 6px rgba(0,0,0,.6);}
.g-item::before{content:"";position:absolute;inset:0;background:linear-gradient(180deg,rgba(0,0,0,0) 60%,rgba(0,0,0,.55) 100%);opacity:0;transition:opacity .3s ease;}
.g-item:hover::before,.g-item:hover .g-tag{opacity:1;}

/* ---------- LIGHTBOX ---------- */
.lightbox{position:fixed;inset:0;background:rgba(17,17,17,.97);z-index:2000;display:none;align-items:center;justify-content:center;}
.lightbox.open{display:flex;}
.lightbox img{max-width:88vw;max-height:82vh;object-fit:contain;box-shadow:0 20px 60px rgba(0,0,0,.5);}
.lb-close,.lb-prev,.lb-next{position:absolute;color:#fff;font-size:1.6rem;padding:14px;opacity:.75;transition:opacity .25s ease;}
.lb-close{top:2vh;right:3vw;font-size:1.4rem;}
.lb-prev{left:2vw;top:50%;transform:translateY(-50%);font-size:2rem;}
.lb-next{right:2vw;top:50%;transform:translateY(-50%);font-size:2rem;}
.lb-close:hover,.lb-prev:hover,.lb-next:hover{opacity:1;}

/* ---------- SERVICES ---------- */
.services{padding:12vh 0;background:var(--graphite);color:var(--ivory);}
.services .section-head p{color:rgba(247,246,242,.55);}
.service-row{
  display:flex;align-items:baseline;gap:5vw;padding:34px 0;
  border-top:1px solid rgba(247,246,242,.14);
}
.service-row:last-child{border-bottom:1px solid rgba(247,246,242,.14);}
.service-row .snum{font-size:clamp(1.6rem,3vw,2.6rem);font-weight:200;color:var(--bronze);width:90px;flex-shrink:0;}
.service-row h4{font-size:clamp(1.15rem,2vw,1.6rem);font-weight:300;flex:1;min-width:180px;}
.service-row p{color:rgba(247,246,242,.55);max-width:340px;font-size:.92rem;line-height:1.6;}

/* ---------- ABOUT ---------- */
.about{padding:14vh 0;}
.about-inner{max-width:760px;}
.about h2{font-size:clamp(1.9rem,3.4vw,2.9rem);font-weight:300;line-height:1.25;}
.about p{margin-top:24px;color:var(--fg-soft);font-size:1.02rem;line-height:1.75;}

/* ---------- CONTACT ---------- */
.contact{background:var(--graphite);color:var(--ivory);padding:16vh 0 12vh;}
.contact h2{font-size:clamp(2.2rem,5vw,3.8rem);font-weight:300;line-height:1.1;max-width:680px;}
.contact p{margin-top:22px;color:rgba(247,246,242,.65);font-size:1.05rem;max-width:460px;}
.contact-cta{margin-top:46px;display:flex;gap:18px;flex-wrap:wrap;align-items:center;}
.wa-big{background:#fff;color:var(--graphite);padding:20px 38px;font-size:1rem;border-radius:2px;letter-spacing:.02em;display:inline-flex;align-items:center;gap:12px;transition:.3s ease;}
.wa-big:hover{background:var(--bronze);color:#fff;transform:translateY(-2px);}
.contact-meta{margin-top:60px;display:flex;gap:60px;flex-wrap:wrap;border-top:1px solid rgba(247,246,242,.15);padding-top:30px;}
.contact-meta div span{display:block;font-size:.72rem;letter-spacing:.1em;text-transform:uppercase;color:var(--bronze);margin-bottom:8px;}
.contact-meta div a,.contact-meta div p{font-size:1rem;font-weight:300;}

/* ---------- FOOTER ---------- */
footer{padding:6vh 0;background:var(--ivory);}
.footer-inner{display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:20px;font-size:.82rem;color:var(--fg-soft);}
.footer-links{display:flex;gap:22px;flex-wrap:wrap;}
.footer-links a:hover{color:var(--graphite);}

/* ---------- FLOATING WHATSAPP ---------- */
.fab-wa{
  position:fixed;bottom:calc(26px + env(safe-area-inset-bottom,0px));z-index:900;
  right:26px;
  background:#171717;color:#fff;width:58px;height:58px;border-radius:50%;
  display:flex;align-items:center;justify-content:center;box-shadow:0 10px 30px rgba(0,0,0,.25);
  transition:transform .3s ease,background .3s ease;
}
.fab-wa:hover{transform:scale(1.08);background:var(--bronze);}
[dir="rtl"] .fab-wa{right:auto;left:26px;}

/* ---------- RTL ---------- */
[dir="rtl"] body{font-family:'Segoe UI',Tahoma,Arial,sans-serif;}
[dir="rtl"] .scroll-hint{writing-mode:vertical-lr;}
[dir="rtl"] .filters,[dir="rtl"] .nav-links,[dir="rtl"] .contact-meta,[dir="rtl"] .footer-links,[dir="rtl"] .hero-cta,[dir="rtl"] .contact-cta{direction:rtl;}
[dir="rtl"] .lang-switch{flex-direction:row-reverse;}

/* ---------- RESPONSIVE ---------- */
@media(max-width:980px){
  .nav-links,.nav-right .lang-switch,.nav-cta{display:none;}
  .burger{display:flex;}
  .featured-grid{grid-template-columns:1fr;}
  .featured-img{min-height:340px;}
  .product-grid{grid-template-columns:repeat(2,1fr);}
  .masonry{columns:2 160px;}
  .service-row{flex-wrap:wrap;}
  .contact-meta{gap:34px;}
}
@media(max-width:560px){
  .container{padding:0 22px;}
  .hero-content{left:22px;right:22px;bottom:12vh;}
  .hero-cta{flex-direction:column;align-items:flex-start;}
  .btn-primary,.btn-outline{width:100%;text-align:center;}
  .featured-text{padding:6vh 22px;}
  .masonry{columns:1 100%;}
}
</style>
</head>
<body>

<nav class="nav" id="nav">
  <div class="nav-inner">
    <a href="#top" class="logo"><span data-i18n="logo_ar">نجارة الألمنيوم و PVC</span><small data-i18n="logo_sub">Aluminium &amp; PVC</small></a>
    <ul class="nav-links">
      <li><a href="#top" data-i18n="nav_home">Accueil</a></li>
      <li><a href="#produits" data-i18n="nav_products">Produits</a></li>
      <li><a href="#galerie" data-i18n="nav_gallery">Réalisations</a></li>
      <li><a href="#services" data-i18n="nav_services">Services</a></li>
      <li><a href="#apropos" data-i18n="nav_about">À propos</a></li>
      <li><a href="#contact" data-i18n="nav_contact">Contact</a></li>
    </ul>
    <div class="nav-right">
      <div class="lang-switch">
        <button onclick="setLang('fr')" data-lang-btn="fr">FR</button>
        <button onclick="setLang('ar')" data-lang-btn="ar">AR</button>
        <button onclick="setLang('en')" data-lang-btn="en">EN</button>
      </div>
      <a class="nav-cta" href="https://wa.me/213792106924" target="_blank" rel="noopener">WhatsApp</a>
    </div>
    <button class="burger" onclick="toggleMenu()" aria-label="menu">
      <span></span><span></span><span></span>
    </button>
  </div>
</nav>

<div class="mobile-menu" id="mMenu">
  <a href="#top" onclick="toggleMenu()" data-i18n="nav_home">Accueil</a>
  <a href="#produits" onclick="toggleMenu()" data-i18n="nav_products">Produits</a>
  <a href="#galerie" onclick="toggleMenu()" data-i18n="nav_gallery">Réalisations</a>
  <a href="#services" onclick="toggleMenu()" data-i18n="nav_services">Services</a>
  <a href="#apropos" onclick="toggleMenu()" data-i18n="nav_about">À propos</a>
  <a href="#contact" onclick="toggleMenu()" data-i18n="nav_contact">Contact</a>
  <a class="m-cta" href="https://wa.me/213792106924" target="_blank" rel="noopener">WhatsApp</a>
  <div class="m-lang">
    <button onclick="setLang('fr')" data-lang-btn="fr">FR</button>
    <button onclick="setLang('ar')" data-lang-btn="ar">AR</button>
    <button onclick="setLang('en')" data-lang-btn="en">EN</button>
  </div>
</div>

<header class="hero" id="top">
  <img src="{{door_alu_5}}" alt="Réalisation menuiserie aluminium">
  <div class="hero-overlay"></div>
  <div class="hero-content">
    <h1 data-i18n-html="hero_title">Aluminium &amp; PVC,<br>pensés pour votre espace.</h1>
    <p data-i18n="hero_sub">Fabrication et installation sur mesure.</p>
    <div class="hero-cta">
      <a class="btn-primary" href="https://wa.me/213792106924" target="_blank" rel="noopener" data-i18n="hero_cta1">Parler sur WhatsApp</a>
      <a class="btn-outline" href="#galerie" data-i18n="hero_cta2">Voir nos réalisations</a>
    </div>
  </div>
  <span class="scroll-hint" data-i18n="scroll">Défiler</span>
</header>

<section class="intro">
  <div class="container reveal">
    <div class="eyebrow" data-i18n="intro_eyebrow">Savoir-faire</div>
    <h2 data-i18n="intro_title">Le savoir-faire au service de vos espaces.</h2>
    <p data-i18n="intro_text">Nous réalisons et installons des solutions en aluminium et PVC adaptées à chaque espace, du résidentiel aux projets sur mesure.</p>
  </div>
</section>

<section class="featured">
  <div class="featured-grid reveal">
    <div class="featured-img"><img src="{{cuisine_3}}" alt="Cuisine sur mesure"></div>
    <div class="featured-text">
      <span class="num">01</span>
      <h3 data-i18n="feat_title">Créations sur mesure</h3>
      <p data-i18n="feat_text">Chaque réalisation est pensée selon les dimensions et les besoins réels de l'espace, du choix des matériaux à la pose finale.</p>
      <a class="btn-outline" href="#galerie" data-i18n="feat_btn">Découvrir nos réalisations</a>
    </div>
  </div>
</section>

<section class="products" id="produits">
  <div class="container">
    <div class="section-head reveal">
      <h2 data-i18n="prod_title">Produits</h2>
      <p data-i18n="prod_sub">Une gamme complète en aluminium et PVC, fabriquée et installée sur mesure.</p>
    </div>
  </div>
  <div class="product-grid reveal">
    <a href="#galerie" class="product" onclick="setFilter('aluminium')">
      <img src="{{door_alu_1}}" alt="Fenêtres et portes aluminium">
      <div class="product-label"><span class="pnum">01</span><h4 data-i18n="prod_alu">Fenêtres &amp; portes Aluminium</h4></div>
    </a>
    <a href="#galerie" class="product" onclick="setFilter('pvc')">
      <img src="{{door_pvc_1}}" alt="Fenêtres et portes PVC">
      <div class="product-label"><span class="pnum">02</span><h4 data-i18n="prod_pvc">Fenêtres &amp; portes PVC</h4></div>
    </a>
    <a href="#galerie" class="product" onclick="setFilter('cuisines')">
      <img src="{{cuisine_1}}" alt="Cuisines et rangements">
      <div class="product-label"><span class="pnum">03</span><h4 data-i18n="prod_kit">Cuisines &amp; rangements</h4></div>
    </a>
    <a href="#galerie" class="product" onclick="setFilter('douche')">
      <img src="{{douche_2}}" alt="Parois et portes de douche">
      <div class="product-label"><span class="pnum">04</span><h4 data-i18n="prod_sh">Parois &amp; portes de douche</h4></div>
    </a>
  </div>
</section>

<section class="gallery-section" id="galerie">
  <div class="container">
    <div class="section-head reveal">
      <h2 data-i18n="gal_title">Réalisations</h2>
      <p data-i18n="gal_sub">Un aperçu de nos fabrications et installations récentes.</p>
    </div>
    <div class="filters reveal">
      <button class="filter-btn active" data-filter="all" onclick="setFilter('all')" data-i18n="f_all">Tout</button>
      <button class="filter-btn" data-filter="aluminium" onclick="setFilter('aluminium')" data-i18n="f_alu">Aluminium</button>
      <button class="filter-btn" data-filter="pvc" onclick="setFilter('pvc')" data-i18n="f_pvc">PVC</button>
      <button class="filter-btn" data-filter="cuisines" onclick="setFilter('cuisines')" data-i18n="f_kit">Cuisines</button>
      <button class="filter-btn" data-filter="douche" onclick="setFilter('douche')" data-i18n="f_sh">Douche</button>
    </div>
    <div class="masonry reveal" id="masonry">
      <!-- items injected by JS -->
    </div>
  </div>
</section>

<section class="services" id="services">
  <div class="container">
    <div class="section-head reveal">
      <h2 data-i18n="serv_title">Services</h2>
      <p data-i18n="serv_sub">De la fabrication à la pose, un accompagnement complet.</p>
    </div>
    <div class="reveal">
      <div class="service-row"><span class="snum">01</span><h4 data-i18n="serv1_t">Fabrication</h4><p data-i18n="serv1_p">Fabrication d'éléments en aluminium et PVC adaptés à vos dimensions.</p></div>
      <div class="service-row"><span class="snum">02</span><h4 data-i18n="serv2_t">Solutions Aluminium</h4><p data-i18n="serv2_p">Fenêtres, portes et parois en aluminium, sur mesure.</p></div>
      <div class="service-row"><span class="snum">03</span><h4 data-i18n="serv3_t">Solutions PVC</h4><p data-i18n="serv3_p">Fenêtres et portes PVC, isolantes et durables.</p></div>
      <div class="service-row"><span class="snum">04</span><h4 data-i18n="serv4_t">Installation</h4><p data-i18n="serv4_p">Pose soignée directement sur site par l'atelier.</p></div>
      <div class="service-row"><span class="snum">05</span><h4 data-i18n="serv5_t">Aménagement intérieur</h4><p data-i18n="serv5_p">Cuisines, rangements et parois de douche sur mesure.</p></div>
    </div>
  </div>
</section>

<section class="about" id="apropos">
  <div class="container about-inner reveal">
    <h2 data-i18n="about_title">Un atelier local. Des réalisations sur mesure.</h2>
    <p data-i18n="about_text">Spécialisé dans la fabrication et l'installation de solutions en aluminium et PVC, nous adaptons chaque réalisation aux besoins et aux dimensions de votre espace.</p>
  </div>
</section>

<section class="contact" id="contact">
  <div class="container reveal">
    <h2 data-i18n="contact_title">Votre projet commence ici.</h2>
    <p data-i18n="contact_text">Parlez-nous de votre besoin directement sur WhatsApp.</p>
    <div class="contact-cta">
      <a class="wa-big" href="https://wa.me/213792106924" target="_blank" rel="noopener">
        <svg width="22" height="22" viewBox="0 0 24 24" fill="currentColor"><path d="M12.04 2C6.58 2 2.13 6.45 2.13 11.91c0 1.75.46 3.45 1.32 4.95L2 22l5.25-1.38c1.44.79 3.06 1.2 4.79 1.2 5.46 0 9.91-4.45 9.91-9.91C21.95 6.45 17.5 2 12.04 2zm5.8 14.02c-.24.68-1.4 1.32-1.93 1.4-.5.08-1.13.11-1.82-.11-.42-.14-.96-.32-1.65-.62-2.9-1.25-4.79-4.16-4.94-4.35-.14-.19-1.18-1.57-1.18-3 0-1.42.75-2.12 1.01-2.41.27-.29.58-.36.78-.36.19 0 .39 0 .55.01.18.01.42-.07.65.5.24.58.82 2 .89 2.15.07.14.12.31.02.5-.09.19-.14.31-.28.48-.14.17-.29.37-.42.5-.14.14-.28.29-.12.57.16.28.72 1.19 1.55 1.93 1.07.95 1.96 1.25 2.24 1.39.28.14.44.12.6-.07.16-.19.68-.79.87-1.06.18-.28.36-.23.6-.14.24.09 1.55.73 1.82.87.27.14.44.21.51.32.07.11.07.65-.17 1.33z"/></svg>
        <span data-i18n="contact_cta">Contacter sur WhatsApp</span>
      </a>
    </div>
    <div class="contact-meta">
      <div>
        <span data-i18n="c_phone">Téléphone</span>
        <a href="tel:+213792106924">+213 792 10 69 24</a>
      </div>
      <div>
        <span data-i18n="c_fb">Facebook</span>
        <a href="https://www.facebook.com/profile.php?id=61575091777923" target="_blank" rel="noopener" data-i18n="c_fb_link">Voir la page</a>
      </div>
    </div>
  </div>
</section>

<footer>
  <div class="container footer-inner">
    <span data-i18n="footer_name">Menuiserie Aluminium &amp; PVC — <span data-i18n="footer_copy">Tous droits réservés</span></span>
    <div class="footer-links">
      <a href="https://wa.me/213792106924" target="_blank" rel="noopener">WhatsApp</a>
      <a href="https://www.facebook.com/profile.php?id=61575091777923" target="_blank" rel="noopener">Facebook</a>
      <a href="#top" data-i18n="nav_home">Accueil</a>
      <a href="#contact" data-i18n="nav_contact">Contact</a>
    </div>
  </div>
</footer>

<a class="fab-wa" href="https://wa.me/213792106924" target="_blank" rel="noopener" aria-label="WhatsApp">
  <svg width="26" height="26" viewBox="0 0 24 24" fill="currentColor"><path d="M12.04 2C6.58 2 2.13 6.45 2.13 11.91c0 1.75.46 3.45 1.32 4.95L2 22l5.25-1.38c1.44.79 3.06 1.2 4.79 1.2 5.46 0 9.91-4.45 9.91-9.91C21.95 6.45 17.5 2 12.04 2zm5.8 14.02c-.24.68-1.4 1.32-1.93 1.4-.5.08-1.13.11-1.82-.11-.42-.14-.96-.32-1.65-.62-2.9-1.25-4.79-4.16-4.94-4.35-.14-.19-1.18-1.57-1.18-3 0-1.42.75-2.12 1.01-2.41.27-.29.58-.36.78-.36.19 0 .39 0 .55.01.18.01.42-.07.65.5.24.58.82 2 .89 2.15.07.14.12.31.02.5-.09.19-.14.31-.28.48-.14.17-.29.37-.42.5-.14.14-.28.29-.12.57.16.28.72 1.19 1.55 1.93 1.07.95 1.96 1.25 2.24 1.39.28.14.44.12.6-.07.16-.19.68-.79.87-1.06.18-.28.36-.23.6-.14.24.09 1.55.73 1.82.87.27.14.44.21.51.32.07.11.07.65-.17 1.33z"/></svg>
</a>

<div class="lightbox" id="lightbox">
  <button class="lb-close" onclick="closeLB()">&times;</button>
  <button class="lb-prev" onclick="navLB(-1)">&#8249;</button>
  <img id="lbImg" src="" alt="">
  <button class="lb-next" onclick="navLB(1)">&#8250;</button>
</div>

<script>
/* ---------- GALLERY DATA ---------- */
const GALLERY = [
  {src:"{{door_alu_1}}", cat:"aluminium", label:{fr:"Porte aluminium",ar:"باب ألمنيوم",en:"Aluminium door"}},
  {src:"{{door_alu_2}}", cat:"aluminium", label:{fr:"Porte &amp; fenêtre aluminium",ar:"باب ونافذة ألمنيوم",en:"Aluminium door & window"}},
  {src:"{{door_alu_3}}", cat:"aluminium", label:{fr:"Porte aluminium vitrée",ar:"باب ألمنيوم زجاجي",en:"Glazed aluminium door"}},
  {src:"{{door_alu_4}}", cat:"aluminium", label:{fr:"Porte aluminium",ar:"باب ألمنيوم",en:"Aluminium door"}},
  {src:"{{door_alu_5}}", cat:"aluminium", label:{fr:"Baie coulissante aluminium",ar:"باب منزلق ألمنيوم",en:"Aluminium sliding door"}},
  {src:"{{win_alu_1}}", cat:"aluminium", label:{fr:"Fenêtre aluminium à volet",ar:"نافذة ألمنيوم بمصراع",en:"Aluminium shutter window"}},
  {src:"{{win_alu_2}}", cat:"aluminium", label:{fr:"Fenêtre coulissante aluminium",ar:"نافذة ألمنيوم منزلقة",en:"Aluminium sliding window"}},
  {src:"{{door_pvc_1}}", cat:"pvc", label:{fr:"Porte PVC décorative",ar:"باب PVC مزخرف",en:"Decorative PVC door"}},
  {src:"{{door_pvc_2}}", cat:"pvc", label:{fr:"Porte PVC vitrée",ar:"باب PVC زجاجي",en:"Glazed PVC door"}},
  {src:"{{win_pvc_1}}", cat:"pvc", label:{fr:"Fenêtre PVC à deux vantaux",ar:"نافذة PVC بمصراعين",en:"Twin-panel PVC window"}},
  {src:"{{win_pvc_2}}", cat:"pvc", label:{fr:"Installation fenêtres PVC",ar:"تركيب نوافذ PVC",en:"PVC windows installation"}},
  {src:"{{win_pvc_3}}", cat:"pvc", label:{fr:"Fenêtre PVC installée",ar:"نافذة PVC مركبة",en:"Installed PVC window"}},
  {src:"{{cuisine_1}}", cat:"cuisines", label:{fr:"Cuisine sur mesure",ar:"مطبخ حسب الطلب",en:"Custom kitchen"}},
  {src:"{{cuisine_2}}", cat:"cuisines", label:{fr:"Cuisine sur mesure",ar:"مطبخ حسب الطلب",en:"Custom kitchen"}},
  {src:"{{cuisine_3}}", cat:"cuisines", label:{fr:"Cuisine installée",ar:"مطبخ مركب",en:"Installed kitchen"}},
  {src:"{{cuisine_4}}", cat:"cuisines", label:{fr:"Cuisine sur mesure",ar:"مطبخ حسب الطلب",en:"Custom kitchen"}},
  {src:"{{douche_1}}", cat:"douche", label:{fr:"Paroi de douche",ar:"حاجز دش",en:"Shower enclosure"}},
  {src:"{{douche_2}}", cat:"douche", label:{fr:"Paroi de douche installée",ar:"حاجز دش مركب",en:"Installed shower enclosure"}}
];

let currentLang = "fr";
let currentFilter = "all";
let lbIndex = 0;

function renderGallery(){
  const m = document.getElementById("masonry");
  m.innerHTML = "";
  GALLERY.forEach((item, i)=>{
    const div = document.createElement("div");
    div.className = "g-item" + (currentFilter!=="all" && item.cat!==currentFilter ? " hide":"");
    div.dataset.cat = item.cat;
    div.onclick = ()=>openLB(i);
    div.innerHTML = `<img src="${item.src}" alt="${item.label[currentLang]}" loading="lazy"><span class="g-tag">${item.label[currentLang]}</span>`;
    m.appendChild(div);
  });
}

function setFilter(cat){
  currentFilter = cat;
  document.querySelectorAll(".filter-btn").forEach(b=>b.classList.toggle("active", b.dataset.filter===cat));
  document.querySelectorAll(".g-item").forEach(el=>{
    el.classList.toggle("hide", cat!=="all" && el.dataset.cat!==cat);
  });
  document.getElementById("galerie").scrollIntoView({behavior:"smooth"});
}

function openLB(i){
  lbIndex = i;
  document.getElementById("lbImg").src = GALLERY[i].src;
  document.getElementById("lbImg").alt = GALLERY[i].label[currentLang];
  document.getElementById("lightbox").classList.add("open");
  document.body.style.overflow="hidden";
}
function closeLB(){
  document.getElementById("lightbox").classList.remove("open");
  document.body.style.overflow="";
}
function navLB(dir){
  lbIndex = (lbIndex + dir + GALLERY.length) % GALLERY.length;
  document.getElementById("lbImg").src = GALLERY[lbIndex].src;
  document.getElementById("lbImg").alt = GALLERY[lbIndex].label[currentLang];
}
document.addEventListener("keydown", (e)=>{
  if(!document.getElementById("lightbox").classList.contains("open")) return;
  if(e.key==="Escape") closeLB();
  if(e.key==="ArrowRight") navLB(1);
  if(e.key==="ArrowLeft") navLB(-1);
});
/* touch swipe */
let touchX=null;
const lb = document.getElementById("lightbox");
lb.addEventListener("touchstart", e=>{touchX=e.touches[0].clientX;});
lb.addEventListener("touchend", e=>{
  if(touchX===null) return;
  const dx = e.changedTouches[0].clientX - touchX;
  if(Math.abs(dx) > 40) navLB(dx>0 ? -1 : 1);
  touchX=null;
});
lb.addEventListener("click", e=>{ if(e.target===lb) closeLB(); });

/* ---------- MENU / NAV SCROLL ---------- */
function toggleMenu(){
  document.getElementById("mMenu").classList.toggle("open");
}
window.addEventListener("scroll", ()=>{
  document.getElementById("nav").classList.toggle("scrolled", window.scrollY > 40);
});

/* ---------- REVEAL ON SCROLL ---------- */
const io = new IntersectionObserver((entries)=>{
  entries.forEach(en=>{ if(en.isIntersecting){ en.target.classList.add("in"); io.unobserve(en.target); } });
},{threshold:.12});
document.querySelectorAll(".reveal").forEach(el=>io.observe(el));

/* ---------- I18N ---------- */
const I18N = {
  fr:{
    logo_ar:"نجارة الألمنيوم و PVC", logo_sub:"Aluminium &amp; PVC",
    nav_home:"Accueil", nav_products:"Produits", nav_gallery:"Réalisations", nav_services:"Services", nav_about:"À propos", nav_contact:"Contact",
    hero_title:"Aluminium &amp; PVC,<br>pensés pour votre espace.",
    hero_sub:"Fabrication et installation sur mesure.",
    hero_cta1:"Parler sur WhatsApp", hero_cta2:"Voir nos réalisations", scroll:"Défiler",
    intro_eyebrow:"Savoir-faire",
    intro_title:"Le savoir-faire au service de vos espaces.",
    intro_text:"Nous réalisons et installons des solutions en aluminium et PVC adaptées à chaque espace, du résidentiel aux projets sur mesure.",
    feat_title:"Créations sur mesure",
    feat_text:"Chaque réalisation est pensée selon les dimensions et les besoins réels de l'espace, du choix des matériaux à la pose finale.",
    feat_btn:"Découvrir nos réalisations",
    prod_title:"Produits", prod_sub:"Une gamme complète en aluminium et PVC, fabriquée et installée sur mesure.",
    prod_alu:"Fenêtres &amp; portes Aluminium", prod_pvc:"Fenêtres &amp; portes PVC", prod_kit:"Cuisines &amp; rangements", prod_sh:"Parois &amp; portes de douche",
    gal_title:"Réalisations", gal_sub:"Un aperçu de nos fabrications et installations récentes.",
    f_all:"Tout", f_alu:"Aluminium", f_pvc:"PVC", f_kit:"Cuisines", f_sh:"Douche",
    serv_title:"Services", serv_sub:"De la fabrication à la pose, un accompagnement complet.",
    serv1_t:"Fabrication", serv1_p:"Fabrication d'éléments en aluminium et PVC adaptés à vos dimensions.",
    serv2_t:"Solutions Aluminium", serv2_p:"Fenêtres, portes et parois en aluminium, sur mesure.",
    serv3_t:"Solutions PVC", serv3_p:"Fenêtres et portes PVC, isolantes et durables.",
    serv4_t:"Installation", serv4_p:"Pose soignée directement sur site par l'atelier.",
    serv5_t:"Aménagement intérieur", serv5_p:"Cuisines, rangements et parois de douche sur mesure.",
    about_title:"Un atelier local. Des réalisations sur mesure.",
    about_text:"Spécialisé dans la fabrication et l'installation de solutions en aluminium et PVC, nous adaptons chaque réalisation aux besoins et aux dimensions de votre espace.",
    contact_title:"Votre projet commence ici.",
    contact_text:"Parlez-nous de votre besoin directement sur WhatsApp.",
    contact_cta:"Contacter sur WhatsApp",
    c_phone:"Téléphone", c_fb:"Facebook", c_fb_link:"Voir la page",
    footer_name:"Menuiserie Aluminium &amp; PVC — ", footer_copy:"Tous droits réservés"
  },
  ar:{
    logo_ar:"نجارة الألمنيوم و PVC", logo_sub:"ألمنيوم و PVC",
    nav_home:"الرئيسية", nav_products:"المنتجات", nav_gallery:"الإنجازات", nav_services:"الخدمات", nav_about:"من نحن", nav_contact:"اتصل بنا",
    hero_title:"ألمنيوم و PVC،<br>مصمّمة لمساحتك.",
    hero_sub:"تصنيع وتركيب حسب الطلب.",
    hero_cta1:"تواصل عبر واتساب", hero_cta2:"شاهد إنجازاتنا", scroll:"مرّر للأسفل",
    intro_eyebrow:"خبرتنا",
    intro_title:"الخبرة في خدمة مساحتك.",
    intro_text:"نقوم بتصنيع وتركيب حلول الألمنيوم و PVC المناسبة لكل مساحة، من المنازل إلى المشاريع الخاصة.",
    feat_title:"إبداعات حسب الطلب",
    feat_text:"كل إنجاز يُصمم وفق أبعاد واحتياجات المساحة الفعلية، من اختيار المواد إلى التركيب النهائي.",
    feat_btn:"اكتشف إنجازاتنا",
    prod_title:"المنتجات", prod_sub:"تشكيلة كاملة من الألمنيوم و PVC، مصنوعة ومركبة حسب الطلب.",
    prod_alu:"نوافذ وأبواب ألمنيوم", prod_pvc:"نوافذ وأبواب PVC", prod_kit:"مطابخ وخزائن", prod_sh:"حواجز وأبواب دش",
    gal_title:"الإنجازات", gal_sub:"نظرة على أحدث تصنيعاتنا وتركيباتنا.",
    f_all:"الكل", f_alu:"ألمنيوم", f_pvc:"PVC", f_kit:"مطابخ", f_sh:"دش",
    serv_title:"الخدمات", serv_sub:"من التصنيع إلى التركيب، مرافقة كاملة.",
    serv1_t:"التصنيع", serv1_p:"تصنيع عناصر الألمنيوم و PVC حسب أبعادكم.",
    serv2_t:"حلول الألمنيوم", serv2_p:"نوافذ وأبواب وحواجز ألمنيوم حسب الطلب.",
    serv3_t:"حلول PVC", serv3_p:"نوافذ وأبواب PVC عازلة ومتينة.",
    serv4_t:"التركيب", serv4_p:"تركيب دقيق مباشرة في الموقع من طرف الورشة.",
    serv5_t:"التهيئة الداخلية", serv5_p:"مطابخ وخزائن وحواجز دش حسب الطلب.",
    about_title:"ورشة محلية. إنجازات حسب الطلب.",
    about_text:"متخصصون في تصنيع وتركيب حلول الألمنيوم و PVC، نكيّف كل إنجاز حسب احتياجات وأبعاد مساحتكم.",
    contact_title:"مشروعك يبدأ من هنا.",
    contact_text:"حدّثونا عن احتياجكم مباشرة عبر واتساب.",
    contact_cta:"تواصل عبر واتساب",
    c_phone:"الهاتف", c_fb:"فيسبوك", c_fb_link:"زيارة الصفحة",
    footer_name:"نجارة الألمنيوم و PVC — ", footer_copy:"جميع الحقوق محفوظة"
  },
  en:{
    logo_ar:"نجارة الألمنيوم و PVC", logo_sub:"Aluminium &amp; PVC",
    nav_home:"Home", nav_products:"Products", nav_gallery:"Projects", nav_services:"Services", nav_about:"About", nav_contact:"Contact",
    hero_title:"Aluminium &amp; PVC,<br>designed for your space.",
    hero_sub:"Custom fabrication and installation.",
    hero_cta1:"Talk on WhatsApp", hero_cta2:"See our projects", scroll:"Scroll",
    intro_eyebrow:"Craftsmanship",
    intro_title:"Craftsmanship for every space.",
    intro_text:"We fabricate and install aluminium and PVC solutions tailored to every space, from homes to custom projects.",
    feat_title:"Custom creations",
    feat_text:"Every project is designed around the real dimensions and needs of the space, from material choice to final installation.",
    feat_btn:"Discover our projects",
    prod_title:"Products", prod_sub:"A full range of aluminium and PVC, made and installed to measure.",
    prod_alu:"Aluminium windows &amp; doors", prod_pvc:"PVC windows &amp; doors", prod_kit:"Kitchens &amp; storage", prod_sh:"Shower doors &amp; enclosures",
    gal_title:"Projects", gal_sub:"A look at our recent fabrication and installation work.",
    f_all:"All", f_alu:"Aluminium", f_pvc:"PVC", f_kit:"Kitchens", f_sh:"Shower",
    serv_title:"Services", serv_sub:"From fabrication to installation, full support.",
    serv1_t:"Fabrication", serv1_p:"Aluminium and PVC elements made to your exact dimensions.",
    serv2_t:"Aluminium solutions", serv2_p:"Custom aluminium windows, doors and partitions.",
    serv3_t:"PVC solutions", serv3_p:"Insulating, durable PVC windows and doors.",
    serv4_t:"Installation", serv4_p:"Careful on-site installation by the workshop.",
    serv5_t:"Interior fit-out", serv5_p:"Custom kitchens, storage and shower enclosures.",
    about_title:"A local workshop. Work made to measure.",
    about_text:"Specialised in fabricating and installing aluminium and PVC solutions, we tailor every project to the needs and dimensions of your space.",
    contact_title:"Your project starts here.",
    contact_text:"Tell us about your needs directly on WhatsApp.",
    contact_cta:"Contact on WhatsApp",
    c_phone:"Phone", c_fb:"Facebook", c_fb_link:"Visit the page",
    footer_name:"Aluminium &amp; PVC Workshop — ", footer_copy:"All rights reserved"
  }
};

function setLang(lang){
  currentLang = lang;
  const dict = I18N[lang];
  document.documentElement.lang = lang;
  document.documentElement.dir = lang==="ar" ? "rtl" : "ltr";
  document.querySelectorAll("[data-i18n]").forEach(el=>{
    const key = el.getAttribute("data-i18n");
    if(dict[key]!==undefined) el.textContent = dict[key];
  });
  document.querySelectorAll("[data-i18n-html]").forEach(el=>{
    const key = el.getAttribute("data-i18n-html");
    if(dict[key]!==undefined) el.innerHTML = dict[key];
  });
  document.querySelectorAll("[data-lang-btn]").forEach(b=>{
    b.classList.toggle("active", b.dataset.langBtn===lang);
  });
  renderGallery();
}

renderGallery();
setLang("fr");
</script>
</body>
</html>
