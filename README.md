# Hotzone Party v4

- Host ist neutraler Spielleiter, sieht immer die Geheimzahl, trägt Team-Tipps per Buttons (1–10) ein und löst auf.
- Hinweisgeber im aktiven Team sieht die Zahl nur lokal (Overlay) und gibt ein Wort als Hinweis.
- Teams beraten sich mündlich; der Host klickt den Team-Tipp.
- Punkte (pro Zug): Abstand 0→5, 1→3, 2→2, 3→1, ≥4→0.
- Eine Runde besteht aus zwei Zügen: Rot, dann Blau. Punkte werden **sofort nach jedem Zug** vergeben.
- Match: Best-of-X Runden (z. B. 5). Am Ende: Sieger oder Unentschieden. Konfetti!

## Nutzung
1. Öffne `index.html` über **HTTPS** (GitHub Pages/Netlify/Vercel oder lokal via `npx serve`). `file://` blockiert oft P2P.
2. Host klickt **„Raum erstellen (Host)“** → Code teilen.
3. Spieler geben Name/Team an → **Beitreten**.
4. Host: Best‑of‑Runden wählen → **Match starten** → pro Zug Tipp setzen → **Auflösen**.

Fallback: **Lokales Spiel starten** + Discord‑Screenshare.
