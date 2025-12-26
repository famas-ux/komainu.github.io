---
layout: page
title: "Boîte à outils"
permalink: /boite-outils/
date: 2025-12-26
categories: [bitcoin, outils]
---

<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Boîte à outils Bitcoin</title>

<style>
  body {
    font-family: Arial, Helvetica, sans-serif;
    background-color: #ffffff;
    color: #1c1c1e;
    margin: 0;
    padding: 20px 10px;
    line-height: 1.8;
  }
  .container {
    max-width: 700px;
    margin: auto;
  }
  h1, h2 {
    text-align: center;
    color: #f7931a; /* titre principal et h2 */
  }
  nav {
    text-align: center;
    margin-bottom: 30px;
  }
  nav a {
    margin: 0 8px;
    color: #1d4ed8; /* bleu menu */
    font-weight: bold;
    text-decoration: none;
  }
  nav a:hover {
    text-decoration: underline;
  }
  .card {
    background-color: #f9f9f9;
    border-radius: 12px;
    padding: 20px;
    margin: 25px 0;
    border-left: 4px solid #00a86b;
  }
  .card h2 {
    text-align: left;
    color: #00a86b; /* titre carte */
    margin-top: 0;
  }
  ul {
    padding-left: 20px;
  }
  ul li {
    margin-bottom: 8px;
  }
  a {
    color: #d97706; /* liens orange */
    font-weight: bold;
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }
  footer {
    margin-top: 40px;
    padding-top: 20px;
    border-top: 1px solid #ccc;
    text-align: center;
  }
  footer a {
    margin: 0 8px;
    color: #1d4ed8; /* bleu menu footer */
    font-weight: bold;
    text-decoration: none;
  }
  footer a:hover {
    text-decoration: underline;
  }
</style>
</head>

<body>
<div class="container">

<h1>Boîte à outils Bitcoin</h1>

<nav>
  <!-- Sécurité & Privacy -->
  <a href="#tempmail">Temp-Mail</a>
  <a href="#protonmail">Proton Mail</a>
  <a href="#protonauth">Authenticator</a>
  <a href="#protondrive">Proton Drive</a>
  <a href="#privacyguides">Privacy Guides</a>

  <!-- Wallets Bitcoin -->
  <a href="#protonwallet">Proton Wallet</a>
  <a href="#bullwallet">Bull Wallet / Bull Échanges</a>
  <a href="#blitzwallet">Blitz Wallet</a>

  <!-- Réseaux décentralisés -->
  <a href="#nostr">Nostr</a>

  <!-- Répertoires -->
  <a href="#btcdir">BTC Dir</a>
  <a href="#bitzy">Bitzy</a>

  <!-- Outils techniques -->
  <a href="#json2map">json2map</a>
  <a href="#omnitools">OmniTools</a>
  <a href="#aiscience">AI Science</a>

  <!-- Données réseau -->
  <a href="#mempool">Mempool.space</a>
  <a href="#timechaincalendar">Timechain Calendar</a>

  <!-- Analyse & Dashboards -->
  <a href="#clarkmoody">Clark Moody</a>
  <a href="#wickedbitcoin">Wicked Smart Bitcoin</a>
  <a href="#bitbo">bitbo.io</a>
</nav>

<!-- Temp-Mail -->
<div class="card" id="tempmail">
  <h2>Temp-Mail</h2>
  <ul>
    <li>Email temporaire et anonyme</li>
    <li>Réduction du spam</li>
    <li>Inscription sans identité</li>
    <li>Emails auto-destructibles</li>
  </ul>
  <p><a href="https://temp-mail.org/fr/" target="_blank">Site officiel 🔗</a></p>
</div>

<!-- Proton Mail -->
<div class="card" id="protonmail">
  <h2>Proton Mail</h2>
  <ul>
    <li>Chiffrement de bout en bout</li>
    <li>Basé en Suisse</li>
    <li>Aucune exploitation des données</li>
    <li>Compatible PGP</li>
  </ul>
  <p>
    <a href="https://planb.academy/fr/tutorials/computer-security/communication/proton-mail-c3b010ce-254d-4546-b382-19ab9261c6a2" target="_blank">
      Source PlanB Academy 🔗
    </a><br>
    <a href="https://proton.me/fr/mail" target="_blank">Site officiel 🔗</a>
  </p>
