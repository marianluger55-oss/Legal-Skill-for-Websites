# Prüfpunkte im Detail

Stand: Oktober 2026. Vor Verwendung auf Aktualität prüfen (siehe SKILL.md).
Status je Punkt: ✅ erfüllt · ⚠️ zu klären · ❌ fehlt · — nicht anwendbar (mit Begründung).

---

## Modul A: Basis (jede geschäftliche Website)

### A1 Rechtstexte vorhanden und erreichbar
- [ ] Impressum, Datenschutzerklärung und (falls Cookies/Tracking) Cookie-Einstellungen von **jeder Seite** erreichbar, idealerweise im Footer, maximal 2 Klicks
- [ ] Eindeutig benannt („Impressum“, „Datenschutz“), nicht hinter Sammelbegriffen versteckt
- [ ] Auch auf Mobile, in allen Sprachversionen, auf Subdomains (Shop, Portal, Buchung) und im eingeloggten Bereich verlinkt
- [ ] Als HTML-Text, nicht als Bild oder nur als PDF
- [ ] Herkunft und Stand (Datum/Version) der Texte bekannt

### A2 Impressum (§ 5 ECG) und Offenlegung (§ 25 MedienG)
- [ ] Name bzw. Firma, Rechtsform, Sitz, Anschrift
- [ ] E-Mail für schnelle Kontaktaufnahme (Telefon empfohlen)
- [ ] Unternehmensgegenstand
- [ ] Firmenbuchnummer und Firmenbuchgericht (falls eingetragen)
- [ ] UID-Nummer (falls vorhanden)
- [ ] Zuständige Aufsichts- bzw. Gewerbebehörde, Kammerzugehörigkeit
- [ ] Reglementierte Berufe: Berufsbezeichnung, Verleihungsstaat, Kammer/Berufsverband, Hinweis auf berufsrechtliche Vorschriften
- [ ] Offenlegung nach MedienG: Medieninhaber, Unternehmensgegenstand, ggf. Beteiligungsverhältnisse, grundlegende Richtung
- [ ] **Kein Hinweis/Link mehr auf die EU-OS-Plattform** – sie wurde am 20.07.2025 abgeschaltet; auch aus AGB und E-Mail-Signaturen entfernen
- [ ] Zielmarkt DE: Verweis auf DDG statt TMG

### A3 Cookies & Einwilligung (§ 165 TKG 2021, DSGVO)
- [ ] Vor der Einwilligung werden keine nicht notwendigen Cookies/Skripte geladen (Inkognito-Fenster, Netzwerk-Tab der Entwicklertools)
- [ ] „Akzeptieren“ und „Ablehnen“ gleichwertig auf der ersten Ebene, keine vorausgewählten Häkchen
- [ ] Einwilligung jederzeit widerrufbar (dauerhafter Link „Cookie-Einstellungen“)
- [ ] Angaben im Banner und in der Datenschutzerklärung entsprechen den tatsächlich gesetzten Cookies
- [ ] Cookielose Analytics trotzdem in der Datenschutzerklärung beschrieben

### A4 Technische Datenschutz-Basics
- [ ] HTTPS auf allen Seiten, kein Mixed Content
- [ ] Schriften, Icons und Skripte lokal eingebunden (keine IP-Übertragung an Dritte ohne Grundlage, z. B. Google Fonts)
- [ ] YouTube, Karten, Social-Embeds erst nach Einwilligung (2-Klick-Lösung)
- [ ] Keine Social-Plugins, die beim Seitenaufruf Daten übertragen

### A5 Formulare
- [ ] Nur notwendige Pflichtfelder (Datenminimierung)
- [ ] Datenschutzhinweis mit Link direkt beim Formular
- [ ] Einwilligungs-Checkbox nur, wo eine Einwilligung nötig ist, nie vorausgewählt
- [ ] Verschlüsselte Übertragung; Spam-Schutz ohne Einwilligungspflicht oder mit Einwilligung
- [ ] Speicherort und Löschfrist der Anfragen festgelegt

