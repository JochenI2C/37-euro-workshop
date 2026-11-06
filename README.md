# GICHTKLAR 14 · Verkaufsseite für den 37-€-Workshop

Verkaufsseite für **GICHTKLAR 14**, ein 14-Tage-Ernährungssystem für Männer ab 45 mit Gicht.

## Projekt-Kontext

- **Ziel:** ein preiswertes und trotzdem werthaltiges **Einstiegsprodukt** zum Thema Gicht anbieten. Der Workshop kostet **37 € statt 199 €**, als Einmalzahlung und ohne Abo.
- **Markenumfeld:** Die Seite gehört zu Jochen Heins Gicht-Angebot neben
  - [gicht-lotse.de](https://gicht-lotse.de), der aktuellen Hauptseite
  - [gicht-coach.de](https://gicht-coach.de)
- **Corporate Identity:** übernommen von gicht-lotse.de und gicht-coach.de
  - Hauptfarbe Blau `#3383C5`, dunkles Blau `#1159AF` (Button-Hover, Eyebrow, Garantie)
  - Akzent Orange `#FF8533` (durchgestrichener Preis)
  - Überschriften `#1A202C`, Text `#2D3748`, Nebentext `#718096`, Hellblau-Fläche `#EAF3FB`
  - Schrift Helvetica
- **Verkaufsplattform:** [bryght.social](https://bryght.social). Beide Buttons verlinken auf den Bestell-Link dort.
- **Veröffentlichung:** Die URL steht noch nicht fest.
- **Layout-Vorlage:** [jens-neubeck.com/pre_kurs_strategie](https://jens-neubeck.com/pre_kurs_strategie). Zweispaltiger Aufbau: Kopf zentriert, links das Produkt-Cover, rechts Bullets, Preis und Button. Danach folgen Story, Kundenstimmen, Autoren-Block, Garantie, zweiter Button und Footer.

## Lokal ansehen

`index.html` doppelklicken. Die Seite öffnet sich im Browser, ein Server ist nicht nötig.

## Aufbau

- `index.html`: die komplette Seite (HTML und CSS in einer Datei)
- `bilder/cover.png`: 3D-Box-Mockup GICHTKLAR 14 (720 × 960 px, transparenter Hintergrund)
- `bilder/logo-web.jpg`: Gicht-Lotse-Logo für den Seitenkopf (520 px breit, aus `logo/gicht-lotse-logo-quer.jpg`)
- `bilder/favicon.png`: Browser-Icon (180 px, aus `logo/gicht-lotse-icon-quadrat.webp`)
- `bilder/logo/`: alle Original-Logo-Varianten (quer, 16:9, quadratisch, nur das G-Icon)
- `bilder/autor.jpg`: Autoren-Foto (Foto: Aljoscha Habel); `bilder/autor.svg` springt ein, falls es fehlt
- `docs/lovable-prompt.md`: fertiger Prompt, um die Seite in Lovable zu bauen
- `docs/copy-notizen.md`: Produktnamen und Hinweise zur Copy
- `docs/mockup/box.html`: Quelle des Box-Mockups (HTML/CSS 3D). Texte und Farben dort ändern und neu rendern, der Befehl steht oben in der Datei
- `docs/mockup/gichtklar14-box-1080x1440.png`: Box-Mockup in voller Größe, z. B. für Social Media oder bryght.social
- `docs/referenz/mockup-pre-kurs-strategie.webp`: Box-Mockup aus dem Referenzprojekt, als Vorlage für ein eigenes GICHTKLAR-14-Cover. **Nicht selbst auf der Seite verwenden.**

## Noch offen

- [ ] Bestell-Link von bryght.social an beiden Buttons einsetzen. Vorläufig verlinken sie auf https://gicht-coach.de/ernaehrungsratgeber/
- [x] Eigenes 3D-Box-Mockup für GICHTKLAR 14 im Stil der Referenz erstellt und als Cover eingesetzt
- [x] Farben und Schriften von gicht-lotse.de und gicht-coach.de übernommen
- [x] Drei Kundenstimmen von gicht-coach.de übernommen (Thomas, Michael, Monika; Hinweis auf Einzelberatung im Footer)
- [x] Impressum und Datenschutz verlinkt (gicht-lotse.de/impressum, gicht-lotse.de/datenschutz)
- [ ] Datenschutzerklärung auf gicht-lotse.de um diese Seite ergänzen: Hosting über GitHub Pages, Verkauf über bryght.social
- [ ] Impressum prüfen: „§ 5 TMG“ auf „§ 5 DDG“ aktualisieren; als Heilpraktiker ggf. Berufsbezeichnung und zuständige Aufsichtsbehörde angeben
- [x] Autoren-Foto hinzugefügt (Bildnachweis: Aljoscha Habel, ggf. im Impressum nennen)
- [ ] Veröffentlichungs-URL festlegen
