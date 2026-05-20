---
title: "IStyleSheet gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.css.IStyleSheet gränssnitt. StyleSheet‑gränssnittet är det abstrakta basgränssnittet för alla typer av stilblad. Det representerar ett enskilt stilblad som är associerat med ett strukturerat dokument. I HTML representerar StyleSheet‑gränssnittet antingen ett externt stilblad inkluderat via HTML‑LINK‑elementet eller ett inbäddat STYLE‑element. I XML representerar detta gränssnitt ett externt stilblad inkluderat via en stilblads‑processinstruktion. CSS‑stilblad kommer dessutom att implementera det mer specialiserade CSSStyleSheet‑gränssnittet."
type: docs

url: /sv/java/com.aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

StyleSheet‑gränssnittet är det abstrakta basgränssnittet för alla typer av stilblad. Det representerar ett enskilt stilblad som är associerat med ett strukturerat dokument. I HTML representerar StyleSheet‑gränssnittet antingen ett externt stilblad, inkluderat via HTML‑LINK‑elementet, eller ett inbäddat STYLE‑element. I XML representerar detta gränssnitt ett externt stilblad, inkluderat via en stilblads‑processinstruktion. CSS‑stilblad kommer dessutom att implementera det mer specialiserade [`CSSStyleSheet`](../icssstylesheet/)‑gränssnittet.

Se även [CSS Object Model (CSSOM) # StyleSheet Interface Specification](https://drafts.csswg.org/cssom/#the-stylesheet-interface).

```java
public interface IStyleSheet
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
[getDisabled]
[setDisabled] The disabled property of the `StyleSheet` interface determines whether the style sheet is prevented from applying to the document. |
| [getHref](../../com.aspose.html.dom.css/istylesheet/href/) href‑egenskapen för `StyleSheet`‑gränssnittet returnerar platsen för stilbladet. |
| [getMedia](../../com.aspose.html.dom.css/istylesheet/media/) media‑egenskapen för `StyleSheet`‑gränssnittet specificerar den avsedda målmediet för stilinformation. Det är ett skrivskyddat, array‑likt [`MediaList`](../imedialist/)‑objekt och kan tas bort med deleteMedium() och läggas till med appendMedium(). |
| [getOwnerNode](../../com.aspose.html.dom.css/istylesheet/ownernode/) Noden som associerar detta stilblad med dokumentet. För HTML kan detta vara motsvarande LINK‑ eller STYLE‑element. För XML kan det vara den länkande processinstruktionen. För stilblad som inkluderas av andra stilblad är värdet för detta attribut null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/istylesheet/parentstylesheet/) För stilblads‑språk som stödjer konceptet stilblads‑inkludering representerar detta attribut det inkluderande stilbladet, om ett sådant finns. Om stilbladet är ett toppnivå‑stilblad, eller om språkets stilblads‑funktioner inte stödjer inkludering, är värdet för detta attribut null. |
| [getTitle](../../com.aspose.html.dom.css/istylesheet/title/) title‑egenskapen för `StyleSheet`‑gränssnittet returnerar den rådgivande titeln för det aktuella stilbladet. |
| [getType](../../com.aspose.html.dom.css/istylesheet/type/) Detta specificerar stilblads‑språket för detta stilblad. Stilblads‑språket anges som en innehållstyp (t.ex. \"text/css\"). |

## Anmärkningar

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referens

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[The StyleSheet Interface](https://drafts.csswg.org/cssom/#the-stylesheet-interface) – The official CSSOM definition.

### Se även

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
