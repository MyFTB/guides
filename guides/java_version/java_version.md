---
layout: page
title: Die korrekte Java Version (32-/64-Bit Problematik)
permalink: /java-version
thumbnail: /guides/java_version/thumbnail.jpg
---

Minecraft Modpacks sind aufgrund der **hohen Anzahl an Modifikationen** oft sehr **arbeitsspeicherhungrig**.
Dies stellt ein Problem für die 32-Bit Version von Java dar: sie kann **nur maximal 1,5GB RAM** zur Verfügung stellen.

Da dies oftmals **zu wenig für Modpacks** ist, ist die Verwendung einer korrekten Java-Version notwendig.

Wird der Launcher mit einer 32-Bit Version von Java gestartet, erscheint folgende Warnung:

![32-Bit Warnung](/guides/java_version/warnung.png)

---

Zunächst einmal sollte überprüft werden, ob der verwendete **Computer** überhaupt **64-Bit Anwendungen unterstützt**.
Öffne dazu die Systeminformationen über einen der folgenden beiden Wege:

- auf der Tastatur Windows- und Pause-Taste gleichzeitig drücken
- im Ausführen-Dialog (Windows- & R-Taste) `control /name Microsoft.System` eingeben

Steht unter **Systemtyp**, dass ihr ein 64-Bit Betriebssystem besitzt, könnt ihr weiter fortfahren. Besitzt ihr nur ein 32-Bit
Betriebssystem, könnt ihr leider keine 64-Bit Anwendungen verwenden.

![Systeminformationen](/guides/java_version/system.png)

---

Da man über die **offizielle Java Downloadseite** oftmals **nur eine 32-Bit Version** erhält, ist es nun wichtig zu überprüfen, 
welche Version aktuell installiert ist.

Öffne dazu die Übersicht der installierten Programme:

- Windows 7 und darunter: `Programme und Funktionen` in der Systemsteuerung
- Windows 8, 10, etc.: Rechtsklick auf den Start-Button, `Apps und Features` im geöffneten Menü

![Programme und Funktionen unter Windows 7](/guides/java_version/win7.png)
![Apps und Features unter Windows 10](/guides/java_version/win10.png)

Steht der **Zusatz `(64-bit)`** hinter der Java-Version, **ist diese korrekt**. Andere Versionen sollten **zur Vermeidung von 
Komplikationen entfernt werden**. Außerdem sollte darauf geachtet werden, **dass es sich um Java 8 handelt**, da andere Versionen 
von aktuellen Modpacks nicht unterstützt werden.

Eine korrekte Version kann über die [Java Downloadseite](https://java.com/de/download/manual.jsp) unter dem Link `Windows Offline (64-Bit)` heruntergeladen werden.