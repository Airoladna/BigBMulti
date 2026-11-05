# Mein Tamagotchi 3D

Spielbares Tamagotchi im Browser (3D-Raum mit Three.js, Figur aus deiner Vorlage).

## Auf GitHub Pages veröffentlichen
1. Auf github.com ein neues Repository anlegen (z. B. `tamagotchi`), öffentlich.
2. **Add file → Upload files** und alle Dateien aus diesem Ordner hochladen
   (`index.html`, `.nojekyll`, `README.md`). `index.html` muss im Hauptverzeichnis liegen.
3. **Commit changes**.
4. **Settings → Pages**: Source = *Deploy from a branch*, Branch = `main`, Ordner = `/ (root)` → Save.
5. Nach 1–2 Minuten erreichbar unter `https://DEIN-NAME.github.io/tamagotchi/`.

## Hinweise
- Braucht Internet (three.js wird von cdn.jsdelivr.net geladen) und einen Browser mit WebGL.
- Nicht per Doppelklick lokal öffnen: Lokal mit `python3 -m http.server` starten.
- Spielstand liegt im Browser (localStorage), pro Gerät getrennt.

## Spielen
- Tipp auf den Boden: Figur läuft dorthin. Tipp auf die Figur: streicheln. Tipp auf 💩: wegräumen.
- Buttons: Essen, Spielen (Äpfel fangen, Wischen oder Pfeiltasten), Schlafen, Waschen, Medizin, Streicheln.
- Werte sinken mit der Zeit, auch wenn die Seite zu ist (langsamer). Bei 0 Gesundheit stirbt die Figur.
