---
title: Interface ISVGAnimatedPathData
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Svg.Paths.ISVGAnimatedPathData gränssnitt. SVGAanimatedPathDatagränssnittet stöder element som har ett dattribut som innehåller SVGsökvägsdata och stöder möjligheten att animera det attributet.
type: docs
weight: 1680
url: /sv/net/aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

SVGAanimatedPathData-gränssnittet stöder element som har ett 'd'-attribut som innehåller SVG-sökvägsdata och stöder möjligheten att animera det attributet.

```csharp
public interface ISVGAnimatedPathData
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AnimatedPathSegList](../../aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) { get; } | Ger tillgång till det aktuella animerade innehållet i 'd'-attributet i en form som matchar en för en med SVG:s syntax. Om det givna attributet eller egenskapen animeras, innehåller det aktuella animerade värdet för attributet eller egenskapen, och både själva objektet och dess innehåll är skrivskyddade. Om det givna attributet eller egenskapen för närvarande inte animeras, innehåller samma värde som pathSegList. |
| [PathSegList](../../aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) { get; } | Ger tillgång till basinnehållet (dvs. statiskt) i 'd'-attributet i en form som matchar en för en med SVG:s syntax. Således, om 'd'-attributet har ett "absolute moveto (M)" och ett "absolute arcto (A)"-kommando, kommer pathSegList att ha två poster: en SVG_PATHSEG_MOVETO_ABS och en SVG_PATHSEG_ARC_ABS. |

### Se även

* namnutrymme [Aspose.Html.Dom.Svg.Paths](../../aspose.html.dom.svg.paths/)
* hopsättning [Aspose.HTML](../../)


