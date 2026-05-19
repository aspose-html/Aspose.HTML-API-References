---
title: "Clase Path2D"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.canvas.Path2D clase. La interfaz Path2D de la API Canvas 2D se utiliza para declarar rutas que luego se usan en objetos CanvasRenderingContext2D. Los métodos de ruta de la interfaz CanvasRenderingContext2D también están presentes en esta interfaz y le permiten crear rutas que puede conservar y reproducir según sea necesario en un canvas"
type: docs

url: /es/java/com.aspose.html.dom.canvas/path2d/
---
## Path2D class

La interfaz Path2D de la API Canvas 2D se utiliza para declarar rutas que luego se usan en objetos CanvasRenderingContext2D. Los métodos de ruta de la interfaz CanvasRenderingContext2D también están presentes en esta interfaz y le permiten crear rutas que puede retener y reproducir según sea necesario en un canvas.

```java
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Path2D](path2d/#constructor)() | devuelve un nuevo objeto Path2D recién instanciado |
| [Path2D](path2d/#constructor_1)(Path2D) | devuelve un nuevo objeto Path2D recién instanciado con otra ruta como argumento (crea una copia) |
| [Path2D](path2d/#constructor_2)(String) | devuelve un nuevo objeto Path2D recién instanciado con una cadena que contiene datos de ruta SVG. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | Añade a la ruta la ruta proporcionada como argumento. |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | Añade a la ruta la ruta proporcionada como argumento. |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | Añade un arco a la ruta que está centrado en la posición (x, y) con radio r, comenzando en startAngle y terminando en endAngle, yendo en la dirección indicada por anticlockwise (por defecto en sentido horario). |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | Añade un arco a la ruta que está centrado en la posición (x, y) con radio r, comenzando en startAngle y terminando en endAngle, yendo en la dirección indicada por anticlockwise (por defecto en sentido horario). |
| [arcTo](../../com.aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | Añade un arco a la ruta con los puntos de control y radio dados, conectado al punto anterior mediante una línea recta. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | Añade una curva cúbica Bézier a la ruta. Requiere tres puntos. Los dos primeros son puntos de control y el tercero es el punto final. El punto de inicio es el último punto de la ruta actual, que puede cambiarse usando moveTo() antes de crear la curva Bézier. |
| [closePath](../../com.aspose.html.dom.canvas/path2d/closepath/)() | Hace que el punto del lápiz se mueva de nuevo al inicio de la subruta actual. Intenta dibujar una línea recta desde el punto actual hasta el inicio. Si la forma ya está cerrada o tiene solo un punto, esta función no hace nada. |
| [dispose](../../com.aspose.html.dom.canvas/path2d/dispose/)() | Descarta el objeto. |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | Añade una elipse a la ruta que está centrada en la posición (x, y) con los radios radiusX y radiusY, comenzando en startAngle y terminando en endAngle, yendo en la dirección indicada por anticlockwise (por defecto en sentido horario). |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Añade una elipse a la ruta que está centrada en la posición (x, y) con los radios radiusX y radiusY, comenzando en startAngle y terminando en endAngle, yendo en la dirección indicada por anticlockwise (por defecto en sentido horario). |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se usa para recuperar el objeto ECMAScript. |
| [lineTo](../../com.aspose.html.dom.canvas/path2d/lineto/)(double, double) | Conecta el último punto de la subruta a las coordenadas x, y mediante una línea recta. |
| [moveTo](../../com.aspose.html.dom.canvas/path2d/moveto/)(double, double) | Mueve el punto de inicio de una nueva subruta a las coordenadas (x, y). |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | Añade una curva cuadrática Bézier a la ruta actual. |
| [rect](../../com.aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | Crea una ruta para un rectángulo en la posición (x, y) con un tamaño determinado por width y height. |

### Ver también

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
