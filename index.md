---
layout: page
title: Journal de bord
permalink: /
---

<!-- Menu -->
- [Home](/)
- [About](/about/)
- [Bull Wallet](/bull-wallet/)

<!-- Pastille Komainu centrée -->
<p style="text-align:center;">
  <img src="Komainu.PNG" alt="Komainu" style="width:120px;height:120px;border-radius:50%;border:2px solid #0f0;margin-bottom:20px;">
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
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%d %B %Y" }}
{% endfor %}
