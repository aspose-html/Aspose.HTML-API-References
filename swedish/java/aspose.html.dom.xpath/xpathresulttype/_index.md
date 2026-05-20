---
title: "XPathResultType‑enum"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.xpath.XPathResultType‑enum. En osignerad kort integer som anger vilken typ av resultat detta är. Om en specifik typ anges returneras resultatet som motsvarande typ med hjälp av XPath‑typkonverteringar där det krävs och är möjligt."
type: docs

url: /sv/java/com.aspose.html.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

En osignerad short som indikerar vilken typ av resultat detta är. Om en specifik `type` anges, kommer resultatet att returneras som motsvarande typ, med XPath-typkonverteringar där det krävs och är möjligt.

```java
public enum XPathResultType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Any | `0` | Denna kod representerar ingen specifik typ. En utvärdering av ett XPath‑uttryck kommer aldrig att producera denna typ. Om denna typ begärs returnerar utvärderingen den typ som naturligt uppstår vid utvärderingen av uttrycket. Om det naturliga resultatet är en nodmängd när typen `Any` begärdes, blir `UnorderedNodeIterator` alltid den resulterande typen. Alla andra representationer av en nodmängd måste begäras explicit. |
| Number | `1` | Resultatet är ett tal enligt definitionen i [XPath 1.0]. Dokumentändringar gör inte talet ogiltigt, men kan innebära att en omvärdering inte ger samma tal. |
| String | `2` | Resultatet är en Sträng enligt definitionen i [XPath 1.0]. Dokumentändringar gör inte Strängen ogiltig, men kan innebära att Strängen inte längre motsvarar det aktuella dokumentet. |
| Boolean | `3` | Resultatet är ett booleskt värde enligt definitionen i [XPath 1.0]. Dokumentändringar gör inte det booleska värdet ogiltigt, men kan innebära att en omvärdering inte ger samma booleska värde. |
| UnorderedNodeIterator | `4` | Resultatet är en nodmängd enligt definitionen i [XPath 1.0] som kommer att nås iterativt, vilket kan leda till att noderna inte levereras i någon särskild ordning. Dokumentändringar gör iterationen ogiltig. Detta är standardtypen som returneras om resultatet är en nodmängd och typen `Any` begärs. |
| OrderedNodeIterator | `5` | Resultatet är en nodmängd enligt definitionen i [XPath 1.0] som kommer att nås iterativt och som levererar noder i dokumentordning. Dokumentändringar gör iterationen ogiltig. |
| UnorderedNodeSnapshot | `6` | Resultatet är en nodmängd enligt definitionen i [XPath 1.0] som kommer att nås som en snapshot‑lista med noder som kan vara i godtycklig ordning. Dokumentändringar gör inte snapshotet ogiltigt, men kan innebära att en omvärdering inte ger samma snapshot och att noderna i snapshotet kan ha ändrats, flyttats eller tagits bort från dokumentet. |
| OrderedNodeSnapshot | `7` | Resultatet är en nodmängd enligt definitionen i [XPath 1.0] som kommer att nås som en snapshot‑lista med noder i den ursprungliga dokumentordningen. Dokumentändringar gör inte snapshotet ogiltigt, men kan innebära att en omvärdering inte ger samma snapshot och att noderna i snapshotet kan ha ändrats, flyttats eller tagits bort från dokumentet. |
| AnyUnorderedNode | `8` | Resultatet är en nodmängd enligt definitionen i [XPath 1.0] och kommer att nås som en enskild nod, som kan vara `null` om nodmängden är tom. Dokumentändringar gör inte noden ogiltig, men kan innebära att resultatnoden inte längre motsvarar det aktuella dokumentet. Detta är en bekvämlighet som möjliggör optimering eftersom implementationen kan stoppa så snart någon nod i den resulterande mängden har hittats. Om det finns mer än en nod i det faktiska resultatet kan den returnerade enskilda noden vara annorlunda än den första i dokumentordning. |
| FirstOrderedNode | `9` | Resultatet är en nodmängd enligt definitionen i [XPath 1.0] och kommer att nås som en enskild nod, som kan vara `null` om nodmängden är tom. Dokumentändringar gör inte noden ogiltig, men kan innebära att resultatnoden inte längre motsvarar det aktuella dokumentet. Detta är en bekvämlighet som möjliggör optimering eftersom implementationen kan stoppa så snart den första noden i dokumentordning i den resulterande mängden har hittats. Om det finns mer än en nod i det faktiska resultatet kommer den returnerade enskilda noden att vara den första i dokumentordning. |

### Se även

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
