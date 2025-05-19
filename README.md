<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>QualiClean – Audit Qualité Propreté</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f4f9fb;
      color: #333;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #ffffff;
      padding: 1rem 2rem;
      border-bottom: 2px solid #dceef2;
    }

    .logo img {
      height: 50px;
    }

    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #2c97de;
      font-weight: bold;
    }

    .hero {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 2rem;
      background-color: #e8f7fa;
    }

    .hero-text {
      max-width: 50%;
    }

    .hero h1 {
      font-size: 2.5rem;
      color: #2c97de;
    }

    .hero p {
      font-size: 1.2rem;
    }

    .cta {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.75rem 1.5rem;
      background-color: #2c97de;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }

    .hero-img {
      max-width: 45%;
      border-radius: 8px;
    }

    .features {
      padding: 2rem;
      background-color: #ffffff;
      text-align: center;
    }

    .features-grid {
      display: flex;
      justify-content: space-around;
      margin-top: 2rem;
      flex-wrap: wrap;
      gap: 2rem;
    }

    .feature {
      width: 30%;
      min-width: 220px;
    }

    .feature i {
      font-size: 2rem;
      color: #2c97de;
      margin-bottom: 0.5rem;
    }

    .contact {
      background-color: #f0f9f8;
      padding: 2rem;
      text-align: center;
    }

    footer {
      background-color: #2c97de;
      color: white;
      text-align: center;
      padding: 1rem 0;
    }

    .reseaux a {
      margin: 0 10px;
      color: white;
      font-size: 1.5rem;
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">
      <img src="img/QualiClean-Logo.png" alt="Logo QualiClean" />
    </div>
    <nav>
      <a href="#fonctionnalites">Fonctionnalités</a>
      <a href="#contact">Contact</a>
      <a href="#reseaux">Réseaux</a>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-text">
      <h1>L’audit qualité, réinventé.</h1>
      <p>Une application mobile pensée pour les professionnels de la propreté.</p>
      <a class="cta" href="#">Tester gratuitement</a>
    </div>
    <img class="hero-img" src="https://source.unsplash.com/cleaning-office/800x500" alt="Nettoyage en entreprise" />
  </section>

  <section class="features" id="fonctionnalites">
    <h2>Fonctionnalités clés</h2>
    <div class="features-grid">
      <div class="feature">
        <i class="fas fa-mobile-alt"></i>
        <h3>100 % mobile</h3>
        <p>Disponible sur tous les smartphones et tablettes.</p>
      </div>
      <div class="feature">
        <i class="fas fa-brain"></i>
        <h3>IA intégrée</h3>
        <p>Analyse vocale, détection d’anomalies, indicateurs en temps réel.</p>
      </div>
      <div class="feature">
        <i class="fas fa-file-alt"></i>
        <h3>Rapports instantanés</h3>
        <p>Export PDF, CSV et synthèses automatiques personnalisées.</p>
      </div>
    </div>
  </section>

  <section class="contact" id="contact">
    <h2>Contact</h2>
    <p>Pour plus d’informations ou une démonstration personnalisée :</p>
    <p>Email : <a href="mailto:contact@qualiclean.fr">contact@qualiclean.fr</a></p>
    <p>Adresse : 12 rue Paul-Déroulède, 92800 Puteaux</p>
  </section>

  <footer id="reseaux">
    <div class="reseaux">
      <a href="#"><i class="fab fa-linkedin"></i></a>
      <a href="#"><i class="fab fa-instagram"></i></a>
      <a href="#"><i class="fab fa-facebook"></i></a>
    </div>
    <p>&copy; 2025 QualiClean – Groupe Saturne. Tous droits réservés.</p>
  </footer>

</body>
</html>
