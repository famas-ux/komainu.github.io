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

<div id="nostr-widget" style="max-width:600px;margin:0 auto;"></div>

<script src="https://unpkg.com/nostr-blog-widget@latest/dist/index.js"></script>
<script>
  new NostrBlogWidget({
    el: document.getElementById('nostr-widget'),
    pubkey: 'npub1yh2aytq422srfl54ul3qs7q2n0atx4fdfw95zdzfvznyz2njhckqg6l33l',
    limit: 5
  });
</script>