### A6 Urheber- und Bildrechte
- [ ] Lizenzen für Bilder, Videos, Schriften, Icons dokumentiert (Quelle, Lizenz, Datum)
- [ ] Bildnachweise, wo die Lizenz sie verlangt
- [ ] Zustimmung abgebildeter Personen liegt vor
- [ ] Keine fremden Marken oder Logos ohne Nutzungsrecht
- [ ] Nutzungsrechte an KI-generierten Inhalten geklärt

### A7 Weitere Basis-Pflichten
- [ ] Impressumsangaben auch in geschäftlichen E-Mails (Signatur) und auf Social-Media-Profilen
- [ ] Domain und Firmenname auf Marken- und Namensrechte geprüft
- [ ] Prozess für Meldung und Entfernung rechtswidriger Nutzerinhalte (Kommentare, Bewertungen)
- [ ] Werbung als solche erkennbar; Gewinnspiele mit Teilnahmebedingungen
- [ ] Preisangaben passend zum Umsatzsteuerstatus („inkl. USt“ bzw. Hinweis auf Kleinunternehmerregelung)

---

## Modul B: Datenschutz-Tiefencheck & Auftragsverarbeitung

Jeder Dienst, der personenbezogene Daten verarbeitet, braucht eine Rechtsgrundlage, bei Auftragsverarbeitern einen AVV (Art. 28 DSGVO) und einen Eintrag in der Datenschutzerklärung. Wer die Website für den Betreiber hostet oder laufend betreut (Agentur, Freelancer), ist selbst Auftragsverarbeiter und braucht ebenfalls einen AVV.

### B1 Dienste-Inventar
Als Tabelle ausfüllen, eine Zeile pro Dienst:

| Dienst | Zweck | Rolle | AVV abgeschlossen am | Drittland & Grundlage | In Datenschutzerklärung | Status |
| --- | --- | --- | --- | --- | --- | --- |
| Hosting | Server | Auftragsverarbeiter | | | | |
| Agentur / Betreuer | Wartung, Support | Auftragsverarbeiter | | | | |
| CDN / DNS (z. B. Cloudflare) | Auslieferung, Schutz | Auftragsverarbeiter | | | | |
| E-Mail-Versand | Formulare, Transaktionsmails | Auftragsverarbeiter | | | | |
| Analytics | Reichweitenmessung | Auftragsverarbeiter | | | | |
| Monitoring | Verfügbarkeit | Auftragsverarbeiter | | | | |
| Office/Kalender (z. B. Google, Microsoft) | Mail, Termine | Auftragsverarbeiter | | | | |
| Shop-System | Bestellungen | Auftragsverarbeiter | | | | |
| Zahlungsanbieter | Zahlungen | meist eigener Verantwortlicher | | | | |
| Newsletter-Tool | Newsletter | Auftragsverarbeiter | | | | |
| KI-/Chatbot-Anbieter | Chat | Auftragsverarbeiter | | | | |

- [ ] Jeder AVV liegt vor (Datum, Version, Ablageort)
- [ ] US-Anbieter: Zertifizierung unter dem EU-US Data Privacy Framework aktiv geprüft, sonst Standardvertragsklauseln + Transfer-Folgenabschätzung
- [ ] Liste der Subdienstleister liegt dem Betreiber vor

### B2 Abgleich Datenschutzerklärung ↔ Technik
- [ ] Verantwortlicher mit Kontaktdaten; Datenschutzbeauftragter, falls bestellt
- [ ] **Jeder Dienst aus B1** genannt, mit Zweck, Rechtsgrundlage (Art. 6 DSGVO) und Empfänger
- [ ] Drittlandtransfers samt Grundlage
- [ ] Jedes Formular (Kontakt, Buchung, Newsletter, Bewerbung) mit Zweck und Speicherdauer
- [ ] Server-Logfiles (Inhalt, Dauer)
- [ ] Cookies/Tracking deckungsgleich mit Banner und tatsächlichem Verhalten
- [ ] Speicherdauern bzw. Löschkriterien
- [ ] Betroffenenrechte vollständig (Auskunft, Berichtigung, Löschung, Einschränkung, Übertragbarkeit, Widerspruch, Widerruf)
- [ ] Beschwerderecht bei der Aufsichtsbehörde (AT: Datenschutzbehörde)
- [ ] Profiling / automatisierte Entscheidungen, falls zutreffend
- [ ] Stand-Datum aktuell

