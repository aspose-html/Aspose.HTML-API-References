---
title: "XPathResultType‑enum"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.xpath.XPathResultType‑enum. Een unsigned short die aangeeft welk type resultaat dit is. Als een specifiek type is opgegeven, wordt het resultaat geretourneerd als het overeenkomstige type met behulp van XPath‑typeconversies waar nodig en mogelijk."
type: docs

url: /nl/java/com.aspose.html.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

Een unsigned short die aangeeft van welk type resultaat dit is. Als een specifiek `type` is opgegeven, wordt het resultaat geretourneerd als het overeenkomstige type, met gebruik van XPath-typeconversies waar vereist en mogelijk.

```java
public enum XPathResultType
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Any | `0` | Deze code vertegenwoordigt geen specifiek type. Een evaluatie van een XPath‑expressie zal dit type nooit opleveren. Als dit type wordt aangevraagd, retourneert de evaluatie welk type dan ook dat natuurlijk voortkomt uit de evaluatie van de expressie. Als het natuurlijke resultaat een knooppuntset is wanneer het type `Any` werd aangevraagd, is `UnorderedNodeIterator` altijd het resulterende type. Elke andere weergave van een knooppuntset moet expliciet worden aangevraagd. |
| Number | `1` | Het resultaat is een getal zoals gedefinieerd in [XPath 1.0]. Documentwijziging maakt het getal niet ongeldig, maar kan betekenen dat een her-evaluatie niet hetzelfde getal oplevert. |
| String | `2` | Het resultaat is een String zoals gedefinieerd in [XPath 1.0]. Documentwijziging maakt de String niet ongeldig, maar kan betekenen dat de String niet langer overeenkomt met het huidige document. |
| Boolean | `3` | Het resultaat is een boolean zoals gedefinieerd in [XPath 1.0]. Documentwijziging maakt de boolean niet ongeldig, maar kan betekenen dat een her-evaluatie niet dezelfde boolean oplevert. |
| UnorderedNodeIterator | `4` | Het resultaat is een knooppuntset zoals gedefinieerd in [XPath 1.0] die iteratief wordt benaderd, wat mogelijk geen knooppunten in een specifieke volgorde oplevert. Documentwijziging maakt de iteratie ongeldig. Dit is het standaardtype dat wordt geretourneerd als het resultaat een knooppuntset is en het type `Any` wordt aangevraagd. |
| OrderedNodeIterator | `5` | Het resultaat is een knooppuntset zoals gedefinieerd in [XPath 1.0] die iteratief wordt benaderd en document‑geordende knooppunten oplevert. Documentwijziging maakt de iteratie ongeldig. |
| UnorderedNodeSnapshot | `6` | Het resultaat is een knooppuntset zoals gedefinieerd in [XPath 1.0] die wordt benaderd als een snapshot‑lijst van knooppunten die mogelijk niet in een specifieke volgorde staan. Documentwijziging maakt de snapshot niet ongeldig, maar kan betekenen dat een her‑evaluatie niet dezelfde snapshot oplevert en dat knooppunten in de snapshot zijn gewijzigd, verplaatst of verwijderd uit het document. |
| OrderedNodeSnapshot | `7` | Het resultaat is een knooppuntset zoals gedefinieerd in [XPath 1.0] die wordt benaderd als een snapshot‑lijst van knooppunten die in de oorspronkelijke documentvolgorde staan. Documentwijziging maakt de snapshot niet ongeldig, maar kan betekenen dat een her‑evaluatie niet dezelfde snapshot oplevert en dat knooppunten in de snapshot zijn gewijzigd, verplaatst of verwijderd uit het document. |
| AnyUnorderedNode | `8` | Het resultaat is een knooppuntset zoals gedefinieerd in [XPath 1.0] en wordt benaderd als een enkel knooppunt, dat `null` kan zijn als de knooppuntset leeg is. Documentwijziging maakt het knooppunt niet ongeldig, maar kan betekenen dat het resultaat‑knooppunt niet langer overeenkomt met het huidige document. Dit is een gemak dat optimalisatie mogelijk maakt omdat de implementatie kan stoppen zodra een willekeurig knooppunt in de resulterende set is gevonden. Als er meer dan één knooppunt in het daadwerkelijke resultaat is, is het geretourneerde enkele knooppunt mogelijk niet het eerste in documentvolgorde. |
| FirstOrderedNode | `9` | Het resultaat is een knooppuntset zoals gedefinieerd in [XPath 1.0] en wordt benaderd als een enkel knooppunt, dat `null` kan zijn als de knooppuntset leeg is. Documentwijziging maakt het knooppunt niet ongeldig, maar kan betekenen dat het resultaat‑knooppunt niet langer overeenkomt met het huidige document. Dit is een gemak dat optimalisatie mogelijk maakt omdat de implementatie kan stoppen zodra het eerste knooppunt in documentvolgorde van de resulterende set is gevonden. Als er meer dan één knooppunt in het daadwerkelijke resultaat is, zal het geretourneerde enkele knooppunt het eerste in documentvolgorde zijn. |

### Zie ook

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
