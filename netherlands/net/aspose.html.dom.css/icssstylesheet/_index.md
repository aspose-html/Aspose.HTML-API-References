---
title: Interface ICSSStyleSheet
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Css.ICSSStyleSheet koppel. De CSSStyleSheetinterface is een concrete interface die wordt gebruikt om een CSSstijlblad weer te geven dwz een stijlblad waarvan het inhoudstype tekst/css is.
type: docs
weight: 510
url: /nl/net/aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

De CSSStyleSheet-interface is een concrete interface die wordt gebruikt om een CSS-stijlblad weer te geven, dwz een stijlblad waarvan het inhoudstype "tekst/css" is.

```csharp
public interface ICSSStyleSheet : IStyleSheet
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CSSRules](../../aspose.html.dom.css/icssstylesheet/cssrules/) { get; } | De lijst met alle CSS-regels in de stylesheet. Dit omvat zowel regelsets als at-rules. |
| [OwnerRule](../../aspose.html.dom.css/icssstylesheet/ownerrule/) { get; } | Als deze stijlpagina afkomstig is van een @import-regel, bevat het kenmerk ownerRule de CSSImportRule. In dat geval is het kenmerk ownerNode in de StyleSheet-interface null. Als de stijlpagina afkomstig is van een element of een verwerkingsinstructie, is het kenmerk ownerRule null en bevat het kenmerk ownerNode de Node. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [DeleteRule](../../aspose.html.dom.css/icssstylesheet/deleterule/)(int) | Wordt gebruikt om een regel uit de stijlpagina te verwijderen. |
| [InsertRule](../../aspose.html.dom.css/icssstylesheet/insertrule/)(string, int) | Wordt gebruikt om een nieuwe regel in de stijlpagina in te voegen. De nieuwe regel wordt nu onderdeel van de cascade. |

### Zie ook

* interface [IStyleSheet](../istylesheet/)
* naamruimte [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* montage [Aspose.HTML](../../)