### B3 Interne Pflichten des Betreibers
- [ ] Verarbeitungsverzeichnis (Art. 30 DSGVO) geführt bzw. Betreiber darauf hingewiesen
- [ ] Prozess für Betroffenenanfragen und Datenpannen (Meldung binnen 72 h)
- [ ] Personalisierte Admin-Konten mit 2FA, alte Zugänge entfernt
- [ ] Backups: Ort, Verschlüsselung, Aufbewahrung dokumentiert

---

## Modul C: Barrierefreiheit (BaFG, gilt seit 28.06.2025)

### C1 Anwendbarkeit
- [ ] Ist online ein Vertragsabschluss mit Verbrauchern möglich (Shop, Buchung, Abo, digitale Mitgliedschaft)? Wenn nein → nicht anwendbar, dokumentieren
- [ ] Reine B2B-Websites und private Websites sind nicht erfasst
- [ ] Kleinstunternehmen-Ausnahme geprüft (< 10 Beschäftigte UND Umsatz oder Bilanzsumme ≤ 2 Mio. €); gilt nur für Dienstleister, nicht für Hersteller/Händler von BaFG-Produkten
- [ ] Ausgenommene Websites brauchen keine Barrierefreiheitserklärung
- [ ] Buchungsstrecken auf Subdomains oder bei Drittanbietern zählen zur Website
- [ ] Betreiber über die Schwellenwerte informiert
- [ ] Zielmarkt DE: BFSG entsprechend beachten

### C2 Anforderungen (Maßstab EN 301 549 / WCAG 2.1–2.2 Stufe AA)
- [ ] Gesamte Kauf- bzw. Buchungsstrecke per Tastatur bedienbar, Fokus sichtbar
- [ ] Textkontrast mindestens 4,5:1 (große Schrift 3:1)
- [ ] Sinnvolle Alternativtexte; dekorative Bilder leer markiert
- [ ] Formulare mit sichtbaren Labels und verständlichen Fehlermeldungen
- [ ] Saubere Überschriften-Hierarchie, Landmarks, Sprachangabe
- [ ] 200 % Zoom und mobile Ansicht ohne Inhaltsverlust
- [ ] Untertitel bei Videos, kein Autoplay mit Ton
- [ ] Cookie-Banner, Dialoge und Chat-Widgets selbst barrierefrei
- [ ] Rechtstexte als barrierefreier Text
- [ ] Automatischer Test (axe, Lighthouse) plus manueller Screenreader-Test (NVDA, VoiceOver)

### C3 Barrierefreiheitserklärung
- [ ] Vorhanden und verlinkt; beschreibt die Dienstleistung und wie die Anforderungen erfüllt werden
- [ ] Nicht barrierefreie Bereiche und Gründe
- [ ] Kontakt für Rückmeldungen zu Barrieren
- [ ] Zuständige Marktüberwachung (AT: Sozialministeriumservice)
- [ ] Datum der letzten Prüfung
- [ ] Bei Berufung auf unverhältnismäßige Belastung: Begründung dokumentiert

---

## Modul D: Onlineshop & B2C-Vertragsabschluss

### D1 Rechtstexte
- [ ] AGB vor Abschluss abrufbar, speicher- und druckbar
- [ ] Rücktrittsbelehrung (Muster laut FAGG) inkl. Ausnahmen (Maßanfertigung, versiegelte Waren, digitale Inhalte …)
- [ ] Muster-Widerrufsformular verfügbar
- [ ] Rücktrittsbelehrung um Hinweis auf den Widerrufsbutton ergänzt
- [ ] Versand-, Zahlungs- und Lieferbedingungen, Lieferzeiten, Liefergebiete
- [ ] Gewährleistung (VGG) korrekt, Garantien klar getrennt
- [ ] Hinweis auf alternative Streitbeilegung nur bei Teilnahme; kein OS-Plattform-Link

