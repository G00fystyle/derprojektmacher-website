# DER PROJEKTMACHER V16.8

Designversion vom 3. Oktober 2026. Grundlage: die aktuell veröffentlichte Website auf derprojektmacher.eu und die Änderungswünsche im referenzierten Gespräch. Das frühere ChatGPT-ZIP V16.7 war hier nicht als Datei verfügbar. Dieses Paket enthält sämtliche lokal verlinkten Seiten und Assets der veröffentlichten Website.

## GitHub aktualisieren

ZIP entpacken und den gesamten Inhalt ins bestehende Website-Repository übernehmen: insbesondere index.html, kontakt.html und assets/css/site.css. Auch Unterseiten übernehmen: sie verwenden die versionierte CSS-Adresse und einheitliche Kontaktlinks. CNAME und .nojekyll liegen im Stammverzeichnis. Keine zusätzliche v16.8-Unterordnerebene veröffentlichen. Anschließend die Seite neu laden.

## Änderungen

- Hero-Headline dunkelblau; Claim ausschließlich im Logo sichtbar.
- Gemeinsame USP-Überschrift für Desktop und Mobil; Planungssatz als eigener sichtbarer Absatz.
- Kompakter Kontaktbereich mit orange gefüllter E-Mail-Schaltfläche, dezentem „oder“ und orange umrandetem Kontaktformular.
- Kontakt- und E-Mail-Links öffnen einen neuen Kontext; Datenschutzlink im Formular ebenfalls, damit Eingaben erhalten bleiben.
- Orange dekorative Trennlinien auch aus den alten CSS-Regeln entfernt.
- Desktop-Symbole im dunklen Stärkenband sichtbar gezeichnet.
- Versionsparameter am CSS verhindert die Verwendung der alten zwischengespeicherten CSS-Datei nach dem Upload.
- Prelaunch-Banner genau einmal je Seite; noindex,nofollow beibehalten.

## Formular und V17

V16.8 enthält die Formulargestaltung mit den bestehenden Feldern und Dateiauswahl, aber keine Microsoft-365-Integration und keinen funktionsfähigen Versand. Dies wird direkt oberhalb der Felder erklärt; die Sendeschaltfläche bleibt deaktiviert. Die vorhandene Basin-Platzhalterkonfiguration ist keine aktive Verbindung. V17 bleibt für die Microsoft-365-Anbindung reserviert. Mailto verwendet die vom Besucher konfigurierte Mail-App oder Webmail-Zuordnung; ein bestimmter Mailanbieter wird nicht erzwungen.

## Prüfungen

Alle sechs Seiten separat in Desktop- (1440 Pixel) und Mobilansicht (390 Pixel) visuell geprüft. Startseite und Kontaktseite zusätzlich bei 320, 768 und 1024 Pixeln auf horizontalen Überlauf geprüft: keiner festgestellt. Startseite vollständig durchgesehen, mobile Details bedienbar und CTA-Gestaltung kontrolliert. Der Kontaktformularlink öffnete im Browser einen zweiten Tab, während die Startseite offen blieb. E-Mail-Linkadresse und target=_blank geprüft; kein E-Mail-Versand ausgelöst. Alle relativen Datei-Verweise auf vorhandene Ziele geprüft. ZIP auf Integrität geprüft.

Impressum und Datenschutz behalten ihre vorhandenen Platzhalter und den vorläufigen Inhalt; sie sind inhaltlich noch nicht für den Geschäftsbeginn vervollständigt. Keine Live-Veröffentlichung vorgenommen.
