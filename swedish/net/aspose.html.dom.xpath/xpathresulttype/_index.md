---
title: Enum XPathResultType
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.XPath.XPathResultType uppräkning. En osignerad kortslutning som indikerar vilken typ av resultat detta är. Om en specifik typanges kommer resultatet att returneras som motsvarande typ med hjälp av XPathtypkonverteringar där så krävs och är möjligt.
type: docs
weight: 2610
url: /sv/net/aspose.html.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

En osignerad kortslutning som indikerar vilken typ av resultat detta är. Om en specifik `typ`anges, kommer resultatet att returneras som motsvarande -typ, med hjälp av XPath-typkonverteringar där så krävs och är möjligt.

```csharp
public enum XPathResultType
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Any | `0` | Den här koden representerar inte en specifik typ. En utvärdering av ett XPath-uttryck kommer aldrig att producera den här typen. Om denna typ efterfrågas, returnerar utvärderingen vilken typ som naturligt är resultatet av utvärderingen av uttrycket. Om det naturliga resultatet är en nod inställd när`Några` typ efterfrågades alltså`UnorderedNodeIterator` är alltid den resulterande typen. Alla andra representationer av en noduppsättning måste uttryckligen begäras. |
| Number | `1` | Resultatet är ett tal som definieras av [XPath 1.0]. Dokumentändring ogiltigförklarar inte numret, men kan betyda att omvärdering inte skulle ge samma siffra. |
| String | `2` | Resultatet är en sträng som definieras av [XPath 1.0]. Dokumentändring ogiltigförklarar inte strängen, men kan innebära att strängen inte längre motsvarar det aktuella dokumentet. |
| Boolean | `3` | Resultatet är en boolean som definieras av [XPath 1.0]. Dokumentändring ogiltigförklarar inte booleanvärdet, men kan betyda att omvärdering inte skulle ge samma boolean. |
| UnorderedNodeIterator | `4` | Resultatet är en noduppsättning enligt definitionen av [XPath 1.0] som kommer att nås iterativt, som kanske inte producerar noder i en viss ordning. Dokumentändring ogiltigförklarar iterationen. Detta är standardtypen som returneras om resultatet är en noduppsättning och`Några` typ begärs. |
| OrderedNodeIterator | `5` | Resultatet är en noduppsättning enligt definitionen av [XPath 1.0] som kommer att nås iterativt, som kommer att producera dokumentbeställda noder. Dokumentändring ogiltigförklarar iterationen. |
| UnorderedNodeSnapshot | `6` | Resultatet är en noduppsättning enligt definitionen av [XPath 1.0] som kommer att nås som en ögonblicksbild lista över noder som kanske inte är i en viss ordning. Dokumentändring ogiltigförklarar inte ögonblicksbilden men kan innebära att omvärdering inte skulle ge samma ögonblicksbild och noder i ögonblicksbilden kan ha ändrats, flyttats eller tagits bort från dokumentet. |
| OrderedNodeSnapshot | `7` | Resultatet är en noduppsättning som definieras av [XPath 1.0] som kommer att nås som en ögonblicksbild lista över noder som kommer att vara i originaldokumentordning. Dokumentändring ogiltigförklarar inte ögonblicksbilden men kan innebära att omvärdering inte skulle ge samma ögonblicksbild och noder i ögonblicksbilden kan ha ändrats, flyttats eller tagits bort från dokumentet. |
| AnyUnorderedNode | `8` | Resultatet är en noduppsättning enligt definitionen av [XPath 1.0] och kommer att nås som en enda nod, som kan vara`null`om noduppsättningen är tom. Dokumentändring ogiltigförklarar inte noden, men kan innebära att resultatnoden inte längre motsvarar det aktuella dokumentet. Detta är en bekvämlighet som tillåter optimering eftersom implementeringen kan stoppa när någon -nod i den resulterande uppsättningen har hittats. Om det finns mer än en nod i det faktiska resultatet, kanske den enda noden som returneras kanske inte är den första i dokumentordning. |
| FirstOrderedNode | `9` | Resultatet är en noduppsättning enligt definitionen av [XPath 1.0] och kommer att nås som en enda nod, som kan vara`null`om noduppsättningen är tom. Dokumentändring ogiltigförklarar inte noden, men kan innebära att resultatnoden inte längre motsvarar det aktuella dokumentet. Detta är en bekvämlighet som tillåter optimering eftersom implementeringen kan stoppa när den första noden i dokumentordning för den resulterande uppsättningen har hittats. Om det finns mer än en -nod i det faktiska resultatet, kommer den enda noden som returneras att vara den första i dokumentordning. |

### Se även

* namnutrymme [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* hopsättning [Aspose.HTML](../../)


