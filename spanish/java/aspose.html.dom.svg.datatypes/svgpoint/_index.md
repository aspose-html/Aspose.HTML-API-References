---
title: "SVGPoint Clase"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.svg.datatypes.SVGPoint class. Muchas de las interfaces DOM de SVG hacen referencia a objetos de la clase SVGPoint. Un SVGPoint es un par de coordenadas x y. Cuando se usa en operaciones de matrices, un SVGPoint se trata como un vector de la forma x y 1. Si un objeto SVGRect está designado como solo lectura, intentar asignar a uno de sus atributos provocará que se lance una excepción"
type: docs

url: /es/java/com.aspose.html.dom.svg.datatypes/svgpoint/
---
## SVGPoint class

Muchas de las interfaces SVG DOM hacen referencia a objetos de la clase SVGPoint. Un SVGPoint es un par de coordenadas (x, y). Cuando se utiliza en operaciones matriciales, un SVGPoint se trata como un vector de la forma: [x] [y] [1] Si un objeto SVGRect se designa como de solo lectura, entonces intentar asignar a uno de sus atributos provocará que se lance una excepción.

```java
public class SVGPoint : SVGValueType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [X](../../com.aspose.html.dom.svg.datatypes/svgpoint/x/) { get; set; } | La coordenada X. |
| [Y](../../com.aspose.html.dom.svg.datatypes/svgpoint/y/) { get; set; } | La coordenada Y. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Libera recursos no administrados y, opcionalmente, administrados. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se utiliza para obtener el objeto ECMAScript. |
| [matrixTransform](../../com.aspose.html.dom.svg.datatypes/svgpoint/matrixtransform/)(SVGMatrix) | Aplica una transformación matricial 2x3 a este objeto SVGPoint y devuelve un nuevo objeto SVGPoint transformado: newpoint = matrix* thispoint |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgpoint/toString/)() | Devuelve una cadena que representa esta instancia. |

### Ver también

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
