---
title: "XPathResultType Enum"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.xpath.XPathResultType enum. En osignerad kort som indikerar vilken typ av resultat detta är. Om en specifik typ anges kommer resultatet att returneras som motsvarande typ med hjälp av XPath-typkonverteringar där det krävs och är möjligt."
type: docs

url: /sv/java/com.aspose.html.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

En osignerad kortvariabel som indikerar vilken typ av resultat detta är. Om en specifik `type` anges, kommer resultatet att returneras som motsvarande typ, med XPath-typkonverteringar där det krävs och är möjligt.

```java
public enum XPathResultType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Any | `0` | Denna kod representerar ingen specifik typ. En utvärdering av ett XPath-uttryck kommer aldrig att producera denna typ. Om denna typ begärs returnerar utvärderingen den typ som naturligt uppstår vid utvärderingen av uttrycket. Om det naturliga resultatet är en nodmängd när `Any`-typen begärdes, blir `UnorderedNodeIterator` alltid den resulterande typen. Alla andra representationer av en nodmängd måste begäras explicit. |
| Number | `1` | Resultatet är ett tal enligt definitionen i [XPath 1.0]. Dokumentändringar ogiltigförklarar inte talet, men kan innebära att en nyutvärdering inte ger samma tal. |
| String | `2` | Resultatet är en Sträng enligt definitionen i [XPath 1.0]. Dokumentändringar ogiltigförklarar inte Strängen, men kan innebära att Strängen inte längre motsvarar det aktuella dokumentet. |
| Boolean | `3` | Resultatet är ett booleskt värde enligt definitionen i [XPath 1.0]. Dokumentändringar ogiltigförklarar inte det booleska värdet, men kan innebära att en nyutvärdering inte ger samma värde. |
| UnorderedNodeIterator | `4` | Resultatet är en nodmängd enligt definitionen i [XPath 1.0] som kommer att nås iterativt, vilket kanske inte ger noder i någon särskild ordning. Dokumentändringar ogiltigförklarar iterationen. Detta är standardtypen som returneras om resultatet är en nodmängd och `Any`-typen begärs. |
| OrderedNodeIterator | `5` | Resultatet är en nodmängd enligt definitionen i [XPath 1.0] som kommer att nås iterativt och som ger dokumentordnade noder. Dokumentändringar ogiltigförklarar iterationen. |
| UnorderedNodeSnapshot | `6` | Resultatet är en nodmängd enligt definitionen i [XPath 1.0] som kommer att nås som en ögonblicksbildlista av noder som kanske inte är i någon särskild ordning. Dokumentändringar ogiltigförklarar inte ögonblicksbilden men kan innebära att en nyutvärdering inte ger samma ögonblicksbild och att noderna i ögonblicksbilden kan ha ändrats, flyttats eller tagits bort från dokumentet. |
| OrderedNodeSnapshot | `7` | Resultatet är en nodmängd enligt definitionen i [XPath 1.0] som kommer att nås som en ögonblicksbildlista av noder som kommer att vara i originaldokumentets ordning. Dokumentändringar ogiltigförklarar inte ögonblicksbilden men kan innebära att en nyutvärdering inte ger samma ögonblicksbild och att noderna i ögonblicksbilden kan ha ändrats, flyttats eller tagits bort från dokumentet. |
| AnyUnorderedNode | `8` | Resultatet är en nodmängd enligt definitionen i [XPath 1.0] och kommer att nås som en enskild nod, som kan vara `null` om nodmängden är tom. Dokumentändringar ogiltigförklarar inte noden, men kan innebära att resultatnoden inte längre motsvarar det aktuella dokumentet. Detta är en bekvämlighet som möjliggör optimering eftersom implementeringen kan stoppa så snart någon nod i den resulterande mängden har hittats. Om det finns mer än en nod i det faktiska resultatet kan den returnerade enskilda noden vara annorlunda än den första i dokumentordning. |
| FirstOrderedNode | `9` | Resultatet är en nodmängd enligt definitionen i [XPath 1.0] och kommer att nås som en enskild nod, som kan vara `null` om nodmängden är tom. Dokumentändringar ogiltigförklarar inte noden, men kan innebära att resultatnoden inte längre motsvarar det aktuella dokumentet. Detta är en bekvämlighet som möjliggör optimering eftersom implementeringen kan stoppa så snart den första noden i dokumentordning i den resulterande mängden har hittats. Om det finns mer än en nod i det faktiska resultatet kommer den returnerade enskilda noden att vara den första i dokumentordning. |

### Se även

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
