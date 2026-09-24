# Yoob 
<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>LIFTEX Elevators &amp; Parts</title>
<style>
:root{--navy:#102A43;--blue:#1769AA;--gold:#D6A84F;--bg:#fff;--alt:#F5F7FA;--tx:#102A43;--mu:#667085;--card:#fff;--bd:#e3e8ef;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0b1a2b;--alt:#0f2236;--tx:#e8eef5;--mu:#9fb0c3;--card:#132a42;--bd:#22405c}}
:root[data-theme="dark"]{--bg:#0b1a2b;--alt:#0f2236;--tx:#e8eef5;--mu:#9fb0c3;--card:#132a42;--bd:#22405c}
html{scroll-behavior:smooth;scroll-padding-top:calc(72px + env(safe-area-inset-top,0px))}
*{box-sizing:border-box;margin:0}
body{background:var(--bg);color:var(--tx);font:16px/1.6 "Segoe UI",Tahoma,Arial,sans-serif;overflow-x:hidden}
img,svg{max-width:100%}
.w{max-width:1140px;margin:0 auto;padding:0 20px}
a{color:inherit;text-decoration:none}
header{position:sticky;top:env(safe-area-inset-top,0px);z-index:20;background:var(--navy);color:#fff}
.hb{display:flex;align-items:center;gap:20px;height:64px}
.logo{display:flex;flex-direction:column;line-height:1.1}
.logo b{font-size:22px;letter-spacing:2px}.logo small{font-size:11px;color:var(--gold);letter-spacing:.5px}
nav{display:flex;gap:22px;margin-inline:auto;font-size:15px}
nav a{opacity:.85;padding:6px 0}nav a:hover{opacity:1;color:var(--gold)}
.rt{display:flex;align-items:center;gap:12px}
.lg{display:flex;border:1px solid rgba(255,255,255,.3);border-radius:8px;overflow:hidden}
.lg button{background:none;border:0;color:#fff;padding:5px 10px;font:600 12px inherit;cursor:pointer;opacity:.75}
.lg button.on{background:#fff;color:var(--navy);opacity:1}
.btn{display:inline-block;background:var(--blue);color:#fff;padding:11px 22px;border-radius:8px;font-weight:600;font-size:15px;border:2px solid var(--blue);cursor:pointer;transition:.2s;text-align:center}
.btn:hover{background:#125a94}
.btn.gh{background:none;border-color:rgba(255,255,255,.55)}.btn.gh:hover{background:rgba(255,255,255,.12)}
.btn.o{background:none;color:var(--tx);border-color:var(--blue)}.btn.o:hover{background:var(--blue);color:#fff}
#bg{display:none;background:none;border:0;color:#fff;font-size:26px;cursor:pointer;line-height:1}
.hero{background:linear-gradient(120deg,#0b1f33,var(--navy) 55%,#17466e);color:#fff;padding:72px 0}
.hero .w{display:grid;grid-template-columns:1.2fr .8fr;gap:40px;align-items:center}
.eb{color:var(--gold);font-weight:600;letter-spacing:1px;margin:6px 0 16px}
.hero h1{font-size:clamp(30px,4.6vw,50px);line-height:1.15;margin-bottom:18px}
.hero p{color:#c9d6e3;max-width:540px;margin-bottom:28px}
.cta{display:flex;flex-wrap:wrap;gap:12px}
.lift{height:320px;max-width:300px;margin-inline:auto;width:100%;border:8px solid #2a4a68;border-radius:14px 14px 0 0;background:linear-gradient(#e8eef5,#c5d3e0);display:flex;position:relative;overflow:hidden;box-shadow:0 20px 50px rgba(0,0,0,.35)}
.lift i{flex:1;background:linear-gradient(90deg,#8fa5ba,#dfe8f0 50%,#8fa5ba);border-inline:1px solid #6d859c}
.lift:before{content:"";position:absolute;top:10px;left:50%;width:0;height:0;margin-left:-9px;border:9px solid transparent;border-bottom:14px solid var(--gold);border-top:0;z-index:2}
.sec{padding:72px 0}.alt{background:var(--alt)}
.hd{text-align:center;max-width:640px;margin:0 auto 40px}
.hd h2{font-size:clamp(26px,3.4vw,36px);margin-bottom:10px}
.hd h2:after{content:"";display:block;width:44px;height:3px;background:var(--gold);margin:12px auto 0}
.hd p{color:var(--mu)}
.grid{display:grid;gap:22px}.g3{grid-template-columns:repeat(3,minmax(0,1fr))}.g4{grid-template-columns:repeat(4,minmax(0,1fr))}.g5{grid-template-columns:repeat(5,minmax(0,1fr));gap:16px}
.card,.pc{background:var(--card);border:1px solid var(--bd);border-radius:12px;overflow:hidden}
.card:hover,.pc:hover{box-shadow:0 8px 24px rgba(16,42,67,.12)}
.ph{height:150px;display:flex;align-items:center;justify-content:center;color:rgba(255,255,255,.92);position:relative;background-image:repeating-linear-gradient(90deg,rgba(255,255,255,.05) 0 2px,transparent 2px 28px),linear-gradient(135deg,var(--a),var(--b))}
.ph:after{content:"";position:absolute;bottom:0;inset-inline:0;height:3px;background:var(--gold);opacity:.75}
.ph svg{width:62px;height:62px}
.g0{--a:#102A43;--b:#1769AA}.g1{--a:#1769AA;--b:#0d3f66}.g2{--a:#183a5a;--b:#3b7fb8}.g3x{--a:#0b1f33;--b:#1f5d94}
.cb{padding:16px 18px 18px}.card h3{font-size:18px;margin-bottom:4px}.card p{color:var(--mu);font-size:14px;margin-bottom:10px}
.lnk{color:var(--blue);font-weight:600;font-size:14px}
.pc .ph{height:96px}.pc .ph svg{width:44px;height:44px}.pc h4{font-size:14px;padding:10px 8px;text-align:center}
.mid{text-align:center;margin-top:32px}
.sv .ph{height:170px}
.wy{text-align:center;padding:8px}
.wy .ic{width:58px;height:58px;border-radius:50%;background:var(--navy);color:var(--gold);display:flex;align-items:center;justify-content:center;margin:0 auto 12px}
.wy .ic svg{width:28px;height:28px}.wy h3{font-size:17px}.wy p{color:var(--mu);font-size:14px}
.ct{background:var(--navy);color:#fff;text-align:center}
.ct h2{font-size:clamp(26px,3.4vw,36px);margin-bottom:12px}.ct .sub{color:#c9d6e3;max-width:600px;margin:0 auto 32px}
.cg{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:16px}
.cl{background:rgba(255,255,255,.07);border:1px solid rgba(255,255,255,.18);border-radius:12px;padding:20px 12px;display:block;transition:.2s}
.cl:hover{background:var(--blue);border-color:var(--blue)}
.cl svg{width:30px;height:30px;color:var(--gold);margin-bottom:8px}.cl:hover svg{color:#fff}
.cl b{display:block}.cl small{display:block;color:#c9d6e3;font-size:13px}.cl code{display:block;margin-top:8px;font:13px inherit;direction:ltr;word-break:break-all}
.dn{margin-top:22px;font-size:13px;color:var(--gold)}
footer{background:#0b1f33;color:#c9d6e3;padding:44px 0 24px;font-size:14px}
.fg{display:grid;grid-template-columns:1.4fr 1fr 1fr;gap:28px;margin-bottom:28px}
footer b.l{color:#fff;font-size:20px;letter-spacing:2px;display:block}
footer .col a{display:block;padding:3px 0}footer a:hover{color:var(--gold)}
.cp{border-top:1px solid rgba(255,255,255,.12);padding-top:18px;text-align:center;font-size:13px}
@media(max-width:900px){
.g3{grid-template-columns:repeat(2,minmax(0,1fr))}.g4{grid-template-columns:repeat(2,minmax(0,1fr))}.g5{grid-template-columns:repeat(3,minmax(0,1fr))}.cg{grid-template-columns:repeat(2,minmax(0,1fr))}
.hero .w{grid-template-columns:1fr}.lift{height:200px;max-width:220px;order:-1}.hero{padding:44px 0}
#bg{display:block}.rt .btn{display:none}.hb{gap:10px}.logo{margin-inline-end:auto}
nav{display:none;position:absolute;top:64px;inset-inline:0;background:var(--navy);flex-direction:column;gap:0;padding:8px 20px 16px;border-top:1px solid rgba(255,255,255,.12)}
nav.open{display:flex}nav a{padding:12px 0;border-bottom:1px solid rgba(255,255,255,.08)}
.fg{grid-template-columns:1fr 1fr}.fg>div:first-child{grid-column:1/-1}}
@media(max-width:560px){.g3,.g4{grid-template-columns:minmax(0,1fr)}.g5{grid-template-columns:repeat(2,minmax(0,1fr))}.cg{grid-template-columns:minmax(0,1fr)}.sec{padding:52px 0}.cta .btn{flex:1}}
</style>
</head>
<body>
<header id="hd"><div class="w hb">
<a class="logo" href="#home"><b>LIFTEX</b><small data-k="ep"></small></a>
<nav id="nv"></nav>
<div class="rt"><div class="lg"><button data-l="0">EN</button><button data-l="1">FR</button><button data-l="2">AR</button></div>
<a class="btn" href="#contact" data-k="cu"></a><button id="bg" aria-label="Menu">&#9776;</button></div>
</div></header>

<section class="hero" id="home"><div class="w">
<div><div class="eb">LIFTEX &middot; <span data-k="ep"></span></div>
<h1 data-k="h1"></h1><p data-k="hp"></p>
<div class="cta"><a class="btn" href="#elevators" data-k="vo"></a><a class="btn gh" href="#contact" data-k="cu"></a></div></div>
<div class="lift" aria-hidden="true"><i></i><i></i></div>
</div></section>

<section class="sec" id="elevators"><div class="w">
<div class="hd"><h2 data-k="eh"></h2><p data-k="es"></p></div>
<div class="grid g3" id="eg"></div>
<div class="mid"><a class="btn" href="#contact" data-k="ae"></a></div>
</div></section>

<section class="sec alt" id="parts"><div class="w">
<div class="hd"><h2 data-k="ph"></h2><p data-k="ps"></p></div>
<div class="grid g5" id="pg"></div>
<div class="mid"><a class="btn" href="#contact" data-k="ap"></a></div>
</div></section>

<section class="sec" id="services"><div class="w">
<div class="hd"><h2 data-k="sh"></h2></div>
<div class="grid g4 sv" id="sg"></div>
</div></section>

<section class="sec alt" id="why"><div class="w">
<div class="hd"><h2 data-k="wh"></h2></div>
<div class="grid g4" id="wg"></div>
</div></section>

<section class="sec ct" id="contact"><div class="w">
<h2 data-k="ch"></h2><p class="sub" data-k="cs"></p>
<div class="cg" id="cg"></div>
<p class="dn" data-k="dn"></p>
</div></section>

<footer><div class="w">
<div class="fg">
<div><b class="l">LIFTEX</b><span data-k="ep"></span><p style="margin-top:8px" data-k="h1"></p></div>
<div class="col" id="fn"></div>
<div class="col" id="fs"></div>
</div>
<div class="cp" data-k="cp"></div>
</div></footer>

<script>
const D={
ep:'Elevators & Parts|Ascenseurs & Pièces|مصاعد وقطع غيار',
cu:'Contact Us|Contactez-nous|تواصل معنا',
h1:'Reliable Elevator Solutions for Every Building|Des solutions d\'ascenseurs fiables pour chaque bâtiment|حلول مصاعد موثوقة لكل مبنى',
hp:'We provide elevator solutions, equipment and spare parts, with professional services for supply, installation, maintenance and support.|Nous proposons des solutions d\'ascenseurs, des équipements et des pièces détachées, avec des services professionnels de fourniture, d\'installation, de maintenance et d\'assistance.|نوفّر حلول المصاعد والمعدات وقطع الغيار، مع خدمات احترافية للتوريد والتركيب والصيانة والدعم.',
vo:'View Our Elevators|Voir nos ascenseurs|شاهد مصاعدنا',
eh:'Our Elevators|Nos ascenseurs|مصاعدنا',
es:'Discover our range of elevator solutions designed for residential, commercial and specialized applications.|Découvrez notre gamme de solutions d\'ascenseurs pour applications résidentielles, commerciales et spécialisées.|اكتشف مجموعتنا من حلول المصاعد المصممة للاستخدامات السكنية والتجارية والمتخصصة.',
vd:'View Details|Voir détails|عرض التفاصيل',
ae:'Ask About an Elevator|Demander un ascenseur|اسأل عن مصعد',
ph:'Elevator Spare Parts|Pièces détachées d\'ascenseurs|قطع غيار المصاعد',
ps:'Quality components and spare parts for reliable elevator operation and maintenance.|Composants et pièces de qualité pour un fonctionnement et une maintenance fiables.|قطع ومكوّنات عالية الجودة لتشغيل وصيانة موثوقين للمصاعد.',
ap:'Ask About a Part|Demander une pièce|اسأل عن قطعة',
sh:'Our Services|Nos services|خدماتنا',
wh:'Why LIFTEX|Pourquoi LIFTEX|لماذا LIFTEX',
ch:'Let’s Talk About Your Elevator Project|Parlons de votre projet d\'ascenseur|لنتحدث عن مشروع المصعد الخاص بك',
cs:'Need an elevator, spare parts, installation or maintenance service? Contact our team and tell us what you need.|Besoin d\'un ascenseur, de pièces détachées, d\'une installation ou d\'une maintenance ? Contactez notre équipe et dites-nous ce qu\'il vous faut.|هل تحتاج إلى مصعد أو قطع غيار أو تركيب أو صيانة؟ تواصل مع فريقنا وأخبرنا بما تحتاجه.',
dn:'Demo contact details, for presentation only.|Coordonnées de démonstration uniquement.|بيانات تواصل تجريبية للعرض فقط.',
cp:'© 2026 LIFTEX Elevators & Parts — Demo Website|© 2026 LIFTEX Elevators & Parts — Site de démonstration|© 2026 LIFTEX Elevators & Parts — موقع تجريبي',
n0:'Home|Accueil|الرئيسية',n1:'Elevators|Ascenseurs|المصاعد',n2:'Spare Parts|Pièces détachées|قطع الغيار',n3:'Services|Services|الخدمات',n4:'Contact|Contact|تواصل معنا'
};
const IC={
pass:'<rect x="14" y="8" width="36" height="48"/><path d="M32 8v48M23 20l4-5 4 5M37 44l4 5 4-5"/>',
glass:'<rect x="10" y="8" width="44" height="48"/><path d="M32 8v48M10 32h44"/>',
home:'<path d="M8 30 32 10l24 20M14 26v28h36V26"/><rect x="27" y="38" width="10" height="16"/>',
frt:'<rect x="12" y="16" width="40" height="34"/><path d="M12 16l40 34M52 16 12 50"/>',
hosp:'<rect x="10" y="10" width="44" height="44" rx="6"/><path d="M32 20v24M20 32h24"/>',
car:'<path d="M8 40h48v-8l-8-10H24l-8 10z"/><circle cx="20" cy="44" r="5"/><circle cx="44" cy="44" r="5"/>',
motor:'<rect x="10" y="22" width="32" height="22" rx="4"/><rect x="42" y="28" width="12" height="10"/><circle cx="26" cy="33" r="6"/><path d="M16 44v8M36 44v8"/>',
panel:'<rect x="12" y="8" width="40" height="48" rx="4"/><rect x="18" y="14" width="28" height="12"/><circle cx="22" cy="36" r="3"/><circle cx="32" cy="36" r="3"/><circle cx="42" cy="36" r="3"/><circle cx="22" cy="46" r="3"/><circle cx="32" cy="46" r="3"/><circle cx="42" cy="46" r="3"/>',
door:'<rect x="10" y="8" width="44" height="48"/><path d="M32 8v48M28 32h-4M36 32h4"/>',
gear:'<circle cx="32" cy="32" r="11"/><circle cx="32" cy="32" r="3"/><path d="M32 8v9M32 47v9M8 32h9M47 32h9M15 15l6 6M43 43l6 6M49 15l-6 6M21 43l-6 6"/>',
rail:'<path d="M22 6v52M42 6v52M14 16h16M34 16h16M14 32h16M34 32h16M14 48h16M34 48h16"/>',
btn:'<circle cx="32" cy="32" r="22"/><circle cx="32" cy="32" r="10"/><path d="M27 35l5-6 5 6"/>',
shield:'<path d="M32 6l22 8v18c0 14-10 22-22 26C20 54 10 46 10 32V14z"/><path d="M22 32l7 7 13-14"/>',
cabin:'<rect x="12" y="8" width="40" height="48"/><rect x="18" y="14" width="28" height="26"/><path d="M12 50h40M18 34h28"/>',
chip:'<rect x="18" y="18" width="28" height="28" rx="3"/><path d="M26 10v8M38 10v8M26 46v8M38 46v8M10 26h8M10 38h8M46 26h8M46 38h8"/><rect x="26" y="26" width="12" height="12"/>',
box:'<rect x="10" y="10" width="18" height="18"/><rect x="36" y="10" width="18" height="18"/><rect x="10" y="36" width="18" height="18"/><rect x="36" y="36" width="18" height="18"/>',
ship:'<path d="M6 42h52l-8 12H14z"/><rect x="14" y="26" width="14" height="16"/><rect x="30" y="30" width="12" height="12"/><path d="M46 34h6v8"/>',
hat:'<path d="M12 42a20 20 0 0 1 40 0z"/><rect x="8" y="42" width="48" height="6" rx="2"/><path d="M32 20v22"/>',
srch:'<circle cx="28" cy="28" r="14"/><path d="M38 38l16 16M22 28l4 4 8-8"/>',
wr:'<path d="M42 10a12 12 0 0 0-12 16L10 46l8 8 20-20a12 12 0 0 0 16-12l-8 8-7-2-2-7z"/>',
star:'<path d="M32 8l7 15 16 2-12 11 3 16-14-8-14 8 3-16L9 25l16-2z"/>',
sup:'<path d="M12 36v-6a20 20 0 0 1 40 0v6"/><rect x="8" y="34" width="8" height="14" rx="3"/><rect x="48" y="34" width="8" height="14" rx="3"/><path d="M52 48c0 6-8 8-16 8"/>',
wa:'<path d="M10 12h44v30H26l-12 10V42h-4z"/><path d="M20 22h24M20 32h14"/>',
ph:'<path d="M18 8h10l4 12-6 4c3 7 8 12 14 14l4-6 12 4v10c0 4-4 8-8 8C30 54 10 34 10 16c0-4 4-8 8-8z"/>',
ml:'<rect x="8" y="14" width="48" height="36" rx="3"/><path d="M8 16l24 20 24-20"/>',
fb:'<circle cx="32" cy="32" r="24"/><path d="M36 54V34h6M30 34h12M36 34c0-8 0-12 8-12"/>'};
const svg=n=>`<svg viewBox="0 0 64 64" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round">${IC[n]}</svg>`;
const E=[
['pass','Passenger Elevator|Ascenseur de personnes|مصعد ركاب','Passenger lifts for residential buildings, offices and hotels.|Pour immeubles résidentiels, bureaux et hôtels.|مصاعد ركاب للمباني السكنية والمكاتب والفنادق.'],
['glass','Panoramic Glass Elevator|Ascenseur panoramique vitré|مصعد بانورامي زجاجي','Glass panoramic lifts for modern buildings and malls.|Pour bâtiments modernes et centres commerciaux.|للمباني الحديثة والمراكز التجارية.'],
['home','Residential Elevator|Ascenseur résidentiel|مصعد منزلي','Home elevators for houses and villas.|Pour maisons et villas.|مصاعد منزلية وفيلات.'],
['frt','Freight Elevator|Monte-charge|مصعد بضائع','Built for moving goods and heavy loads.|Conçu pour les marchandises et charges lourdes.|مخصص لنقل البضائع والأحمال.'],
['hosp','Hospital / Patient Elevator|Ascenseur hospitalier|مصعد مستشفيات','Suited to hospitals and healthcare facilities.|Adapté aux hôpitaux et établissements de santé.|مناسب للمستشفيات والمرافق الصحية.'],
['car','Car Elevator|Ascenseur de voitures|مصعد سيارات','Vehicle lifts for garages and car parks.|Pour garages et parkings.|مصاعد السيارات والمواقف.']];
const P=[['motor','Elevator Motors|Moteurs d\'ascenseur|محركات المصاعد'],['panel','Control Panels|Armoires de commande|لوحات التحكم'],['door','Elevator Doors|Portes d\'ascenseur|أبواب المصاعد'],['gear','Door Operators|Opérateurs de porte|مشغّلات الأبواب'],['rail','Guide Rails|Rails de guidage|سكك التوجيه'],['btn','Push Buttons|Boutons-poussoirs|أزرار الاستدعاء'],['shield','Safety Components|Composants de sécurité|مكوّنات الأمان'],['cabin','Elevator Cabins|Cabines d\'ascenseur|كبائن المصاعد'],['chip','Controllers|Contrôleurs|وحدات التحكم'],['box','Other Components|Autres composants|مكوّنات أخرى']];
const S=[
['ship','Supply & Export|Fourniture et export|التوريد والتصدير','We supply and export elevator systems and components for different building requirements.|Nous fournissons et exportons des systèmes et composants d\'ascenseurs selon les besoins de chaque bâtiment.|نورّد ونصدّر أنظمة ومكوّنات المصاعد لمختلف متطلبات المباني.'],
['hat','Installation|Installation|التركيب','Professional elevator installation with attention to safety, precision and reliable operation.|Installation professionnelle axée sur la sécurité, la précision et la fiabilité.|تركيب احترافي للمصاعد بعناية بالسلامة والدقة والتشغيل الموثوق.'],
['srch','Maintenance|Maintenance|الصيانة','Preventive and corrective maintenance to keep elevator systems safe and reliable.|Maintenance préventive et corrective pour des ascenseurs sûrs et fiables.|صيانة وقائية وتصحيحية للحفاظ على أمان المصاعد وموثوقيتها.'],
['wr','Repair & Support|Réparation et assistance|الإصلاح والدعم','Technical assistance and repair services to help keep your elevator operating properly.|Assistance technique et réparation pour un fonctionnement optimal de votre ascenseur.|مساعدة فنية وخدمات إصلاح لإبقاء مصعدك يعمل بشكل سليم.']];
const W=[
['star','Quality|Qualité|الجودة','Reliable products and components.|Produits et composants fiables.|منتجات ومكوّنات موثوقة.'],
['shield','Safety|Sécurité|السلامة','Safety-focused elevator solutions.|Solutions d\'ascenseurs axées sur la sécurité.|حلول مصاعد تركّز على السلامة.'],
['hat','Professional Service|Service professionnel|خدمة احترافية','From supply to installation and maintenance.|De la fourniture à l\'installation et à la maintenance.|من التوريد إلى التركيب والصيانة.'],
['sup','Long-Term Support|Support à long terme|دعم طويل الأمد','Technical assistance and after-sales support.|Assistance technique et service après-vente.|مساعدة فنية ودعم ما بعد البيع.']];
const C=[
['wa','WhatsApp|WhatsApp|واتساب','Send us a message|Envoyez-nous un message|أرسل لنا رسالة','+213 XX XX XX XX','https://wa.me/213000000000'],
['ph','Phone|Téléphone|الهاتف','Call us|Appelez-nous|اتصل بنا','+213 XX XX XX XX','tel:+213000000000'],
['ml','Email|E-mail|البريد الإلكتروني','Send us an email|Envoyez-nous un e-mail|راسلنا بالبريد','contact@liftex-demo.com','mailto:contact@liftex-demo.com'],
['fb','Facebook|Facebook|فيسبوك','Visit our Facebook|Visitez notre Facebook|زوروا صفحتنا على فيسبوك','LIFTEX Elevators','https://www.facebook.com/']];
const T=(s,i)=>`data-t="${s}"`;
const ext=h=>h.startsWith('http')?' target="_blank" rel="noopener"':'';
const $=s=>document.getElementById(s);
$('nv').innerHTML=['home','elevators','parts','services','contact'].map((h,i)=>`<a href="#${h}" data-k="n${i}"></a>`).join('');
$('fn').innerHTML=$('nv').innerHTML;
$('eg').innerHTML=E.map((e,i)=>`<article class="card"><div class="ph g${i%4?i%4:0}${i%4==3?'x':''}">${svg(e[0])}</div><div class="cb"><h3 ${T(e[1])}></h3><p ${T(e[2])}></p><a class="lnk" href="#contact" data-k="vd"></a></div></article>`).join('');
$('pg').innerHTML=P.map((p,i)=>`<div class="pc"><div class="ph g${i%4==3?'3x':i%4}">${svg(p[0])}</div><h4 ${T(p[1])}></h4></div>`).join('').replace(/g3x/g,'g3x');
$('sg').innerHTML=S.map((s,i)=>`<article class="card"><div class="ph g${[2,0,1,3][i]==3?'3x':[2,0,1,3][i]}">${svg(s[0])}</div><div class="cb"><h3 ${T(s[1])}></h3><p ${T(s[2])}></p></div></article>`).join('');
$('wg').innerHTML=W.map(w=>`<div class="wy"><div class="ic">${svg(w[0])}</div><h3 ${T(w[1])}></h3><p ${T(w[2])}></p></div>`).join('');
$('cg').innerHTML=C.map(c=>`<a class="cl" href="${c[4]}"${ext(c[4])}>${svg(c[0])}<b ${T(c[1])}></b><small ${T(c[2])}></small><code>${c[3]}</code></a>`).join('');
$('fs').innerHTML=C.map(c=>`<a href="${c[4]}"${ext(c[4])} ${T(c[1])}></a>`).join('');
function setLang(i){
 const r=document.documentElement;r.lang=['en','fr','ar'][i];r.dir=i==2?'rtl':'ltr';
 document.querySelectorAll('[data-k]').forEach(e=>e.textContent=D[e.dataset.k].split('|')[i]);
 document.querySelectorAll('[data-t]').forEach(e=>e.textContent=e.dataset.t.split('|')[i]);
 document.querySelectorAll('.lg button').forEach(b=>b.classList.toggle('on',b.dataset.l==i));
 document.title='LIFTEX '+D.ep.split('|')[i];
 try{localStorage.setItem('lx',i)}catch(e){}
}
document.querySelectorAll('.lg button').forEach(b=>b.onclick=()=>setLang(+b.dataset.l));
$('bg').onclick=()=>$('nv').classList.toggle('open');
$('nv').onclick=e=>{if(e.target.tagName=='A')$('nv').classList.remove('open')};
let s=0;try{s=+localStorage.getItem('lx')||0}catch(e){}
setLang(s);
</script>
</body>
</html>
  
