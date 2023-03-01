---
title: Interface ISVGAnimatedPathData
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Dom.Svg.Paths.ISVGAnimatedPathData interfaz. La interfaz SVGAnimatedPathData admite elementos que tienen un atributo d que contiene datos de ruta SVG y admite la capacidad de animar ese atributo.
type: docs
weight: 1680
url: /es/net/aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

La interfaz SVGAnimatedPathData admite elementos que tienen un atributo 'd' que contiene datos de ruta SVG y admite la capacidad de animar ese atributo.

```csharp
public interface ISVGAnimatedPathData
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AnimatedPathSegList](../../aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) { get; } | Proporciona acceso a los contenidos animados actuales del atributo 'd' en una forma que coincide uno por uno con la sintaxis de SVG. Si el atributo o la propiedad dados se están animando, contiene el valor animado actual del atributo o la propiedad, y tanto el objeto en sí como su contenido son de solo lectura. Si el atributo o la propiedad dados no se están animando actualmente, contiene el mismo valor que pathSegList. |
| [PathSegList](../../aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) { get; } | Proporciona acceso al contenido base (es decir, estático) del atributo 'd' en una forma que coincide uno a uno con la sintaxis de SVG. Por lo tanto, si el atributo 'd' tiene un comando "absolute moveto (M)" y "absolute arcto (A)", entonces pathSegList tendrá dos entradas: un SVG_PATHSEG_MOVETO_ABS y un SVG_PATHSEG_ARC_ABS. |

### Ver también

* espacio de nombres [Aspose.Html.Dom.Svg.Paths](../../aspose.html.dom.svg.paths/)
* asamblea [Aspose.HTML](../../)


