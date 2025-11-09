<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>LES ÎLES AGENCY — Collection Officielle 2025</title>
  <style>
    /* ---------- THEME GLOBAL (fond + doré) ---------- */
    :root{
      --gold:#FFD700;
      --gold-deep:#B8860B;
      --dark:rgba(0,0,0,.65);
      --card:rgba(255,255,255,.10);
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family:'Poppins',system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;
      color:#fff;
      /* ⚠️ FOND : le fichier que tu as dans /assets s'appelle "assets.couverture.jpg" */
      background: linear-gradient(rgba(0,0,0,.35),rgba(0,0,0,.55)),
                  url('assets/assets.couverture.jpg') center/cover no-repeat fixed;
    }
    a{color:var(--gold);text-decoration:none}

    header{
      position:fixed; inset:0 0 auto 0; z-index:10;
      display:flex; align-items:center; justify-content:space-between;
      padding:12px 22px; background:var(--dark); backdrop-filter:blur(4px)
    }
    header img{height:50px;border-radius:10px}
    nav a{margin:0 12px;font-weight:700}
    nav a:hover{color:#fff}

    .wrap{padding-top:96px}

    /* ---------- HERO ---------- */
    .hero{
      text-align:center; padding:120px 20px 80px;
      background:rgba(0,0,0,.38); animation:fadeIn 1.2s ease
    }
    .hero h1{font-size:42px; margin:0 0 10px; color:var(--gold); text-shadow:0 0 22px var(--gold)}
    .hero p{font-size:18px; opacity:.95}
    .btn{
      display:inline-block; margin-top:18px; padding:14px 28px; border-radius:30px;
      font-weight:800; border:0; cursor:pointer;
      background:var(--gold); color:#000; box-shadow:0 0 16px rgba(255,215,0,.6);
      transition:.25s transform,.25s filter,.25s background
    }
    .btn:hover{transform:translateY(-2px); filter:brightness(1.02)}
    .btn--ghost{background:#fff; color:var(--gold-deep)}

    /* ---------- BOUTIQUE ---------- */
    section{padding:70px 20px}
    .section-title{
      text-align:center; font-size:30px; margin:0 0 32px;
      color:var(--gold); text-shadow:0 0 14px var(--gold)
    }
    .grid{
      display:grid; gap:22px; grid-template-columns:repeat( auto-fit, minmax(240px, 1fr) );
      max-width:1100px; margin:0 auto
    }
    .card{
      background:var(--card); border-radius:20px; padding:18px; text-align:center;
      box-shadow:0 0 10px rgba(255,215,0,.30); transition:.25s transform,.25s box-shadow
    }
    .card:hover{transform:translateY(-8px); box-shadow:0 0 24px rgba(255,215,0,.7)}
    .card img{width:100%; height:auto; border-radius:14px; margin-bottom:12px; background:#222}
    .card h3{color:var(--gold); margin:6px 0 4px}
    .price{display:inline-block; margin:6px 0 10px; font-weight:800; color:#fff; background:rgba(0,0,0,.35); padding:6px 12px; border-radius:999px; box-shadow:0 0 12px rgba(255,215,0,.35)}
    .card p{opacity:.95}

    /* ---------- PERSONNALISATION / FLOCAGE ---------- */
    .options{
      max-width:980px; margin:0 auto; background:var(--card);
      padding:22px; border-radius:20px; box-shadow:0 0 14px rgba(255,215,0,.35)
    }
    .row{display:grid; gap:14px; grid-template-columns:repeat( auto-fit, minmax(220px,1fr))}
    label{display:block; font-weight:700; margin-top:4px}
    select,input[type="text"]{
      width:100%; padding:10px 12px; border-radius:10px; border:1px solid var(--gold);
      background:rgba(255,255,255,.08); color:#fff; outline:none
    }
    .models{display:grid; gap:16px; grid-template-columns:repeat( auto-fit, minmax(190px,1fr))}
    .mock{
      border-radius:16px; height:200px; display:flex; align-items:center; justify-content:center;
      position:relative; box-shadow:0 0 16px rgba(0,0,0,.35); cursor:pointer; transition:.2s transform
    }
    .mock:hover{transform:translateY(-3px)}
    .mock .text{font-weight:900; font-size:20px; text-align:center; padding:0 8px}
    .mock[data-style="arc"]  .text{letter-spacing:1px; text-shadow:0 0 10px rgba(0,0,0,.35)}
    .mock[data-style="ligne"] .text{text-transform:uppercase}
    .mock[data-style="badge"] .text{background:rgba(0,0,0,.35); padding:6px 12px; border-radius:10px}
    .swatches{display:flex; gap:8px; flex-wrap:wrap; margin-top:10px}
    .swatch{
      width:26px; height:26px; border-radius:50%; border:1px solid rgba(255,255,255,.55);
      cursor:pointer; outline:2px solid transparent
    }
    .swatch.active{outline-color:var(--gold)}
    .note{opacity:.9; font-size:13px; margin-top:10px}

    footer{ text-align:center; padding:30px; color:var(--gold); font-size:.95rem; background:var(--dark)}

    @keyframes fadeIn{from{opacity:0; transform:translateY(18px)} to{opacity:1; transform:translateY(0)}}
  </style>
</head>
<body>
  <header>
    <img src="assets/Logo.png" alt="Logo Les Îles Agency">
    <nav>
      <a href="#boutique">Boutique</a>
      <a href="#flocage">À propos</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main class="wrap">
    <!-- HERO -->
    <section class="hero">
      <h1>LES ÎLES AGENCY 2025</h1>
      <p>La fierté des îles, l’élégance à ton image 🌴</p>
      <a href="#boutique" class="btn">Découvrir la collection</a>
    </section>

    <!-- BOUTIQUE -->
    <section id="boutique">
      <h2 class="section-title">Boutique Officielle</h2>

      <div class="grid">
        <!-- Sweat rouge -->
        <article class="card">
          <img src="assets.produits.sweet-rouge.jpg" alt="Sweat Rouge">
          <h3>Sweat Rouge</h3>
          <span class="price">49,99 €</span>
          <p><div class="actions" style="margin-top:10px;">
  <a class="btn" href="https://www.paypal.com/ncp/payment/AGHJTXLTEWWUA" target="_blank">
    Commander
  </a>
</div>



        </article>

        <!-- Créa noir & or -->
        <article class="card">
          <img src="assets.produits.crea-noir-or.jpg" alt="Créa Noir & Or">
          <h3>Créa Noir & Or</h3>
          <span class="price">14,99 €</span>
          <p>Élégance dorée, 100% authenticité.</p><div class="actions" style="margin-top:10px;">
  <a class="btn" href="https://www.paypal.com/ncp/payment/JPJQCQ6W3FJC2" target="_blank">
    Commander
  </a>
</div>

        </article>

        <!-- Casquette noir -->
        <article class="card">
          <img src="assets.produits.casquette-noir.jpg" alt="Casquette Noir">
          <h3>Casquette Noir</h3>
          <span class="price">17,99 €</span>
          <p><div class="actions" style="margin-top:10px;">
  <a class="btn" href="https://www.paypal.com/ncp/payment/JPJQCQ6W3FJC2" target="_blank">
    Commander
  </a>
</div>


        </article>

        <!-- Chemise cuisinier -->
        <article class="card">
          <img src="assets.produits.chemise-noir.jpg" alt="Chemise Cuisinier">
          <h3>Chemise Cuisinier</h3>
          <span class="price">59,99 €</span>
          <p><div class="actions" style="margin-top:10px;">
  <a class="btn" href="https://www.paypal.com/ncp/payment/SF5MU7HEKJD24" target="_blank">
    Commander
  </a>
</div>


        </article>

        <!-- Mina Queen (si tu veux plus tard ajouter un prix) -->
        <article class="card">
          <img src="assets.produit.mina-queen-official.jpg" alt="Mina Queen Official">
          <h3>Mina Queen Official</h3>
          <p>Collection Reine des Îles 2025.</p>
        </article>
      </div>

      <div style="text-align:center; margin-top:28px">
        <button class="btn" onclick="ouvrirPaiement()">💳 Commander via PayPal</button>
        <p class="note">Le résumé de ta commande est copié automatiquement. Colle-le en note dans PayPal.</p>
      </div>
    </section>

    <!-- PERSONNALISATION / FLOCAGE -->
    <section id="flocage">
      <h2 class="section-title">Personnalise ton flocage</h2>

      <div class="options">
        <div class="row">
          <div>
            <label for="taille">Taille</label>
            <select id="taille">
              <option value="3 ans">3 ans</option>
              <option value="4 ans">4 ans</option>
              <option value="6 ans">6 ans</option>
              <option value="8 ans">8 ans</option>
              <option value="10 ans">10 ans</option>
              <option value="12 ans">12 ans</option>
              <option value="14 ans">14 ans</option>
              <option value="XS">XS</option>
              <option value="S" selected>S</option>
              <option value="M">M</option>
              <option value="L">L</option>
              <option value="XL">XL</option>
              <option value="XXL">XXL</option>
              <option value="3XL">3XL</option>
            </select>
          </div>

          <div>
            <label for="couleur">Couleur</label>
            <select id="couleur">
              <option value="Blanc" selected>Blanc</option>
              <option value="Noir">Noir</option>
              <option value="Rouge">Rouge</option>
              <option value="Bleu">Bleu</option>
              <option value="Rose">Rose</option>
              <option value="Or">Or</option>
            </select>
          </div>

          <div>
            <label for="texte">Texte personnalisé (facultatif)</label>
            <input id="texte" type="text" placeholder="Ex : Reine des Îles 👑">
          </div>
        </div>

        <div style="margin-top:16px">
          <div class="swatches" id="swatches"></div>
          <p class="note">Choisis une couleur puis un style de flocage :</p>
        </div>

        <div class="models" id="models">
          <div class="mock" data-style="arc"   data-bg="#ffffff"><div class="text">LES ÎLES</div></div>
          <div class="mock" data-style="ligne" data-bg="#111111"><div class="text">LES ÎLES</div></div>
          <div class="mock" data-style="badge" data-bg="#c21e1e"><div class="text">LES ÎLES</div></div>
        </div>

        <div style="text-align:center; margin-top:18px">
          <button class="btn" onclick="ouvrirPaiement(true)">✨ Créer mon flocage & Payer</button>
        </div>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact">
      <h2 class="section-title">Contact</h2>
      <div style="text-align:center">
        <p>Une question ? Écris-nous : <a href="mailto:les.iles.agency.corse@gmail.com">les.iles.agency.corse@gmail.com</a></p>
        <p class="note">Tu peux aussi préciser ta taille/couleur/texte directement par email après paiement.</p>
      </div>
    </section>
  </main>

  <footer>© 2025 LES ÎLES AGENCY — Tous droits réservés</footer>

  <script>
    /* --------- Couleurs disponibles (pour les swatches & les maquettes) --------- */
    const colorHex = {
      "Blanc":"#ffffff",
      "Noir":"#111111",
      "Rouge":"#c21e1e",
      "Bleu":"#1f4ed6",
      "Rose":"#e76ba7",
      "Or":"#c7a008"
    };

    // fabrique les pastilles de couleur
    const swWrap = document.getElementById('swatches');
    const selectCouleur = document.getElementById('couleur');
    Object.entries(colorHex).forEach(([name,hex],i)=>{
      const b=document.createElement('button');
      b.className='swatch'+(i===0?' active':'');
      b.style.background=hex;
      b.title=name;
      b.onclick=()=>{
        [...swWrap.children].forEach(x=>x.classList.remove('active'));
        b.classList.add('active');
        selectCouleur.value=name;
        majMocks();
      };
      swWrap.appendChild(b);
    });

    // met à jour le texte/couleur dans les maquettes
    const inputTexte = document.getElementById('texte');
    const models = [...document.querySelectorAll('.mock')];
    function majMocks(){
      const col=selectCouleur.value;
      const hex=colorHex[col]||'#ffffff';
      const t=inputTexte.value.trim() || 'LES ÎLES AGENCY';
      models.forEach(m=>{
        m.style.background=hex;
        const el=m.querySelector('.text');
        el.textContent=t;
        el.style.color=(col==='Noir')?'#fefefe':'#111';
        // petite touche d’or
        if(m.dataset.style==='ligne'){ el.style.letterSpacing='2px'; el.style.textShadow='0 0 10px rgba(255,215,0,.45)'; }
        if(m.dataset.style==='arc'){ el.style.textShadow='0 0 12px rgba(0,0,0,.35), 0 0 14px rgba(255,215,0,.35)'; }
        if(m.dataset.style==='badge'){ el.style.background='rgba(0,0,0,.35)'; el.style.borderRadius='10px'; el.style.padding='6px 12px'; }
      });
    }
    inputTexte.addEventListener('input',majMocks);
    selectCouleur.addEventListener('change',majMocks);
    majMocks();

    // copie un résumé et ouvre PayPal
    function ouvrirPaiement(depuisFlocage=false){
      const taille = document.getElementById('taille')?.value || '—';
      const couleur = document.getElementById('couleur')?.value || '—';
      const texte = (document.getElementById('texte')?.value || '').trim();
      const resume =
        `Commande LES ÎLES AGENCY
- Taille : ${taille}
- Couleur : ${couleur}
- Flocage : ${texte || 'aucun'}
(merci d’ajouter ce texte en note du paiement)`;

      if(navigator.clipboard){
        navigator.clipboard.writeText(resume).catch(()=>{});
      }
      const url = 'https://www.paypal.com/ncp/payment/9DFPFZUZG35Z4';
      window.open(url,'_blank');
      if(depuisFlocage){
        alert("Résumé copié dans le presse-papiers ✅\nColle-le dans la note PayPal pour qu’on imprime exactement ce que tu veux.");
      }
    }
  </script>
</body>
</html>
