# Repository-Regeln

- Dieses Repository gehört zur Website avitpac.de.
- Arbeite standardmäßig auf dem Branch `main`.
- Bei Website-Änderungen bestehendes Design und bestehende Funktionen möglichst beibehalten.
- Netlify Forms, Kontaktformular, WhatsApp-Link, Impressum und Datenschutz dürfen nicht versehentlich beschädigt werden.
- Netlify übernimmt anschließend automatisch das Deployment.

## Standardablauf für Änderungswünsche

- Normale Änderungswünsche in diesem Repository beziehen sich automatisch auf avitpac.de. Der Nutzer muss weder avitpac.de noch `AGENTS.md`, GitHub, Netlify, den Branch `main`, das Committen oder das Pushen ausdrücklich erwähnen.
- Bei jedem eindeutigen Änderungswunsch automatisch die passenden Dateien im Repository bearbeiten.
- Dabei bestehende Funktionen und das bestehende Design möglichst beibehalten.
- Vor größeren strukturellen Änderungen automatisch vom aktuellen Stand einen Backup-Branch im Format `backup-vor-grossen-aenderungen-YYYY-MM-DD` erstellen und zu GitHub pushen. Existiert der Name bereits, eine fortlaufende Endung wie `-2`, `-3` usw. ergänzen.
- Nach der Änderung die betroffenen Dateien und den resultierenden Diff prüfen.
- Anschließend ausschließlich die beabsichtigten Änderungen committen und auf `main` pushen.
- Nur nachfragen, wenn der Änderungswunsch wirklich unklar ist oder mehrere deutlich unterschiedliche Umsetzungen möglich sind.

Beispiele für vollständige Änderungswünsche sind:

- „Ändere den Text im Hero-Bereich.“
- „Mach den Kontaktbereich moderner.“
- „Füge einen neuen Abschnitt für Lieferanten hinzu.“
- „Mach die Überschrift größer.“
- „Ändere die Telefonnummer im Footer.“
- „Baue einen neuen Bereich für Geschäftspartner ein.“
