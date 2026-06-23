---
title: "ISVGAnimatedPathData Interfaz"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.svg.paths.ISVGAnimatedPathData interfaz. La interfaz SVGAnimatedPathData admite elementos que tienen un atributo d que contiene datos de ruta SVG y permite animar ese atributo"
type: docs

url: /es/java/com.aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

La interfaz SVGAnimatedPathData soporta elementos que tienen un atributo ‘d’ que contiene datos de ruta SVG, y permite animar ese atributo.

```java
public interface ISVGAnimatedPathData
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getAnimatedPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) Proporciona acceso al contenido animado actual del atributo ‘d’ en una forma que coincide uno a uno con la sintaxis de SVG. Si el atributo o propiedad dado está siendo animado, contiene el valor animado actual del atributo o propiedad, y tanto el objeto mismo como su contenido son de solo lectura. Si el atributo o propiedad dado no está siendo animado, contiene el mismo valor que pathSegList. |
| [getPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) Proporciona acceso al contenido base (es decir, estático) del atributo ‘d’ en una forma que coincide uno a uno con la sintaxis de SVG. Por lo tanto, si el atributo ‘d’ tiene un comando "moveto absoluto (M)" y un comando "arcto absoluto (A)", entonces pathSegList tendrá dos entradas: un SVG_PATHSEG_MOVETO_ABS y un SVG_PATHSEG_ARC_ABS. |

### Ver también

* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