</div>

<!-- Proton Authenticator -->
<div class="card" id="protonauth">
  <h2>Proton Authenticator</h2>
  <ul>
    <li>2FA hors ligne</li>
    <li>Standard TOTP</li>
    <li>Renforce la sécurité des comptes</li>
    <li>Gratuit</li>
  </ul>
  <p>
    <a href="https://planb.academy/fr/tutorials/computer-security/authentication/proton-authenticator-047ca2eb-a922-4e0e-8f75-1b89d23951ae" target="_blank">
      Source PlanB Academy 🔗
    </a><br>
    <a href="https://proton.me/fr/authenticator" target="_blank">Site officiel 🔗</a>
  </p>
</div>

<!-- Proton Drive -->
<div class="card" id="protondrive">
  <h2>Proton Drive</h2>
  <ul>
    <li>Stockage chiffré de bout en bout</li>
    <li>Respect de la vie privée</li>
    <li>Alternative à Google Drive</li>
    <li>Basé en Suisse</li>
  </ul>
  <p>
    <a href="https://planb.academy/fr/tutorials/computer-security/data/proton-drive-03cbe49f-6ddc-491f-8786-bc20d98ebb16" target="_blank">
      Source PlanB Academy 🔗
    </a><br>
    <a href="https://proton.me/fr/drive" target="_blank">Site officiel 🔗</a>
  </p>
</div>

<!-- Proton Wallet -->
<div class="card" id="protonwallet">
  <h2>Proton Wallet</h2>
  <ul>
    <li>Envoi de bitcoin via email</li>
    <li>Intégré à l’écosystème Proton</li>
    <li>Interface simple</li>
    <li>Idéal pour débutants</li>
  </ul>
  <p>
    <a href="https://planb.academy/fr/tutorials/wallet/desktop/proton-wallet-0bee0bba-ab62-4db0-8c63-b2ad698ca178" target="_blank">
      Source PlanB Academy 🔗
    </a><br>
    <a href="https://proton.me/fr/wallet" target="_blank">Site officiel 🔗</a>
  </p>
</div>

<!-- AI Science -->
<div class="card" id="aiscience">
  <h2>Awesome AI for Science</h2>
  <ul>
    <li>Répertoire IA pour la recherche</li>
    <li>Outils open source</li>
    <li>Veille scientifique structurée</li>
    <li>Multi-disciplines</li>
  </ul>
  <p>
    <a href="https://zdoc.app/en/ai-boost/awesome-ai-for-science" target="_blank">
      Source 🔗
    </a><br>
    <em>Cité par Renaud Lifchitz</em>
  </p>
</div>

<!-- Privacy Guides -->
<div class="card" id="privacyguides">
  <h2>Privacy Guides</h2>
  <ul>
    <li>Communauté collaborative de défense de la vie privée</li>
    <li>Projet à but non lucratif géré par des bénévoles</li>
    <li>Actualités et recommandations sur outils et services</li>
    <li>Connaissances et guides de confidentialité et sécurité</li>
  </ul>
  <p><a href="https://www.privacyguides.org/fr/" target="_blank">Site officiel 🔗</a></p>
</div>

<!-- Nostr -->
<div class="card" id="nostr">
  <h2>Nostr – Réseau social décentralisé</h2>
  <ul>
    <li>Protocole ouvert et sans autorité centrale</li>
    <li>Résistant à la censure</li>
    <li>Identité basée sur des clés cryptographiques</li>
    <li>Interopérable entre clients</li>
    <li>Alternative à Twitter et Telegram</li>
  </ul>
  <p>
    <a href="https://speakerdeck.com/rlifchitz/nostr-reseau-social-et-espace-de-liberte-decentralise" target="_blank">
      Présentation – Renaud Lifchitz 🔗
    </a><br>
    <a href="https://planb.academy/fr/tutorials/node/others/nostr-f6d21a64-9b04-4f21-ba1c-02c98cc91f98" target="_blank">
      Source PlanB Academy 🔗
    </a><br>
    <a href="https://nostr.fr/" target="_blank">
      Site francophone 🔗
    </a>
  </p>
