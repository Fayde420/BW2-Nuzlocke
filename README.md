# BW2-Nuzlocke — Live-Tracker (Solo-Nuzlocke)

Live-Anzeige eines **Solo-Nuzlockes** in Pokémon Schwarz 2: Team, PC-Box,
aktueller Gegner (folgt dem Kampf), **Friedhof** (tote Pokémon), Routen und
Orden — direkt aus dem laufenden Spiel.

**Live:** https://fayde420.github.io/BW2-Nuzlocke/  (Passwort erforderlich)

## Tracker einrichten
Du brauchst: **BizHawk** (melonDS-Core), dein **BW2-ROM**, **Python 3**.

1. Den Ordner **`tracker/`** herunterladen.
2. In der CMD einmalig den Ordner festlegen, dann BizHawk neu starten:
   ```cmd
   setx AUTOTRACKER_DIR "C:\Pfad\zum\tracker"
   ```
3. BizHawk → ROM laden → **Tools → Lua Console** → `live_team.lua` laden.
4. Bridge starten: **`start_solo.bat`**  (= `python bridge.py`).
5. Diese Seite öffnen (Passwort eingeben) — die Daten erscheinen live.

## Hinweise
- Firebase-DB ist offen (kein Login) — URL nicht breit teilen.
- BW2-ROM & BizHawk sind nicht enthalten.