### D2 Vorvertragliche Informationen (§ 4 FAGG)
- [ ] Wesentliche Eigenschaften der Ware/Leistung
- [ ] Gesamtpreis inkl. USt (bzw. Kleinunternehmer-Hinweis), Versand- und Zusatzkosten vor der Bestellung
- [ ] Grundpreis, wo vorgeschrieben
- [ ] Bei Preisermäßigungen: niedrigster Preis der letzten 30 Tage
- [ ] Identität und Kontaktdaten des Unternehmers im Bestellprozess erreichbar
- [ ] Laufzeit und Kündigungsbedingungen bei Dauerschuldverhältnissen

### D3 Bestellprozess
- [ ] Zusammenfassung vor Abschluss (Artikel, Menge, Gesamtpreis, Lieferung, Zahlungsart, Laufzeit)
- [ ] Bestellbutton eindeutig, z. B. „zahlungspflichtig bestellen“
- [ ] Eingabefehler vor Absenden korrigierbar
- [ ] AGB wirksam einbezogen; Newsletter-Opt-in getrennt und nicht vorausgewählt
- [ ] Keine Dark Patterns (vorausgewählte Zusatzleistungen, falsche Verknappung)
- [ ] Lieferbeschränkungen und Zahlungsarten spätestens zu Beginn des Bestellvorgangs
- [ ] Gastbestellung möglich oder Kontozwang begründet

### D4 Widerrufsbutton (§ 13a FAGG – Pflicht für Verträge ab 01.10.2026; in DE seit 19.06.2026)
- [ ] Funktion beschriftet mit „Vertrag widerrufen“ (Gesetzeswortlaut empfohlen)
- [ ] Hervorgehoben und leicht zugänglich, **nicht erst nach Login**
- [ ] Während der gesamten Rücktrittsfrist verfügbar
- [ ] Formular fragt nur ab: Name, Angaben zur Identifizierung des Vertrags, elektronischer Kontakt für die Bestätigung; Teilrücktritt möglich
- [ ] Absende-Schaltfläche beschriftet mit „Widerruf bestätigen“
- [ ] Unverzügliche Eingangsbestätigung auf dauerhaftem Datenträger (E-Mail) mit Inhalt, Datum und Uhrzeit
- [ ] Bei Shop-Systemen (Shopify, WooCommerce …): Lösung eingerichtet und getestet

### D5 Nach der Bestellung
- [ ] Zugangs- und Vertragsbestätigung per E-Mail mit Vertragsinhalt, AGB und Rücktrittsbelehrung
- [ ] Rechnungen mit allen Pflichtangaben
- [ ] Kundenbewertungen: Hinweis, ob und wie die Echtheit geprüft wird

### D6 Produktspezifisch (falls zutreffend)
- [ ] Elektrogeräte, Batterien, Verpackung: Rücknahme- und Entsorgungshinweise, Registrierungen
- [ ] Lebensmittel: Allergene und Pflichtangaben vor dem Kauf
- [ ] Altersbeschränkte Produkte: Altersprüfung
- [ ] Produktsicherheit (GPSR): Hersteller- und Sicherheitsangaben

### D7 Weitere Shop-Pflichten
- [ ] Geoblocking-Verbot (VO (EU) 2018/302): keine ungerechtfertigte Sperre, Umleitung oder Schlechterstellung von EU-Kunden
- [ ] ECG-Informationen: technische Schritte zum Vertragsschluss, Speicherung des Vertragstexts, Vertragssprachen, Korrektur von Eingabefehlern, Verhaltenskodizes
- [ ] EU-Verpackungsverordnung (PPWR, ab August 2026) und Lizenzierung in den Zielländern
- [ ] Zielmarkt DE: Verpackungsregister LUCID, deutsche Kennzeichnungspflichten
- [ ] Jährlicher Re-Check von Impressum, AGB-Klauseln und Rechtsprechung

---

## Modul E: SaaS, Abo & Payments

### E1 Vertragsdokumente
- [ ] Nutzungsbedingungen/AGB: Leistungsumfang, Verfügbarkeit/SLA, Haftung, Laufzeit, Kündigung, Preisänderungen
- [ ] B2B: AVV-Vorlage für Kunden, Liste der Subdienstleister, technische und organisatorische Maßnahmen
- [ ] Nutzungsrichtlinie (Acceptable Use) bei Uploads oder Nutzerinhalten
- [ ] Preisübersicht brutto/netto passend zur Zielgruppe
- [ ] AGB versioniert; Zustimmung zu Änderungen nachweisbar

