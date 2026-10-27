---
name: website-legal-check-at
description: Rechtlicher Website-Check nach österreichischem Recht (mit DE-Hinweisen), gestaffelt nach Projekttyp – Landingpage, Unternehmenswebsite, Onlineshop, SaaS/Abo. Prüft Rechtstexte und deren Anzeige, Datenschutz und Auftragsverarbeitungsverträge, Barrierefreiheit (BaFG), Widerrufsbutton, Abo-Verlängerung, Payments und KI-Kennzeichnung. Verwenden, wenn eine Website vor dem Go-Live oder im Jahres-Check rechtlich geprüft werden soll.
---

# Website Legal-Check (Österreich / DACH)

Prüft eine geschäftliche Website vor dem Go-Live oder im jährlichen Re-Check. Rechtsrahmen Österreich: ECG, MedienG, DSGVO/DSG, TKG 2021, FAGG, KSchG, BaFG, AI Act. Bei Zielmarkt Deutschland zusätzlich: DDG, TDDDG, BFSG, BGB.

## Grundregeln

- **Keine Rechtsberatung.** Der Check prüft, ob die nötigen Dokumente und Funktionen *vorhanden, korrekt eingebunden und mit der Technik konsistent* sind. Ob ein Rechtstext inhaltlich richtig ist, beurteilt ein Anwalt. Jeder Bericht trägt diesen Hinweis.
- **Aktualität zuerst.** Stand dieses Skills: Oktober 2026. Vor jedem Check per Websuche nach Änderungen suchen, mindestens: „WKO Internetrecht aktuell“, „FAGG Änderung“, „Barrierefreiheitsgesetz“, „AI Act Artikel 50“, „Abmahnung Website aktuell“. Neue Pflichten in den Bericht aufnehmen und darauf hinweisen, dass `references/checkliste.md` aktualisiert werden sollte.
- **Selbst nachsehen statt annehmen.** Seiten tatsächlich öffnen (Fetch oder Browser): Footer-Links, Cookie-Banner, Netzwerk-Requests vor Einwilligung, Checkout, Widerrufs- und Kündigungsfunktion. Was nicht prüfbar ist (z. B. abgeschlossene AVVs), als ⚠️ markieren und beim Nutzer erfragen.
- **Status je Punkt:** ✅ erfüllt · ⚠️ zu klären / vom Betreiber zu liefern · ❌ fehlt (blockiert Go-Live) · — nicht anwendbar (immer mit Begründung).

## Ablauf

1. **Eckdaten erfragen** (nur was fehlt, eine Frage nach der anderen):
   - URL (Live oder Staging) und Art der Website
   - Zielgruppe: Verbraucher (B2C), Unternehmen (B2B) oder beides
   - Zielmärkte (nur AT, auch DE, EU-weit)
   - Größe des Betreibers: Beschäftigte und Jahresumsatz bzw. Bilanzsumme (für die BaFG-Ausnahme)
   - Eingesetzte Dienste (Hosting, CDN, Mail, Analytics, Fonts, Embeds, Shop-System, Zahlungsanbieter, Newsletter, Chatbot)
   - Funktionen: Shop, Abo, Accounts/Login, Terminbuchung, Newsletter, KI-Chatbot, Nutzerinhalte, Ads-Tracking
   - Reglementierter Beruf? (z. B. Ärztin, Psychologe, Anwalt, Steuerberater)
2. **Klassifizieren** nach der Tabelle unten und die gewählten Module in einer Zeile nennen.
3. **Aktualitäts-Recherche** (siehe Grundregeln).
4. **Module abarbeiten** – nur die ausgelösten. Die vollständigen Prüfpunkte stehen in `references/checkliste.md`; diese Datei vor dem Prüfen lesen. Zu jedem Punkt Status + Fundstelle (URL, Beobachtung, Screenshot).
5. **Bericht erstellen** nach `templates/bericht-vorlage.md`: Ergebnis GO/NO-GO oben, dann offene Punkte mit Verantwortlichem und Frist, dann die Module, dann das Dienste-Inventar, zuletzt die Quellen.

