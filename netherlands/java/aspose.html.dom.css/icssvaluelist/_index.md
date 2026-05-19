---
title: "ICSSValueList Interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.css.ICSSValueList interface. De CSSValueList interface is afgeleid van de CSSValue interface en biedt de abstractie van een geordende collectie van CSS‑waarden."
type: docs

url: /nl/java/com.aspose.html.dom.css/icssvaluelist/
---
## ICSSValueList interface

De CSSValueList interface is afgeleid van de [`CSSValue`](../cssvalue/) interface en biedt de abstractie van een geordende collectie van CSS‑waarden.

Sommige eigenschappen staan een lege lijst toe in hun syntaxis. In dat geval gebruiken deze eigenschappen de identifier none. Dus, een lege lijst betekent dat de eigenschap de waarde none heeft.

De items in de CSSValueList zijn toegankelijk via een geheel getal index, beginnend bij 0.

```java
public interface ICSSValueList
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssvaluelist/item/) Deze methode wordt gebruikt om een CSSValue op te halen via een ordinale index. De volgorde in deze collectie vertegenwoordigt de volgorde van de waarden in de CSS‑stijleigenschap. Als de index groter dan of gelijk is aan het aantal waarden in de lijst, retourneert deze null. |
| [getLength](../../com.aspose.html.dom.css/icssvaluelist/length/) De alleen‑lezen eigenschap length van de CSSValueList interface geeft het aantal CSSValues in de lijst weer. Het bereik van geldige indexwaarden is 0 tot en met length‑1. |

## Opmerkingen

Deze interface maakte deel uit van een poging om een getypeerd CSS Object Model te creëren. Deze poging is opgegeven, en de meeste browsers implementeren het niet.

Om uw doel te bereiken, kunt u gebruiken:

het niet‑getypeerde [CSS Object Model](https://drafts.csswg.org/cssom/), breed ondersteund, of het moderne [CSS Typed Object Model API](https://drafts.css-houdini.org/css-typed-om/#stylevalue-objects), minder ondersteund en als experimenteel beschouwd.

### Zie ook

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
