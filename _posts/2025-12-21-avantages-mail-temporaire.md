<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Temp-Mail vs Email Classique | Bitcoin France</title>
  <style>
    body {
      font-family: monospace;
      background-color: #1c1c1e; /* fond sombre Bitcoin style */
      margin: 0;
      padding: 0 10px;
      color: #fff;
    }

    .container {
      max-width: 400px;
      margin: 20px auto;
    }

    .card {
      border: 2px solid #f7931a; /* orange Bitcoin */
      border-radius: 10px;
      padding: 16px;
      margin-bottom: 16px;
      background-color: #222; /* carte sombre */
      line-height: 1.5;
    }

    .card.temp {
      border-color: #00cc66; /* vert pour Temp-Mail */
      background-color: #111;
    }

    .card-header {
      font-weight: bold;
      text-align: center;
      border-bottom: 1px solid #f7931a;
      padding-bottom: 8px;
      margin-bottom: 8px;
      color: #f7931a;
    }

    .card.temp .card-header {
      border-color: #00cc66;
      color: #00cc66;
    }

    .card ul {
      list-style: none;
      padding-left: 0;
      margin: 0;
    }

    .card ul li::before {
      content: "⚡ "; /* icône légère Bitcoin/éclair */
      color: #f7931a;
    }

    .card.temp ul li::before {
      content: "✔ ";
      color: #00cc66;
    }

    .advantages {
      max-width: 400px;
      margin: auto;
      padding: 0 16px;
      line-height: 1.5;
    }

    .advantages span {
      display: block;
      margin-bottom: 6px;
      color: #f7931a;
    }

    .advantages span.temp {
      color: #00cc66;
    }

    @media (max-width: 450px) {
      body {
        padding: 0 5px;
      }
      .container, .advantages {
        max-width: 100%;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <div class="card-header">Email Classique</div>
      <ul>
        <li>Permanente</li>
        <li>Identité requise</li>
        <li>Spam fréquent</li>
        <li>Risque piratage moyen</li>
        <li>Multi-comptes complexes</li>
      </ul>
    </div>

    <div class="card temp">
      <div class="card-header">Temp-Mail</div>
      <ul>
        <li>Temporaire</li>
        <li>Anonyme</li>
        <li>Zéro spam</li>
        <li>Sécurisé</li>
        <li>Multi-comptes faciles</li>
      </ul>
    </div>

    <div class="advantages">
      <span>✔ Recevez vos emails sans exposer votre vraie boîte</span>
      <span>✔ Testez des services sans spam ni risque</span>
      <span>✔ Créez des comptes multiples facilement</span>
    </div>
  </div>
</body>
</html>
