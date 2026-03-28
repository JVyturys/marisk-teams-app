# MaRisk-Novelle: Gap-Analyse (MS Teams App)

Ein Compliance-Produktivitäts-Tool zur interaktiven Gap-Analyse, Statusverfolgung und Kommentierung der aktuellen MaRisk-Änderungen. Das Tool ist primär als **Personal Tab App** für Microsoft Teams konzipiert, funktioniert aber auch als Standalone-Webanwendung im Browser.

## Kernfunktionen
* **Differenzprotokoll:** Direkter Vergleich von alten und neuen MaRisk-Textziffern.
* **Gap-Analyse & Tracking:** Setzen von Status (Offen, In Bearbeitung, Erledigt), Prioritäten und Zuständigkeiten.
* **Offline-Ready:** Speichert alle Fortschritte automatisch im lokalen Speicher des Browsers (`localStorage`).
* **Export & Import:** Vollständiger Daten-Export als CSV (für Excel) oder JSON (für Backups/Migrationen).
* **MS Teams Integration:** Nahtlose Einbindung via Teams JS SDK (v2), inklusive dynamischer Dark-Mode-Unterstützung.

## Tech-Stack
* **Frontend:** HTML5, CSS3, Vanilla JavaScript (keine externen Frameworks nötig).
* **Teams-Integration:** Microsoft Teams JavaScript Client SDK.
* **Hosting:** GitHub Pages.

## Setup für MS Teams
Die App wird über eine `manifest.json` via Sideloading im MS Teams Admin Center oder direkt im Client hochgeladen. Als Hosting-URL für den Tab wird der GitHub Pages Link verwendet.
