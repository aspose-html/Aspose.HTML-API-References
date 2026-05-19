---
title: "IMediaList Interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.css.IMediaList interface. De MediaList‑interface biedt de abstractie van een geordende verzameling media zonder te definiëren of te beperken hoe deze verzameling wordt geïmplementeerd. Een lege lijst is hetzelfde als een lijst die het medium 'all' bevat."
type: docs

url: /nl/java/com.aspose.html.dom.css/imedialist/
---
## IMediaList interface

De MediaList-interface biedt de abstractie van een geordende collectie media, zonder te definiëren of te beperken hoe deze collectie wordt geïmplementeerd. Een lege lijst is hetzelfde als een lijst die het medium "all" bevat.

Zie ook de [CSS Object Model (CSSOM) # ](https://www.w3.org/TR/cssom-1/#the-medialist-interface)[MediaList](https://www.w3.org/TR/cssom-1/#the-medialist-interface).

```java
public interface IMediaList : IEnumerable<String>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/imedialist/item/) De item(index)-methode moet een serialisatie van de mediavraag in de verzameling mediavragen op de opgegeven index retourneren, of null, als de index groter dan of gelijk is aan het aantal mediavragen in de verzameling. |
| [getLength](../../com.aspose.html.dom.css/imedialist/length/) Het length‑attribuut moet het aantal mediavragen in de verzameling mediavragen retourneren. Het bereik van geldige media is 0 tot en met length‑1. |
| [getMediaText](../../com.aspose.html.dom.css/imedialist/mediatext/) Een Stringifier die een DOMString retourneert die de MediaList als tekst weergeeft, en die tevens toelaat een nieuwe MediaList in te stellen. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [appendMedium](../../com.aspose.html.dom.css/imedialist/appendmedium/)(String) | Voegt het medium newMedium toe aan het einde van de lijst. Als newMedium al wordt gebruikt, wordt het eerst verwijderd. |
| [deleteMedium](../../com.aspose.html.dom.css/imedialist/deletemedium/)(String) | Verwijdert het medium aangeduid door oldMedium uit de lijst. |

## Opmerkingen

Opmerking: MediaList is een live‑lijst; het bijwerken van de lijst met behulp van de hieronder genoemde eigenschappen of methoden zal onmiddellijk het gedrag van het document bijwerken.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referentie

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # medialist](https://drafts.csswg.org/cssom/#medialist) – The CSSOM definition.

## Voorbeelden

Het volgende zou naar de console loggen een tekstuele weergave van de MediaList van de eerste stylesheet die op het huidige document is toegepast.

```java
var stylesheets = document.StyleSheets;
var stylesheet = stylesheets[0];
Console.Write(stylesheet.Media.MediaText);
```

### Zie ook

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
