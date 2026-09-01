---
title: "IMediaList-gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.css.IMediaList gränssnitt. MediaList-gränssnittet tillhandahåller en abstraktion av en ordnad samling av media utan att definiera eller begränsa hur samlingen implementeras. En tom lista är densamma som en lista som innehåller mediet all"
type: docs

url: /sv/java/com.aspose.html.dom.css/imedialist/
---
## IMediaList interface

MediaList‑gränssnittet tillhandahåller abstraktionen av en ordnad samling av media, utan att definiera eller begränsa hur samlingen implementeras. En tom lista är samma som en lista som innehåller mediet "all".

Se även [CSS Object Model (CSSOM) # ](https://www.w3.org/TR/cssom-1/#the-medialist-interface)[MediaList](https://www.w3.org/TR/cssom-1/#the-medialist-interface).

```java
public interface IMediaList : IEnumerable<String>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/imedialist/item/) Metoden item(index) måste returnera en serialisering av mediafrågan i samlingen av mediafrågor som anges av index, eller null om index är större än eller lika med antalet mediafrågor i samlingen. |
| [getLength](../../com.aspose.html.dom.css/imedialist/length/) length‑attributet måste returnera antalet mediafrågor i samlingen av mediafrågor. Giltigt intervall för media är 0 till length‑1 inklusive. |
| [getMediaText](../../com.aspose.html.dom.css/imedialist/mediatext/) En Stringifier som returnerar en DOMString som representerar MediaList som text, och som även låter dig ange en ny MediaList. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [appendMedium](../../com.aspose.html.dom.css/imedialist/appendmedium/)(String) | Lägger till mediet newMedium i slutet av listan. Om newMedium redan används tas det först bort. |
| [deleteMedium](../../com.aspose.html.dom.css/imedialist/deletemedium/)(String) | Tar bort mediet som anges av oldMedium från listan. |

## Anmärkningar

Obs: MediaList är en levande lista; att uppdatera listan med egenskaper eller metoder som listas nedan uppdaterar omedelbart dokumentets beteende.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referens

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # medialist](https://drafts.csswg.org/cssom/#medialist) – The CSSOM definition.

## Exempel

Följande skulle skriva ut en textuell representation av MediaList för den första stilmallen som tillämpas på det aktuella dokumentet i konsolen.

```java
var stylesheets = document.StyleSheets;
var stylesheet = stylesheets[0];
Console.Write(stylesheet.Media.MediaText);
```

### Se även

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
