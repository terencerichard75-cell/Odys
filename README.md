<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Terence Richard - Head of Revenue · Odys</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;1,300;1,400&family=Jost:wght@200;300;400;500&display=swap" rel="stylesheet">
<style>
:root{--cream:#F0F0EE;--cream-dark:#E4E4E2;--ink:#1A1714;--sand:#C9B99A;--sand-light:#D8D8D6;--terra:#8B6B4A;--white:#FAFAFA;--accent:#2D6A5A;--accent-light:#4a9e89;}
*{margin:0;padding:0;box-sizing:border-box;}html{scroll-behavior:smooth;}
body{background:var(--cream);color:var(--ink);font-family:'Jost',Georgia,sans-serif;font-weight:300;overflow-x:hidden;}
nav{position:fixed;top:0;left:0;right:0;z-index:100;padding:0 48px;height:64px;display:flex;align-items:center;justify-content:space-between;background:rgba(26,23,20,0.97);backdrop-filter:blur(12px);border-bottom:1px solid rgba(201,185,154,0.15);transition:border-color 0.4s,top 0.3s;}
nav.scrolled{border-bottom-color:rgba(201,185,154,0.4);}
.nav-logo{font-family:'Cormorant Garamond',Georgia,serif;font-size:15px;font-weight:400;letter-spacing:0.15em;text-transform:uppercase;color:#FDFAF5;text-decoration:none;}
.nav-links{display:flex;gap:36px;list-style:none;}
.nav-links a,.nav-btn{font-size:10px;font-weight:400;letter-spacing:0.18em;text-transform:uppercase;color:#FDFAF5;text-decoration:none;opacity:0.5;transition:opacity 0.3s;padding-bottom:3px;}
.nav-btn{background:none;border:none;cursor:pointer;font-family:'Jost',Georgia,sans-serif;}
.nav-btn:hover,.nav-links a:hover{opacity:1;}
.nav-btn.active{opacity:1;border-bottom:1px solid var(--sand);}
.nav-links a.active{opacity:1;border-bottom:1px solid var(--sand);}
.hamburger{display:none;flex-direction:column;justify-content:center;gap:5px;width:36px;height:36px;background:none;border:none;cursor:pointer;padding:4px;z-index:200;}
.hamburger span{display:block;width:22px;height:1.5px;background:#FDFAF5;transition:transform 0.3s,opacity 0.3s;transform-origin:center;}
.hamburger.open span:nth-child(1){transform:translateY(6.5px) rotate(45deg);}
.hamburger.open span:nth-child(2){opacity:0;}
.hamburger.open span:nth-child(3){transform:translateY(-6.5px) rotate(-45deg);}
.mobile-menu{display:none;position:fixed;top:64px;left:0;right:0;bottom:0;background:rgba(245,240,232,0.98);backdrop-filter:blur(16px);z-index:99;flex-direction:column;align-items:center;justify-content:center;gap:4px;}
.mobile-menu.open{display:flex;}
.mobile-menu a,.mobile-link{font-size:11px;font-weight:400;letter-spacing:0.26em;text-transform:uppercase;color:#1A1714;background:none;border:none;border-bottom:1px solid rgba(201,185,154,0.2);text-decoration:none;padding:18px 40px;opacity:0.6;transition:opacity 0.25s;width:260px;text-align:center;cursor:pointer;font-family:'Jost',Georgia,sans-serif;display:block;}
.mobile-menu a:last-child{border-bottom:none;}.mobile-menu a:hover,.mobile-menu a:active,.mobile-link:hover{opacity:1;}

/* HERO */
#hero{min-height:100vh;display:flex;flex-direction:column;justify-content:center;padding:120px 48px 80px;position:relative;overflow:hidden;}
.hero-bg-letter{position:absolute;top:50%;right:-30px;transform:translateY(-50%);font-family:'Cormorant Garamond',Georgia,serif;font-size:30vw;font-weight:300;color:transparent;-webkit-text-stroke:1px rgba(45,106,90,0.1);pointer-events:none;user-select:none;line-height:1;}
.hero-eyebrow{font-size:11px;font-weight:400;letter-spacing:0.22em;text-transform:uppercase;color:var(--accent);margin-bottom:32px;opacity:0;animation:fadeUp 0.8s 0.3s ease forwards;}
.hero-title{font-family:'Cormorant Garamond',Georgia,serif;font-size:clamp(38px,5.5vw,82px);font-weight:300;line-height:1.12;max-width:820px;opacity:0;animation:fadeUp 0.9s 0.5s ease forwards;}
.hero-title em{font-style:italic;color:var(--accent);}
.hero-sub{margin-top:40px;font-size:14px;font-weight:300;letter-spacing:0.04em;line-height:1.85;max-width:480px;opacity:0;animation:fadeUp 0.8s 0.8s ease forwards;color:rgba(26,23,20,0.7);}
.hero-scroll{position:absolute;bottom:48px;left:48px;display:flex;align-items:center;gap:16px;font-size:10px;letter-spacing:0.22em;text-transform:uppercase;color:var(--sand);opacity:0;animation:fadeIn 1s 1.4s ease forwards;}
.hero-scroll::before{content:'';display:block;width:40px;height:1px;background:var(--sand);}

/* SECTIONS */
section{padding:110px 48px;}
.s-num{font-family:'Cormorant Garamond',Georgia,serif;font-size:88px;font-weight:300;color:transparent;-webkit-text-stroke:1px rgba(45,106,90,0.18);line-height:1;margin-bottom:-16px;user-select:none;}
.s-label{font-size:10px;font-weight:400;letter-spacing:0.26em;text-transform:uppercase;color:var(--accent);margin-bottom:18px;}
.s-title{font-family:'Cormorant Garamond',Georgia,serif;font-size:clamp(30px,3.8vw,52px);font-weight:300;line-height:1.2;margin-bottom:16px;max-width:680px;}
.s-title em{font-style:italic;color:var(--accent);}
.s-divider{width:44px;height:1px;background:var(--accent-light);margin-bottom:48px;margin-top:8px;opacity:0.5;}
.reveal{opacity:0;transform:translateY(28px);transition:opacity 0.75s ease,transform 0.75s ease;}
.reveal.visible{opacity:1;transform:none;}

/* ABOUT */
#about{background:var(--cream);}
.about-body{max-width:820px;}
.about-quote{font-family:'Cormorant Garamond',Georgia,serif;font-size:22px;font-style:italic;font-weight:300;color:var(--accent);line-height:1.6;margin-top:8px;}
.about-p{font-size:15px;line-height:1.9;color:rgba(26,23,20,0.78);margin-bottom:28px;}

/* UNDERSTANDING */
#understanding{background:var(--white);}
.cards-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:3px;margin-top:56px;}
.card{background:var(--cream);padding:44px 36px;transition:background 0.35s;}
.card:hover{background:var(--cream-dark);}
.card-n{font-family:'Cormorant Garamond',Georgia,serif;font-size:44px;font-weight:300;color:rgba(45,106,90,0.2);margin-bottom:20px;line-height:1;}
.card-h{font-family:'Cormorant Garamond',Georgia,serif;font-size:21px;font-weight:400;line-height:1.35;margin-bottom:14px;}
.card-p{font-size:13.5px;line-height:1.9;color:rgba(26,23,20,0.72);}
.card-tag{display:inline-block;margin-top:18px;font-size:9.5px;letter-spacing:0.2em;text-transform:uppercase;color:var(--accent);border-bottom:1px solid rgba(45,106,90,0.25);padding-bottom:2px;}

/* CHALLENGES */
#challenges{background:var(--ink);color:var(--cream);}
#challenges .s-label{color:rgba(74,158,137,0.9);}
#challenges .s-title{color:var(--cream);}
#challenges .s-num{-webkit-text-stroke-color:rgba(74,158,137,0.08);}
#challenges .s-divider{background:rgba(74,158,137,0.35);}
.ch-list{display:flex;flex-direction:column;gap:2px;margin-top:52px;}
.ch-item{display:grid;grid-template-columns:72px 1fr 280px;align-items:center;gap:24px;padding:32px 36px;background:rgba(255,255,255,0.03);border-left:1px solid rgba(74,158,137,0.15);transition:background 0.35s,border-color 0.35s;}
.ch-item:hover{background:rgba(255,255,255,0.06);border-left-color:rgba(74,158,137,0.7);}
.ch-idx{font-family:'Cormorant Garamond',Georgia,serif;font-size:26px;font-weight:300;color:rgba(74,158,137,0.4);}
.ch-text{font-family:'Cormorant Garamond',Georgia,serif;font-size:21px;font-weight:300;line-height:1.45;color:var(--cream);}
.ch-note{font-size:11.5px;letter-spacing:0.06em;color:rgba(74,158,137,0.55);line-height:1.75;text-align:right;}
.ch-verdict{margin-top:52px;padding:44px;border:1px solid rgba(74,158,137,0.2);font-family:'Cormorant Garamond',Georgia,serif;font-size:24px;font-style:italic;font-weight:300;color:rgba(74,158,137,0.85);line-height:1.65;max-width:760px;}

/* OBJECTION */
#objection{background:var(--cream);}
.obj-grid{display:grid;grid-template-columns:1fr 1fr;gap:72px;align-items:start;margin-top:52px;}
.obj-left{background:var(--ink);color:var(--cream);padding:52px 44px;}
.obj-lbl{font-size:10px;letter-spacing:0.24em;text-transform:uppercase;color:rgba(74,158,137,0.8);margin-bottom:22px;}
.obj-quote{font-family:'Cormorant Garamond',Georgia,serif;font-size:26px;font-style:italic;font-weight:300;line-height:1.55;color:rgba(245,240,232,0.82);}
.resp-step{display:flex;gap:22px;padding:28px 0;border-bottom:1px solid rgba(45,106,90,0.18);}
.resp-step:last-child{border-bottom:none;}
.step-dot{width:30px;height:30px;border:1px solid rgba(45,106,90,0.4);display:flex;align-items:center;justify-content:center;font-family:'Cormorant Garamond',Georgia,serif;font-size:15px;font-weight:400;color:var(--accent);flex-shrink:0;margin-top:2px;}
.step-h{font-family:'Cormorant Garamond',Georgia,serif;font-size:17px;font-weight:500;margin-bottom:9px;}
.step-p{font-size:13.5px;line-height:1.9;color:rgba(26,23,20,0.72);}
.bridge{display:flex;flex-direction:column;align-items:center;gap:12px;margin-top:52px;padding:36px 32px;background:var(--cream-dark);}
.b-node{text-align:center;width:100%;max-width:520px;}
.b-lbl{font-size:9.5px;letter-spacing:0.2em;text-transform:uppercase;color:var(--accent);margin-bottom:10px;}
.b-val{font-family:'Cormorant Garamond',Georgia,serif;font-size:19px;font-weight:400;line-height:1.4;}
.b-sub{font-size:12px;color:rgba(26,23,20,0.55);margin-top:6px;line-height:1.6;}
.b-arrow{color:rgba(45,106,90,0.5);font-size:24px;flex-shrink:0;}

/* PREUVES */
#preuves{background:var(--white);}
.tabs-bar{display:flex;border-bottom:1px solid rgba(45,106,90,0.25);margin-top:44px;overflow-x:auto;}
@media(max-width:680px){.tabs-bar{display:grid;grid-template-columns:1fr 1fr;overflow-x:visible;border-bottom:none;gap:3px;}.tabs-bar .tab-btn{border:1px solid rgba(45,106,90,0.25);border-bottom:2px solid transparent;margin-bottom:0;padding:12px 8px;}.tabs-bar .tab-btn.active{border-color:var(--accent);color:var(--ink);}}
.tab-btn{padding:14px 26px;font-size:10.5px;font-weight:400;letter-spacing:0.15em;text-transform:uppercase;color:rgba(26,23,20,0.42);background:none;border:none;border-bottom:2px solid transparent;cursor:pointer;transition:color 0.3s,border-color 0.3s;white-space:nowrap;font-family:'Jost',Georgia,sans-serif;margin-bottom:-1px;}
.tab-btn:hover{color:var(--ink);}.tab-btn.active{color:var(--ink);border-bottom-color:var(--accent);}
.tab-pane{display:none;padding-top:52px;}.tab-pane.active{display:block;}
.proof-grid{display:grid;grid-template-columns:1fr 1fr;gap:72px;align-items:start;}
.proof-ch-lbl{font-size:10px;letter-spacing:0.22em;text-transform:uppercase;color:var(--accent);margin-bottom:14px;}
.proof-ch-box{padding:36px 32px;background:var(--cream);border-left:3px solid rgba(45,106,90,0.35);font-family:'Cormorant Garamond',Georgia,serif;font-size:21px;font-weight:300;line-height:1.5;}
.proof-ev-lbl{font-size:10px;letter-spacing:0.22em;text-transform:uppercase;color:var(--accent);margin-bottom:18px;}
.proof-ev-p{font-size:14px;line-height:1.9;color:rgba(26,23,20,0.78);}
.kpis{display:flex;gap:28px;margin-top:28px;padding-top:28px;border-top:1px solid rgba(45,106,90,0.18);flex-wrap:wrap;}
.kpi-val{font-family:'Cormorant Garamond',Georgia,serif;font-size:38px;font-weight:300;color:var(--accent);line-height:1;margin-bottom:5px;}
.kpi-lbl{font-size:10.5px;letter-spacing:0.08em;color:rgba(26,23,20,0.48);line-height:1.45;}

/* JOURS */
#jours{background:var(--cream);}
.phases{display:grid;grid-template-columns:repeat(3,1fr);gap:3px;margin-top:52px;}
.phase{padding:44px 36px;background:var(--white);transition:background 0.35s;position:relative;overflow:hidden;}
.phase:hover{background:var(--cream-dark);}
.phase-period{font-size:10px;letter-spacing:0.22em;text-transform:uppercase;color:var(--accent);margin-bottom:10px;}
.phase-h{font-family:'Cormorant Garamond',Georgia,serif;font-size:24px;font-weight:400;line-height:1.3;margin-bottom:28px;}
.phase-items{list-style:none;display:flex;flex-direction:column;gap:13px;}
.phase-item{font-size:13px;line-height:1.75;color:rgba(26,23,20,0.72);padding-left:14px;position:relative;}
.phase-item::before{content:'-';position:absolute;left:0;color:rgba(45,106,90,0.5);font-size:10px;top:1px;}
.phase-accent{position:absolute;bottom:0;left:0;right:0;height:2px;background:transparent;transition:background 0.4s;}
.phase:hover .phase-accent{background:rgba(45,106,90,0.4);}

/* CTA */
#cta{background:var(--ink);color:var(--cream);text-align:center;padding:110px 48px;}
#cta .s-label{color:rgba(74,158,137,0.9);}
#cta .s-num{-webkit-text-stroke-color:rgba(74,158,137,0.06);}
.cta-title{font-family:'Cormorant Garamond',Georgia,serif;font-size:clamp(34px,4.5vw,62px);font-weight:300;line-height:1.22;max-width:680px;margin:0 auto 28px;color:#F5F5F5;}
.cta-title em{font-style:italic;color:rgba(74,158,137,0.85);}
.cta-sub{font-size:14.5px;line-height:1.85;color:rgba(245,240,232,0.55);max-width:540px;margin:0 auto 52px;}
.cta-btns{display:flex;gap:18px;justify-content:center;flex-wrap:wrap;}
.btn-p{padding:15px 38px;background:#F0F0EE;color:#1A1714;font-size:10.5px;letter-spacing:0.2em;text-transform:uppercase;text-decoration:none;font-family:'Jost',Georgia,sans-serif;font-weight:400;transition:background 0.3s;border:none;cursor:pointer;}
.btn-p:hover{background:var(--sand-light);}
.btn-s{padding:15px 38px;border:1px solid rgba(74,158,137,0.3);color:rgba(245,240,232,0.65);font-size:10.5px;letter-spacing:0.2em;text-transform:uppercase;text-decoration:none;font-family:'Jost',Georgia,sans-serif;font-weight:400;transition:border-color 0.3s,color 0.3s;background:none;cursor:pointer;}
.btn-s:hover{border-color:rgba(74,158,137,0.7);color:var(--cream);}

footer{background:var(--ink);border-top:1px solid rgba(201,185,154,0.1);padding:28px 48px;display:flex;align-items:center;justify-content:space-between;}
.ft-name{font-family:'Cormorant Garamond',Georgia,serif;font-size:12px;letter-spacing:0.1em;color:rgba(255,255,255,0.5);}
.ft-note{font-size:10.5px;letter-spacing:0.1em;color:rgba(255,255,255,0.3);}

@keyframes fadeUp{from{opacity:0;transform:translateY(24px);}to{opacity:1;transform:translateY(0);}}
@keyframes fadeIn{from{opacity:0;}to{opacity:1;}}

@media(max-width:960px){.cards-grid{grid-template-columns:1fr 1fr;}.phases{grid-template-columns:1fr;}.ch-item{grid-template-columns:56px 1fr;}.ch-note{display:none;}.obj-grid{grid-template-columns:1fr;gap:40px;}.proof-grid{grid-template-columns:1fr;gap:36px;}}
@media(max-width:680px){nav{padding:0 20px;}.nav-links{display:none;}.hamburger{display:flex;}section{padding:72px 20px;}#hero{padding:96px 20px 56px;}.cards-grid{grid-template-columns:1fr;}footer{flex-direction:column;gap:10px;text-align:center;}.cta-btns{flex-direction:column;align-items:center;}}
</style>
<script>
function showTab(idx){
  document.querySelectorAll('.tab-btn').forEach(function(b,i){b.classList.toggle('active',i===idx);});
  document.querySelectorAll('.tab-pane').forEach(function(p,i){p.classList.toggle('active',i===idx);});
}
</script>
</head>
<body>

<nav id="navbar">
  <a href="https://odys.travel/" class="nav-logo" target="_blank" rel="noopener">ODYS</a>
  <ul class="nav-links">
    <li><button class="nav-btn" onclick="scroll2('about')">Profil</button></li>
    <li><button class="nav-btn" onclick="scroll2('understanding')">Compréhension</button></li>
    <li><button class="nav-btn" onclick="scroll2('challenges')">Défis</button></li>
    <li><button class="nav-btn" onclick="scroll2('objection')">Positionnement</button></li>
    <li><button class="nav-btn" onclick="scroll2('preuves')">Preuves</button></li>
    <li><button class="nav-btn" onclick="scroll2('jours')">90 Jours</button></li>
    <li><button class="nav-btn" onclick="scroll2('cta')">Contact</button></li>
  </ul>
  <button class="hamburger" id="hamburger" aria-label="Menu" onclick="toggleMenu()"><span></span><span></span><span></span></button>
</nav>

<div class="mobile-menu" id="mobileMenu">
  <button class="mobile-link" onclick="closeMenu();scroll2('about')">Profil</button>
  <button class="mobile-link" onclick="closeMenu();scroll2('understanding')">Compréhension</button>
  <button class="mobile-link" onclick="closeMenu();scroll2('challenges')">Défis</button>
  <button class="mobile-link" onclick="closeMenu();scroll2('objection')">Positionnement</button>
  <button class="mobile-link" onclick="closeMenu();scroll2('preuves')">Preuves</button>
  <button class="mobile-link" onclick="closeMenu();scroll2('jours')">90 Jours</button>
  <button class="mobile-link" onclick="closeMenu();scroll2('cta')">Contact</button>
</div>

<!-- HERO -->
<section id="hero">
  <div class="hero-bg-letter" aria-hidden="true">O</div>
  <p class="hero-eyebrow">Terence Richard &nbsp;&middot;&nbsp; Candidature Head of Revenue &nbsp;&middot;&nbsp; Odys</p>
  <h1 class="hero-title">Odys a construit la base produit.<br>Il faut maintenant un moteur<br>pour <em>transformer cette base en revenu.</em></h1>
  <p class="hero-sub">Cette page présente ma compréhension d'Odys, des enjeux du poste Head of Revenue, et les raisons concrètes pour lesquelles mon parcours est aligné avec cette phase d'accélération.</p>
  <div class="hero-scroll">Candidature spontanée · 2026</div>
</section>

<!-- ABOUT -->
<section id="about">
  <div class="reveal visible">
    <p class="s-num">00</p>
    <p class="s-label">Qui je suis</p>
    <h2 class="s-title">Vingt ans à construire<br><em>des moteurs de croissance</em></h2>
    <div class="s-divider"></div>
  </div>
  <div class="about-body reveal visible">
    <p class="about-p">Mon parcours se situe à l'intersection de la stratégie commerciale, du développement de réseaux et de l'exécution terrain. J'ai passé vingt ans à construire des systèmes commerciaux où la croissance ne dépend pas d'une seule personne — mais d'un écosystème de partenaires, de processus et d'outils bien posés.</p>
    <p class="about-p">Chez Exta Archis, j'ai construit de zéro un réseau national de plus de 700 architectes et décorateurs d'intérieur — onboarding, formation, outillage CRM, activation commerciale. Ce que j'ai appris : un réseau ne performe que si ses membres comprennent le produit, font confiance au modèle, et savent comment le valoriser auprès de leurs clients. C'est exactement la dynamique d'un réseau de DMC.</p>
    <p class="about-p">Chez BCD Travel et CWT, j'ai hérité d'équipes et de P&L sous pression, coordonné des opérations commerciales sur 13 pays, et livré de la croissance sans disruption. J'ai appris à entrer dans une organisation structurée, à lire vite les dynamiques humaines, à gagner la confiance — et à faire avancer les choses sans casser ce qui fonctionne.</p>
    <p class="about-p">Chez Workforce Logiq, j'ai construit le go-to-market France from scratch : zéro présence, zéro notoriété, premier contrat majeur en 18 mois. C'est exactement le muscle qu'Odys a besoin d'activer pour structurer son acquisition et ses nouveaux marchés.</p>
    <p class="about-quote">&laquo;&thinsp;Je n'arrive pas avec un agenda de transformation. J'arrive avec l'expérience pour savoir ce qui doit être protégé, le jugement pour savoir où pousser, et la discipline pour exécuter de façon cohérente dans la durée.&thinsp;&raquo;</p>
  </div>
</section>

<!-- UNDERSTANDING -->
<section id="understanding">
  <div class="reveal visible">
    <p class="s-num">01</p>
    <p class="s-label">Ce que j'ai compris d'Odys</p>
    <h2 class="s-title">Une solution née du terrain,<br><em>entrée dans une nouvelle phase</em></h2>
    <div class="s-divider"></div>
  </div>
  <div class="cards-grid reveal visible">
    <div class="card">
      <div class="card-n">01</div>
      <h3 class="card-h">Un produit construit de l'intérieur, pas du dessus.</h3>
      <p class="card-p">Odys est née des besoins réels des fondatrices pour leur propre agence réceptive. Ce n'est pas une solution tech imposée au secteur — c'est une plateforme pensée par et pour des acteurs DMC. Cette légitimité terrain est un avantage compétitif rare, et un argument de vente puissant à activer.</p>
      <span class="card-tag">Produit & crédibilité</span>
    </div>
    <div class="card">
      <div class="card-n">02</div>
      <h3 class="card-h">Intégration Evaneos : l'agilité startup avec le socle d'un groupe établi.</h3>
      <p class="card-p">Depuis 2025, Odys s'industrialise au sein d'Evaneos. Cela signifie des ressources, une marque reconnue dans le voyage responsable, et un accès potentiel à un écosystème d'agences partenaires. La phase d'accélération sur 12-24 mois n'est pas un pari — c'est une trajectoire tracée.</p>
      <span class="card-tag">Contexte stratégique</span>
    </div>
    <div class="card">
      <div class="card-n">03</div>
      <h3 class="card-h">Un marché mondial, fragmenté, encore sans leader SaaS clair.</h3>
      <p class="card-p">Les DMC sont des acteurs locaux par nature — culturellement, linguistiquement, opérationnellement. Odys vise à devenir la solution de référence mondiale pour ce segment. C'est une fenêtre d'opportunité rare, avec un ICP bien défini et une proposition de valeur différenciée à structurer et à scaler.</p>
      <span class="card-tag">Opportunité de marché</span>
    </div>
  </div>
</section>

<!-- CHALLENGES -->
<section id="challenges">
  <div class="reveal visible">
    <p class="s-num">02</p>
    <p class="s-label">Ce que j'ai compris du poste</p>
    <h2 class="s-title">Les quatre chantiers<br><em>du Head of Revenue</em></h2>
    <div class="s-divider"></div>
  </div>
  <div class="ch-list reveal visible">
    <div class="ch-item">
      <div class="ch-idx">01</div>
      <div class="ch-text">Construire et déployer la stratégie go-to-market : ICP, positionnement, pricing, canaux d'acquisition — de zéro à scalable.</div>
      <div class="ch-note">Stratégie GTM<br>Acquisition & funnel</div>
    </div>
    <div class="ch-item">
      <div class="ch-idx">02</div>
      <div class="ch-text">Être dans l'action quotidienne — démos, closing, feedback terrain — tout en posant les fondations sales durables.</div>
      <div class="ch-note">Sales & business dev<br>MRR · CAC · Conversion</div>
    </div>
    <div class="ch-item">
      <div class="ch-idx">03</div>
      <div class="ch-text">Structurer le Customer Success pour accompagner la montée en charge — onboarding, adoption, rétention, expansion.</div>
      <div class="ch-note">CS scalable<br>Rétention & expansion</div>
    </div>
    <div class="ch-item">
      <div class="ch-idx">04</div>
      <div class="ch-text">Construire le pilotage revenue de bout en bout — dashboards, process, outils — et préparer l'organisation pour la suite.</div>
      <div class="ch-note">Structuration & reporting<br>Préparation à la croissance</div>
    </div>
  </div>
  <blockquote class="ch-verdict reveal visible">&laquo;&thinsp;Ce que vous cherchez : quelqu'un qui jongle naturellement entre stratégie et exécution, qui teste, apprend, ajuste — et qui fait avancer les sujets même au-delà de son scope quand c'est nécessaire.&thinsp;&raquo;</blockquote>
</section>

<!-- OBJECTION / POSITIONNEMENT -->
<section id="objection">
  <div class="reveal visible">
    <p class="s-num">03</p>
    <p class="s-label">La question légitime</p>
    <h2 class="s-title">Pourquoi moi<br><em>sans background SaaS pur ?</em></h2>
    <div class="s-divider"></div>
  </div>
  <div class="obj-grid reveal visible">
    <div class="obj-left">
      <p class="obj-lbl">L'objection</p>
      <p class="obj-quote">&laquo;&thinsp;Le profil idéal a entre 6 et 10 ans d'expérience en SaaS B2B, en phase d'accélération de 1 à 5M€ ARR. Terence vient du voyage et du B2B services — est-ce vraiment aligné ?&thinsp;&raquo;</p>
    </div>
    <div>
      <div class="resp-step">
        <div class="step-dot">I</div>
        <div>
          <h4 class="step-h">Reconnaître</h4>
          <p class="step-p">Je n'ai pas piloté un ARR SaaS de 1 à 5M€ en tant que Head of Revenue. C'est une observation juste et je ne vais pas l'esquiver.</p>
        </div>
      </div>
      <div class="resp-step">
        <div class="step-dot">II</div>
        <div>
          <h4 class="step-h">Le contexte Odys change l'équation</h4>
          <p class="step-p">Odys ne vend pas du SaaS générique — elle vend une solution verticale à des DMC, des acteurs du voyage réceptif avec des codes culturels, opérationnels et relationnels très spécifiques. Mon expérience du secteur voyage (BCD Travel, CWT, Exta Archis) n'est pas adjacente au sujet — elle est au cœur du profil client cible. Comprendre un DMC depuis l'intérieur, c'est un avantage compétitif réel face à un profil SaaS pur qui devra tout apprendre du marché.</p>
        </div>
      </div>
      <div class="resp-step">
        <div class="step-dot">III</div>
        <div>
          <h4 class="step-h">Les compétences revenue sont là</h4>
          <p class="step-p">J'ai construit des go-to-market from scratch, géré des P&L, piloté des équipes sales, onboardé des réseaux de partenaires à l'échelle. Les outils changent, les principes restent. Ce que j'apporte : la capacité à structurer, exécuter et itérer vite — dans un environnement que je connais mieux que la plupart.</p>
        </div>
      </div>
    </div>
  </div>
  <div class="bridge reveal visible">
    <div class="b-node">
      <div class="b-lbl">Ce que je connais</div>
      <div class="b-val">Le marché du voyage, les acteurs locaux, les dynamiques DMC</div>
      <div class="b-sub">Compréhension terrain immédiate du client cible d'Odys</div>
    </div>
    <div class="b-arrow">&#8595;</div>
    <div class="b-node">
      <div class="b-lbl">Ce que j'ai prouvé</div>
      <div class="b-val">Construction GTM, activation réseau, pilotage commercial multi-pays</div>
      <div class="b-sub">Expérience directement transférable à la phase d'accélération</div>
    </div>
    <div class="b-arrow">&#8595;</div>
    <div class="b-node">
      <div class="b-lbl">Ce que j'apporte</div>
      <div class="b-val">Crédibilité terrain + rigueur structurelle + exécution autonome</div>
      <div class="b-sub">Le profil hybride rare pour un poste à la croisée du produit et du marché</div>
    </div>
  </div>
</section>

<!-- PREUVES -->
<section id="preuves">
  <div class="reveal visible">
    <p class="s-num">04</p>
    <p class="s-label">Aligné sur vos défis spécifiques</p>
    <h2 class="s-title">Quatre preuves,<br><em>pas des promesses</em></h2>
    <div class="s-divider"></div>
  </div>
  <div class="reveal visible">
    <div class="tabs-bar">
      <button class="tab-btn active" onclick="showTab(0)">GTM from scratch</button>
      <button class="tab-btn" onclick="showTab(1)">Réseau & onboarding</button>
      <button class="tab-btn" onclick="showTab(2)">Organisation matrix</button>
      <button class="tab-btn" onclick="showTab(3)">Stabilité équipe</button>
    </div>

    <div class="tab-pane active" id="tp0">
      <div class="proof-grid">
        <div>
          <p class="proof-ch-lbl">Votre défi</p>
          <div class="proof-ch-box">Construire la stratégie go-to-market d'Odys — ICP, positionnement, canaux d'acquisition — dans un marché international fragmenté, avec un budget contraint et sans playbook existant.</div>
        </div>
        <div>
          <p class="proof-ev-lbl">Ma preuve</p>
          <p class="proof-ev-p">Chez Workforce Logiq, j'ai conduit le lancement de l'activité en France sans présence préalable, sans notoriété, sans équipe constituée. J'ai défini les cibles prioritaires, construit le discours commercial, identifié les bons points d'entrée dans les organisations — et signé un premier contrat majeur en 18 mois sur une base zéro.<br><br>C'est exactement le muscle qu'Odys a besoin d'activer : partir d'une base produit solide, identifier les ICP les plus accessibles, et convertir les premiers clients en références scalables.</p>
          <div class="kpis">
            <div><div class="kpi-val">&euro;1M</div><div class="kpi-lbl">Contrat signé<br>sur base zéro</div></div>
            <div><div class="kpi-val">18</div><div class="kpi-lbl">Mois pour le<br>premier grand compte</div></div>
            <div><div class="kpi-val">0</div><div class="kpi-lbl">Notoriété<br>au démarrage</div></div>
          </div>
        </div>
      </div>
    </div>

    <div class="tab-pane" id="tp1">
      <div class="proof-grid">
        <div>
          <p class="proof-ch-lbl">Votre défi</p>
          <div class="proof-ch-box">Onboarder, activer et retenir des DMC aux cultures et maturités très variées. Construire un Customer Success scalable qui accompagne l'adoption produit et génère de l'expansion.</div>
        </div>
        <div>
          <p class="proof-ev-lbl">Ma preuve</p>
          <p class="proof-ev-p">Chez Exta Archis, j'ai onboardé et structuré un réseau de plus de 700 architectes et décorateurs d'intérieur — des professionnels indépendants, aux cultures et maturités numériques très variées, qui n'avaient jamais travaillé dans un écosystème de marque structuré.<br><br>J'ai mis en place des outils, des frameworks projets et un suivi CRM pour les aider à intégrer les marques dans leurs projets de façon systématique. Ce que j'ai appris : un réseau performe uniquement quand ses membres comprennent le produit, font confiance au modèle, et savent comment le valoriser. C'est exactement la dynamique d'un CS DMC.</p>
          <div class="kpis">
            <div><div class="kpi-val">700+</div><div class="kpi-lbl">Professionnels<br>onboardés</div></div>
            <div><div class="kpi-val">3x</div><div class="kpi-lbl">Croissance<br>du revenu</div></div>
          </div>
        </div>
      </div>
    </div>

    <div class="tab-pane" id="tp2">
      <div class="proof-grid">
        <div>
          <p class="proof-ch-lbl">Votre défi</p>
          <div class="proof-ch-box">Travailler en lien direct avec Alexia, en coordination étroite avec les équipes Sales, Product, Tech et les parties prenantes Evaneos — une organisation hybride startup/groupe, multi-culturelle, internationale.</div>
        </div>
        <div>
          <p class="proof-ev-lbl">Ma preuve</p>
          <p class="proof-ev-p">Chez CWT, j'ai géré un compte multinational sur 13 pays avec 12 collaborateurs, en coordonnant des fonctions globales, des opérations locales et des parties prenantes exécutives simultanément. Structures matricielles, reportings multi-niveaux, alignement global-local : c'est l'environnement dans lequel je performe — pas une complexité que je subis.</p>
          <div class="kpis">
            <div><div class="kpi-val">13</div><div class="kpi-lbl">Pays<br>coordonnés</div></div>
            <div><div class="kpi-val">12</div><div class="kpi-lbl">Collaborateurs<br>managés</div></div>
            <div><div class="kpi-val">15+</div><div class="kpi-lbl">Ans en org.<br>matricielle</div></div>
          </div>
        </div>
      </div>
    </div>

    <div class="tab-pane" id="tp3">
      <div class="proof-grid">
        <div>
          <p class="proof-ch-lbl">Votre défi</p>
          <div class="proof-ch-box">Rejoindre une équipe soudée en mode startup, à un moment charnière — et créer la confiance rapidement sans déstabiliser ce qui fonctionne déjà.</div>
        </div>
        <div>
          <p class="proof-ev-lbl">Ma preuve</p>
          <p class="proof-ev-p">Chez BCD Travel, j'ai hérité d'une équipe de 10 personnes et d'un P&L sous forte pression budgétaire. Ma première décision n'a pas été de reconstruire — c'était d'écouter, de clarifier les priorités, et de laisser l'équipe comprendre où nous allions ensemble. L'équipe elle-même est devenue l'actif. Les clients sont restés parce que les personnes sont restées.</p>
          <div class="kpis">
            <div><div class="kpi-val">98%</div><div class="kpi-lbl">Taux de rétention<br>clients</div></div>
            <div><div class="kpi-val">+25%</div><div class="kpi-lbl">Croissance<br>du revenu</div></div>
            <div><div class="kpi-val">0</div><div class="kpi-lbl">Départs<br>volontaires</div></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- 90 JOURS -->
<section id="jours">
  <div class="reveal visible">
    <p class="s-num">05</p>
    <p class="s-label">Un plan concret, pas une promesse</p>
    <h2 class="s-title">Les premiers<br><em>90 jours</em></h2>
    <div class="s-divider"></div>
  </div>
  <div class="phases reveal visible">
    <div class="phase">
      <div class="phase-period">Jours 0 – 30</div>
      <h3 class="phase-h">Comprendre avant d'agir</h3>
      <ul class="phase-items">
        <li class="phase-item">Immersion produit complète — comprendre Odys comme un DMC le vivrait</li>
        <li class="phase-item">Entretiens avec les premiers clients : ce qui les a convaincus, leurs frictions, leur usage réel</li>
        <li class="phase-item">Cartographie du funnel existant : lead sources, conversion, churn, expansion</li>
        <li class="phase-item">Alignement avec Alexia sur les priorités revenue des 12 prochains mois</li>
      </ul>
      <div class="phase-accent"></div>
    </div>
    <div class="phase">
      <div class="phase-period">Jours 30 – 60</div>
      <h3 class="phase-h">Poser les fondations</h3>
      <ul class="phase-items">
        <li class="phase-item">Définir l'ICP prioritaire et le positionnement commercial par segment</li>
        <li class="phase-item">Construire le playbook sales : qualification, démo, objections, closing</li>
        <li class="phase-item">Premiers tests d'acquisition outbound sur des marchés ciblés</li>
        <li class="phase-item">Structurer l'onboarding client pour réduire le time-to-value</li>
      </ul>
      <div class="phase-accent"></div>
    </div>
    <div class="phase">
      <div class="phase-period">Jours 60 – 90</div>
      <h3 class="phase-h">Activer la croissance</h3>
      <ul class="phase-items">
        <li class="phase-item">Présenter le plan revenue 2026–2027 à l'équipe et aux parties prenantes Evaneos</li>
        <li class="phase-item">CRM, dashboards et reporting MRR/CAC opérationnels</li>
        <li class="phase-item">Premiers quick wins mesurables — nouveaux clients signés ou pipeline qualifié</li>
        <li class="phase-item">Recommandation sur les recrutements sales et CS à venir</li>
      </ul>
      <div class="phase-accent"></div>
    </div>
  </div>
</section>

<!-- CTA -->
<section id="cta">
  <div class="reveal visible">
    <p class="s-num">06</p>
    <p class="s-label">Continuons la conversation</p>
    <h2 class="cta-title">Odys a construit quelque chose de rare.<br><em>Il est temps de le faire savoir</em> — au bon rythme, avec la bonne méthode.</h2>
    <p class="cta-sub">Je suis convaincu que la combinaison d'une connaissance terrain du secteur voyage et d'une expérience éprouvée en construction commerciale est exactement ce dont Odys a besoin à ce stade. J'aimerais en discuter.</p>
    <div class="cta-btns">
      <button class="btn-p" onclick="window.open('https://linkedin.com/in/terencerichard','_blank')">LinkedIn</button>
      <button class="btn-p" onclick="window.open('https://drive.google.com/file/d/1j4gC4lHRhNJtjueHh_Ahb4JmMIsaVaBt/view?usp=sharing','_blank')">CV</button>
    </div>
    <p style="margin-top:52px;font-family:'Cormorant Garamond',Georgia,serif;font-size:24px;font-style:italic;font-weight:300;color:rgba(245,240,232,0.55);line-height:1.7;max-width:620px;margin-left:auto;margin-right:auto;">&laquo;&thinsp;Choisir le bon pot, préparer le bon sol, et créer les conditions pour que quelque chose grandisse vraiment — c'est ce qui me drive profondément.&thinsp;&raquo;<br><span style="display:block;margin-top:14px;font-family:'Jost',sans-serif;font-size:12px;letter-spacing:0.22em;text-transform:uppercase;font-style:normal;color:rgba(245,240,232,0.35);">Terence Richard</span><span style="display:block;margin-top:10px;font-family:'Jost',sans-serif;font-size:14.5px;font-style:normal;color:rgba(245,240,232,0.45);letter-spacing:0.08em;"><span>terence.richard75</span><span>&#64;</span><span>gmail.com</span> &nbsp;&middot;&nbsp; +33 6 58 84 10 85</span></p>
  </div>
</section>

<footer>
  <span class="ft-name">Terence Richard — Candidature Head of Revenue · Odys</span>
  <span class="ft-note">Préparé dans le cadre du processus de recrutement Odys · 2026</span>
</footer>

<script>
var navbar=document.getElementById('navbar');
window.addEventListener('scroll',function(){navbar.classList.toggle('scrolled',window.scrollY>40);});

function scroll2(id){document.getElementById(id).scrollIntoView({behavior:'smooth'});}
function toggleMenu(){
  document.getElementById('hamburger').classList.toggle('open');
  document.getElementById('mobileMenu').classList.toggle('open');
  document.body.style.overflow=document.getElementById('mobileMenu').classList.contains('open')?'hidden':'';
}
function closeMenu(){
  document.getElementById('hamburger').classList.remove('open');
  document.getElementById('mobileMenu').classList.remove('open');
  document.body.style.overflow='';
}

// Reveal on scroll
if('IntersectionObserver' in window){
  var obs=new IntersectionObserver(function(entries){
    entries.forEach(function(e){if(e.isIntersecting)e.target.classList.add('visible');});
  },{threshold:0.15});
  document.querySelectorAll('.reveal').forEach(function(el){obs.observe(el);});
}
</script>
</body>
</html>
