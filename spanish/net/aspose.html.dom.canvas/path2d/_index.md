---
title: Path2D
second_title: Referencia de API de Aspose.HTML para .NET
description: La interfaz Path2D de la API Canvas 2D se usa para declarar rutas que luego se usan en objetos CanvasRenderingContext2D. Los métodos de ruta de la interfaz CanvasRenderingContext2D también están presentes en esta interfaz y le permiten crear rutas que puede retener y reproducir según sea necesario en un lienzo.
type: docs
weight: 300
url: /es/net/aspose.html.dom.canvas/path2d/
---
## Path2D class

La interfaz Path2D de la API Canvas 2D se usa para declarar rutas que luego se usan en objetos CanvasRenderingContext2D. Los métodos de ruta de la interfaz CanvasRenderingContext2D también están presentes en esta interfaz y le permiten crear rutas que puede retener y reproducir según sea necesario en un lienzo.

```csharp
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Path2D](path2d#constructor)() | devuelve un objeto Path2D recién instanciado |
| [Path2D](path2d#constructor_1)(Path2D) | devuelve un objeto Path2D recién instanciado con otra ruta como argumento (crea una copia) |
| [Path2D](path2d#constructor_2)(string) | devuelve un objeto Path2D recién instanciado con una cadena que consta de datos de ruta SVG. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath#addpath)(Path2D) | Agrega a la ruta la ruta dada por el argumento. |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath#addpath_1)(Path2D, SVGMatrix) | Agrega a la ruta la ruta dada por el argumento. |
| [Arc](../../aspose.html.dom.canvas/path2d/arc#arc)(double, double, double, double, double) | Agrega un arco a la ruta que está centrada en la posición (x, y) con un radio r que comienza en startAngle y termina en endAngle yendo en la dirección dada en sentido contrario a las agujas del reloj (por defecto en el sentido de las agujas del reloj). |
| [Arc](../../aspose.html.dom.canvas/path2d/arc#arc_1)(double, double, double, double, double, bool) | Agrega un arco a la ruta que está centrada en la posición (x, y) con un radio r que comienza en startAngle y termina en endAngle yendo en la dirección dada en sentido contrario a las agujas del reloj (por defecto en el sentido de las agujas del reloj). |
| [ArcTo](../../aspose.html.dom.canvas/path2d/arcto)(double, double, double, double, double) | Añade un arco a la ruta con los puntos de control y radio dados, conectado al punto anterior por una línea recta. |
| [BezierCurveTo](../../aspose.html.dom.canvas/path2d/beziercurveto)(double, double, double, double, double, double) | Agrega una curva de Bézier cúbica a la ruta. Requiere tres puntos. Los dos primeros puntos son puntos de control y el tercero es el punto final. El punto de partida es el último punto de la ruta actual, que se puede cambiar usando moveTo() antes de crear la curva Bézier. |
| [ClosePath](../../aspose.html.dom.canvas/path2d/closepath)() | Hace que la punta de la pluma retroceda hasta el inicio de la subruta actual. Intenta dibujar una línea recta desde el punto actual hasta el inicio. Si la forma ya ha sido cerrada o tiene un solo punto, esta función no hace nada. |
| [Dispose](../../aspose.html.dom.canvas/path2d/dispose)() | Elimina objeto. |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse#ellipse)(double, double, double, double, double, double, double) | Agrega una elipse a la ruta que está centrada en la posición (x, y) con los radios radiusX y radiusY comenzando en startAngle y terminando en endAngle yendo en la dirección dada en sentido contrario a las agujas del reloj (por defecto en el sentido de las agujas del reloj). |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse#ellipse_1)(double, double, double, double, double, double, double, bool) | Agrega una elipse a la ruta que está centrada en la posición (x, y) con los radios radiusX y radiusY comenzando en startAngle y terminando en endAngle yendo en la dirección dada en sentido contrario a las agujas del reloj (por defecto en el sentido de las agujas del reloj). |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |
| [LineTo](../../aspose.html.dom.canvas/path2d/lineto)(double, double) | Conecta el último punto del subtrayecto a las coordenadas x, y con una línea recta. |
| [MoveTo](../../aspose.html.dom.canvas/path2d/moveto)(double, double) | Mueve el punto de inicio de un nuevo subtrayecto a las coordenadas (x, y). |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/path2d/quadraticcurveto)(double, double, double, double) | Agrega una curva de Bézier cuadrática a la ruta actual. |
| [Rect](../../aspose.html.dom.canvas/path2d/rect)(double, double, double, double) | Crea una ruta para un rectángulo en la posición (x, y) con un tamaño determinado por el ancho y la altura. |

### Ver también

* class [DOMObject](../../aspose.html.dom/domobject)
* interface [ICanvasPathMethods](../icanvaspathmethods)
* espacio de nombres [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas)
* asamblea [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