### E2 Abo-Abschluss
- [ ] Vor Abschluss deutlich: Preis pro Periode, Abrechnungsintervall, Mindestlaufzeit, Verlängerungsdauer, Kündigungsfrist
- [ ] Gratis-Testphase: klar, dass und ab wann sie kostenpflichtig wird und was sie dann kostet (sonst entsteht beim Übergang ein neues Rücktrittsrecht – EuGH, Rs. Sofatutor)
- [ ] Abschluss-Button eindeutig, z. B. „zahlungspflichtig abonnieren“
- [ ] B2C: 14 Tage Rücktrittsrecht; bei sofortigem Leistungsbeginn ausdrückliches Verlangen und Bestätigung über Wertersatz bzw. Verlust des Rücktrittsrechts (digitale Inhalte)
- [ ] Widerrufsbutton (D4) auch für Abos
- [ ] Vertragsbestätigung per E-Mail mit allen Konditionen

### E3 Verlängerung & Kündigung
- [ ] B2C mit automatischer Verlängerung: **gesonderter, deutlicher Hinweis vor Beginn der Kündigungsfrist** auf Vertragsende, Verlängerungsdauer und Kündigungsmöglichkeit (§ 6 Abs 1 Z 2 KSchG) – eigene Nachricht, nicht versteckt
- [ ] Kündigung online mindestens so einfach wie der Abschluss
- [ ] Zielmarkt DE: Kündigungsbutton nach § 312k BGB („Verträge hier kündigen“, ohne Login erreichbar)
- [ ] Sofortige Kündigungsbestätigung
- [ ] Preiserhöhungen nur mit wirksamer Klausel oder Zustimmung, rechtzeitig angekündigt
- [ ] Up- und Downgrade sowie anteilige Abrechnung geregelt

### E4 Payments
- [ ] Rolle des Zahlungsanbieters geklärt und in der Datenschutzerklärung genannt
- [ ] Keine Kartendaten auf eigenen Servern (gehostete Zahlungsformulare des Anbieters)
- [ ] Starke Kundenauthentifizierung (PSD2/SCA, 3-D Secure); wiederkehrende Zahlungen korrekt als Mandat eingerichtet
- [ ] SEPA-Lastschrift: Mandatstext und Vorabankündigung
- [ ] Rechnungen mit Pflichtangaben; korrekter USt-Satz je Land bei B2C-Digitalleistungen in der EU (OSS)
- [ ] B2B: Reverse Charge mit UID-Prüfung
- [ ] Ablauf bei fehlgeschlagenen Zahlungen (Mahnstufen, Sperre, Datenzugriff) geregelt
- [ ] Erstattung nach Rücktritt binnen 14 Tagen über dasselbe Zahlungsmittel

### E5 Account & Daten
- [ ] Registrierung nur mit nötigen Daten; Passwörter gehasht; 2FA angeboten
- [ ] Account-Löschung durch Nutzer möglich; Löschkonzept inkl. Backups und gesetzlicher Aufbewahrung (Rechnungen in AT 7 Jahre)
- [ ] Datenexport (Art. 20 DSGVO)
- [ ] EU Data Act: bei Cloud-/SaaS-Leistungen Wechsel und Datenexport zu anderem Anbieter ohne unzulässige Hürden
- [ ] Incident- und Datenpannen-Prozess dokumentiert
- [ ] B2B-Kundendaten nur nach Weisung verarbeitet

---

## Modul F: Sonderfunktionen (nur zutreffende Blöcke)

### F1 KI-Chatbot / KI-Inhalte (AI Act Art. 50, gilt seit 02.08.2026)
- [ ] Nutzer erfährt spätestens beim ersten Kontakt klar, dass er mit einer KI kommuniziert (im Widget selbst, nicht nur in AGB oder Footer)
- [ ] Chat-Daten in der Datenschutzerklärung (Anbieter, Speicherdauer, Training ja/nein); AVV mit dem Anbieter
- [ ] Deepfakes und realistische KI-Bilder von Personen gekennzeichnet
- [ ] KI-Texte zu Themen öffentlichen Interesses ohne redaktionelle Kontrolle gekennzeichnet
- [ ] Hinweis, wenn der Bot zu Rechts-, Gesundheits- oder Finanzthemen antwortet

