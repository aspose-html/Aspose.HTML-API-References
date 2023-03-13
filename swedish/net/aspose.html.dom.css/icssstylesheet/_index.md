---
title: Interface ICSSStyleSheet
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Css.ICSSStyleSheet gränssnitt. CSSStyleSheetgränssnittet är ett konkret gränssnitt som används för att representera en CSSstilmall dvs. en stilmall vars innehållstyp är text/css.
type: docs
weight: 510
url: /sv/net/aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

CSSStyleSheet-gränssnittet är ett konkret gränssnitt som används för att representera en CSS-stilmall, dvs. en stilmall vars innehållstyp är "text/css".

```csharp
public interface ICSSStyleSheet : IStyleSheet
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CSSRules](../../aspose.html.dom.css/icssstylesheet/cssrules/) { get; } | Listan över alla CSS-regler som finns i stilmallen. Detta inkluderar både regeluppsättningar och at-rules. |
| [OwnerRule](../../aspose.html.dom.css/icssstylesheet/ownerrule/) { get; } | Om denna stilmall kommer från en @import-regel, kommer attributet ownerRule att innehålla CSSImportRule. I så fall kommer attributet ownerNode i StyleSheet-gränssnittet att vara null. Om stilmallen kommer från ett element eller en bearbetningsinstruktion kommer attributet ownerRule att vara null och attributet ownerNode kommer att innehålla Node. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [DeleteRule](../../aspose.html.dom.css/icssstylesheet/deleterule/)(int) | Används för att ta bort en regel från stilmallen. |
| [InsertRule](../../aspose.html.dom.css/icssstylesheet/insertrule/)(string, int) | Används för att infoga en ny regel i stilmallen. Den nya regeln blir nu en del av kaskaden. |

### Se även

* interface [IStyleSheet](../istylesheet/)
* namnutrymme [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* hopsättning [Aspose.HTML](../../)


