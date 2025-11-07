# Pflichtenheft für die Website Johannes Müller Zahnarztpraxis

**Inhaltsverzeichnis**

1. [Zielsetzung des Projekts](#1-zielsetzung-des-projekts)
2. [Leistungen des Dienstleisters](#2-leistungen-des-dienstleisters)
3. [Funktionale Anforderungen](#3-funktionale-anforderungen)

   - [3.1 Startseite](#31-startseite)
   - [3.2 Profilseite "Dr. Johannes Müller"](#32-profilseite-dr-johannes-müller)
   - [3.3 Leistungen](#33-leistungen)
   - [3.4 Kontaktseite](#34-kontaktseite)
   - [3.5 Online-Terminbuchung](#35-online-terminbuchung)
   - [3.6 Datenschutzerklärung](#36-datenschutzerklärung)
   - [3.7 Impressum](#37-impressum)
   - [3.8 Footer](#38-footer)
4. [Nicht-funktionale Anforderungen](#4-nicht-funktionale-anforderungen)
   - [4.1 Benutzerfreundlichkeit](#41-benutzerfreundlichkeit)
   - [4.2 Barrierefreiheit](#42-barrierefreiheit)
   - [4.3 Performance](#43-performance)
   - [4.4 Sicherheit](#44-sicherheit)
5. [Designrichtlinien](#5-designrichtlinien)
   - [5.1 Farbkonzept](#51-farbkonzept)
   - [5.2 Typografie](#52-typografie)
   - [5.3 Layout und Gestaltung](#53-layout-und-gestaltung)
6. [Implementierung](#6-implementierung)
   - [6.1 Verwendete Technologien](#61-verwendete-technologien)
   - [6.2 Versionskontrolle und Zusammenarbeit](#62-versionskontrolle-und-zusammenarbeit)
7. [Projektorganisation](#7-projektorganisation)
   - [7.1 Projektteam](#71-projektteam)
   - [7.2 Rollen und Verantwortlichkeiten](#72-rollen-und-verantwortlichkeiten)
   - [7.3 Kommunikationsplan](#73-kommunikationsplan)
   - [7.4 Zeitplan](#74-zeitplan)
8. [Testkonzept](#8-testkonzept)
   - [8.1 Testplanung](#81-testplanung)
   - [8.2 Testfälle](#82-testfälle)
   - [8.3 Abnahmekriterien](#83-abnahmekriterien)
9. [Rechtliche Aspekte](#9-rechtliche-aspekte)
   - [9.1 Datenschutz (DSGVO)](#91-datenschutz-dsgvo)
   - [9.2 Impressumspflicht](#92-impressumspflicht)

---

## 1. Zielsetzung des Projekts

Ziel ist die Erstellung einer modernen, benutzerfreundlichen und professionellen Website für die Zahnarztpraxis von Dr. Johannes Müller in Düsseldorf. Die Website soll Patienten umfassend über die Praxis, das Team und die angebotenen Leistungen informieren sowie die Kontaktaufnahme erleichtern. Sie dient dazu, das Vertrauen der Patienten zu stärken und einen positiven ersten Eindruck zu hinterlassen.

Dieses Pflichtenheft beschreibt die konkrete Umsetzung der Anforderungen und die zu erbringenden Leistungen aus Sicht des Dienstleisters, basierend auf dem Lastenheft und dem Wireframe.

---

## 2. Leistungen des Dienstleisters

Der Dienstleister (bestehend aus Qais Latif) verpflichtet sich zur:

- Entwicklung einer responsiven Website gemäß den definierten Anforderungen.
- Implementierung aller funktionalen und nicht-funktionalen Anforderungen.
- Bereitstellung einer benutzerfreundlichen und barrierefreien Benutzeroberfläche.
- Dokumentation des Entwicklungsprozesses und der technischen Umsetzung.
- Durchführung umfassender Tests zur Sicherstellung der Funktionalität und Qualität.
- Gewährleistung der DSGVO-Konformität und Einhaltung rechtlicher Vorgaben.
- Bereitstellung eines Designkonzepts basierend auf dem vorhandenen Wireframe.

---

## 3. Funktionale Anforderungen

### 3.1 Startseite

**Inhalt und Funktionen:**

- **Header mit Logo und Navigation:**

  - Anzeige des Praxislogos oben links.
  - Navigation mit folgenden Menüpunkten:
    - Home
    - Johannes Müller
    - Leistungen
    - Kontakt
    - Online-Terminbuchung (Doctolib)

- **Bildergalerie:**

  - Rotierende Bilder aus der Praxis (4 Bilder).
  - Navigationspunkte (Dots) zur Steuerung der Galerie.
  - Responsives Verhalten der Bilder je nach Endgerät.

- **Willkommensbereich:**

  - Begrüßungstext mit persönlicher Ansprache.
  - Vorstellung der Praxis und des Teams.
  - Auflistung der Spezialgebiete in Listenform.

- **Patientenbewertungen:**

  - Anzeige von echten Patientenbewertungen in Form von Testimonials.
  - Navigation zwischen den Bewertungen mittels Pfeilbuttons oder automatischem Übergang.

- **Häufig gestellte Fragen (FAQ):**

  - Interaktive Elemente zur Darstellung von FAQs.
  - Klappmenüs zur Anzeige von Antworten.

- **Footer:**

  - Links zu Impressum und Datenschutzerklärung.
  - Social-Media-Icons mit Verlinkungen.

---

<br>

<img src="Wireframe/SVG/Home.svg" alt="description" width="1920" height="1080">

<br>

---

### 3.2 Profilseite "Dr. Johannes Müller"

**Inhalt und Funktionen:**

- **Header und Navigation:** Konsistent mit der Startseite.
- **Bildergalerie:**

  - Rotierende Bilder von Dr. Müller (bei der Arbeit, Vorträge, Praxis).

- **Lebenslauf:**

  - Chronologischer Werdegang mit folgenden Abschnitten:
    - Ausbildung und Qualifikationen.
    - Praktische Erfahrung im Ausland.
    - Veröffentlichungen mit Verweisen auf externe Quellen.

- **Kontaktmöglichkeiten:**

  - Klar dargestellte Kontaktdaten.
  - Verlinkung zur Kontaktseite.

---

<br>

<img src="Wireframe/SVG/Johannes-Müller.svg" alt="description" width="1920" height="1080">

<br>

---  

### 3.3 Leistungen

**Inhalt und Funktionen:**

- **Header und Navigation:** Konsistent mit anderen Seiten.

- **Darstellung der Leistungen:**

  - Übersicht aller angebotenen zahnärztlichen Leistungen.
  - Jede Leistung enthält:
    - Titel der Leistung.
    - Ausführliche Beschreibung.
    - Optional: Bildmaterial oder Icons zur Visualisierung.

---

<br>

<img src="Wireframe/SVG/Leistung.svg" alt="description" width="1920" height="1080">

<br>

---

### 3.4 Kontaktseite

**Inhalt und Funktionen:**

- **Header und Navigation:** Konsistent mit anderen Seiten.
- **Kontaktformular:**
  - **Felder:**

    - Vor- und Nachname (Pflichtfeld).
    - E-Mail-Adresse (Pflichtfeld, Validierung auf E-Mail-Format).
    - Betreff (Pflichtfeld).
    - Nachricht (Pflichtfeld).

  - **Datenschutz-Checkbox:**

    - Zustimmung zur Verarbeitung der Daten gemäß DSGVO.
    - Link zur Datenschutzerklärung.

  - **Senden-Button:**

    - Bestätigungsmeldung nach erfolgreichem Versand.
    - Eingaben werden per E-Mail an die Praxis gesendet.

- **Kontaktinformationen:**

  - Telefonnummer (anklickbar für direkte Anwahl auf Mobilgeräten).
  - Faxnummer.
  - E-Mail-Adresse (`mailto:`-Link).
 
---

<br>

<img src="Wireframe/SVG/Kontakt.svg" alt="description" width="1920" height="1080">

<br>

---

### 3.5 Online-Terminbuchung

**Inhalt und Funktionen:**

- **Integration von Doctolib:**

  - Prominenter Link oder Button zur Online-Terminvereinbarung.
  - Weiterleitung auf die Doctolib-Seite der Praxis.

- **Benutzerfreundlichkeit:**

  - Der Link oder Button ist auf allen Seiten sichtbar und leicht zugänglich.

### 3.6 Datenschutzerklärung

**Inhalt und Funktionen:**

- **Umfassende Datenschutzerklärung:**

  - Informationen zur Verarbeitung personenbezogener Daten.
  - Details zur Datenerfassung über:

    - Cookies.
    - Server-Log-Dateien.
    - Kontaktformular und Terminbuchung.

- **Rechte der Nutzer:**

  - Auskunftsrecht.
  - Recht auf Berichtigung, Löschung, Einschränkung der Verarbeitung.
  - Widerspruchsrecht.

- **Kontakt für Datenschutzfragen:**

  - Kontaktdaten des Verantwortlichen für Datenschutzanfragen.

### 3.7 Impressum

**Inhalt und Funktionen:**

- **Gesetzlich vorgeschriebene Angaben:**

  - Name und vollständige Anschrift der Praxis.
  - Kontaktdaten (Telefon, Fax, E-Mail).
  - Berufsbezeichnung und zuständige Kammer.
  - Berufsrechtliche Regelungen und Verweise darauf.
  - Angaben zur Aufsichtsbehörde.

### 3.8 Footer

**Inhalt und Funktionen:**

- **Links:**

  - Impressum.
  - Datenschutzerklärung.

- **Social-Media-Icons:**

  - Verlinkungen zu:
    - Facebook
    - X (ehemals Twitter)
    - Instagram
    - LinkedIn

- **Design:**

  - Konsistentes Farbschema.
  - Gut lesbare Schriftarten.

---

## 4. Nicht-funktionale Anforderungen

### 4.1 Benutzerfreundlichkeit

- **Intuitive Navigation:**

  - Klare Menüstruktur.
  - Gut sichtbare und verständliche Navigationselemente.

- **Klare Call-to-Action-Elemente:**

  - Hervorgehobene Buttons für wichtige Aktionen (z.B. Termin vereinbaren).

- **Lesbarkeit:**

  - Ausreichende Schriftgröße und -art.
  - Hoher Kontrast zwischen Text und Hintergrund.

### 4.2 Barrierefreiheit

- **Erfüllung von WCAG 2.1 Level AA:**

  - Alt-Texte für Bilder.
  - Fokus-Indikatoren für Tastaturnavigation.
  - Skalierbare Schriftgrößen.
  - Vermeidung von rein farblichen Unterscheidungen.

### 4.3 Performance

- **Ladezeit:**

  - Maximale Ladezeit der Startseite unter 3 Sekunden bei einer 3G-Verbindung.

- **Optimierung:**

  - Komprimierung von Bildern (Verwendung von WebP-Format).
  - Minimierung von CSS und JavaScript.

### 4.4 Sicherheit

- **Datenschutz:**

  - DSGVO-konforme Verarbeitung und Speicherung personenbezogener Daten.

---

## 5. Designrichtlinien

### 5.1 Farbkonzept

**Hauptfarben:**

- **#1C1C1C:** Dunkles Hintergrundgrau (Logo-Bereich).
- **#D4BA6A:** Gold (Logo-Zahn & Lorbeer).
- **#FFFFFF:** Weiß (Haupt-Hintergrund).
- **#F5F5F5:** Helles Grau (Inhaltsabschnitte).
- **#4A90E2:** Medizinisches Blau (Akzente).

**Komplementärfarben:**

- **Sage-Grün:**

  - **#C5D5C5:** Helles Sage.
  - **#9FB4A1:** Mittleres Sage.
  - **#748B75:** Dunkles Sage.
- **Navy-Blau:**

  - **#394F6B:** Helles Navy.
  - **#2C3E50:** Mittleres Navy.
  - **#1B2631:** Dunkles Navy.

**Neutralfarben:**

- **#E6E6E6:** Helles Grau.
- **#B8B8B8:** Mittleres Grau.
- **#808080:** Dunkles Grau.

### 5.2 Typografie

- **Schriftarten:**
  - Hauptschriftart: Arial, sans-serif.
  - Alternativschriftarten: Inter, Verdana, Helvetica.
- **Schriftgrößen:**

  - Basis-Schriftgröße: 16px.
- **Schriftfarben:**

  - Haupttext: #1C1C1C.
  - Überschriften: #1C1C1C.
  - Links und Akzente: #4A90E2 oder #D4BA6A.

### 5.3 Layout und Gestaltung

- **Responsives Design:**

  - Verwendung von flexiblen Layouts (Flexbox, Grid).

- **Breakpoints für verschiedene Bildschirmgrößen:**

  - Mobil: bis 640px.
  - Tablet: bis 1024px.
  - Laptop: bis 1440px
  - Desktop: ab 1441px.

- **Bilder und Medien:**

  - Optimierte Bildformate (WebP).
  - Anpassung der Bildausschnitte je nach Gerät (`object-position`).

- **Iconografie:**

  - Verwendung von Material Symbols für Symbole (z.B. Kalender, Menü).

- **Buttons und Interaktive Elemente:**

  - Klar erkennbare Hover- und Fokuszustände.
  - Ausreichende Klickflächen für mobile Geräte.

---

## 6. Implementierung

### 6.1 Verwendete Technologien

- **HTML5:** Strukturierung der Inhalte.

- **CSS3:** Gestaltung der Website.
 
- **JavaScript:** Interaktive Funktionen (z.B. Bildergalerie, FAQ-Klappmenüs).
- **Fonts:**
  - Google Fonts für Material Symbols.
- **Bildformate:**
  - Verwendung von modernen Formaten wie WebP für optimierte Ladezeiten.
- **Tools:**
  - Code-Editoren wie Visual Studio Code.
  - Testing-Tools wie Playwright für automatisierte Tests.

### 6.2 Versionskontrolle und Zusammenarbeit

- **Versionskontrolle:** Einsatz von Git.
- **Repository:** Gemeinsames Projekt-Repository auf git.ide3.de
- **Zusammenarbeit:**
  - Regelmäßige Commits mit aussagekräftigen Nachrichten.
  - Pull Requests und Code Reviews.

---

## 7. Projektorganisation

### 7.1 Projektteam

- **Dienstleister:** team bestehend aus Qais Latif.
- **Auftraggeber:** Zahnarztpraxis Dr. Johannes Müller.

### 7.2 Rollen und Verantwortlichkeiten

- **Qais Latif**

  - Frontend-Entwicklung.
  - Implementierung der Benutzeroberfläche.
  - Testing und Qualitätssicherung.

### 7.3 Kommunikationsplan

- **Meetings:**

  - Wöchentliches Update-Meeting (online über discord).

- **Kommunikationskanäle:**

  - Discord oder Whatsapp für kurzfristige Abstimmungen.

### 7.4 Zeitplan

**15.11.2024:**

- Erstellung und Finalisierung des Pflichtenhefts
- Aufsetzen der Entwicklungsumgebung

**20.11.2024:**

- Frontend-Implementierung
- Integration von Doctolib
- Code Reviews

**24.11.2024:**

- Durchführung automatisierter Tests
- Manuelle Tests und Optimierungen
- Dokumentation

**27.11.2024:**

- Finale Anpassungen
- Projektabnahme

---

## 8. Testkonzept

### 8.1 Testplanung

**Ziele:**

- **Sicherstellung der Funktionalität:** Alle Funktionen der Website sollen wie vorgesehen arbeiten.
- **Überprüfung der Responsivität:** Die Website muss auf verschiedenen Geräten und Bildschirmgrößen korrekt dargestellt werden.
- **Kompatibilitätstests:** Gewährleistung der Kompatibilität mit gängigen Webbrowsern.
- **Performance:** Sicherstellung von kurzen Ladezeiten und reibungsloser Interaktion.

**Testmethoden:**

- **Automatisierte End-to-End-Tests:**

  - Einsatz von Playwright.
  - Tests simulieren Benutzerinteraktionen auf Desktop, Tablet und Mobilgeräten.

- **Manuelle Tests:**

  - Prüfung von Usability und Benutzerfreundlichkeit.
  - Visuelle Kontrolle des Designs und der Darstellung.

- **Kompatibilitätstests:**

  - Tests auf verschiedenen Browsern (Chrome, Firefox, Safari, Edge) und Betriebssystemen.

### 8.2 Testfälle

**Allgemeine Funktionen:**

- **Navigation:**

  - Links in der Hauptnavigation führen zu den korrekten Seiten.
  - Burger-Menü funktioniert auf mobilen Geräten.

- **Footer:**

  - Links zu Impressum und Datenschutzerklärung funktionieren.
  - Social-Media-Icons leiten korrekt weiter.

**Seitenspezifische Tests:**

- **Startseite:**

  - **Bildergalerie:**

    - Automatischer Wechsel der Bilder alle 5 Sekunden.
    - Manuelles Wechseln über die Dots funktioniert.
    - Bilder werden korrekt und in angemessener Qualität dargestellt.

  - **Bewertungssektion:**

    - Bewertungen wechseln automatisch und manuell.
    - Sternebewertung wird korrekt angezeigt.

  - **FAQ-Sektion:**

    - Fragen lassen sich ein- und ausklappen.
    - Nur eine Frage ist gleichzeitig geöffnet.

- **Profilseite "Johannes Müller":**
  - **Bildergalerie:**

    - Bilder von Dr. Müller wechseln korrekt.
    - Bilder sind angemessen positioniert.

  - **Inhalte:**

    - Lebenslauf ist vollständig und korrekt dargestellt.
    - Links zu Veröffentlichungen funktionieren.

- **Leistungen:**
  - **Leistungsübersicht:**

    - Alle Leistungen sind aufgelistet und korrekt beschrieben.
    - Hover-Effekte auf den Leistungsboxen funktionieren.

- **Kontaktseite:**
  - **Kontaktformular:**

    - Pflichtfelder sind korrekt als solche markiert.
    - Validierung funktioniert (z.B. korrekte E-Mail-Adresse).
    - Datenschutzcheckbox muss aktiviert sein, bevor das Formular gesendet werden kann.

  - **Fehlerbehandlung:**

    - Bei fehlerhaften Eingaben werden entsprechende Fehlermeldungen angezeigt.

- **Datenschutzerklärung und Impressum:**

  - Texte sind vollständig und entsprechen den gesetzlichen Anforderungen.
  - Kontaktinformationen sind korrekt.

**Responsives Design:**

- **Desktop und laptop(≥1024px):**

  - Layout entspricht dem Design.
  - Keine überflüssigen Scrollleisten vorhanden.

- **Tablet (640px–1023px):**

  - Navigation wechselt zum Burger-Menü.
  - Inhalte passen sich dem Bildschirm an.

- **Mobil (≤639px):**

  - Inhalte sind gut lesbar.
  - Touch-Elemente sind ausreichend groß und gut erreichbar.

### 8.3 Abnahmekriterien

**Funktionale Abnahme:**

- Alle im Pflichtenheft definierten Funktionen sind implementiert und funktionieren einwandfrei.
- Keine kritischen Fehler oder Bugs vorhanden.

**Nicht-funktionale Abnahme:**

- Performance-Ziele sind erreicht (z.B. Ladezeit der Startseite unter 3 Sekunden).
- Designrichtlinien wurden eingehalten.

**Dokumentation:**

- Technische Dokumentation ist vollständig.
- Testprotokolle liegen vor und sind nachvollziehbar.

**Rechtliche Konformität:**

- DSGVO-Vorgaben sind umgesetzt.
- Impressum ist vollständig und korrekt.

**Freigabe durch den Auftraggeber:**

- Nach Präsentation der finalen Website und Durchsicht aller Dokumentationen erteilt der Auftraggeber die Abnahme.

---

## 9. Rechtliche Aspekte

### 9.1 Datenschutz (DSGVO)

**Einwilligungserklärung:**

- Vor Absenden des Kontaktformulars muss der Nutzer aktiv in die Verarbeitung seiner Daten einwilligen.
- Checkbox mit Verlinkung zur Datenschutzerklärung ist vorhanden.

**Datenschutzerklärung:**

- Entspricht den gesetzlichen Anforderungen.
- Detaillierte Informationen zur Verarbeitung personenbezogener Daten, Cookies, Server-Log-Dateien und Nutzung von Drittanbietern (z.B. Doctolib).

**Datenlöschung und Auskunft:**

- Verfahren zur Anforderung von Auskunft oder Löschung der Daten ist beschrieben.

**Sicherheitsmaßnahmen:**

- SSL-Verschlüsselung für die gesamte Website.

### 9.2 Impressumspflicht

**Vollständige Angaben:**

- Name, Adresse und Kontaktdaten der Praxis.
- Berufsbezeichnung und zuständige Kammer.
- Berufliche Qualifikationen.
- Angaben zur Aufsichtsbehörde.
- Verweise auf berufsrechtliche Regelungen.

**Aktualität und Richtigkeit:**

- Regelmäßige Überprüfung und Aktualisierung der Impressumsdaten.

---

<br>

Erstellt von Qais Latif am 20. November 2024.