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

 <!-- 🩸 SWEET ROUGE -->
<div class="produit" style="text-align:center; margin-bottom:40px;">
  <img src="assets/sweet-rouge.jpg" alt="Sweet Rouge" style="width:200px; border-radius:12px; box-shadow:0 0 15px gold;">
  <h3 style="color:gold; margin-top:10px;">Sweet Rouge</h3>
  <p style="font-weight:bold; color:#FFD700;">Prix : 49,99 €</p>
  <p style="color:white;">Édition premium – coupe moderne, tissu doux et confortable.</p>
</div>

<!-- ⚫ CREA NOIR & OR -->
<div class="produit" style="text-align:center; margin-bottom:40px;">
  <img src="assets/crea-noir-or.jpg" alt="Crea Noir & Or" style="width:200px; border-radius:12px; box-shadow:0 0 15px gold;">
  <h3 style="color:gold; margin-top:10px;">Crea Noir & Or</h3>
  <p style="font-weight:bold; color:#FFD700;">Prix : 14,99 €</p>
  <p style="color:white;">Style minimaliste avec détails dorés élégants.</p>
</div>

<!-- 🧢 CASQUETTE NOIR -->
<div class="produit" style="text-align:center; margin-bottom:40px;">
  <img src="assets/casquette-noir.jpg" alt="Casquette Noir" style="width:200px; border-radius:12px; box-shadow:0 0 15px gold;">
  <h3 style="color:gold; margin-top:10px;">Casquette Noir</h3>
  <p style="font-weight:bold; color:#FFD700;">Prix : 17,99 €</p>
  <p style="color:white;">Casquette officielle Les Îles Agency – édition 2025.</p>
</div>

<!-- 👨‍🍳 CHEMISE CUISINIER -->
<div class="produit" style="text-align:center; margin-bottom:40px;">
  <img src="assets/chemise-cuisinier.jpg" alt="Chemise Cuisinier" style="width:200px; border-radius:12px; box-shadow:0 0 15px gold;">
  <h3 style="color:gold; margin-top:10px;">Chemise Cuisinier</h3>
  <p style="font-weight:bold; color:#FFD700;">Prix : 59,99 €</p>
  <p style="color:white;">Chemise professionnelle brodée – design exclusif Les Îles Agency.</p>
</div>
    </div>
    <!-- 🔽 Début de la section personnalisation 🔽 -->
<div class="options-produit" style="text-align:center; margin-bottom:20px;">
  <h3 style="color: gold;">Personnalise ton article 👕</h3>

<!-- Taille -->
<label for="taille" style="display:block; margin-top:10px;">Taille :</label>
<select id="taille" style="padding:8px; border-radius:8px; margin-top:5px;">
  <option value="3ans">3 ans</option>
  <option value="4ans">4 ans</option>
  <option value="6ans">6 ans</option>
  <option value="8ans">8 ans</option>
  <option value="10ans">10 ans</option>
  <option value="12ans">12 ans</option>
  <option value="14ans">14 ans</option>
  <option value="XS">XS</option>
  <option value="S">S</option>
  <option value="M">M</option>
  <option value="L">L</option>
  <option value="XL">XL</option>
  <option value="XXL">XXL</option>
  <option value="3XL">3XL</option>
</select>
  <!-- Couleur -->
<label for="couleur" style="display:block; margin-top:10px;">Couleur :</label>
<select id="couleur" style="padding:8px; border-radius:8px; margin-top:5px;">
  <option value="blanc">Blanc</option>
  <option value="noir">Noir</option>
  <option value="rouge">Rouge</option>
  <option value="bleu">Bleu</option>
  <option value="rose">Rose</option>
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
