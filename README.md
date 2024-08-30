# Grüne Webfonts

Dieses Repository bietet die im [Styleguide für digitale Anwendungen](https://zeroheight.com/0cb5678fa/p/150f78-typografie)
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

- GrueneType wird ausschließlich im Schnitt Black Condensed Italic verwendet

## Lizenzen

Die Schriften im `fonts` Verzeichnis unterliegen diversen Lizenzen:

- GruenType: TODO

- PT Sans Regular, PT Sans Bold: ParaType Free Font License (enthalten
  als Datei `LICENSE.txt` im selben Verzeichnis)

- Arvo Gruen, Arvo Regular: TODO

Alle weiteren Inhalte sind gemeinfrei (Public Domain).

## netzbegrünung

Dies ist ein Service von netzbegrünung.

TODO: Ein Standard-Satz über netzbegrünung.

Weitere Informationen unter [netzbegruenung.de](https://blog.netzbegruenung.de/)
