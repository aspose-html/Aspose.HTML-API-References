---
title: Interface ICSSRule
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Css.ICSSRule gränssnitt. CSSRulegränssnittet är det abstrakta basgränssnittet för alla typer av CSSsatser. Detta inkluderar både regeluppsättningar och atregler. En implementering förväntas bevara alla regler som anges i en CSSstilmall även om regeln inte känns igen av tolken. Okända regler representeras med hjälp avICSSUnknownRule gränssnitt.
type: docs
weight: 470
url: /sv/net/aspose.html.dom.css/icssrule/
---
## ICSSRule interface

CSSRule-gränssnittet är det abstrakta basgränssnittet för alla typer av CSS-satser. Detta inkluderar både regeluppsättningar och at-regler. En implementering förväntas bevara alla regler som anges i en CSS-stilmall, även om regeln inte känns igen av tolken. Okända regler representeras med hjälp av!:ICSSUnknownRule gränssnitt.

```csharp
public interface ICSSRule
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssrule/csstext/) { get; set; } | Den tolkbara textrepresentationen av regeln. Detta återspeglar regelns nuvarande tillstånd och inte dess initiala värde. |
| [ParentRule](../../aspose.html.dom.css/icssrule/parentrule/) { get; } | Om denna regel finns i en annan regel (t.ex. en stilregel inuti ett @mediablock), är detta den innehållande regeln. Om den här regeln inte är kapslad i några andra regler, returnerar den null. |
| [ParentStyleSheet](../../aspose.html.dom.css/icssrule/parentstylesheet/) { get; } | Stilmall som innehåller denna regel. |
| [Type](../../aspose.html.dom.css/icssrule/type/) { get; } | Typen av regeln, enligt definitionen ovan. Förväntningen är att bindningsspecifika castingmetoder kan användas för att casta ner från en instans av CSSRule-gränssnittet till det specifika härledda gränssnittet som antyds av typen. |

### Se även

* namnutrymme [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* hopsättning [Aspose.HTML](../../)


