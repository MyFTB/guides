# Beitragsrichtlinien, Anleitung zur Erstellung

Um einheitliche und korrekte Anleitungen zu gewähren, stellen wir einige Grundvoraussetzungen an die Mitarbeitenden.
Viele Fallen sind bereits durch den genutzten Static Site Generator [Jekyll](https://jekyllrb.com/) beseitigt, 
und der Aufwand auf ein Minimum reduziert.

> **Hinweis:** aus ersichtlichen Gründen, haben nur einige Teammitglieder direkten Schreibzugriff auf die Dateien. Damit
du deine Anleitung einbringen kannst, ist es notwendig, dieses Repository zu [forken](https://help.github.com/en/github/getting-started-with-github/fork-a-repo)
und anschließend einen [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork) mit dem Inhalt deines Forks zu erstellen.
Dieser wird dann von den berechtigten Teammitgliedern überprüft und anschließend eingepflegt, sofern alles in Ordnung ist.

Damit das Erstellen einer Anleitung auch reibungslos klappt, gibt es hier eine kurze Anleitung dazu:

1. Erstelle einen Unterordner im Ordner [guides](guides/). Wähle einen kurzen und prägnanten Namen, der für deine Anleitung zutreffend ist, 
und sich nicht mit anderen Namen überschneidet.
2. Erstelle im eben erstellen Ordner eine Datei mit dem selben Namen, sowie der Dateiendung `.md`
3. Füge der Datei eine Kopfzeile hinzu:

   ```
   ---
   layout: page
   title: Die korrekte Java Version (32-/64-Bit Problematik)
   permalink: /java-version
   thumbnail: /guides/java_version/thumbnail.jpg
   ---
   ```


   - Die Option `layout` **muss** auf `page` gesetzt sein!
   
   - Gib deiner Anleitung unter `title` eine kurze Überschrift.
   
   - Vergib deiner Anleitung mit `permalink` einen Link. Um die Übersicht zu bewahren, 
     solltest du hier ebenfalls den Namen des Ordners verwenden.
     
   - Gib deiner Anleitung ein Gesicht: Lege ein `thumbnail` fest, welches auf der Startseite angezeigt wird. Dieses **muss** in
     der Größe von 400x250 Pixel, und **sollte** im Format `.jpg`, vorliegen. 
     
   - Möchtest du eine Schritt für Schritt Anleitung erstellen ([Beispiel](https://guides.myftb.de/crashs)), füge die Zeile `stepbystep: true` vor den unteren drei Strichen ein.
   
4. Nun kannst du deiner kreativität freien Lauf lassen: Füge unterhalb der Kopfzeile den gewünschten Text ein, 
der anschließend auf der Seite dargestellt werden soll. Hierfür solltest du das [Markdown-Format](https://www.markdownguide.org/cheat-sheet/) verwenden.

   Benötigst du Beispiele, schau dir zum Beispiel die Anleitung [zum Hochladen eines Crash-Reports](https://raw.githubusercontent.com/MyFTB/guides/master/guides/crashs/crashs.md)
   oder [zum installieren der korrekten Java-Version](https://raw.githubusercontent.com/MyFTB/guides/master/guides/java_version/java_version.md) an.
   Dort sollte gut zu sehen sein, wie du die benötigten Formate verwendest.