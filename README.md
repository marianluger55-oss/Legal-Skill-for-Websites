# website-legal-check-at

Ein Claude-Skill für den rechtlichen Check geschäftlicher Websites nach **österreichischem Recht** (mit Hinweisen für Deutschland). Der Check ist nach Projekttyp gestaffelt: Eine Landingpage bekommt den schlanken Basis-Check, ein Onlineshop oder eine SaaS mit Abo den vollen.

> **Keine Rechtsberatung.** Der Skill prüft, ob Rechtstexte und Pflichtfunktionen vorhanden, korrekt eingebunden und mit der Technik konsistent sind. Ob ein Text inhaltlich stimmt, beurteilt ein Anwalt. Stand der Inhalte: Oktober 2026 – der Skill sucht vor jedem Check selbst nach neuen Gesetzesänderungen.

## Was geprüft wird

| Modul | Wann | Inhalt |
| --- | --- | --- |
| A Basis | immer | Impressum (ECG), Offenlegung (MedienG), Erreichbarkeit der Rechtstexte, Cookie-Einwilligung (TKG 2021), Fonts/Embeds, Formulare, Bildrechte |
| B Datenschutz & AVVs | immer | Dienste-Inventar mit AVV-Status, Drittlandtransfer, Abgleich Datenschutzerklärung ↔ Technik |
| C Barrierefreiheit | B2C-Vertragsabschluss, kein Kleinstunternehmen | BaFG-Anwendbarkeit, WCAG-AA-Anforderungen, Barrierefreiheitserklärung |
| D Onlineshop / B2C | Verbraucher schließen online Verträge | FAGG-Infos, Bestellbutton, Widerrufsbutton (§ 13a FAGG), Geoblocking, Produktpflichten |
| E SaaS / Abo / Payments | Abos, Accounts, Web-Apps | Abo-Abschluss, Gratis-Tests, Verlängerungshinweis (§ 6 KSchG), Kündigung, PSD2, OSS, Data Act |
| F Sonderfunktionen | je nach Funktion | KI-Chatbot (AI Act Art. 50), Newsletter, Terminbuchung, Login, Bewertungen, Werbe-Tracking |

## Aufbau

```
website-legal-check-at/
├── SKILL.md                    # Ablauf, Klassifizierung, Grundregeln
├── references/checkliste.md    # alle Prüfpunkte im Detail + Quellen
└── templates/bericht-vorlage.md
```

## Installation

**Claude Code:** Ordner nach `~/.claude/skills/` (persönlich) oder `.claude/skills/` im Projekt kopieren.

```bash
git clone <repo-url>
cp -r website-legal-check-at ~/.claude/skills/
```

**Claude-App (claude.ai / Desktop):** Ordner als ZIP packen (der Ordner selbst muss im ZIP liegen) und in den Einstellungen unter den Skills hochladen.

## Verwendung

Zum Beispiel:

- „Mach einen Legal-Check für https://example.at“
- „Prüfe meinen Shop vor dem Go-Live rechtlich“
- „Jahres-Check für unsere SaaS-Website“

Der Skill fragt die fehlenden Eckdaten ab (B2C/B2B, Größe des Unternehmens, eingesetzte Dienste, Funktionen), ordnet die Website ein, recherchiert aktuelle Änderungen, prüft die Seite selbst und liefert einen Bericht mit GO/NO-GO und einer Liste offener Punkte.

## Aktualisieren

Die Prüfpunkte stehen in `references/checkliste.md`. Ändert sich die Rechtslage, dort anpassen und das Stand-Datum in `SKILL.md` erneuern. Pull Requests willkommen.

## Lizenz

MIT – siehe `LICENSE`.
