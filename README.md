<!DOCTYPE html><html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>LES ÎLES AGENCY — Boutique officielle</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root{
      --rouge:#8B0000;      /* rouge profond */
      --rouge-fonce:#5d0000;/* dégradé bas */
      --doré:#d4af37;       /* or élégant */
      --texte:#ffffff;
      --noir:#0b0b0b;
    }
    *{box-sizing:border-box}
    body{
      margin:0; font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif; color:var(--texte); background:linear-gradient(180deg,var(--rouge),var(--rouge-fonce));
      background-attachment:fixed; min-height:100vh;
    }
    .wrap{max-width:680px; margin:0 auto;}
    /* Barre de nav mobile */
    header{position:sticky; top:0; z-index:50; backdrop-filter:saturate(140%) blur(6px); background:rgba(10,10,10,.35); border-bottom:1px solid rgba(212,175,55,.25)}
    .nav{display:flex; align-items:center; justify-content:space-between; padding:12px 16px}
    .brand{display:flex; align-items:center; gap:10px}
    .logo{width:34px; height:34px; border:2px solid var(--doré); border-radius:50%; display:grid; place-items:center; color:var(--doré); font-weight:700; font-family:"Playfair Display",serif}
    .brand-title{font-family:"Playfair Display",serif; font-weight:700; letter-spacing:.5px}
    .nav a{color:var(--texte); text-decoration:none; font-size:14px}
    .menu{display:flex; gap:14px}/* Hero */
