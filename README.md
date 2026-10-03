# DER PROJEKTMACHER – Website V16.4 (Prelaunch)

## Upload auf GitHub Pages
Alle Dateien und Ordner dieses Pakets in das Root-Verzeichnis des GitHub-Repositories hochladen. Die Ordnerstruktur muss erhalten bleiben.

Wichtige Dateien:
- `index.html` – einzige Startseite für Desktop **und** Mobil
- `assets/css/site.css` – gemeinsames responsives Design für Startseite und Unterseiten
- `erfahrung-kompetenz.html` – vorbereitete Kompetenz-Unterseite
- `digital-marketing.html` – Unterseite für die digitale Umsetzung
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


## Prelaunch-Hinweis
Auf der Startseite und den regulären Unterseiten steht nur ein dezenter Hinweis ganz oben: „DER PROJEKTMACHER befindet sich derzeit im Aufbau; der Geschäftsbetrieb wurde noch nicht aufgenommen.“ Der restliche Auftritt ist bereits wie die finale Website formuliert. Zum offiziellen Start wird dieser Hinweis entfernt und die Suchmaschinenfreigabe (`noindex`) angepasst.


## Änderungen V16.2
- Einsatzfelder und Leistungen auf der Startseite zu einem kompakten Schwerpunkt-Bereich zusammengeführt.
- Drei Bereiche mit Industrie-, Haus- und Personen-Icon beibehalten.
- Wiederholungen des Wortes „Projekt“ reduziert.
- Erfahrungsblock auf vier kompakte Kompetenzsignale erweitert.
- Desktop und Mobile bleiben in einer einzigen `index.html` responsive kombiniert.


## V16.3 – Digitale Leistungen
- Mobile USP vollständig: vier Punkte inkl. „Klare nächste Schritte“.
- Neuer Schwerpunkt „Digital & Marketing“ auf der Startseite.
- Neue Unterseite `digital-marketing.html` für Details zu Recruiting, Kundengewinnung, Websites, digitalen Abläufen, Anbieter-/Handwerkerrecherche sowie Angebotsvergleich/Preisspiegel.
- Die öffentliche Website nennt das DWP-System bewusst nicht als Qualifikation oder Partnerschaft. Diese Bezeichnung erst nach tatsächlich absolvierter Einschulung/aktiver Berechtigung und mit zulässiger Markenverwendung ergänzen.


## Änderungen V16.4
- Der Prelaunch-Hinweis bleibt als einziger Hinweis ganz oben: „DER PROJEKTMACHER befindet sich derzeit im Aufbau; der Geschäftsbetrieb wurde noch nicht aufgenommen.“
- „Digital & Marketing“ auf der Startseite in „Digitale Umsetzung“ überführt, damit der Bereich stärker zur Marke DER PROJEKTMACHER passt.
- Mobile Schwerpunktkarten weiter verdichtet. Die ausführlichen Inhalte bleiben über aufklappbare Details auch mobil zugänglich.
- Wichtige Inhalte werden damit nicht mehr ausschließlich über `.desktop-extra` ausgeblendet.
- Mobile Touchflächen für Details, Kompetenzprofil, Kontakt und Footerlinks vergrößert.
- Hero-Text und Kontaktformulierung sprachlich gestrafft; Wiederholungen reduziert.
- Canonical-Tags auf relevanten Unterseiten ergänzt und OpenGraph-Basisdaten auf der Startseite vorbereitet.
- Strukturierte Unternehmensdaten / LocalBusiness werden bewusst erst nach tatsächlicher Gewerbeanmeldung ergänzt.
- Zum offiziellen Start: oberen Prelaunch-Hinweis und `noindex,nofollow` entfernen, Search Console/Bing einrichten und optional einen dezenten Kontakt-CTA im Hero aktivieren.
