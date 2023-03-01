---
title: SVGSVGElement.CurrentScale
second_title: Referencia de API de Aspose.HTML para .NET
description: SVGSVGElement propiedad. En un elemento svg más externo este atributo indica el factor de escala actual en relación con la vista inicial para tener en cuenta las operaciones de ampliación y panorámica del usuario como se describe en Ampliación y panorámica. Los atributos DOM currentScale y currentTranslate son equivalentes a la matriz 2x3 abcdef  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y. Si la ampliación está habilitada es decir zoomAndPanmagnificar el efecto es como si se colocara una transformación adicional en el nivel más externo del fragmento del documento SVG es decir fuera del elemento svg más externo. Cuando se accede en un elemento svg que no es un elemento svg más externo no está definido qué comportamiento tiene este atributo.
type: docs
weight: 10
url: /es/net/aspose.html.dom.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

En un elemento svg más externo, este atributo indica el factor de escala actual en relación con la vista inicial para tener en cuenta las operaciones de ampliación y panorámica del usuario, como se describe en Ampliación y panorámica. Los atributos DOM currentScale y currentTranslate son equivalentes a la matriz 2x3 [abcdef] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. Si la "ampliación" está habilitada (es decir, zoomAndPan="magnificar"), el efecto es como si se colocara una transformación adicional en el nivel más externo del fragmento del documento SVG (es decir, fuera del elemento svg más externo). Cuando se accede en un elemento 'svg' que no es un elemento svg más externo, no está definido qué comportamiento tiene este atributo.

```csharp
public float CurrentScale { get; set; }
```

### El valor de la propiedad

La escala actual.

### Ver también

* class [SVGSVGElement](../)
* espacio de nombres [Aspose.Html.Dom.Svg](../../svgsvgelement/)
* asamblea [Aspose.HTML](../../../)