.hero{padding:38px 18px 24px; text-align:center; background:radial-gradient(1200px 400px at 50% -200px, rgba(212,175,55,.18), transparent 60%)}
.slogan{font-family:"Playfair Display",serif; font-size:28px; line-height:1.25; margin:10px 0 16px}
.cta{display:inline-block; background:linear-gradient(180deg,#f2d870,var(--doré)); color:#331b00; padding:14px 18px; border-radius:12px; font-weight:700; text-decoration:none; box-shadow:0 4px 18px rgba(212,175,55,.35); border:1px solid #b89221}
.note{opacity:.9; font-size:13px; margin-top:10px}

/* Section titres */
section{padding:20px 16px}
h2{font-family:"Playfair Display",serif; font-weight:700; margin:0 0 12px; color:var(--doré)}
p.lead{opacity:.95; margin:0 0 14px}

/* Carte produit */
.grid{display:grid; gap:14px}
.card{background:rgba(0,0,0,.25); border:1px solid rgba(212,175,55,.2); border-radius:16px; padding:14px; display:grid; grid-template-columns:92px 1fr; gap:12px}
.card img{width:92px; height:92px; object-fit:cover; border-radius:12px; border:1px solid rgba(212,175,55,.35)}
.card h3{margin:0 0 6px; font-size:18px; font-family:"Playfair Display",serif}
.price{color:var(--doré); font-weight:700; margin:4px 0 10px}
.btn{display:inline-block; background:transparent; color:var(--doré); border:1px solid var(--doré); padding:10px 12px; border-radius:10px; text-decoration:none; font-weight:600}
.btn:hover{background:rgba(212,175,55,.12)}
.btn.gold{background:linear-gradient(180deg,#f7e598,var(--doré)); color:#2a1900; border:none}

/* Flocage perso */
.panel{background:rgba(0,0,0,.28); border:1px solid rgba(212,175,55,.25); border-radius:16px; padding:16px}

/* Contact */
.contact-box{display:grid; gap:10px; background:rgba(0,0,0,.22); border:1px solid rgba(212,175,55,.2); border-radius:16px; padding:16px}
.contact-box a{color:var(--doré)}

/* Footer */
footer{padding:28px 16px 60px; text-align:center; color:#f7f3e4; opacity:.9}
footer small{display:block; margin-top:6px}

/* Motif discret d’îles en fond */
body::before{content:""; position:fixed; inset:0; pointer-events:none; background:url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 200 200" opacity="0.08"><defs><linearGradient id="g" x1="0" y1="0" x2="1" y2="1"><stop stop-color="%23d4af37" offset="0"/><stop stop-color="%23d4af37" stop-opacity="0.2" offset="1"/></linearGradient></defs><g fill="url(%23g)"><path d="M28 54c10-18 32-14 44-7 13 8 15 24 2 33-12 8-36 9-44-2-5-6-4-15-2-24z"/><circle cx="160" cy="60" r="10"/><circle cx="170" cy="72" r="4"/><circle cx="152" cy="78" r="3"/></g></svg>') repeat; background-size:280px 220px}

/* Petits écrans extra */
@media(min-width:560px){ .card{grid-template-columns:120px 1fr} .card img{width:120px;height:120px} }

  </style>
</head>
<body>
  <header>
    <div class="wrap nav">
      <div class="brand">
        <div class="logo">Î</div>
        <div class="brand-title">LES ÎLES AGENCY</div>
      </div>
      <nav class="menu">
        <a href="#boutique">Boutique</a>
        <a href="#apropos">À propos</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>  <main class="wrap">
    <section class="hero">
      <h1 class="slogan">La fierté des îles, l’élégance à ton image.</h1>
      <a class="cta" href="#boutique">Commander maintenant</a>
      <div class="note">Paiement carte & PayPal • Livraison à domicile</div>
    </section><section id="nouveautes">
  <h2>Édition limitée · Nouveautés</h2>
  <p class="lead">Pièces phares signées <strong>LES ÎLES AGENCY</strong> — flocage doré premium, coupe confortable, style assuré.</p>
</section>

<section id="boutique">
  <h2>Boutique</h2>
  <div class="grid">
    <!-- Tee-shirt -->
    <article class="card">
      <img src="https://via.placeholder.com/600x600/101010/ffffff?text=Tee-shirt+Les+%C3%8Eles+Agency" alt="Tee-shirt Les ÎLES AGENCY (avant/dos)"/>
      <div>
        <h3>Tee-shirt Les ÎLES AGENCY</h3>
        <div class="price">12,99 €</div>
        <p class="lead">Logo doré côté cœur · Grand logo & message au dos · Noir / Blanc / Rouge / Bleu · Tailles S–XXL</p>
        <a class="btn gold" href="#" data-produit="Tee-shirt Les ÎLES AGENCY" data-prix="12,99 €" onclick="return precommande(this)">Précommander maintenant</a>
      </div>
    </article>
    <!-- Sweat-shirt -->
    <article class="card">
      <img src="https://via.placeholder.com/600x600/101010/ffffff?text=Sweat+%C3%A0+capuche+Les+%C3%8Eles+Agency" alt="Sweat Les ÎLES AGENCY (avant/dos)"/>
      <div>
        <h3>Sweat-shirt à capuche</h3>
        <div class="price">18,99 €</div>
        <p class="lead">Capuche confortable · Logo doré côté cœur · Grand logo au dos · Tailles S–XXL</p>
        <a class="btn gold" href="#" data-produit="Sweat-shirt Les ÎLES AGENCY" data-prix="18,99 €" onclick="return precommande(this)">Précommander maintenant</a>
      </div>
    </article>
    <!-- Casquette -->
    <article class="card">
      <img src="https://via.placeholder.com/600x600/101010/ffffff?text=Casquette+Les+%C3%8Eles+Agency" alt="Casquette Les ÎLES AGENCY"/>
      <div>
        <h3>Casquette brodée</h3>
        <div class="price">14,99 €</div>
        <p class="lead">Brodage doré premium · Réglable · Finition premium</p>
        <a class="btn gold" href="#" data-produit="Casquette Les ÎLES AGENCY" data-prix="14,99 €" onclick="return precommande(this)">Précommander maintenant</a>
      </div>
    </article>
    <!-- Chemise -->
    <article class="card">
      <img src="https://via.placeholder.com/600x600/101010/ffffff?text=Chemise+Les+%C3%8Eles+Agency" alt="Chemise Les ÎLES AGENCY"/>
      <div>
        <h3>Chemise élégante</h3>
        <div class="price">29,99 €</div>
        <p class="lead">Noir élégant · Détails dorés · Coupe moderne</p>
        <a class="btn gold" href="#" data-produit="Chemise Les ÎLES AGENCY" data-prix="29,99 €" onclick="return precommande(this)">Précommander maintenant</a>
      </div>
    </article>
  </div>
</section>

<section id="flocage" class="panel">
  <h2>Créer ton flocage personnalisé ✍️</h2>
  <p class="lead">Personnalise ton vêtement tout en gardant le logo officiel <strong>LES ÎLES AGENCY</strong> côté cœur et le grand flocage au dos. Ajoute ton prénom, ton rôle ou ton pseudo.</p>
  <a class="btn" href="#" data-produit="Flocage personnalisé" data-prix="Sur devis" onclick="return precommande(this)">Je crée mon flocage</a>
</section>

<section id="apropos">
  <h2>À propos</h2>
  <p class="lead"><strong>LES ÎLES AGENCY</strong> est née entre la Corse et La Réunion. Nous unissons créateurs et talents des îles autour d’une même vision : fierté, élégance, réussite.</p>
  <p class="lead"><em>Cordialement, La Direction.</em></p>
</section>

<section id="contact">
  <h2>Contact</h2>
  <div class="contact-box">
    <div>Une question, une commande ou un partenariat ?</div>
    <a href="mailto:les.iles.agency.corse@gmail.com?subject=Contact%20LES%20%C3%8ELES%20AGENCY">les.iles.agency.corse@gmail.com</a>
  </div>
</section>

  </main>  <footer>
    <div class="wrap">
      <div><strong>LES ÎLES AGENCY</strong></div>
      <small>© 2025 — La fierté des îles, l’élégance à ton image.</small>
    </div>
  </footer>  <script>
    // Pré-remplit un email de précommande (simple et efficace sur mobile)
    function precommande(el){
      const produit = el.getAttribute('data-produit') || 'Produit';
      const prix = el.getAttribute('data-prix') || '';
      const subject = encodeURIComponent('Précommande — ' + produit);
      const body = encodeURIComponent(
        `Bonjour Les ÎLES AGENCY,%0D%0A%0D%0AJe souhaite précommander : ${produit} (${prix}).%0D%0ACouleur : ____  |  Taille : ____  |  Quantité : ____%0D%0AAdresse de livraison : __________________________%0D%0AMode de paiement souhaité : Carte / PayPal%0D%0A%0D%0AMerci !`);
      window.location.href = `mailto:les.iles.agency.corse@gmail.com?subject=${subject}&body=${body}`;
      return false;
    }
  </script></body>
</html>
