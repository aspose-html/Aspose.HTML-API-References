---
title: Interface ICSSStyleSheet
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Dom.Css.ICSSStyleSheet koppel. Die CSSStyleSheetSchnittstelle ist eine konkrete Schnittstelle die verwendet wird um ein CSSStylesheet darzustellen dh ein Stylesheet dessen Inhaltstyp text/css ist.
type: docs
weight: 510
url: /de/net/aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

Die CSSStyleSheet-Schnittstelle ist eine konkrete Schnittstelle, die verwendet wird, um ein CSS-Stylesheet darzustellen, dh ein Stylesheet, dessen Inhaltstyp "text/css" ist.

```csharp
public interface ICSSStyleSheet : IStyleSheet
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CSSRules](../../aspose.html.dom.css/icssstylesheet/cssrules/) { get; } | Die Liste aller im Stylesheet enthaltenen CSS-Regeln. Dies umfasst sowohl Regelsätze als auch at-Regeln. |
| [OwnerRule](../../aspose.html.dom.css/icssstylesheet/ownerrule/) { get; } | Wenn dieses Stylesheet aus einer @import-Regel stammt, enthält das Attribut ownerRule die CSSImportRule. In diesem Fall ist das OwnerNode-Attribut in der StyleSheet-Schnittstelle null. Wenn das Stylesheet von einem Element oder einer Verarbeitungsanweisung stammt, ist das Attribut „ownerRule“ null und das Attribut „ownerNode“ enthält den Knoten „Node. “. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [DeleteRule](../../aspose.html.dom.css/icssstylesheet/deleterule/)(int) | Wird verwendet, um eine Regel aus dem Stylesheet zu löschen. |
| [InsertRule](../../aspose.html.dom.css/icssstylesheet/insertrule/)(string, int) | Wird verwendet, um eine neue Regel in das Stylesheet einzufügen. Die neue Regel wird nun Teil der Kaskade. |

### Siehe auch

* interface [IStyleSheet](../istylesheet/)
* namensraum [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* Montage [Aspose.HTML](../../)


