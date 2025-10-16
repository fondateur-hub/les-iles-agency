<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>LES ÎLES AGENCY — Boutique officielle</title>
  <style>
    :root {
      --or: #d4af37;
      --noir: #0b0b0b;
      --blanc: #ffffff;
      --fond-transparent: rgba(0, 0, 0, 0.6);
    }

    body {
      margin: 0;
      font-family: "Poppins", sans-serif;
      color: var(--blanc);
      background: url("assets/couverture.jpg") center/cover no-repeat fixed;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: var(--fond-transparent);
      padding: 15px 30px;
      position: sticky;
      top: 0;
      backdrop-filter: blur(5px);
      z-index: 10;
    }

    header img {
      height: 60px;
    }

    nav a {
      margin: 0 15px;
      color: var(--or);
      text-decoration: none;
      font-weight: 600;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      text-align: center;
      padding: 120px 20px;
      background-color: var(--fond-transparent);
    }

    .hero h1 {
      font-size: 48px;
      color: var(--or);
      margin-bottom: 10px;
    }

    .hero h2 {
      font-size: 24px;
      font-weight: 400;
      color: var(--blanc);
      margin-bottom: 25px;
    }

    .hero button {
      background-color: var(--or);
      border: none;
      color: var(--noir);
      padding: 15px 40px;
      font-size: 18px;
      border-radius: 30px;
      cursor: pointer;
      font-weight: bold;
      transition: all 0.3s ease;
    }

    .hero button:hover {
      background-color: #b8942c;
      transform: scale(1.05);
    }

    .boutique {
      padding: 60px 20px;
      text-align: center;
      background-color: var(--fond-transparent);
    }

    .boutique h2 {
      color: var(--or);
      font-size: 36px;
      margin-bottom: 40px;
    }

    .produits {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
      justify-content: center;
      align-items: center;
    }

    .produit {
      background-color: rgba(255, 255, 255, 0.1);
      border-radius: 20px;
      overflow: hidden;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
      transition: transform 0.3s ease;
    }

    .produit:hover {
      transform: translateY(-5px);
    }

    .produit img {
      width: 100%;
      height: 280px;
      object-fit: cover;
    }

    .produit h3 {
      margin: 10px 0;
      color: var(--or);
    }

    .produit p {
      color: var(--blanc);
      font-size: 14px;
    }

    footer {
      text-align: center;
      padding: 30px;
      background-color: var(--fond-transparent);
      color: var(--or);
      font-size: 14px;
    }

    .paypal-btn {
      margin-top: 20px;
    }

    .paypal-btn a {
      background-color: var(--or);
      color: var(--noir);
      padding: 12px 25px;
      border-radius: 25px;
      text-decoration: none;
      font-weight: bold;
      transition: all 0.3s ease;
    }

    .paypal-btn a:hover {
      background-color: #b8942c;
    }
  </style>
</head>
<body>

  <header>
    <img src="assets/Logo.png" alt="Logo Les Îles Agency">
    <nav>
      <a href="#boutique">Boutique</a>
      <a href="#a-propos">À propos</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>LES ÎLES AGENCY 2025</h1>
    <h2>La fierté des îles, l’élégance à ton image</h2>
    <button onclick="window.location.href='#boutique'">Découvrir la collection</button>
  </section>

  <section id="boutique" class="boutique">
    <h2>Boutique Officielle</h2>
    <div class="produits">
      <div class="produit">
        <img src="assets/produits/sweet-rouge.jpg" alt="Sweat Rouge">
        <h3>Sweat Rouge</h3>
        <p>Édition 2025 – Style Îles Agency</p>
      </div>
      <div class="produit">
        <img src="assets/produits/crea-noir-or.jpg" alt="Créa Noir & Or">
        <h3>Créa Noir & Or</h3>
        <p>Élégance dorée, 100% authenticité</p>
      </div>
      <div class="produit">
        <img src="assets/produits/casquette-noir.jpg" alt="Casquette Noir">
        <h3>Casquette Noir</h3>
        <p>Un style unique signé Les Îles</p>
      </div>
      <div class="produit">
        <img src="assets/produits/chemise-noir.jpg" alt="Chemise Noir">
        <h3>Chemise Noir</h3>
        <p>Classe tropicale et raffinée</p>
      </div>
      <div class="produit">
        <img src="assets/produits/mina-queen-official.jpg" alt="Mina Queen">
        <h3>Mina Queen Official</h3>
        <p>Collection Reine des Îles 2025</p>
      </div>
    </div>

    <div class="paypal-btn">
      <a href="https://www.paypal.com/paypalme/fondateurilesacencylivecuisto" target="_blank">
        💳 Commander via PayPal
      </a>
    </div>
  </section>

  <footer>
    © 2025 LES ÎLES AGENCY — Tous droits réservés
  </footer>

</body>
</html>
