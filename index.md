---
layout: home
title: Home
---

# Journal de bord

fait avec ❤️ par famas

[MISSION DESTROY FIAT](https://app.bullbitcoin.com/registration/famas)

<div class="card-btc">
  <div class="card-btc-header">
    <span class="card-btc-title">Bitcoin · Prix en euros</span>
    <span class="card-btc-source">donnée temps réel</span>
  </div>

  <div class="card-btc-price">
    <span id="btc-eur">—</span>
  </div>

  <p class="card-btc-text">
    Le prix affiché correspond au cours moyen du bitcoin exprimé en euros,
    mis à jour automatiquement. Il reflète l’équilibre instantané entre l’offre
    et la demande sur les principaux marchés internationaux.
  </p>
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
    document.getElementById("btc-eur").textContent = "—";
  }
}
updateBTCPrice();
setInterval(updateBTCPrice, 60000);
</script>


- [About]({{ "/about" | relative_url }})
