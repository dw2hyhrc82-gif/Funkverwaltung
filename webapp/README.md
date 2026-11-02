# Funkverwaltung – Web-App für Sicherheitsdienste

Single-File-Web-App (`index.html`, ohne Build-Schritt und ohne Server) zur Verwaltung von Funkgeräten, Akkus und Zubehör im Sicherheitsdienst.

## Funktionen
- **Übersicht**: Kennzahlen (verfügbar, ausgegeben, überfällig, defekt), überfällige Rückgaben, Geräte je Objekt
- **Ausgabe & Rücknahme**: Gerät mit Akkus und Zubehör an Mitarbeiter/in für ein Objekt ausgeben, Rückgabefrist, Schnellrücknahme per Kennung/Seriennummer (auch per Barcode-Scanner), Zustandserfassung
- **Übergabeprotokoll** zum Drucken mit Unterschriftsfeldern
- **Stammdaten**: Funkgeräte, Akkus (inkl. Ladezyklen), Zubehör (Bestand/frei), Personal, Objekte
- **Verlauf**: abgeschlossene Ausgaben, Aktivitätsprotokoll, CSV-Export
- **Daten & Backup**: JSON-Backup/-Import, Beispieldaten, Zurücksetzen
- Hell-/Dunkelmodus, mobiltauglich

## Nutzung
`webapp/index.html` im Browser öffnen oder über GitHub Pages ausliefern (`/webapp/`).
Die Daten werden lokal im Browser (localStorage) gespeichert – regelmäßig ein Backup herunterladen.
