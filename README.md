# Modulo — Atelier für erfahrungsbasierte Supervision

Website-Entwurf, zusammengeführt aus zwei KI-generierten Vorschlägen (Banani,
Google Stitch) plus der gemeinsam entwickelten Konzeptarbeit (Metaphern,
Farbprinzip, Struktur, Copy).

## Stand

`index.html` ist ein einzelner, statischer One-Pager-Entwurf zur Durchsicht.
Bilder in `images/` stammen aus den beiden KI-Entwürfen (Platzhalter, keine
eigene Fotografie) und sind entsprechend als vorläufig zu behandeln.

Offene Punkte, bevor das live gehen kann:

- Eigene Fotografie statt der KI-generierten Platzhalterbilder
- Echte Biografie/Foto in „Über mich" (Name, Kongress-Teilnahme)
- Adresse in Potsdam eintragen
- Preise prüfen (aktuell aus dem Banani-Entwurf übernommen, nicht final)
- Kontaktformular an ein echtes Backend/E-Mail-Ziel anbinden

## Technik

Gestaltet mit [Tailwind CSS](https://tailwindcss.com) v4, nach denselben
Konventionen wie der Übungskatalog: Farben als semantische Tokens
(`primary`, `muted`, `border` …) in `src/styles.css`, Layout direkt als
Utility-Klassen in `index.html`. Wiederkehrende Bausteine (`.btn`,
`.btn-outline`, `.card`, Formularfelder) stehen dort als Komponenten-Klassen.

Die gebaute Datei `assets/styles.css` ist eingecheckt, damit die Seite ohne
Build-Schritt läuft (z. B. auf GitHub Pages). Nach Änderungen an Klassen oder
Tokens neu bauen:

```bash
npm install
npm run build   # einmalig
npm run dev     # baut bei jeder Änderung neu
```

## Gestaltungsprinzip

Petrol (`#2B4A45`) ist die einzige gestaltete Akzentfarbe — sie steht für
Struktur und Methode. Jede andere Farbe darf ausschließlich durch echte
fotografierte Materialien ins Bild kommen, nie durch Gestaltung.
