---
layout: page
title: Journal de bord
permalink: /
---

<!-- Pastille Komainu centrée -->
<p style="text-align:center;">
  <img src="Komainu.PNG" alt="Komainu" style="width:150px;height:150px;border:1px solid #000;margin-bottom:20px;">
</p>

# Journal de bord

fait avec ❤️ par famas

[MISSION DESTROY FIAT](https://app.bullbitcoin.com/registration/famas)

<div class="btc-price-home">
  <small>Bitcoin (EUR)</small><br>
  <strong id="btc-eur">—</strong>
</div>

<script>
async function updateBTCPrice() {
  try {
    const r = await fetch(
      "https://api.coingecko.com/api/v3/simple/price?ids=bitcoin&vs_currencies=eur"
    );
    const d = await r.json();
    document.getElementById("btc-eur").textContent =
      d.bitcoin.eur.toLocaleString("fr-FR", {
        style: "currency",
        currency: "EUR"
      });
  } catch {
    document.getElementById("btc-eur").textContent = "Erreur";
  }
}

updateBTCPrice();
setInterval(updateBTCPrice, 60000);
</script>

## Derniers posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%d %B %Y" }}
{% endfor %}

## Nostr Feed

<!-- Embed direct du profil Yakihonne -->
<iframe
  src="https://yakihonne.com/profile/nprofile1qqszt4wj9s249gp5l6270csg0q9fh74n25k5hz6px3ykpfjp9fetutq7hxjv4/embed"
  style="width:100%;max-width:600px;height:400px;border:none;"
  loading="lazy">
</iframe>