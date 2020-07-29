# Bearbeiten von ".md" Dateien

## Über Markdown

[Markdown](https://de.wikipedia.org/wiki/Markdown) ist ein Dateiformat, welches vielseitige Textformatierungen mit einer einfachen Syntax ermöglicht, ähnlich den Formatierungsoptionen die in Online-Foren häufig Verwendung finden.

Da Markdown ein textbasiertes Format ist und frei in andere Formate (PDF, DOCX, ODT) konvertiert werden kann eignet es sich gut, um kollaborativ an Dokumenten zu arbeiten.

### Markdown Syntax lernen

Die wichtigsten Elemente von Markdown können innerhalb weniger Minuten erlernt werden. Eine gute Ressource ist [Mastering Markdown](https://guides.github.com/features/mastering-markdown/).

### Markdown Visual Editor

Um in GitHub bequem wie in Word oder LibreOffice/OpenOffice schreiben zu können, gibt es für Chrome und Firefox das Plugin [GitHub Writer](https://ckeditor.com/github-writer/), mit dem der reine Online-Texteditor von GitHub in einen "What You See Is What You Get" Editor verwandelt wird.

## Dateien bearbeiten

### Berechtigung freischalten

Um Dateien zu bearbeiten (oder neue anzulegen) muss zuerst die korrekte Berechtigung vergeben werden. Dafür kannst Du ein Issue (Supportanfrage) anlegen, wir schalten Dich dann frei:

![](https://user-images.githubusercontent.com/1525711/88807750-6bbaa780-d1b2-11ea-9b97-a61f2e8da7c8.png)

![](https://user-images.githubusercontent.com/1525711/88807920-8856df80-d1b2-11ea-9728-93ac8c5f698e.png)

### Speichern - "Commit"

Ohne zu weit ins Detail zu gehen, GitHub verwendet, wie der Name erahnen lässt, "Git", eine Software zur Versionierung von Dateien. Damit wird jede gespeicherte Änderung als einzelner Schritt aufgezeichnet und alle Änderungen sind jederzeit nachvollziehbar. "Speichern" heißt hier also "to commit", und jeder solche "Commit" sollte mit einer kurzen Nachricht versehen sein, was eigentlich geändert wird.

Das sieht dann so aus:

![](https://user-images.githubusercontent.com/1525711/88808873-b38dfe80-d1b3-11ea-8d6b-128dd7c7ccbb.png)

Was genau ein "Branch" ist geht für diese Anleitung zu weit, für unsere Zwecke reicht im Zweifel immer mit "Master" zu arbeiten. Einfach gesagt können Branches dazu verwendet werden, parallel an Dokumenten zu arbeiten, wer sich mit Git auskennt (oder die [richtige Arbeitsweise kennenlernen möchte](https://guides.github.com/activities/hello-world/)) kann natürlich gerne mit Branches arbeiten.

### Datei anlegen oder hochladen

Mit dem Button "Add File" kann eine neue Datei angelegt werden, oder eine bestehende hochgeladen. Wichtig beim Anlegen neuer Dateien ist die Angabe der Dateiendung ".md", um das korrekte Dateiformat zu verwenden.

![](https://user-images.githubusercontent.com/1525711/88808740-8b060480-d1b3-11ea-8d20-1ced29c1578a.png)

### Bestehende Datei bearbeiten

Dateinamen klicken

![](https://user-images.githubusercontent.com/1525711/88809292-3c0c9f00-d1b4-11ea-979f-82228a94f8a5.png)

Auf das Stiftsymbol klicken

![](https://user-images.githubusercontent.com/1525711/88809393-5e9eb800-d1b4-11ea-95ab-614548b532d8.png)

Und schon kann man editieren!

Zum Schluss noch eine kurze Nachricht was eigentlich geändert wurde und schon kann mit "Commit" gespeichert werden.

### Datei herunterladen

Dateinamen klicken

![](https://user-images.githubusercontent.com/1525711/88809292-3c0c9f00-d1b4-11ea-979f-82228a94f8a5.png)

"Raw" klicken

![](https://user-images.githubusercontent.com/1525711/88809707-b6d5ba00-d1b4-11ea-8ecf-72e3bd0a85a9.png)

Und nun Rechtsklick → Speichern unter

## Markdown konvertieren

Wenn ein Dokument GitHub verlassen soll, zum Beispiel für das Offline-Lernen, muss es zuerst heruntergeladen werden, dann kann es einfach mit https://cloudconvert.com/ online verwandelt werden:

*   PDF: https://cloudconvert.com/md-to-pdf / https://www.markdowntopdf.com
*   Open Office: https://cloudconvert.com/md-to-odt
*   MS Office Word: https://cloudconvert.com/md-to-docx

Bestehende Dateien können natürlich auch zu Markdown konvertiert werden, zu komplizierte Formatierungen gehen dabei aber verloren. Dabei helfen [MS Office Word to MD](https://word2md.com/), [PDF to MD](https://pdf2md.morethan.io/) und [Open Office to MD](https://www.privatedaddy.com/convert_odt_to_md).

Volle Kontrolle über diverse Formate ist mit dem Tool https://pandoc.org/ offline möglich.
