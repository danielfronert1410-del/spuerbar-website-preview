# ✅ Quelle der Wahrheit — spuerbar-ich-sein.de

**Stand: 2026-08-02.** Dieser Ordner ist die **einzige** maßgebliche Quelle
für die Live-Website. Er ist ein Klon des Deploy-Repos
**`danielfronert1410-del/spuerbar-website-preview`** (Branch `main`), aus dem
**Hostinger** per Git-Auto-Deploy direkt `public_html` befüllt.

## Arbeitsregeln (nie wieder gegenseitiges Überschreiben)
1. **Vor jeder Änderung:** `git pull` (aktuellen Live-Stand ziehen).
2. **Direkt HTML/Assets editieren** — kein `gen.mjs`-Rebuild. Die alte
   Pipeline liegt archiviert unter `../_ARCHIV-spuerbar-website-gen.mjs/`.
3. **Immer nur einer** editiert+deployt zur Zeit (Daniel ODER Steffi),
   vorher kurz abstimmen.
4. **Deploy** = Commit + Push nach `origin/main` → Hostinger geht live
   (ggf. in Hostinger „Bereitstellen" + CDN-Cache leeren).

## Referenz-Stand bei Anlage
HEAD `98235d5` (30.07.2026) — enthält Steffis kompletten Live-Stand:
33 Seiten, eigene Fonts, Presse-Bilder, Burnout-Seite, llms.txt, VFP-Siegel +
Social-Icons sitewide, große SEO-Vertiefung (Narzissmus/Panik/Angst), Geo-
Feinschliff, Buch-Slug-Redirects.
