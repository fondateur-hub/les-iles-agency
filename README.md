<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>LES ÎLES AGENCY — Collection Officielle 2025</title>
  <style>
    /* ---------- STYLE GLOBAL ---------- */
 body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  color: white;
  background: 
    linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)),
    url('assets/couverture.jpg') center/cover no-repeat fixed;
  background-attachment: fixed;
  background-size: cover;
  background-position: center;
  animation: fadeIn 2s ease;
}h1, h2 {
  text-shadow: 0 0 10px gold, 0 0 25px goldenrod, 0 0 35px gold;
 }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: rgba(0, 0, 0, 0.6);
      padding: 15px 25px;
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 10;
      box-shadow: 0 0 20px rgba(0,0,0,0.5);
    }

    header img {
      height: 55px;
      border-radius: 10px;
    }

    nav a {
      color: #FFD700;
      text-decoration: none;
      margin: 0 15px;
      font-weight: 600;
      transition: 0.3s;
    }

    nav a:hover {
      color: #fff;
      text-shadow: 0 0 10px #FFD700;
    }

    /* ---------- SECTION HERO ---------- */
    .hero {
      text-align: center;
      padding: 180px 20px 100px;
      background: rgba(0, 0, 0, 0.45);
    }

    .hero h1 {
      font-size: 3em;
      background: linear-gradient(90deg, #FFD700, #fff, #FFD700);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      animation: shine 4s linear infinite;
      text-shadow: 0 0 20px rgba(255,215,0,0.7);
    }

    @keyframes shine {
      0% { background-position: -200px; }
      100% { background-position: 200px; }
    }

    .hero p {
      font-size: 1.2em;
      color: #fff;
      margin-bottom: 20px;
    }

    .hero button {
      background: #FFD700;
      color: black;
      border: none;
      padding: 15px 35px;
      font-size: 1em;
      border-radius: 30px;
      cursor: pointer;
      font-weight: bold;
      box-shadow: 0 0 20px rgba(255, 215, 0, 0.6);
      transition: all 0.3s ease;
    }

    .hero button:hover {
      background: white;
      color: #B8860B;
      transform: scale(1.05);
    }

    /* ---------- SECTION BOUTIQUE ---------- */
    .boutique {
      text-align: center;
      padding: 100px 20px;
      background: rgba(0, 0, 0, 0.75);
    }

    .boutique h2 {
      font-size: 2em;
      color: #FFD700;
      text-shadow: 0 0 20px #FFD700;
      margin-bottom: 40px;
    }

    .produits {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 25px;
    }

    .produit {
      background: rgba(255, 255, 255, 0.08);
      border-radius: 20px;
      padding: 20px;
      width: 260px;
      text-align: center;
      transition: 0.3s;
      box-shadow: 0 0 15px rgba(255,215,0,0.3);
    }

    .produit:hover {
      transform: translateY(-8px);
      box-shadow: 0 0 30px rgba(255,215,0,0.7);
    }

    .produit img {
      width: 100%;
      height: auto;
      border-radius: 15px;
      margin-bottom: 10px;
    }

    .produit h3 {
      color: #FFD700;
      margin-bottom: 8px;
    }

    .paypal {
      margin-top: 50px;
    }

    .paypal button {
      background: #FFD700;
      color: black;
      border: none;
      padding: 15px 30px;
      font-size: 1em;
      border-radius: 30px;
      cursor: pointer;
      font-weight: bold;
      box-shadow: 0 0 20px rgba(255,215,0,0.6);
      transition: all 0.3s ease;
    }

    .paypal button:hover {
      background: white;
      color: #B8860B;
      transform: scale(1.05);
    }

    footer {
      text-align: center;
      padding: 30px;
      color: #FFD700;
      font-size: 0.9em;
      background: rgba(0, 0, 0, 0.7);
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(40px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @media (max-width: 768px) {
      .hero h1 { font-size: 2.3em; }
      .produit { width: 85%; }
    }
  </style>
</head>

<body>
  <header>
    <img src="assets/Logo.png" alt="Logo Les Îles Agency">
    <nav>
      <a href="#boutique">Boutique</a>
      <a href="#apropos">À propos</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>LES ÎLES AGENCY 2025</h1>
    <p>La fierté des îles, l'élégance à ton image 🌴</p>
    <button onclick="window.location.href='#boutique'">Découvrir la collection</button>
  </section>

  <section id="boutique" class="boutique">
    <h2>Boutique Officielle</h2>
    <div class="produits">
      <div class="produit">
        <img src="assets.produits.sweet-rouge.jpg" alt="Sweat Rouge">
        <h3>Sweat Rouge</h3>
        <p>Édition 2025 – Style Îles Agency</p>
      </div>

      <div class="produit">
        <img src="assets.produits.crea-noir-or.jpg" alt="Créa Noir & Or">
        <h3>Créa Noir & Or</h3>
        <p>Élégance dorée, 100% authenticité</p>
      </div>

      <div class="produit">
        <img src="assets.produits.casquette-noir.jpg" alt="Casquette Noir">
        <h3>Casquette Noir</h3>
        <p>Un style unique signé Les Îles</p>
      </div>

      <div class="produit">
        <img src="assets.produits.chemise-noir.jpg" alt="Chemise Noir">
        <h3>Chemise Noir</h3>
        <p>Classe tropicale et raffinée</p>
      </div>

      <div class="produit">
        <img src="assets.produit.mina-queen-official.jpg" alt="Mina Queen Official">
        <h3>Mina Queen Official</h3>
        <p>Collection Reine des Îles 2025</p>
      </div>
    </div>
    <!-- 🔽 Début de la section personnalisation 🔽 -->
<div class="options-produit" style="text-align:center; margin-bottom:20px;">
  <h3 style="color: gold;">Personnalise ton article 👕</h3>

  <!-- Taille -->
  <label for="taille" style="display:block; margin-top:10px;">Taille :</label>
  <select id="taille" style="padding:8px; border-radius:8px; margin-top:5px;">
    <option value="S">S</option>
    <option value="M">M</option>
    <option value="L">L</option>
    <option value="XL">XL</option>
  </select>

  <!-- Couleur -->
  <label for="couleur" style="display:block; margin-top:10px;">Couleur :</label>
  <select id="couleur" style="padding:8px; border-radius:8px; margin-top:5px;">
    <option value="noir">Noir</option>
    <option value="blanc">Blanc</option>
    <option value="or">Or</option>
  </select>

  <!-- Texte personnalisé -->
  <label for="perso" style="display:block; margin-top:10px;">Texte personnalisé (facultatif) :</label>
  <input id="perso" type="text" placeholder="Ex : Reine des Îles 👑" 
         style="padding:8px; border-radius:8px; width:80%; margin-top:5px; border:1px solid gold; background:rgba(255,255,255,0.1); color:white;">

  <!-- Bouton commander -->
  <button 
    onclick="window.open('https://paypal.me/lesilesagency','_blank')" 
    style="margin-top:20px; background:gold; color:black; border:none; padding:12px 25px; border-radius:25px; font-weight:bold; cursor:pointer; box-shadow:0 0 15px gold; transition:all 0.3s;">
    💳 Commander via PayPal
  </button>
</div>
<!-- 🔼 Fin de la section personnalisation 🔼 -->

  <div style="text-align:center; margin-top:20px;">
    <p>Ou scanne ce QR code :</p>
    <img src="https://i.ibb.co/5rkymrH/paypal-les-iles-agency.png" 
         alt="QR Code PayPal Les Îles Agency" 
         width="200" 
         style="border-radius:12px; box-shadow:0 0 25px gold;">
  </div>
</div>
    </div>
  </section>
<section id="apropos" style="padding: 60px 20px; text-align: center; color: white;">
  <h2 style="color: gold; font-size: 2em; margin-bottom: 10px;">À propos</h2>
  <p style="max-width: 600px; margin: auto; font-size: 1.1em; line-height: 1.6;">
    <b>LES ÎLES AGENCY</b> est une marque née de la passion des îles et de l’élégance tropicale.
    Notre mission est de mettre en avant la fierté et le style unique des îles
    à travers des collections modernes, authentiques et haut de gamme.
    Chaque création représente l’esprit, la chaleur et la beauté des îles 🌺.
  </p>
</section>

<section id="contact" style="padding: 60px 20px; text-align: center; color: white;">
  <h2 style="color: gold; font-size: 2em; margin-bottom: 10px;">Contact</h2>
  <p style="font-size: 1.1em;">📩 Email :
    <a href="mailto:les.iles.agency.corse@gmail.com" style="color: gold; text-decoration: none;">
      les.iles.agency.corse@gmail.com
    </a>
  </p>
  <p style="font-size: 1.1em;">📍 Basée à <b>La Réunion</b> — disponible dans toute la France et les DOM 🇫🇷</p>
</section>
  <footer>
    © 2025 LES ÎLES AGENCY — Tous droits réservés
  </footer>
</body>
</html>
