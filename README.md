<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Qualiclean - L'application d'audit qualité dédiée aux métiers de la propreté.">
  <title>Qualiclean - Audit qualité terrain</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      background: #f9fdfc;
      color: #222;
    }
    header {
      background: #00cfcf;
      padding: 1rem 2rem;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    header img {
      height: 40px;
    }
    nav a {
      color: white;
      margin-left: 1rem;
      text-decoration: none;
      font-weight: 500;
    }
    .hero {
      text-align: center;
      padding: 4rem 2rem;
      background: #e4f9f8;
    }
    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.2rem;
      margin-bottom: 2rem;
    }
    .cta {
      background: #00cfcf;
      color: white;
      padding: 1rem 2rem;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
      text-decoration: none;
    }
    .features {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      padding: 3rem 2rem;
      background: #ffffff;
    }
    .feature {
      flex: 0 1 250px;
      margin: 1rem;
      background: #f1fdfc;
      padding: 1.5rem;
      border-radius: 8px;
      text-align: center;
    }
    footer {
      background: #00cfcf;
      color: white;
      text-align: center;
      padding: 1.5rem;
    }
  </style>
</head>
<body>
  <header>
    <img src="QualiClean-Logo.png" alt="Logo Qualiclean">
    <nav>
      <a href="#features">Fonctionnalités</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  <section class="hero">
    <h1>L’audit qualité terrain réinventé</h1>
    <p>Qualiclean, l’application mobile & web pour vos contrôles propreté assistés par IA.</p>
    <a class="cta" href="#">Tester maintenant</a>
  </section>
  <section class="features" id="features">
    <div class="feature">
      <h3>Checklist intelligente</h3>
      <p>Simplifiez vos audits avec des formulaires guidés</p>
    </div>
    <div class="feature">
      <h3>Analyse des anomalies</h3>
      <p>Historique, photos, commentaires en un clic</p>
    </div>
    <div class="feature">
      <h3>Exports & KPIs</h3>
      <p>Rapports PDF et CSV configurables</p>
    </div>
    <div class="feature">
      <h3>Interface collaborative</h3>
      <p>Suivi des actions correctives en équipe</p>
    </div>
  </section>
  <footer id="contact">
    <p>&copy; 2025 Qualiclean • Léo Bouty – contact@qualiclean.app</p>
  </footer>
</body>
</html>
