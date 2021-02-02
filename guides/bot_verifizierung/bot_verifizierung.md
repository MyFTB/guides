---
layout: page
title: Verifizierung mit dem MyFTB Bot (Rollenvergabe)
permalink: /verifizierung-myftb-bot
thumbnail: /guides/bot_verifizierung/thumbnail.jpg
stepbystep: true
---

Damit du auf dem MyFTB [Teamspeak](https://myftb.de/teamspeak)- und [Discord](https://myftb.de/discord)-Server auch die passenden Gruppen zu deinem Minecraft-Account, 
also beispielsweise VIP oder Stammspieler, erhältst, musst du dich zunächt verifizieren. 
Dadurch wird dein Minecraft-Account mit deinem Discord-Konto bzw. deiner Teamspeak-Identität verbunden.

Für beide Plattformen ist der Ablauf grundsätzlich der selbe. Wichtig ist, dass du auf einem unserer Minecraft-Server eingeloggt sein musst!

## Teamspeak:

- **Schritt 1:** Beim Beitritt unseres [Teamspeak-Servers](https://myftb.de/teamspeak) wirst du von unserem Bot angeschrieben.
![MyFTBLauncher](/guides/bot_verifizierung/teamspeak1.jpg)
- **(Optional:)** Hast du keine Nachricht erhalten, kannst du den Chat auch manuell über einen Link in der Eingangshalle erreichen
![MyFTBLauncher](/guides/bot_verifizierung/teamspeak4.jpg)
- **Schritt 3:** Starte den Verifizierungsprozess mit `verify DeinSpielername`
![MyFTBLauncher](/guides/bot_verifizierung/teamspeak2.jpg)
- **Schritt 4:** Auf unserem Minecraft-Server bekommst du im Chat einen Code zugeschickt
![Logfenster](/guides/bot_verifizierung/ingame.jpg)
- **Schritt 5:** Schreibe den Bot mit `code ErhaltenerCodeAusDemChat` an
![Browserfenster](/guides/bot_verifizierung/teamspeak3.jpg)
- **Schritt 6:** Du bist nun verifiziert und erhältst automatisch die korrekten Gruppen

## Discord

> Hinweis: Alle Befehle können auch auf dem MyFTB Discord-Server ausgeführt werden. Hierfür musst du nur ein `!` vor den jeweiligen Befehl schreiben. Beispielsweise im Privatchat `verify DeinSpielername`, während es auf dem Server `!verify DeinSpielername` ist.

- **Schritt 1:** Beim Beitritt unseres [Discord-Servers](https://myftb.de/discord) wirst du von unserem Bot angeschrieben.
![MyFTBLauncher](/guides/bot_verifizierung/discord4.jpg)
- **(Optional:)** Hast du keine Nachricht erhalten, kannst du den Chat auch manuell über die Seitenleiste öffnen
![MyFTBLauncher](/guides/bot_verifizierung/discord3.jpg)
- **Schritt 3:** Starte den Verifizierungsprozess mit `verify DeinSpielername`
![MyFTBLauncher](/guides/bot_verifizierung/discord1.jpg)
- **Schritt 4:** Auf unserem Minecraft-Server bekommst du im Chat einen Code zugeschickt
![Logfenster](/guides/bot_verifizierung/ingame.jpg)
- **Schritt 5:** Schreibe den Bot mit `code ErhaltenerCodeAusDemChat` an
![Browserfenster](/guides/bot_verifizierung/discord2.jpg)
- **Schritt 6:** Du bist nun verifiziert und erhältst automatisch die korrekten Gruppen

## Aufhebung der Verifizierung

Ein Minecraft-Account kann jeweils nur mit Discord-Konto und einer Teamspeak-Identität verbunden sein. Möchtest du deinen Account neu verifizieren, 
musst du die alte Verifizierung zunächst mit dem Befehl `/unverify` auf einem unserer Minecraft-Server lösen.

## Synchronisierungszeiten

Auf dem Teamspeak-Server werden bei jedem Einloggen deine Gruppen abgeglichen.

Auf dem Discord-Server werden die Gruppen alle 24 Stunden abgeglichen.

Möchtest du in beiden Fällen eine manuelle Synchronisierung anstoßen, kannst du den Bot mit dem Befehl `syncgroups` anschreiben.
