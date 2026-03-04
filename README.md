# Professionelles POS-System (HTML + JavaScript)

Diese Demo ist ein deutlich erweitertes Kassensystem mit Produktverwaltung, Warenkorb, Checkout, Belegausgabe und optionaler GitHub-Speicherung.

## Funktionen
- Produkte **anlegen, bearbeiten und löschen**
- Lagerbestand pro Produkt
- Warenkorb mit Mengensteuerung (+ / - / entfernen)
- Checkout mit Bestandsabzug
- Automatischer Kassenzettel (Datum/Zeit, Positionen, Summe)
- Verkaufsverlauf mit erneut anzeigbaren Belegen
- Lokale Persistenz per `localStorage`
- Optionale GitHub-Speicherung/Laden via GitHub Contents API

## GitHub-Speicherung
Die App kann den kompletten POS-Status als JSON in ein GitHub-Repository speichern.
Dafür werden benötigt:
1. `Owner`
2. `Repo`
3. `Branch`
4. `Dateipfad`
5. Personal Access Token mit passendem Repo-Zugriff

> Hinweis: In einer reinen Frontend-Demo ist das Token im Browser-Kontext verfügbar. Für Produktion empfiehlt sich ein sicheres Backend als Proxy.
