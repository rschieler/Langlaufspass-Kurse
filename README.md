# Langlaufspass Kurse

Kursverwaltung für Langlaufspass.ch (Kunden, Lektionen, Gruppenkurse, Abrechnung).

Live: https://rschieler.github.io/Langlaufspass-Kurse/ (GitHub Pages, Branch `main`, Root)
Test: https://rschieler.github.io/Langlaufspass-Kurse-Test/ (Repo `Langlaufspass-Kurse-Test`)

- Daten: Firebase Firestore, Projekt `langlaufspass-b5289` (Zürich), Anmeldung mit Google
- Zugriff: `firestore.rules` (in der Firebase-Konsole unter Firestore → Regeln veröffentlichen)
- Umgebungsspezifisch: `config.js` (APP_ENV, Firebase-Projekt), `manifest.webmanifest`, `icon-*.png`
- Änderungen zuerst ins Test-Repo, nach Freigabe die gemeinsamen Dateien hierher übernehmen
- `firebase.js` ist aus `src/fb.js` gebündelt (esbuild), sonst keine Build-Schritte
