# Caltera City Forum

Responsive pinke Forum-Vorlage für Caltera City Roleplay. Läuft ohne Build-Schritt.

## GitHub Pages

1. ZIP entpacken.
2. `index.html`, `style.css`, `script.js` und `README.md` in ein GitHub-Repository hochladen.
3. Im Repository **Settings → Pages → Deploy from a branch** wählen, dann den Branch `main` und Ordner `/ (root)` auswählen.

## Demo-Funktionen

- Spieler erhalten beim Öffnen automatisch einen lokalen Gastnamen.
- Vor dem Erstellen ein Forum im Menü auswählen (oder auf eine Forenzeile klicken), dann ein Thema erstellen. Alle Kategorien starten leer ohne Beispielthemen.
- Beiträge anderer öffnen und in offenen Themen antworten.
- Spieler-ID ist erforderlich; Organisation und Tags sind optional.
- Teammitglieder können offene Themen schließen, Präfixe ändern und Status auf „Angenommen“ oder „Abgelehnt“ setzen. Das erzeugt Auszeichnungen.
- Inhaber können im Team-Bereich eigene Ränge und Berechtigungen anlegen.
- Demo-Inhabercode: `CALTERA-OWNER-7F3K-9Q2M`.

## Wichtige technische Grenze

Das Projekt ist statisch. Konten, Rollen und Beiträge liegen im Browser-Speicher und werden nicht mit anderen Besuchern geteilt. Der Inhabercode steht im Frontend und ist öffentlich lesbar. Für echte Anmeldung, gemeinsame Beiträge und sichere Admin-Rechte braucht es ein Backend mit serverseitiger Rechteprüfung.
