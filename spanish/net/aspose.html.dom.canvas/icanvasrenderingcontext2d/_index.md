---
title: Interface ICanvasRenderingContext2D
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Dom.Canvas.ICanvasRenderingContext2D interfaz. La interfaz ICanvasRenderingContext2D se utiliza para dibujar rectángulos texto imágenes y otros objetos en el elemento del lienzo. Proporciona el contexto de representación 2D para la superficie de dibujo de un elemento de lienzo.
type: docs
weight: 260
url: /es/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

La interfaz ICanvasRenderingContext2D se utiliza para dibujar rectángulos, texto, imágenes y otros objetos en el elemento del lienzo. Proporciona el contexto de representación 2D para la superficie de dibujo de un elemento de lienzo.

```csharp
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Canvas](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) { get; } | Una referencia inversa de solo lectura a HTMLCanvasElement. Puede ser nulo si no está asociado con un elemento de lienzo. |
| [FillStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillstyle/) { get; set; } | Color o estilo para usar dentro de las formas. Predeterminado: (negro). |
| [GlobalAlpha](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalalpha/) { get; set; } | Valor alfa que se aplica a formas e imágenes antes de que se compongan en el lienzo. Predeterminado 1.0 (opaco). |
| [GlobalCompositeOperation](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalcompositeoperation/) { get; set; } | Con globalAlpha aplicado, esto establece cómo se dibujan las formas y las imágenes en el mapa de bits existente. Predeterminado: (fuente sobre) |
| [ImageSmoothingEnabled](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/imagesmoothingenabled/) { get; set; } | Modo de suavizado de imagen; si está deshabilitado, las imágenes no se suavizarán si se escalan. |
| [ShadowBlur](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowblur/) { get; set; } | Especifica el efecto de desenfoque. Predeterminado 0 |
| [ShadowColor](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowcolor/) { get; set; } | Color de la sombra. Negro totalmente transparente predeterminado. |
| [ShadowOffsetX](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsetx/) { get; set; } | Distancia horizontal a la que se compensará la sombra. Predeterminado 0. |
| [ShadowOffsetY](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsety/) { get; set; } | Distancia vertical a la que se compensará la sombra. Predeterminado 0. |
| [StrokeStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokestyle/) { get; set; } | Color o estilo a usar para las líneas alrededor de las formas. Predeterminado: (negro). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;string, string&gt;) | Agrega una región de impacto al lienzo. Esto le permite facilitar la detección de aciertos, le permite enrutar eventos a elementos DOM, y hace posible que los usuarios exploren el lienzo sin verlo. |
| [BeginPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | Inicia una nueva ruta al vaciar la lista de subrutas. Llame a este método cuando desee crear una nueva ruta. |
| [ClearHitRegions](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | Elimina todas las regiones afectadas del lienzo. |
| [ClearRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | Establece todos los píxeles en el rectángulo definido por el punto de inicio (x, y) y el tamaño (ancho, alto) en negro transparente, borrando cualquier contenido dibujado previamente. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | Crea una nueva región de recorte mediante el cálculo de la intersección de la región de recorte actual y el área descrita por la ruta, utilizando la regla del número de vueltas distinto de cero. Los subtrayectos abiertos deben cerrarse implícitamente al calcular la región de recorte, sin afectar los subtrayectos reales . La nueva región de recorte reemplaza la región de recorte actual. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | Crea una nueva región de recorte calculando la intersección de la región de recorte actual y el área descrita por la ruta, utilizando la regla del número de vuelta distinto de cero. Los subtrayectos abiertos deben cerrarse implícitamente al calcular la región de recorte, sin afectar los subtrayectos reales. La nueva región de recorte reemplaza a la región de recorte actual. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | Crea una nueva región de recorte calculando la intersección de la región de recorte actual y el área descrita por la ruta, utilizando la regla del número de vuelta distinto de cero. Los subtrayectos abiertos deben cerrarse implícitamente al calcular la región de recorte, sin afectar los subtrayectos reales. La nueva región de recorte reemplaza a la región de recorte actual. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | Crea un nuevo objeto ImageData en blanco con las dimensiones especificadas. Todos los píxeles del nuevo objeto son negros transparentes. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | Crea un nuevo objeto ImageData en blanco con las dimensiones especificadas. Todos los píxeles del nuevo objeto son negros transparentes. |
| [CreateLinearGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | Crea un degradado lineal a lo largo de la línea dada por las coordenadas representadas por los parámetros. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, string) | Crea un patrón utilizando la imagen especificada (un CanvasImageSource). Repite la fuente en las direcciones especificadas por el argumento de repetición. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, string) | Crea un patrón utilizando la imagen especificada (un CanvasImageSource). Repite la fuente en las direcciones especificadas por el argumento de repetición. |
| [CreateRadialGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | Crea un degradado radial dado por las coordenadas de los dos círculos representados por los parámetros. |
| [DrawFocusIfNeeded](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | Si un elemento dado está enfocado, este método dibuja un anillo de enfoque alrededor de la ruta actual. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | Dibuja la imagen especificada. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | Dibuja la imagen especificada. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | Dibuja la imagen especificada. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | Dibuja la imagen especificada. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Dibuja la imagen especificada. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | Dibuja la imagen especificada. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | Rellena los subtrayectos con el estilo de relleno actual y el algoritmo predeterminado CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | Rellena los subtrayectos con el estilo de relleno actual. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | Rellena los subtrayectos con el estilo de relleno actual y el algoritmo predeterminado CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | Rellena los subtrayectos con el estilo de relleno actual. |
| [FillRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | Dibuja un rectángulo relleno en la posición (x, y) cuyo tamaño está determinado por el ancho y el alto. |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(string, double, double) | Dibuja (rellena) un texto dado en la posición dada (x,y). |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(string, double, double, double) | Dibuja (rellena) un texto dado en la posición dada (x,y). |
| [GetImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | Devuelve un objeto ImageData que representa los datos de píxeles subyacentes para el área del lienzo indicada por el rectángulo que comienza en (sx, sy) y tiene un ancho sw y un alto sh. Este método no se ve afectado por la matriz de transformación del lienzo. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | Informa si el punto especificado está contenido o no en la ruta actual. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | Informa si el punto especificado está contenido o no en la ruta actual. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | Informa si el punto especificado está contenido o no en la ruta actual. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Informa si el punto especificado está contenido o no en la ruta actual. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | Informa si el punto especificado está o no dentro del área contenida por el trazo de un camino. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | Informa si el punto especificado está o no dentro del área contenida por el trazo de un camino. |
| [MeasureText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(string) | Devuelve un objeto TextMetrics. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | Pinta los datos del objeto ImageData dado en el mapa de bits. Si se proporciona un rectángulo sucio, solo se pintan los píxeles de ese rectángulo. Este método no se ve afectado por la matriz de transformación del lienzo. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | Pinta los datos del objeto ImageData dado en el mapa de bits. Si se proporciona un rectángulo sucio, solo se pintan los píxeles de ese rectángulo. Este método no se ve afectado por la matriz de transformación del lienzo. |
| [RemoveHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(string) | Elimina la región afectada con el ID especificado del lienzo. |
| [ResetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | Restablece la transformación actual por la matriz de identidad. |
| [Restore](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | Restaura el estado del estilo de dibujo al último elemento en la 'pila de estado' guardada por save(). |
| [Rotate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | Agrega una rotación a la matriz de transformación. El argumento del ángulo representa un ángulo de rotación en el sentido de las agujas del reloj y se expresa en radianes. |
| [Save](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | Guarda el estado del estilo de dibujo actual usando una pila para que pueda revertir cualquier cambio que le haya hecho usando restaurar(). |
| [Scale](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | Agrega una transformación de escala a las unidades del lienzo por x horizontalmente y por y verticalmente. |
| [SetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | Restablece la transformación actual a la matriz de identidad y luego invoca el método transform() con los mismos argumentos. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | Traza los subtrazados con el estilo de trazo actual. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | Traza los subtrazados con el estilo de trazo actual. |
| [StrokeRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | Pinta un rectángulo que tiene un punto inicial en (x, y) y tiene una anchura aw y una altura h en el lienzo, utilizando el estilo de trazo actual. |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(string, double, double) | Dibuja (trazos) un texto dado en la posición dada (x, y). |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(string, double, double, double?) | Dibuja (trazos) un texto dado en la posición dada (x, y). |
| [Transform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | Multiplica la matriz de transformación actual por la matriz descrita por sus argumentos. |
| [Translate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | Añade una transformación de traslación moviendo el lienzo y su origen x horizontalmente y y verticalmente en la cuadrícula. |

### Ver también

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* espacio de nombres [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* asamblea [Aspose.HTML](../../)


