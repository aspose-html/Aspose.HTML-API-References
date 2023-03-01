---
title: Interface ISVGAnimatedPathData
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Svg.Paths.ISVGAnimatedPathData koppel. De SVGAnimatedPathDatainterface ondersteunt elementen met een dattribuut dat SVGpadgegevens bevat en ondersteunt de mogelijkheid om dat attribuut te animeren.
type: docs
weight: 1680
url: /nl/net/aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

De SVGAnimatedPathData-interface ondersteunt elementen met een 'd'-attribuut dat SVG-padgegevens bevat, en ondersteunt de mogelijkheid om dat attribuut te animeren.

```csharp
public interface ISVGAnimatedPathData
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AnimatedPathSegList](../../aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) { get; } | Biedt toegang tot de huidige geanimeerde inhoud van het 'd'-attribuut in een vorm die een-op-een overeenkomt met de SVG-syntaxis. Als het gegeven attribuut of eigenschap wordt geanimeerd, bevat dit de huidige geanimeerde waarde van het attribuut of de eigenschap, en zowel het object zelf als de inhoud ervan zijn alleen-lezen. Als het gegeven attribuut of eigenschap momenteel niet wordt geanimeerd, bevat het dezelfde waarde als pathSegList. |
| [PathSegList](../../aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) { get; } | Biedt toegang tot de basis (dwz statische) inhoud van het 'd'-attribuut in een vorm die een-op-een overeenkomt met de SVG-syntaxis. Dus als het 'd'-attribuut een "absolute moveto (M)" en een "absolute arcto (A)"-opdracht heeft, dan heeft pathSegList twee ingangen: een SVG_PATHSEG_MOVETO_ABS en een SVG_PATHSEG_ARC_ABS. |

### Zie ook

* naamruimte [Aspose.Html.Dom.Svg.Paths](../../aspose.html.dom.svg.paths/)
* montage [Aspose.HTML](../../)


