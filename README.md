# DER PROJEKTMACHER – Website V16 (Prelaunch)

## Upload auf GitHub Pages
Alle Dateien und Ordner dieses Pakets in das Root-Verzeichnis des GitHub-Repositories hochladen. Die Ordnerstruktur muss erhalten bleiben.

Wichtige Dateien:
- `index.html` – einzige Startseite für Desktop **und** Mobil
- `assets/css/site.css` – gemeinsames responsives Design für Startseite und Unterseiten
- `erfahrung-kompetenz.html` – vorbereitete Kompetenz-Unterseite
- `impressum.html` / `datenschutz.html` – vorläufige Rechtstexte mit klar markierten Ergänzungen
- `404.html`, `logo.svg`, `favicon.svg`, `CNAME`, `.nojekyll`, `robots.txt`, `sitemap.xml`

## Desktop und Mobil – keine zwei Websites
Es gibt **keine zweite mobile Homepage**. Dieselbe URL und dieselbe `index.html` werden verwendet. Ab 760 px und darunter passt `assets/css/site.css` Darstellung, Textmenge, Größen und Abstände automatisch an. Das gilt auch für alle bestehenden und zukünftigen Unterseiten.

### Vorgabe für zukünftige Unterseiten
1. Immer dieselbe `assets/css/site.css` einbinden.
2. Keine separaten `mobile.html`-Seiten oder `m.`-Subdomain anlegen.
3. Wichtigste Inhalte auf Desktop und Mobil identisch halten.
4. Mobil: kurze Überschriften, kurze Einleitungen, Details auf Unterseiten oder in aufklappbaren Bereichen.
5. E-Mail bzw. primäre Kontaktmöglichkeit nur gezielt und nicht mehrfach auf jeder Seite wiederholen.
6. Keine geplante Ausbildung oder Berechtigung als vorhandene Qualifikation darstellen.

## Prelaunch-Modus
Diese Version ist bewusst als **zukünftiges Gewerbe im Aufbau** gekennzeichnet:
- Geschäftsbetrieb noch nicht aufgenommen
- keine Auftragsannahme
- alle HTML-Seiten enthalten `meta robots="noindex,nofollow"`

### Vor dem offiziellen Gewerbestart
- Gewerbewortlaut / Berechtigungsumfang mit WKO bzw. zuständiger Stelle final prüfen
- Impressum vollständig ausfüllen
- Datenschutzerklärung an tatsächlich eingesetzte Dienste anpassen
- Kompetenzprofil nur mit belegbaren, tatsächlich vorhandenen Qualifikationen befüllen
- Formulierungen „geplant / im Aufbau“ auf den tatsächlichen Geschäftsbetrieb umstellen
- `noindex,nofollow` aus den HTML-Seiten entfernen
- `robots.txt`, `sitemap.xml`, Canonical-Tags und strukturierte Daten final prüfen
- danach Google Search Console, Google Unternehmensprofil und Bing Webmaster Tools einrichten

## Designprinzip
Mobile-first: weniger Text, größere Marke, klare Informationshierarchie. Details gehören auf Unterseiten, nicht in den Onepager.
