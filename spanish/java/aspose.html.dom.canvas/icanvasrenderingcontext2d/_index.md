---
title: "Interfaz ICanvasRenderingContext2D"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Interfaz com.aspose.html.dom.canvas.ICanvasRenderingContext2D. La interfaz ICanvasRenderingContext2D se utiliza para dibujar rectángulos, texto, imágenes y otros objetos en el elemento canvas. Proporciona el contexto de renderizado 2D para la superficie de dibujo de un elemento canvas."
type: docs

url: /es/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

La interfaz ICanvasRenderingContext2D se utiliza para dibujar rectángulos, texto, imágenes y otros objetos sobre el elemento canvas. Proporciona el contexto de renderizado 2D para la superficie de dibujo de un elemento canvas.

```java
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getCanvas](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) Una referencia de solo lectura al HTMLCanvasElement. Puede ser null si no está asociado a un elemento canvas. |
[getFillStyle]
[setFillStyle] Color or style to use inside shapes. Default: (black). |
[getGlobalAlpha]
[setGlobalAlpha] Alpha value that is applied to shapes and images before they are composited onto the canvas. Default 1.0 (opaque). |
[getGlobalCompositeOperation]
[setGlobalCompositeOperation] With globalAlpha applied this sets how shapes and images are drawn onto the existing bitmap. Default: (source-over) |
[getImageSmoothingEnabled]
[setImageSmoothingEnabled] Image smoothing mode; if disabled, images will not be smoothed if scaled. |
[getShadowBlur]
[setShadowBlur] Specifies the blurring effect. Default 0 |
[getShadowColor]
[setShadowColor] Color of the shadow. Default fully-transparent black. |
[getShadowOffsetX]
[setShadowOffsetX] Horizontal distance the shadow will be offset. Default 0. |
[getShadowOffsetY]
[setShadowOffsetY] Vertical distance the shadow will be offset. Default 0. |
[getStrokeStyle]
[setStrokeStyle] Color or style to use for the lines around shapes. Default: (black). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;String, String&gt;) |  |
| [beginPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | Inicia una nueva ruta vaciando la lista de subrutas. Llame a este método cuando desee crear una nueva ruta. |
| [clearHitRegions](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | Elimina todas las regiones de interacción del canvas. |
| [clearRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | Establece todos los píxeles del rectángulo definido por el punto de inicio (x, y) y el tamaño (ancho, alto) a negro transparente, borrando cualquier contenido dibujado previamente. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | Crea una nueva región de recorte calculando la intersección de la región de recorte actual y el área descrita por la ruta, utilizando la regla del número de vueltas distinto de cero. Las subrutas abiertas deben cerrarse implícitamente al calcular la región de recorte, sin afectar a las subrutas reales. La nueva región de recorte reemplaza a la región de recorte actual. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | Crea una nueva región de recorte calculando la intersección de la región de recorte actual y el área descrita por la ruta, utilizando la regla del número de vueltas distinto de cero. Las subrutas abiertas deben cerrarse implícitamente al calcular la región de recorte, sin afectar a las subrutas reales. La nueva región de recorte reemplaza a la región de recorte actual. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | Crea una nueva región de recorte calculando la intersección de la región de recorte actual y el área descrita por la ruta, utilizando la regla del número de vueltas distinto de cero. Las subrutas abiertas deben cerrarse implícitamente al calcular la región de recorte, sin afectar a las subrutas reales. La nueva región de recorte reemplaza a la región de recorte actual. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | Crea un nuevo objeto ImageData vacío con las dimensiones especificadas. Todos los píxeles del nuevo objeto son negro transparente. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | Crea un nuevo objeto ImageData vacío con las dimensiones especificadas. Todos los píxeles del nuevo objeto son negro transparente. |
| [createLinearGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | Crea un degradado lineal a lo largo de la línea definida por las coordenadas representadas por los parámetros. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, String) | Crea un patrón usando la imagen especificada (un CanvasImageSource). Repite la fuente en las direcciones especificadas por el argumento de repetición. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, String) | Crea un patrón usando la imagen especificada (un CanvasImageSource). Repite la fuente en las direcciones especificadas por el argumento de repetición. |
| [createRadialGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | Crea un degradado radial definido por las coordenadas de los dos círculos representados por los parámetros. |
| [drawFocusIfNeeded](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | Si un elemento dado está enfocado, este método dibuja un anillo de foco alrededor de la ruta actual. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | Dibuja la imagen especificada. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | Dibuja la imagen especificada. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | Dibuja la imagen especificada. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | Dibuja la imagen especificada. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Dibuja la imagen especificada. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | Dibuja la imagen especificada. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | Rellena las subrutas con el estilo de relleno actual y el algoritmo predeterminado CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | Rellena las subrutas con el estilo de relleno actual. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | Rellena las subrutas con el estilo de relleno actual y el algoritmo predeterminado CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | Rellena las subrutas con el estilo de relleno actual. |
| [fillRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | Dibuja un rectángulo relleno en la posición (x, y) cuyo tamaño está determinado por el ancho y la altura. |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(String, double, double) | Dibuja (rellena) un texto dado en la posición (x,y) proporcionada. |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(String, double, double, double) | Dibuja (rellena) un texto dado en la posición (x,y) proporcionada. |
| [getImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | Devuelve un objeto ImageData que representa los datos de píxeles subyacentes para el área del lienzo indicada por el rectángulo que comienza en (sx, sy) y tiene un ancho sw y una altura sh. Este método no se ve afectado por la matriz de transformación del lienzo. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | Informa si el punto especificado está contenido en la ruta actual o no. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | Informa si el punto especificado está contenido en la ruta actual o no. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | Informa si el punto especificado está contenido en la ruta actual o no. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Informa si el punto especificado está contenido en la ruta actual o no. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | Informa si el punto especificado está dentro del área contenida por el trazo de una ruta o no. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | Informa si el punto especificado está dentro del área contenida por el trazo de una ruta o no. |
| [measureText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(String) | Devuelve un objeto TextMetrics. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | Pinta datos del objeto ImageData dado sobre el mapa de bits. Si se proporciona un rectángulo sucio, solo se pintan los píxeles de ese rectángulo. Este método no se ve afectado por la matriz de transformación del lienzo. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | Pinta datos del objeto ImageData dado sobre el mapa de bits. Si se proporciona un rectángulo sucio, solo se pintan los píxeles de ese rectángulo. Este método no se ve afectado por la matriz de transformación del lienzo. |
| [removeHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(String) | Elimina la región de interacción con el id especificado del lienzo. |
| [resetTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | Restablece la transformación actual mediante la matriz identidad. |
| [restore](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | Restaura el estado del estilo de dibujo al último elemento de la 'pila de estado' guardado por save(). |
| [rotate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | Agrega una rotación a la matriz de transformación. El argumento ángulo representa un ángulo de rotación en sentido horario y se expresa en radianes. |
| [save](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | Guarda el estado actual del estilo de dibujo usando una pila para que puedas revertir cualquier cambio que hagas usando restore(). |
| [scale](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | Agrega una transformación de escala a las unidades del lienzo por x horizontalmente y por y verticalmente. |
| [setTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | Restablece la transformación actual a la matriz identidad y luego invoca el método transform() con los mismos argumentos. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | Dibuja el contorno de las subrutas con el estilo de trazo actual. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | Dibuja el contorno de las subrutas con el estilo de trazo actual. |
| [strokeRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | Pinta un rectángulo que tiene un punto de inicio en (x, y) y tiene un ancho w y una altura h sobre el lienzo, usando el estilo de trazo actual. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(String, double, double) | Dibuja (traza) un texto dado en la posición (x, y) proporcionada. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(String, double, double, double?) | Dibuja (traza) un texto dado en la posición (x, y) proporcionada. |
| [transform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | Multiplica la matriz de transformación actual con la matriz descrita por sus argumentos. |
| [translate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | Agrega una transformación de traslación moviendo el lienzo y su origen x horizontalmente y y verticalmente en la cuadrícula. |

### Ver también

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