</div>

<!-- BTC Directory -->
<div class="card" id="btcdir">
  <h2>BTC Directory</h2>
  <ul>
    <li>Annuaire de sites et services Bitcoin</li>
    <li>Navigation par catégorie</li>
    <li>Ressources francophones et internationales</li>
  </ul>
  <p><a href="https://btcdir.org/" target="_blank">Accéder 🔗</a></p>
</div>

<!-- Bitzy -->
<div class="card" id="bitzy">
  <h2>Bitzy</h2>
  <ul>
    <li>Annuaire de sites Bitcoin et crypto</li>
    <li>Classement et recherches rapides</li>
    <li>Ressources mises à jour</li>
  </ul>
  <p><a href="https://www.bitzy.com/" target="_blank">Accéder 🔗</a></p>
</div>

<!-- json2map -->
<div class="card" id="json2map">
  <h2>json2map.com — Visualisation JSON</h2>
  <ul>
    <li>Transforme n’importe quel JSON en carte visuelle arborescente</li>
    <li>Pratique pour explorer des réponses d’API Bitcoin ou dumps de blocs/transactions</li>
    <li>Débogage rapide des structures JSON complexes</li>
    <li>Vue claire et intuitive pour développeurs et débutants</li>
  </ul>
  <p>
    <a href="https://www.json2map.com/" target="_blank">Accéder à json2map.com 🔗</a>
  </p>
</div>

<!-- OmniTools -->
<div class="card" id="omnitools">
  <h2>OmniTools — Boostez votre productivité</h2>
  <p>Faites avancer les choses rapidement avec OmniTools, la boîte à outils ultime pour accélérer vos tâches ! Accédez à des milliers d'utilitaires conviviaux pour modifier des images, du texte, des listes et des données, directement depuis votre navigateur.</p>
  <ul>
    <li>Créer une image transparente</li>
    <li>Embellir JSON</li>
    <li>Modifier la vitesse du GIF</li>
    <li>Trier une liste</li>
    <li>Compresser PNG</li>
    <li>Diviser un texte</li>
    <li>Diviser le PDF</li>
    <li>Découper la vidéo</li>
    <li>Calculer la somme des nombres</li>
  </ul>
  <p>
    <a href="https://omnitools.app/" target="_blank">Accéder à OmniTools 🔗</a><br>
    <em>Cité par Renaud Lifchitz</em>
  </p>
</div>

<!-- Blitz Wallet -->
<div class="card" id="blitzwallet">
  <h2>Blitz Wallet</h2>
  <ul>
    <li>Wallet Bitcoin non-custodial</li>
    <li>Lightning natif pour paiements rapides</li>
    <li>Orienté privacy et sécurité</li>
    <li>Interface simple et intuitive</li>
  </ul>
  <p>
    <a href="https://famas-ux.github.io/komainu.github.io/bitcoin/wallet/2025/12/23/blitz-wallet-points-cles.html" target="_blank">
      Lire l’article complet 🔗
    </a><br>
    <em>Source : Famas — « Blitz Wallet : points clés »</em>
  </p>
</div>

<!-- Bull Wallet / Bull Échanges -->
<div class="card" id="bullwallet">
  <h2>Bull Wallet / Bull Échanges</h2>
  <ul>
    <li>Wallet Bitcoin sécurisé et non-custodial</li>
    <li>Plateforme d’échanges intégrée</li>
    <li>Compatible Lightning pour paiements rapides</li>
    <li>Interface simple et intuitive pour tous niveaux</li>
  </ul>
  <p>
    <a href="https://famas-ux.github.io/komainu.github.io/bull-wallet/" target="_blank">
      Lire l’article complet 🔗
    </a><br>
    <em>Source : Famas — Bull Wallet</em>
  </p>
