---
title: "IStyleSheet-gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.css.IStyleSheet gränssnitt. StyleSheet‑gränssnittet är det abstrakta basgränssnittet för alla typer av stilark. Det representerar ett enskilt stilark som är kopplat till ett strukturerat dokument. I HTML representerar StyleSheet‑gränssnittet antingen ett externt stilark inkluderat via HTML‑LINK‑elementet eller ett inbäddat STYLE‑element. I XML representerar detta gränssnitt ett externt stilark inkluderat via en stilarks‑processinstruktion. CSS‑stilark kommer dessutom att implementera det mer specialiserade CSSStyleSheet‑gränssnittet."
type: docs

url: /sv/java/com.aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

StyleSheet‑gränssnittet är det abstrakta basgränssnittet för alla typer av stilark. Det representerar ett enskilt stilark som är kopplat till ett strukturerat dokument. I HTML representerar StyleSheet‑gränssnittet antingen ett externt stilark, inkluderat via HTML‑LINK‑elementet, eller ett inbäddat STYLE‑element. I XML representerar detta gränssnitt ett externt stilark, inkluderat via en stilarks‑processinstruktion. CSS‑stilark kommer dessutom att implementera det mer specialiserade [`CSSStyleSheet`](../icssstylesheet/)‑gränssnittet.

Se även [CSS Object Model (CSSOM) # StyleSheet Interface Specification](https://drafts.csswg.org/cssom/#the-stylesheet-interface).

```java
public interface IStyleSheet
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
[getDisabled]
[setDisabled] The disabled property of the `StyleSheet` interface determines whether the style sheet is prevented from applying to the document. |
| [getHref](../../com.aspose.html.dom.css/istylesheet/href/) href‑egenskapen i `StyleSheet`‑gränssnittet returnerar platsen för stilarket. |
| [getMedia](../../com.aspose.html.dom.css/istylesheet/media/) media‑egenskapen i `StyleSheet`‑gränssnittet specificerar den avsedda destinationen för media för stilinformation. Den är en skrivskyddad, array‑liknande [`MediaList`](../imedialist/)‑objekt och kan tas bort med deleteMedium() och läggas till med appendMedium(). |
| [getOwnerNode](../../com.aspose.html.dom.css/istylesheet/ownernode/) Noden som kopplar detta stilark till dokumentet. För HTML kan detta vara motsvarande LINK‑ eller STYLE‑element. För XML kan det vara den länkande processinstruktionen. För stilark som inkluderas av andra stilark är värdet på detta attribut null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/istylesheet/parentstylesheet/) För stilarkspråk som stödjer konceptet stilark‑inkludering representerar detta attribut det inkluderande stilarket, om ett sådant finns. Om stilarket är ett top‑level‑stilark, eller om stilarkspråket inte stödjer inkludering, är värdet på detta attribut null. |
| [getTitle](../../com.aspose.html.dom.css/istylesheet/title/) title‑egenskapen i `StyleSheet`‑gränssnittet returnerar den rådgivande titeln för det aktuella stilarket. |
| [getType](../../com.aspose.html.dom.css/istylesheet/type/) Detta specificerar stilarkspråket för detta stilark. Stilarkspråket anges som en innehållstyp (e.g. "text/css"). |

## Anmärkningar

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referens

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[The StyleSheet Interface](https://drafts.csswg.org/cssom/#the-stylesheet-interface) – The official CSSOM definition.

### Se även

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
