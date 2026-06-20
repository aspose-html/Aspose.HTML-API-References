---
title: "IMediaList Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.css.IMediaList Schnittstelle. Die MediaList Schnittstelle bietet die Abstraktion einer geordneten Sammlung von Medien, ohne zu definieren oder einzuschränken, wie diese Sammlung implementiert wird. Eine leere Liste ist dasselbe wie eine Liste, die das Medium \\\"all\\\" enthält."
type: docs

url: /de/java/com.aspose.html.dom.css/imedialist/
---
## IMediaList interface

Das MediaList-Interface bietet die Abstraktion einer geordneten Sammlung von Medien, ohne zu definieren oder einzuschränken, wie diese Sammlung implementiert wird. Eine leere Liste ist dasselbe wie eine Liste, die das Medium \"all\" enthält.

Siehe auch das [CSS Object Model (CSSOM) # ](https://www.w3.org/TR/cssom-1/#the-medialist-interface)[MediaList](https://www.w3.org/TR/cssom-1/#the-medialist-interface).

```java
public interface IMediaList : IEnumerable<String>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/imedialist/item/) Die item(index)-Methode muss eine Serialisierung der Medienabfrage in der Sammlung von Medienabfragen zurückgeben, die durch den Index angegeben ist, oder null, wenn der Index größer oder gleich der Anzahl der Medienabfragen in der Sammlung ist. |
| [getLength](../../com.aspose.html.dom.css/imedialist/length/) Das length-Attribut muss die Anzahl der Medienabfragen in der Sammlung von Medienabfragen zurückgeben. Der gültige Bereich für Medien ist 0 bis length‑1 inklusive. |
| [getMediaText](../../com.aspose.html.dom.css/imedialist/mediatext/) Ein Stringifier, der einen DOMString zurückgibt, der die MediaList als Text darstellt, und außerdem das Setzen einer neuen MediaList ermöglicht. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [appendMedium](../../com.aspose.html.dom.css/imedialist/appendmedium/)(String) | Fügt das Medium newMedium am Ende der Liste hinzu. Wenn das newMedium bereits verwendet wird, wird es zuerst entfernt. |
| [deleteMedium](../../com.aspose.html.dom.css/imedialist/deletemedium/)(String) | Löscht das durch oldMedium angegebene Medium aus der Liste. |

## Hinweise

Hinweis: MediaList ist eine Live-Liste; das Aktualisieren der Liste mittels der unten aufgeführten Eigenschaften oder Methoden wird das Verhalten des Dokuments sofort ändern.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referenz

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # medialist](https://drafts.csswg.org/cssom/#medialist) – The CSSOM definition.

## Beispiele

Das Folgende würde in die Konsole eine textuelle Darstellung der MediaList des ersten auf das aktuelle Dokument angewendeten Stylesheets protokollieren.

```java
var stylesheets = document.StyleSheets;
var stylesheet = stylesheets[0];
Console.Write(stylesheet.Media.MediaText);
```

### Siehe auch

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
