# ClanBomber Original Maps

Die 33 Originalkarten von *ClanBomber* als Datenpaket für [gd-godot-clanbomber](https://github.com/RobinNunkesser/gd-godot-clanbomber).

## Herkunft und Lizenz

- Quelle: `src/maps/*.map` aus dem ClanBomber-Quellbaum (Fork *ClanBomber2*). Die Dateien sind unverändert übernommen und in beiden bekannten Quellbäumen (`clanbomber`, `ClanBomber2`) byte-identisch.
- Urheber: Andreas Hundt und Denis Oliver Kropp (1999–2007), Rene Lopez (Fork 2009/2010). Der jeweilige Kartenautor steht in Zeile 1 jeder Datei.
- Lizenz: **GNU GPL Version 2 oder später**, wie der ClanBomber-Quellbaum (siehe `COPYING`). Eine eigene Lizenzaussage nur für die Karten habe ich im Quellbaum nicht gefunden; die Einordnung als GPL-Datenbestand ist eine Annahme und keine Rechtsberatung.
- Zusätzliche Karten des Eigentümers liegen im Spielrepo (MIT), nicht hier. Dieses Repo enthält bewusst **keine** Sounds oder Grafiken des Originals (Herkunft ungeklärt).

## Nutzung

Das Spielrepo steht unter einer anderen (permissiven) Lizenz und enthält diese Karten nicht. Es lädt sie zur Laufzeit als separates Datenpaket (Ordner `maps/` hierher verlinken oder kopieren oder `CLANBOMBER_MAPS_DIR` setzen). Wer das Paket zusammen mit dem Spiel weitergibt, muss die GPL-Bedingungen für dieses Paket einhalten.

## Format

15 Zeilen: Autor, maximale Spielerzahl, 13 Zeilen mit 17 Zeichen (`*` Wall, `+` Box, `R` Zufall, `S` Ice, `<>^v` Arrow, `o` Trap, `-` außerhalb der Arena, `0`–`7` Startfelder). Einzelne Dateien haben eine Leerzeile vor der Spielerzahl.
