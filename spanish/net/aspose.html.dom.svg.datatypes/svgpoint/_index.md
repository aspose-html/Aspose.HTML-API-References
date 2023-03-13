---
title: Class SVGPoint
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Dom.Svg.DataTypes.SVGPoint clase. Muchas de las interfaces SVG DOM se refieren a objetos de la clase SVGPoint. Un SVGPoint es un par de coordenadas x y. Cuando se usa en operaciones matriciales un SVGPoint se trata como un vector de la forma x y 1 Si un objeto SVGRect se designa como de solo lectura intentar asignarlo a uno de sus atributos resultar en una excepción lanzada.
type: docs
weight: 1250
url: /es/net/aspose.html.dom.svg.datatypes/svgpoint/
---
## SVGPoint class

Muchas de las interfaces SVG DOM se refieren a objetos de la clase SVGPoint. Un SVGPoint es un par de coordenadas (x, y). Cuando se usa en operaciones matriciales, un SVGPoint se trata como un vector de la forma: [x] [y] [1] Si un objeto SVGRect se designa como de solo lectura, intentar asignarlo a uno de sus atributos resultar en una excepción lanzada.

```csharp
public class SVGPoint : SVGValueType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [X](../../aspose.html.dom.svg.datatypes/svgpoint/x/) { get; set; } | La coordenada X. |
| [Y](../../aspose.html.dom.svg.datatypes/svgpoint/y/) { get; set; } | La coordenada Y. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Libera recursos no administrados y, opcionalmente, administrados. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |
| [MatrixTransform](../../aspose.html.dom.svg.datatypes/svgpoint/matrixtransform/)(SVGMatrix) | Aplica una transformación de matriz de 2x3 en este objeto SVGPoint y devuelve un nuevo objeto SVGPoint transformado: newpoint = matrix* thispoint |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgpoint/tostring/)() | Devuelve unString que representa esta instancia. |

### Ver también

* class [SVGValueType](../svgvaluetype/)
* espacio de nombres [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* asamblea [Aspose.HTML](../../)


