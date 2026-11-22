# Langlaufspass Kurse

Kursverwaltung für Langlaufspass.ch (Kunden, Lektionen, Gruppenkurse, Abrechnung).

Live: https://rschieler.github.io/Langlaufspass-Kurse/ (GitHub Pages, Branch `main`, Root)

- Daten: Firebase Firestore, Projekt `langlaufspass-b5289` (Zürich), Anmeldung mit Google
- Zugriff: `firestore.rules` (in der Firebase-Konsole unter Firestore → Regeln veröffentlichen)
- `firebase.js` ist aus `src/fb.js` gebündelt (esbuild), sonst keine Build-Schritte
