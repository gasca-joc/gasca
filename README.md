# Banii pe bune – Chestionar

Chestionar pentru proiectul liceului despre banii adolescenților. Site static (un singur fișier). Răspunsurile se trimit către Google Sheets prin Google Apps Script și se păstrează și local, în browser.

## Publicare pe GitHub Pages

1. Creează un repository public, de ex. `NUME.github.io` sau `banii-pe-bune`.
2. Încarcă `index.html`, `README.md` și `.nojekyll` (Add file → Upload files, trage fișierele, nu folderul).
3. **Settings → Pages**: Source = *Deploy from a branch*, Branch = `main`, `/ (root)`.
4. Site-ul apare la `https://NUME.github.io` (sau `https://utilizator.github.io/banii-pe-bune`).

Pentru un domeniu propriu, adaugă la Custom domain `subdomeniu.domeniul-tau.ro` și un CNAME în DNS către `utilizator.github.io`.

## Fișiere

- `index.html`: site-ul, identic cu `Site_banometrie_final.html`
- `.nojekyll`: publică fișierele exact cum sunt
