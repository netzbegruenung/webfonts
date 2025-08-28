# Grüne Webfonts

Dieses Repository bietet die im [Styleguide für digitale Anwendungen](https://design.gruene.de/4ccd94a80/p/93942a-typografie/b/137a4f)
von Bündnis 90/Die Grünen festgelegten Schriften für die Verwendung auf Webseiten an.

## So funktioniert's

Die Schriften werden mittels CSS-Code in Deine HTML-Seite(n)
eingebunden. Dazu fügst Du im Kopfbereich (zwischen dem `<head>`
und `</head>` Tag) dieses `link` Tag ein:

```html
<link rel="stylesheet" type="text/css" href="https://netzbegruenung.github.io/webfonts/style.css">
```

Oder verwende ein `@import`-Statement in deinem Stylesheet:

```css
@import url('https://netzbegruenung.github.io/webfonts/style.css');
```

Um die Schriften anzuwenden, musst Du per CSS die gewünschte
Kombination aus Schriftart (`font-family`) und Gewicht
(`font-weight`) auf Deinen Inhalt anwenden.

Ein Beispiel dafür findest Du in der Datei `test.html`.

## Testing

Die Datei `test.html` erlaubt einen Test auf Basis der lokal vorhandenen
Font-Dateien. Öffne die Datei einfach im Browser Deiner Wahl.

Online ist diese Datei unter der folgenden URL abrufbar:

https://netzbegruenung.github.io/webfonts/test.html

## Bekannte Limitierungen

- Es gibt keine kursiven Varianten ("Schnitte") der hier angebotenen Schriften

- GrueneType (bzw. GrueneTypeNeue) sieht aus wie Black Italic, ist aber in den Metadaten der Font und im Styleguide als Regular definiert. Für diese Schrift gibt es außerdem keinen anderen Schnitt.

## Lizenzen

Die Schriften im `fonts` Verzeichnis unterliegen diversen Lizenzen:

- GruenType: TODO

- PT Sans Regular, PT Sans Bold: ParaType Free Font License (enthalten
  als Datei `LICENSE.txt` im selben Verzeichnis)

- Arvo Gruen, Arvo Regular: TODO

Alle weiteren Inhalte sind gemeinfrei (Public Domain).

## netzbegrünung

Dies ist ein Service von netzbegrünung.

Unter dem Label netzbegrünung engagieren sich seit 2006 Personen aus dem Umfeld der Partei BÜNDNIS 90/DIE GRÜNEN.

Weitere Informationen unter [netzbegruenung.de](https://blog.netzbegruenung.de/)
