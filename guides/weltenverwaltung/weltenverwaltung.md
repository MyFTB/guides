---
layout: page
title: Erste Schritte mit der Weltenverwaltung
permalink: /weltenverwaltung
thumbnail: /guides/weltenverwaltung/thumbnail.jpg
---

Eine Besonderheit die MyFTB von anderen Servern abhebt sind die eigenen Welten für jeden Spieler. In dieser Anleitung gibt es einen Überblick über grundlegende Befehle zur Verwaltung dieser.

> *Die Ausgaben der Befehle können von Server zu Server variieren!*

---

Der erste wichtige Befehl ist die Erstellung einer Welt mit dem Befehl `/createworld`.

![/createworld](/guides/weltenverwaltung/createworld.jpg)

Um dich im Nachhinein wieder in die Welt teleportieren zu können, verwende den Befehl `/tpworld`.

![/tpworld](/guides/weltenverwaltung/tpworld_mw.jpg)

Mit diesem Befehl landest du in deiner **Hauptwelt**. Diese lässt sich mit `/mainworld` setzen. Um dich in eine spezifische Welt zu teleportieren, verwende `/tpworld Weltennummer`. Eine Auflistung aller deiner Welten erhälst du mit `/worlds`.

![/tpworld](/guides/weltenverwaltung/tpworld.jpg)

Natürlich lassen sich auch Mitbewohner zu einer Welt hinzufügen, um zum Beispiel mit Freunden zusammen auf einer Welt spielen zu können. Das Hinzufügen erfolgt mit `/addresident Spielername`.

![/addresident](/guides/weltenverwaltung/addresident.jpg)

Das Gegenüber erhält eine Chatnachricht mit dem einzugebenden Befehl, um die Einladung anzunehmen. Mit `/invites` lassen sich ebenfalls alle ausstehenden Einladungen anzeigen.

![/invites](/guides/weltenverwaltung/invites.jpg)

Ein hinzugefügter Mitbewohner kann natürlich auch wieder aus der Welt entfernt werden. Der benötigte Befehl lautet `/removeresident Spielername`

![/removeresident](/guides/weltenverwaltung/removeresident.jpg)

Wird die Welt nicht mehr benötigt, kann diese mit `/leaveworld` gelöscht werden. 

**Achtung: Diese Aktion lässt sich nicht rückgängig machen!**

![/leaveworld](/guides/weltenverwaltung/leaveworld.jpg)

Befinden sich noch Mitbewohner in der Welt, muss zuerst ein neuer Weltenbesitzer ernannt werden. Dies geschieht mit `/newowner Spielername`

![/newowner](/guides/weltenverwaltung/newowner.jpg)

---

Weitere nützliche Befehle für die Weltenverwaltung:

- `/settpworld` - Setzt den Spawnpunkt deiner Welt um
- `/unlock` bzw. `/lock` - Erlaubt bzw. sperrt den Zutritt von Nicht-Mitbewohnern zu deiner Welt
- `/pvp` - Aktiviert bzw. deaktiviert PvP in deiner Welt