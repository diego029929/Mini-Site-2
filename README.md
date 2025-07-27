<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Boutique Locale - Accueil</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Inter:wght@300;500&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Inter', sans-serif;
      background: #f7f6f3;
      color: #333;
      line-height: 1.6;
    }
    header {
      background-color: #ffffff;
      padding: 1.5rem 2rem;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 1.8rem;
    }
    nav a {
      margin-left: 1rem;
      text-decoration: none;
      color: #333;
      font-weight: 500;
    }
    .hero {
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      padding: 3rem 2rem;
      background: url('https://images.unsplash.com/photo-1517248135467-4c7edcad34c4') center/cover no-repeat;
      color: white;
    }
    .hero h2 {
      font-family: 'Playfair Display', serif;
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.2rem;
      max-width: 600px;
    }
    .cta {
      margin-top: 2rem;
      padding: 1rem 2rem;
      background: white;
      color: #333;
      border-radius: 8px;
      text-decoration: none;
      font-weight: 600;
      transition: background 0.3s ease;
    }
    .cta:hover {
      background: #f0f0f0;
    }
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 2rem;
      padding: 4rem 2rem;
      background: #fff;
    }
    .feature {
      background: #f9f9f9;
      padding: 2rem;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.04);
      text-align: center;
    }
    .feature h3 {
      font-family: 'Playfair Display', serif;
      margin-bottom: 1rem;
    }
    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      background: #fafafa;
      color: #666;
    }
  </style>
</head>
<body>
  <header>
    <h1>La Petite Boutique</h1>
    <nav>
      <a href="#">Accueil</a>
      <a href="#">Produits</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Bienvenue dans votre boutique locale</h2>
    <p>Des produits artisanaux, un accueil chaleureux et une expérience unique au cœur de votre quartier.</p>
    <a href="#" class="cta">Voir nos produits</a>
  </section>

  <section class="features">
    <div class="feature">
      <h3>Fait main</h3>
      <p>Des créations artisanales conçues avec amour et passion.</p>
    </div>
    <div class="feature">
      <h3>Local & durable</h3>
      <p>Produits issus de fournisseurs locaux respectueux de l’environnement.</p>
    </div>
    <div class="feature">
      <h3>Service personnalisé</h3>
      <p>Un accueil humain et attentionné pour chaque visiteur.</p>
    </div>
  </section>

  <footer>
    &copy; 2025 La Petite Boutique – Tous droits réservés.
  </footer>
</body>
</html>
