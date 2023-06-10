TITLE: 
**[FREE] GTA Huds ausblenden (Geld, Straße und Fahrzeugname etc.)**

Mit diesem Script kann man die Standard-Huds von GTA ausblenden, wie z.B. die Geldanzeige oben rechts, die Straßen und Fahrzeugnamen unten rechts oder auch die Karte. Man kann z.B. einstellen, dass die Karte nur im Fahrzeug angezeigt wird.

**Hier eine Liste, was man alles separat einstellen kann:**

```
local HUD_ELEMENTS = {
    HUD = { id = 0, hidden = false },
    HUD_WANTED_STARS = { id = 1, hidden = true },
    HUD_WEAPON_ICON = { id = 2, hidden = true },
    HUD_CASH = { id = 3, hidden = true },
    HUD_MP_CASH = { id = 4, hidden = true },
    HUD_MP_MESSAGE = { id = 5, hidden = true },
    HUD_VEHICLE_NAME = { id = 6, hidden = true },
    HUD_AREA_NAME = { id = 7, hidden = true },
    HUD_VEHICLE_CLASS = { id = 8, hidden = true },
    HUD_STREET_NAME = { id = 9, hidden = true },
    HUD_HELP_TEXT = { id = 10, hidden = false },
    HUD_FLOATING_HELP_TEXT_1 = { id = 11, hidden = false },
    HUD_FLOATING_HELP_TEXT_2 = { id = 12, hidden = false },
    HUD_CASH_CHANGE = { id = 13, hidden = true },
    HUD_RETICLE = { id = 14, hidden = true },
    HUD_SUBTITLE_TEXT = { id = 15, hidden = false },
    HUD_RADIO_STATIONS = { id = 16, hidden = false },
    HUD_SAVING_GAME = { id = 17, hidden = false },
    HUD_GAME_STREAM = { id = 18, hidden = false },
    HUD_WEAPON_WHEEL = { id = 19, hidden = false },
    HUD_WEAPON_WHEEL_STATS = { id = 20, hidden = false },
    MAX_HUD_COMPONENTS = { id = 21, hidden = false },
    MAX_HUD_WEAPONS = { id = 22, hidden = false },
    MAX_SCRIPTED_HUD_COMPONENTS = { id = 141, hidden = false }
}
```
Wenn man false einstellt, wird es angezeigt, wenn man true einstellt, wird es ausgeblendet. Wenn man das Script im Spiel starten und es nicht funktioniert, den Server neu starten und es wird funktionieren. Vergesst aber nicht, das Script zur server.cfg hinzuzufügen.

**Anleitung zur Installation:**
- von [hier](https://github.com/fivem-open-source/lv_components/releases/tag/final-version) Downloaden (Github Link)
- die .zip Datei entpacken
- bennen das script um so wie es dir passt
- in den resourcen ordner von deinem fivem Server ziehen
- `start SCRIPTNAME` zur server.cfg hinzufügen
- server neustarten, fertig

**Geplante Updates für die Zukunft:**
keine
- Wenn du Bugs findest oder Vorschläge für ein Update hast, öffnen ein Issue oder eine Pull-Request auf [Github](https://github.com/fivem-open-source/lv_components)

Release Download:
[lv_components - version: 1.0](https://github.com/fivem-open-source/lv_components/releases/tag/final-version)

Source Download:
[lv_components v. 1.0](https://github.com/fivem-open-source/lv_components)
