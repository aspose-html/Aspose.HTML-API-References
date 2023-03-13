---
title: Interface ICSSImportRule
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Css.ICSSImportRule koppel. De interface CSSImportRule vertegenwoordigt een importregel binnen een CSSstijlpagina. De importregel wordt gebruikt om stijlregels uit andere stijlbladen te importeren.
type: docs
weight: 410
url: /nl/net/aspose.html.dom.css/icssimportrule/
---
## ICSSImportRule interface

De interface CSSImportRule vertegenwoordigt een @import-regel binnen een CSS-stijlpagina. De @import-regel wordt gebruikt om stijlregels uit andere stijlbladen te importeren.

```csharp
public interface ICSSImportRule : ICSSRule
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Href](../../aspose.html.dom.css/icssimportrule/href/) { get; } | De locatie van de te importeren stijlpagina. Het kenmerk bevat niet de "url(...)"-specificatie rond de URI. |
| [Media](../../aspose.html.dom.css/icssimportrule/media/) { get; } | Een lijst met mediatypen waarvoor deze stylesheet kan worden gebruikt. |
| [StyleSheet](../../aspose.html.dom.css/icssimportrule/stylesheet/) { get; } | De stijlpagina waarnaar deze regel verwijst, als deze is geladen. De waarde van dit attribuut is null als de stijlpagina nog niet is geladen of als deze niet zal worden geladen (bijv. als de stijlpagina voor een mediatype is dat niet wordt ondersteund door de user agent). |

### Zie ook

* interface [ICSSRule](../icssrule/)
* naamruimte [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* montage [Aspose.HTML](../../)


