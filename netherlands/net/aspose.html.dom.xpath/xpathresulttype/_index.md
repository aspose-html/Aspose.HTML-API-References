---
title: Enum XPathResultType
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.XPath.XPathResultType opsomming. Een nietondertekende short die aangeeft wat voor soort resultaat dit is. Als een specifieke typeis opgegeven dan wordt het resultaat geretourneerd als het overeenkomstige type  waar vereist en mogelijk gebruik wordt gemaakt van conversies van het XPathtype.
type: docs
weight: 2610
url: /nl/net/aspose.html.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

Een niet-ondertekende short die aangeeft wat voor soort resultaat dit is. Als een specifieke `type`is opgegeven, dan wordt het resultaat geretourneerd als het overeenkomstige type , waar vereist en mogelijk gebruik wordt gemaakt van conversies van het XPath-type.

```csharp
public enum XPathResultType
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Any | `0` | Deze code vertegenwoordigt geen specifiek type. Een evaluatie van een XPath-expressie zal dit type nooit produceren. Als dit type wordt gevraagd, retourneert de evaluatie welk type dan ook het resultaat is van de evaluatie van de uitdrukking. Als het natuurlijke resultaat een knooppunt is dat is ingesteld wanneer`Elk` type werd toen gevraagd`OngeordendeNodeIterator` is altijd het resulterende type. Elke andere weergave van een knooppuntenset moet expliciet worden aangevraagd. |
| Number | `1` | Het resultaat is een getal zoals gedefinieerd door [XPath 1.0]. Documentwijziging maakt het nummer niet ongeldig, maar kan betekenen dat herbeoordeling niet hetzelfde nummer zou opleveren. |
| String | `2` | Het resultaat is een string zoals gedefinieerd door [XPath 1.0]. Documentwijziging maakt de tekenreeks niet ongeldig, maar kan betekenen dat de tekenreeks niet langer overeenkomt met het huidige document . |
| Boolean | `3` | Het resultaat is een boolean zoals gedefinieerd door [XPath 1.0]. Documentwijziging maakt de boolean niet ongeldig, maar kan betekenen dat herbeoordeling niet dezelfde boolean oplevert. |
| UnorderedNodeIterator | `4` | Het resultaat is een knooppuntenset zoals gedefinieerd door [XPath 1.0] die iteratief wordt benaderd, die mogelijk geen knooppunten in een bepaalde volgorde produceert. Documentwijziging maakt de iteratie ongeldig. Dit is het standaardtype dat wordt geretourneerd als het resultaat een knooppuntset en is`Elk` type is aangevraagd. |
| OrderedNodeIterator | `5` | Het resultaat is een knooppuntenset zoals gedefinieerd door [XPath 1.0] die iteratief zal worden benaderd, die documentgeordende knooppunten zal produceren. Documentwijziging maakt de iteratie ongeldig. |
| UnorderedNodeSnapshot | `6` | Het resultaat is een knooppuntenset zoals gedefinieerd door [XPath 1.0] die wordt geopend als een momentopname lijst met knooppunten die mogelijk niet in een bepaalde volgorde staan. Wijziging van het document maakt de momentopname niet ongeldig, maar kan betekenen dat herbeoordeling niet dezelfde momentopname zou opleveren en dat knooppunten in de momentopname mogelijk zijn gewijzigd, verplaatst of verwijderd uit het document. |
| OrderedNodeSnapshot | `7` | Het resultaat is een knooppuntenset zoals gedefinieerd door [XPath 1.0] die wordt geopend als een momentopname lijst met knooppunten die in de oorspronkelijke documentvolgorde staan. Wijziging van het document maakt de momentopname niet ongeldig, maar kan betekenen dat herbeoordeling niet dezelfde momentopname zou opleveren en dat knooppunten in de momentopname mogelijk zijn gewijzigd, verplaatst of verwijderd uit het document. |
| AnyUnorderedNode | `8` | Het resultaat is een knooppuntset zoals gedefinieerd door [XPath 1.0] en zal worden benaderd als een enkel knooppunt, dat`nul`als de knooppuntenset leeg is. Documentwijziging maakt het knooppunt niet ongeldig, maar kan betekenen dat het resulterende knooppunt niet langer overeenkomt met het huidige document. Dit is een gemak waarmee optimalisatie mogelijk is, aangezien de implementatie kan stoppen zodra een willekeurig -knooppunt in de resulterende set is gevonden. Als er meer dan één knooppunt in het daadwerkelijke resultaat is, is het enige geretourneerde knooppunt mogelijk niet het eerste in de documentvolgorde. |
| FirstOrderedNode | `9` | Het resultaat is een knooppuntset zoals gedefinieerd door [XPath 1.0] en zal worden benaderd als een enkel knooppunt, dat`nul`als de knooppuntenset leeg is. Documentwijziging maakt het knooppunt niet ongeldig, maar kan betekenen dat het resulterende knooppunt niet langer overeenkomt met het huidige document. Dit is een gemak dat optimalisatie mogelijk maakt, aangezien de implementatie kan stoppen zodra het eerste knooppunt in documentvolgorde van de resulterende set is gevonden. Als er meer dan één -knooppunt in het werkelijke resultaat is, is het enige geretourneerde knooppunt het eerste in de documentvolgorde. |

### Zie ook

* naamruimte [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* montage [Aspose.HTML](../../)


