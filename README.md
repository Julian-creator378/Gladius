# Gladius

**Gladius Arena** – ein 3D-Gladiatorenspiel im Browser (three.js).

## Spielen

`index.html` im Browser öffnen – keine Installation nötig (three.js wird von cdnjs geladen).

## Modi

- **Karriere:** zwölf Kämpfe vom Tiro zum freien Mann, mit Denaren und Ausrüstungs-Upgrades im Ludus.
- **Wellen-Modus:** endlose Wellen, ein Leben, Champion in jeder fünften Welle.
- **Online – Koop:** bis zu vier Spieler gemeinsam im Wellen-Modus. Gegner werden pro Mitspieler zäher, gefallene Gladiatoren stehen nach jeder überstandenen Welle wieder auf.
- **Online – Duell:** eins gegen eins, wer zuerst zwei Runden gewinnt, siegt.

## Online spielen

1. Im Hauptmenü **Online** wählen und einen **Koop-Raum** oder **Duell-Raum** erstellen.
2. Den fünfstelligen **Raum-Code** (oder per „Link kopieren“ den Einladungslink) an die Mitspieler schicken.
3. Die Mitspieler geben unter **Online** den Code ein und klicken **Beitreten**.
4. Der Host startet den Kampf.

Die Verbindung läuft direkt zwischen den Browsern (WebRTC über [PeerJS](https://peerjs.com)); der öffentliche PeerJS-Server vermittelt nur den Verbindungsaufbau. Ein eigener Server ist nicht nötig, die Seite kann z. B. über GitHub Pages bereitgestellt werden.

Hinweise:
- Der Host berechnet Gegner und Wellen. Sein Browser-Tab muss deshalb sichtbar bleiben, sonst pausiert das Spiel für alle.
- Online lässt sich das Spiel nicht anhalten; **P**/**Options** öffnet nur das Menü.

## Grafik

Im Hauptmenü lässt sich die Grafik umschalten:

- **Hoch:** Leuchteffekte (Bloom), Vignette, Farbabstimmung, volle Auflösung, schwebender Staub.
- **Schnell:** für schwächere Rechner und Handys, ohne Nachbearbeitung und mit geringerer Auflösung.

Die Wahl wird im Browser gespeichert.

## Steuerung

| Aktion | PS4-Controller | Tastatur & Maus |
|---|---|---|
| Bewegen | Linker Stick | W A S D |
| Kamera drehen | Rechter Stick | Maus oder Q / E |
| Schlag | □ oder R1 | Linksklick oder J |
| Wuchtschlag | △ oder R2 | K |
| Blocken (halten) | L1 oder L2 | Rechtsklick oder Shift |
| Ausweichrolle | ✕ oder ○ | Leertaste |
| Kamera hinter dich | R3 | C |
| Pause | Options | P |
