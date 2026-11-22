# Gașca – Cât costă să fii în gașcă?

Proiect educațional pentru elevi: chestionar, joc de 10 runde, jurnal de 14 zile, rapoarte personale, cutie cu scripturi și statistici. Site static (un singur fișier), datele se salvează local în browser.

## Publicare pe GitHub Pages cu domeniul gasca.[domeniul-tău]

1. Creează un repository public pe GitHub, de ex. `gasca`, și încarcă toate fișierele din acest folder (inclusiv `.nojekyll`).
2. **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder `/ (root)`.
3. **Settings → Pages → Custom domain**: scrie `gasca.domeniul-tău.ro` și salvează. Bifează *Enforce HTTPS* când devine disponibil.
4. La furnizorul domeniului, adaugă în DNS o înregistrare:

| Tip | Nume (Host) | Valoare |
|---|---|---|
| CNAME | `gasca` | `UTILIZATORUL-TĂU.github.io` |

DNS-ul poate dura de la câteva minute la câteva ore. Apoi site-ul apare la `https://gasca.domeniul-tău.ro`.

## Fișiere

- `index.html`: site-ul, identic cu fișierul original `gasca.html`
- `.nojekyll`: spune GitHub Pages să publice fișierele exact cum sunt
