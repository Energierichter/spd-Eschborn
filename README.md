# SPD Eschborn – Online-Antragsformular

Online-Version des Formulars „Anträge an die Stadtverordnetenversammlung“.
Vorschläge gehen per E-Mail an **vorstand@spd-eschborn.de**.

- `index.html` – Formular
- `danke.html` – Bestätigungsseite nach dem Absenden

## Versand (FormSubmit)

Das Formular sendet über [FormSubmit](https://formsubmit.co) (kostenlos, ohne Konto).

1. **Einmalige Aktivierung:** Nach dem ersten Testabsenden schickt FormSubmit eine Bestätigungsmail an vorstand@spd-eschborn.de. Erst nach Klick auf „Activate Form“ werden Vorschläge zugestellt.
2. **Optional – Adresse verbergen:** Die Aktivierungsmail enthält einen zufälligen Alias (z. B. `https://formsubmit.co/abc123…`). Diesen in `index.html` im `action`-Attribut statt der Klartext-Adresse eintragen, damit Spam-Bots die Adresse nicht aus dem Quelltext lesen.
3. Anhänge: bis zu 3 Dateien, zusammen max. 10 MB (Limit von FormSubmit).
4. Spam-Schutz: Captcha von FormSubmit + verstecktes Honeypot-Feld.

## Veröffentlichung (GitHub Pages)

Settings → Pages → Source: „Deploy from a branch“, Branch `main`, Ordner `/ (root)`.
Adresse: https://energierichter.github.io/spd-Eschborn/

## Vor dem Livegang prüfen

- Links zu Impressum und Datenschutz (`https://www.spd-eschborn.de/impressum` bzw. `/datenschutz`) – stimmen die Adressen?
- Datenschutzerklärung von spd-eschborn.de um die Nutzung von FormSubmit ergänzen.
- Freigabe durch den Vorstand.