</div>

<div class="card" id="timechaincalendar">
  <h2>Timechain Calendar</h2>
  <ul>
    <li>Données réseau Bitcoin en temps réel</li>
    <li>Suivi blocs, difficulté, hashrate, récompense</li>
    <li>Prévisions de halving</li>
    <li>Dimension artistique et culturelle de Bitcoin</li>
  </ul>
  <p>
    <a href="https://timechaincalendar.com/en" target="_blank">Accéder 🔗</a><br>
    <em>Source : timechaincalendar.com</em>
  </p>
</div>

<div class="card" id="mempool">
  <h2>Mempool.space</h2>
  <ul>
    <li>Explorateur Bitcoin et mempool open source</li>
    <li>Visualisation temps réel des blocs</li>
    <li>Estimations fiables des frais</li>
    <li>Vues Lightning Network et Liquid</li>
  </ul>
  <p>
    <a href="https://mempool.space/fr/" target="_blank">Accéder 🔗</a><br>
    <em>Source : mempool.space</em>
  </p>
</div>

<div class="card" id="wickedbitcoin">
  <h2>Wicked Smart Bitcoin</h2>
  <ul>
    <li>Visualisations avancées de données Bitcoin</li>
    <li>Approche standard Bitcoin (self-custody, UTXO)</li>
    <li>Prix exprimés en bitcoin</li>
    <li>Analyse technique et philosophique</li>
  </ul>
  <p>
    <a href="https://wickedsmartbitcoin.com/" target="_blank">Accéder 🔗</a><br>
    <em>Source : wickedsmartbitcoin.com</em>
  </p>
</div>

<div class="card" id="clarkmoody">
  <h2>Clark Moody Dashboard</h2>
  <ul>
    <li>Vue globale et temps réel de Bitcoin</li>
    <li>Métriques sécurité, UTXO, frais</li>
    <li>Analyses Lightning Network</li>
    <li>Outil de monitoring et d’éducation</li>
  </ul>
  <p>
    <a href="https://dashboard.clarkmoody.com/" target="_blank">Accéder 🔗</a><br>
    <em>Source : dashboard.clarkmoody.com</em>
  </p>
</div>

<div class="card" id="bitbo">
  <h2>bitbo.io</h2>
  <ul>
    <li>Dashboard Bitcoin temps réel</li>
    <li>Données réseau et mining</li>
    <li>Visualisations claires et pédagogiques</li>
    <li>Accès direct sans inscription</li>
  </ul>
  <p>
    <a href="https://bitbo.io/?standalone=true" target="_blank">Accéder 🔗</a><br>
    <em>Source : bitbo.io</em>
  </p>
</div>

</div>

<!-- Footer -->
<footer>
  <!-- Sécurité & Privacy -->
  <a href="#tempmail">Temp-Mail</a>
  <a href="#protonmail">Proton Mail</a>
  <a href="#protonauth">Authenticator</a>
  <a href="#protondrive">Proton Drive</a>
  <a href="#privacyguides">Privacy Guides</a>

  <!-- Wallets -->
  <a href="#protonwallet">Proton Wallet</a>
  <a href="#bullwallet">Bull Wallet / Bull Échanges</a>
  <a href="#blitzwallet">Blitz Wallet</a>

  <!-- Réseaux -->
  <a href="#nostr">Nostr</a>

  <!-- Répertoires -->
  <a href="#btcdir">BTC Dir</a>
  <a href="#bitzy">Bitzy</a>

  <!-- Outils -->
  <a href="#json2map">json2map</a>
  <a href="#omnitools">OmniTools</a>
  <a href="#aiscience">AI Science</a>

  <!-- Données réseau -->
  <a href="#mempool">Mempool.space</a>
  <a href="#timechaincalendar">Timechain Calendar</a>

  <!-- Analyse -->
  <a href="#clarkmoody">Clark Moody</a>
  <a href="#wickedbitcoin">Wicked Smart Bitcoin</a>
  <a href="#bitbo">bitbo.io</a>
</footer>

</body>
</html>