### F2 Newsletter (§ 174 TKG 2021)
- [ ] Double-Opt-in, protokolliert (Zeitpunkt, Bestätigung)
- [ ] Einwilligungstext nennt Inhalte und Häufigkeit; Abmeldelink in jeder Aussendung
- [ ] Bestandskunden-Ausnahme nur für ähnliche eigene Produkte, mit Widerspruchsmöglichkeit bei der Erhebung
- [ ] Öffnungs-/Klick-Tracking nur mit Einwilligung und in der Datenschutzerklärung

### F3 Terminbuchung
- [ ] Verbindliche B2C-Buchung → Module C und D prüfen (Rücktrittsrecht bzw. Ausnahmen für termingebundene Leistungen)
- [ ] Storno- und No-Show-Regeln vor der Buchung sichtbar
- [ ] Buchungstool im Dienste-Inventar
- [ ] Gesundheits- oder andere sensible Daten (Art. 9 DSGVO) nur über geschützte Wege, keine Freitextfelder in normalen Formularen

### F4 Login-Bereich / Kundenportal
- [ ] Session-Cookies als technisch notwendig dokumentiert
- [ ] Rechtstexte auch eingeloggt erreichbar
- [ ] Minimale Rollen und Rechte; Protokollierung von Admin-Zugriffen

### F5 Nutzerinhalte, Bewertungen, Bewerbungen
- [ ] Bewertungen: Hinweis zur Echtheitsprüfung, keine gekauften oder gefilterten Bewertungen
- [ ] Uploads: Nutzungsrechte und Meldeweg für rechtswidrige Inhalte
- [ ] Bewerbungsformular: eigener Datenschutzabschnitt, Löschfrist (üblich 6–7 Monate)

### F6 Werbe-Tracking & Pixel
- [ ] Meta-Pixel, Google Ads, Tag Manager, LinkedIn Insight Tag nur nach Einwilligung
- [ ] Google Consent Mode mit Standard „denied“
- [ ] Server-Side-Tracking: Einwilligung trotzdem einholen, wo personenbezogen

---

## Quellen
- WKO – Widerrufsbutton im Webshop: https://www.wko.at/internetrecht/e-commerce-widerrufsbutton-webshop
- WKO – Barrierefreiheitsgesetz im E-Commerce (FAQ): https://www.wko.at/internetrecht/barrierefreiheitsgesetz-im-e-commerce-faq
- WKO – FAQs Barrierefreiheitsgesetz: https://www.wko.at/ce-kennzeichnung-normen/faqs-webinar-barrierefreiheitsgesetz
- WKO NÖ – Rechtlicher Check der Website oder des Webshops: https://www.wko.at/noe/e-commerce/rechts-check-rechtliche-ueberpruefung-der-website-webshops
- WKO NÖ – Rechtliche Grundlagen E-Commerce: https://www.wko.at/noe/e-commerce/rechtliche-grundlagen
- IHK – Abschaffung der OS-Plattform: https://www.ihk.de/gera/recht-und-steuern/aktuelles-rechtundsteuern/eu-plattform-fuer-online-streitbeteiligung-wird-abgeschafft-6505768
- IHK Neubrandenburg – Checkliste rechtssichere Website: https://www.neubrandenburg.ihk.de/fileadmin/user_upload/Recht_und_Steuern/Merkbl%C3%A4tter_A-Z/MB_Checkliste_fuer_eine_rechtssichere_Website.pdf
- Händlerbund – 10-Punkte-Jahres-Check: https://www.haendlerbund.de/de/news/aktuelles/wissenssnack/jahrescheck-abmahnrisiko
- OLG Wien 33 R 52/22t – Hinweis auf Abo-Verlängerung: https://verbraucherrecht.at/system/files/2022-10/OLG%20Wien%2033%20R%2052_22t.pdf
- EuGH Sofatutor – Rücktritt bei Gratis-Abo: https://www.ra-plutte.de/eugh-kein-mehrfaches-widerrufsrecht-bei-online-abo/
- AI Act Art. 50 ab 02.08.2026: https://www.it-daily.net/shortnews/eu-ai-act-startet
