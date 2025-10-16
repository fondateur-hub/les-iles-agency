<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>LES ÎLES AGENCY — Boutique officielle</title>
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      color: #fff;
      background: url('assets/couverture.jpg') center/cover no-repeat fixed;
    }

    header {
      background-color: rgba(0, 0, 0, 0.6);
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 15px 30px;
    }

    header img {
      height: 60px;
    }

    nav a {
      color: #d4af37;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    .hero {
      text-align: center;
      padding: 120px 20px;
      background: rgba(0, 0, 0, 0.6);
    }

    .hero h1 {
      font-size: 2.8em;
      margin-bottom: 15px;
      color: #d4af37;
    }

    .hero p {
      font-size: 1.2em;
      margin-bottom: 30px;
    }

    .btn {
      background: #d4af37;
      color: #000;
      padding: 12px 25px;
      border: none;
      border-radius: 25px;
      font-weight: bold;
      cursor: pointer;
      text-decoration: none;
      transition: 0.3s;
    }

    .btn:hover {
      background: #b8962e;
    }

    .boutique {
      background-color: rgba(0, 0, 0, 0.8);
      padding: 50px 20px;
      text-align: center;
    }

    .produits {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .produit {
      background: rgba(255, 255, 255, 0.1);
      border-radius: 12px;
      padding: 15px;
      width: 250px;
      text-align: center;
      transition: transform 0.3s;
    }

    .produit:hover {
      transform: scale(1.05);
    }

    .produit img {
      width: 100%;
      border-radius: 10px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: rgba(0, 0, 0, 0.7);
      font-size: 0.9em;
      color: #d4af37;
    }
  </style>
</head>
<body>
  <header>
    <img src="assets/logo.png" alt="Logo Les Îles Agency" />
    <nav>
      <a href="#">Boutique</a>
      <a href="#">À propos</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>La fierté des îles, l’élégance à ton image</h1>
    <p>Découvre la nouvelle collection 2025 signée LES ÎLES AGENCY</p>
    <a href="https://www.paypal.com/paypalme/fondateurilesacencylivecuisto" class="btn">Commander maintenant</a>
  </section>

  <section class="boutique">
    <h2>🛍️ Nos Produits</h2>
    <div class="produits">
      <div class="produit">
        <img src="assets/produits/sweet-rouge.jpg" alt="Sweat Rouge" />
        <p>Sweat rouge premium</p>
      </div>
      <div class="produit">
        <img src="assets/produits/crea-noir-or.jpg" alt="Créa Noir Or" />
        <p>T-shirt noir & or</p>
      </div>
      <div class="produit">
        <img src="assets/produits/casquette-noir.jpg" alt="Casquette noire" />
        <p>Casquette noire élégante</p>
      </div>
      <div class="produit">
        <img src="assets/produits/chemise-noir.jpg" alt="Chemise noire" />
        <p>Chemise noire signature</p>
      </div>
      <div class="produit">
        <img src="assets/produits/mina-queen-official.jpg" alt="Mina Queen" />
        <p>Édition Reine — Mina Queen</p>
      </div>
    </div>
  </section>

  <footer>
    © 2025 Les Îles Agency — Paiement sécurisé via PayPal 💳
  </footer>
</body>
</html>
