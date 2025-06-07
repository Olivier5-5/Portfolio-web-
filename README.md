<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mon Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f2f2f2;
      color: #333;
    }
    header {
      background-color: #222;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      text-align: center;
      background-color: #444;
      padding: 10px;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
    }
    section {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
      background-color: white;
      margin-bottom: 30px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    .gallery img {
      width: 100%;
      max-width: 300px;
      margin: 10px;
      border-radius: 8px;
    }
    .whatsapp-button {
      display: inline-block;
      background-color: #25D366;
      color: white;
      padding: 10px 20px;
      margin-top: 10px;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
    }
    .whatsapp-button:hover {
      background-color: #1ebc57;
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #222;
      color: white;
    }
    @media screen and (max-width: 600px) {
      nav a {
        display: block;
        margin: 10px 0;
      }
      .gallery img {
        max-width: 100%;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Bienvenue sur mon Portfolio</h1>
    <p>Graphiste créatif & passionné</p>
  </header>

  <nav>
    <a href="#accueil">Accueil</a>
    <a href="#graphique">Mes Graphiques</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="accueil">
    <h2>À propos de moi</h2>
    <p>Je suis un graphiste passionné par la création d'images percutantes et originales. Voici un aperçu de mes créations.</p>
  </section>

  <section id="graphique">
    <h2>Mes Graphiques</h2>
    <div class="gallery">
      <img src="ton-image1.jpg" alt="Graphique 1">
      <img src="ton-image2.jpg" alt="Graphique 2">
      <!-- Tu peux ajouter d'autres images ici -->
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p><strong>Téléphone :</strong> 0143199391</p>
    <p><strong>Email :</strong> armandolivierkouassi986@gmail.com</p>
    <a class="whatsapp-button" href="https://wa.me/225143199391" target="_blank">Me contacter sur WhatsApp</a>
  </section>

  <footer>
  </footer>
</body>
<.


