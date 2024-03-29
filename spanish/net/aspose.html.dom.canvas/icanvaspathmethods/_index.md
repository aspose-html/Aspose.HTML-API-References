---
title: Interface ICanvasPathMethods
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Dom.Canvas.ICanvasPathMethods interfaz. La interfaz ICanvasPathMethods se usa para manipular rutas de objetos.
type: docs
weight: 240
url: /es/net/aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

La interfaz ICanvasPathMethods se usa para manipular rutas de objetos.

```csharp
public interface ICanvasPathMethods
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | Agrega un arco a la ruta que está centrada en la posición (x, y) con un radio r que comienza en startAngle y termina en endAngle yendo en la dirección dada en sentido contrario a las agujas del reloj (por defecto en el sentido de las agujas del reloj). |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | Agrega un arco a la ruta que está centrada en la posición (x, y) con un radio r que comienza en startAngle y termina en endAngle yendo en la dirección dada en sentido contrario a las agujas del reloj (por defecto en el sentido de las agujas del reloj). |
| [ArcTo](../../aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | Añade un arco a la ruta con los puntos de control y radio dados, conectado al punto anterior por una línea recta. |
| [BezierCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | Agrega una curva de Bézier cúbica a la ruta. Requiere tres puntos. Los dos primeros puntos son puntos de control y el tercero es el punto final. El punto de partida es el último punto de la ruta actual, que se puede cambiar usando moveTo() antes de crear la curva Bézier. |
| [ClosePath](../../aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | Hace que la punta de la pluma retroceda hasta el inicio de la subruta actual. Intenta dibujar una línea recta desde el punto actual hasta el inicio. Si la forma ya ha sido cerrada o tiene un solo punto, esta función no hace nada. |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | Agrega una elipse a la ruta que está centrada en la posición (x, y) con los radios radiusX y radiusY comenzando en startAngle y terminando en endAngle yendo en la dirección dada en sentido contrario a las agujas del reloj (por defecto en el sentido de las agujas del reloj). |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Agrega una elipse a la ruta que está centrada en la posición (x, y) con los radios radiusX y radiusY comenzando en startAngle y terminando en endAngle yendo en la dirección dada en sentido contrario a las agujas del reloj (por defecto en el sentido de las agujas del reloj). |
| [LineTo](../../aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | Conecta el último punto del subtrayecto a las coordenadas x, y con una línea recta. |
| [MoveTo](../../aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | Mueve el punto de inicio de un nuevo subtrayecto a las coordenadas (x, y). |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | Agrega una curva de Bézier cuadrática a la ruta actual. |
| [Rect](../../aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | Crea una ruta para un rectángulo en la posición (x, y) con un tamaño determinado por el ancho y la altura. |

### Ver también

* espacio de nombres [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* asamblea [Aspose.HTML](../../)


