Inhalte Anpassen
=========================

Um Inhalte anzupassen muss man sich erst einmal einloggen (und natürlich die entprechenden Berechtigungen haben).

## Textgestaltung 
Inhalte werden mit Markdown formatiert. Dies ist eine einfache Auszeichnungssyntax.
Siehe: https://help.github.com/articles/basic-writing-and-formatting-syntax/


## Neuigkeiten (_posts)
Neuen Eintrag anlegen unter dem Ordner **_posts** mit "Create new file". Der Name sollte dem Pattern 
```
yyyy-MM-dd-Ein-sprechender-Titel.md (z.B. 2017-06-03-Kunst-Suedwest.md) 
```
entsprechen.

Das Datum darf nicht neuer als Heute sein, sonst wird der Artikel nicht veröffentlicht!

**Als ersten braucht die Datei einen sogenannten "Front Matter"**
```
---
type: news
published: true
hideDate: false
title: "Kunst Südwest 7.06 - 16.07.2017"
---
```
Der _title_ kann beliebig gewählt werden. Der _type_ muss "news" sein und _published_ steuert mit den Werten "true" oder "false" ob der Eintrag veröffentlicht wird.
_hideDate_ steuert mit den Werten "true" oder "false" ob ein Datum über dem Eintrag angezeigt wird.

Nach einem Zeilenumbruch kann dann beliebiger Text (formatiert mit Markdown) folgen.

## Vita (_posts)
Im Ordner **_posts** die Datei _2017-06-04-vita.md_ bearbeiten. Den "Front Matter" nicht verändern.

## Galerie (gallery)
Neue Bilder für die Galerie können unter dem Ordner **gallery** hoch geladen werden (Upload files).
Es brauch immer zwei Versionen eines Bildes. Eine für die Vorschau und eines für die große Ansicht.
Diese müssen dem folgenden Names-Pattern entsprechen:
```
Irgend ein Bildname.jpg
Irgend ein Bildname.jpg-thumbnail.jpg
```
Wobei die Version die auf "-thumbnail.jpg" endet die kleine Version ist und in der Breite nicht mehr als 250px haben darf (Höhe entsprechen). 
Die große Version sollte die Maße 1920x1080px nicht überschreiten. 

Die Bilder können am Besten mit dem Programm Gimp oder gThumb skaliert werden.

## Sonstige Bilder (_images)
Unter dem Ordner **_images** befinden sich die sonstige Bilder. Zum Beispiel:
```
intro-bg.jpg (Hintergrung)
juergen.jpg (Profilfoto)
```
Diese bei Bedarf am Besten 1:1 ersetzen.


## Todos
* Https: https://help.github.com/articles/troubleshooting-custom-domains/#https-errors



Grayscale Jekyll theme
=========================

Jekyll theme based on [Grayscale bootstrap theme ](http://ironsummitmedia.github.io/startbootstrap-grayscale/)

## Demo
View this jekyll theme in action [here](https://jeromelachaud.github.io/grayscale-theme)

=========
For more details, read the [documentation](http://jekyllrb.com/)


## Links
https://pages.github.com/versions/

https://www.aleksandrhovhannisyan.com/blog/getting-started-with-jekyll-and-github-pages/

