---
layout: page
title: "Boîte à outils"
permalink: /boite-outils-bitcoin/
date: 2025-12-26
categories: [bitcoin, outils]
---

<style>
body {
    font-family: Arial, Helvetica, sans-serif;
    background-color: #0d0d0d;
    color: #c0ffc0;
    margin: 0;
    padding-top: 70px; /* pour laisser la place au menu fixe */
    line-height: 1.8;
}

.container {
    max-width: 800px;
    margin: auto;
}

h1 {
    text-align: center;
    font-size: 32px;
    color: #00ff66;
    margin-bottom: 25px;
}

/* Menu fixe en haut */
nav {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background-color: #111111;
    padding: 10px 0;
    text-align: center;
    z-index: 1000;
    border-bottom: 2px solid #00ff66;
}

nav a {
    margin: 0 12px;
    color: #00ff66;
    font-weight: bold;
    text-decoration: none;
    transition: color 0.2s;
}

nav a:hover {
    color: #a0ffa0;
    text-decoration: underline;
}

.card {
    background-color: #1a1a1a;
    border-left: 4px solid #00ff66;
    border-radius: 10px;
    padding: 20px;
    margin: 20px 0;
    transition: transform 0.2s, box-shadow 0.2s;
}

.card:hover {
    transform: scale(1.02);
    box-shadow: 0 0 10px #00ff66;
}

.card h2 {
    color: #00ff66;
    margin-top: 0;
}

.card ul {
    padding-left: 20px;
}

.card ul li {
    margin-bottom: 8px;
}

.card a {
    color: #00ff66;
    font-weight: bold;
    text-decoration: none;
}

.card a:hover {
    text-decoration: underline;
}

em {
    color: #a0ffa0;
}

@media (max-width: 600px) {
    .container {
        padding: 10px;
    }
    .card {
        padding: 15px;
    }
    nav a {
        display: block;
        margin: 5px 0;
    }
}
</style>

<div class="container">

<h1>Boîte à outils Bitcoin</h1>

<nav>
  <a href="#tempmail">Temp-Mail</a>
  <a href="#protonmail">Proton Mail</a>
  <a href="#protonauth">Authenticator</a>
  <a href="#protondrive">Proton Drive</a>
  <a href="#protonwallet">Proton Wallet</a>
  <a href="#aiscience">AI Science</a>
  <a href="#nostr">Nostr</a>
</nav>

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

</div>