## Klassifizierung

Entscheidend ist, was auf der Seite passiert, nicht wie sie heißt.

1. Kann ein Verbraucher online einen Vertrag schließen (Kauf, Buchung, Abo, kostenpflichtige Registrierung)? → **Modul D**
2. Gibt es wiederkehrende Zahlungen, Accounts oder eine Web-App? → **Modul E**
3. Wenn 1 = Ja: Ist der Betreiber **kein** Kleinstunternehmen (Kleinstunternehmen = weniger als 10 Beschäftigte UND Jahresumsatz oder Bilanzsumme höchstens 2 Mio. €)? → **Modul C**. Die Ausnahme gilt nur für Dienstleister, nicht für Hersteller oder Händler von Produkten, die selbst unter das BaFG fallen.
4. Nur B2B? → C entfällt, D großteils.
5. Chatbot, Newsletter, Buchung, Login, Nutzerinhalte, Werbe-Tracking? → passende Blöcke aus **Modul F**

| Website-Art | Module |
| --- | --- |
| One-Pager, Landingpage | A, B, F nach Funktion |
| Unternehmenswebsite | A, B, F; bei verbindlicher B2C-Buchung zusätzlich C und D |
| Onlineshop (eigenes System, Shopify, WooCommerce …) | A, B, C (außer Kleinstunternehmen), D, F; E bei Abo-Produkten |
| Web-App / SaaS | A, B, E, F; bei B2C zusätzlich C und D |

Hinweis: Schon ein Formular, über das ein Verbrauchervertrag zustande kommt (z. B. verbindliche Online-Buchung), kann das BaFG auslösen. Ein reines Anfrageformular nicht.

## Module (Kurzüberblick – Details in references/checkliste.md)

- **A Basis (immer):** Rechtstexte erreichbar, Impressum (§ 5 ECG) und Offenlegung (§ 25 MedienG), Cookie-Einwilligung (§ 165 TKG 2021), technische Datenschutz-Basics, Formulare, Urheber- und Bildrechte, Impressum in E-Mails/Social Media, Marken-/Domainrecht.
- **B Datenschutz & AVVs (immer):** Dienste-Inventar mit AVV-Status und Drittlandtransfer, Abgleich Datenschutzerklärung ↔ tatsächlich eingesetzte Technik, interne Pflichten.
- **C Barrierefreiheit (BaFG):** Anwendbarkeit, Anforderungen nach EN 301 549 / WCAG AA, Barrierefreiheitserklärung.
- **D Onlineshop / B2C-Vertrag:** Rechtstexte, vorvertragliche Infos (§ 4 FAGG), Checkout und Bestellbutton, Widerrufsbutton (§ 13a FAGG), Bestätigungen, produktspezifische Pflichten, Geoblocking, Verpackung.
- **E SaaS / Abo / Payments:** Vertragsdokumente, Abo-Abschluss und Gratis-Tests, Verlängerungs-Hinweis (§ 6 Abs 1 Z 2 KSchG), Kündigung, Payments (PSD2, SEPA, USt/OSS), Account-Löschung, Datenexport, EU Data Act.
- **F Sonderfunktionen:** KI-Chatbot (AI Act Art. 50), Newsletter (§ 174 TKG), Terminbuchung, Login-Bereich, Nutzerinhalte, Werbe-Tracking.

## Abschluss

- **GO** nur, wenn kein ❌ offen ist. Jedes ⚠️ bekommt einen Verantwortlichen und ein Datum.
- Jedes „nicht anwendbar“ wird begründet (z. B. „BaFG: Kleinstunternehmen, 3 Beschäftigte, Umsatz < 2 Mio. €“).
- Nachweise empfehlen: Screenshots von Banner, Checkout, Widerrufsbutton und Footer-Links; AVVs als PDF ablegen.
- Re-Check auslösen bei: neuem Dienst oder Plugin, neuer Funktion (Shop, Abo, Chatbot), Gesetzesänderung, spätestens einmal jährlich.
