# Samestellende Afleiding • Graad 8 Afrikaans FAL

Interaktiewe enkel-lêer web-app met les, oefeninge (sleep & los, meerkeuse, kort antwoorde), ’n Bou-’n-woord mini-speletjie en ’n eindtoets. **Klankeffekte** en nou ook ’n **Mute/Unmute**-knoppie (onthou jou keuse via localStorage). CAPS-belyn.

## Gebruik
- **Lokaal:** Maak `index.html` in jou blaaier oop.
- **Moodle:** Voeg as *File* (Display → Embed) of *Page* met `<iframe src="...">`.
- **GitHub Pages:** Sien afdeling onder.

## Mute/Unmute
- Skakel klank aan/af met die **🔊/🔇**-knoppie in die kop. Die instelling word gehou oor sessies heen.

## GitHub Pages (Actions)
1. Nuwe repo op GitHub (bv. `samestellende-afleiding-app`), default branch `main`.
2. Push die inhoud:
   ```bash
   git clone <jou-repo-url>
   cd samestellende-afleiding-app
   # kopieer index.html + .github/workflows/pages.yml + README.md
   git add .
   git commit -m "init: app met mute/unmute"
   git push origin main
   ```
3. *Settings → Pages* → Build and deployment: **GitHub Actions** (workflow ingesluit).

## Alternatief (Deploy from branch)
- *Settings → Pages → Build from branch* → `main` en root.

## Lisensie
- Vir opvoedkundige gebruik in klasse. Pas aan soos jy wil.
