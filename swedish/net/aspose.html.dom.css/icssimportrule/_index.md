---
title: Interface ICSSImportRule
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Css.ICSSImportRule gränssnitt. CSSImportRulegränssnittet representerar en importregel i en CSSformatmall. importregeln används för att importera stilregler från andra stilmallar.
type: docs
weight: 410
url: /sv/net/aspose.html.dom.css/icssimportrule/
---
## ICSSImportRule interface

CSSImportRule-gränssnittet representerar en @import-regel i en CSS-formatmall. @import-regeln används för att importera stilregler från andra stilmallar.

```csharp
public interface ICSSImportRule : ICSSRule
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Href](../../aspose.html.dom.css/icssimportrule/href/) { get; } | Platsen för formatmallen som ska importeras. Attributet kommer inte att innehålla "url(...)"-specifikationen runt URI. |
| [Media](../../aspose.html.dom.css/icssimportrule/media/) { get; } | En lista över mediatyper för vilka denna stilmall kan användas. |
| [StyleSheet](../../aspose.html.dom.css/icssimportrule/stylesheet/) { get; } | Stilmall som refereras till av denna regel, om den har laddats. Värdet på detta attribut är null om stilmallen ännu inte har laddats eller om den inte kommer att laddas (t.ex. om formatmallen är för en mediatyp som inte stöds av användaragenten). |

### Se även

* interface [ICSSRule](../icssrule/)
* namnutrymme [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* hopsättning [Aspose.HTML](../../)


