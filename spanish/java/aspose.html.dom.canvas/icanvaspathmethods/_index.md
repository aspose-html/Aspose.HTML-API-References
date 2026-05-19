---
title: "Interfaz ICanvasPathMethods"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.canvas.ICanvasPathMethods interface. La interfaz ICanvasPathMethods se usa para manipular rutas de objetos."
type: docs

url: /es/java/com.aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

La interfaz ICanvasPathMethods se utiliza para manipular rutas de objetos.

```java
public interface ICanvasPathMethods
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | Añade un arco a la ruta que está centrado en la posición (x, y) con radio r, comenzando en startAngle y terminando en endAngle, yendo en la dirección indicada por anticlockwise (por defecto en sentido horario). |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | Añade un arco a la ruta que está centrado en la posición (x, y) con radio r, comenzando en startAngle y terminando en endAngle, yendo en la dirección indicada por anticlockwise (por defecto en sentido horario). |
| [arcTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | Añade un arco a la ruta con los puntos de control y radio dados, conectado al punto anterior mediante una línea recta. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | Añade una curva cúbica Bézier a la ruta. Requiere tres puntos. Los dos primeros son puntos de control y el tercero es el punto final. El punto de inicio es el último punto de la ruta actual, que puede cambiarse usando moveTo() antes de crear la curva Bézier. |
| [closePath](../../com.aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | Hace que el punto del lápiz se mueva de nuevo al inicio de la subruta actual. Intenta dibujar una línea recta desde el punto actual hasta el inicio. Si la forma ya está cerrada o tiene solo un punto, esta función no hace nada. |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | Añade una elipse a la ruta que está centrada en la posición (x, y) con los radios radiusX y radiusY, comenzando en startAngle y terminando en endAngle, yendo en la dirección indicada por anticlockwise (por defecto en sentido horario). |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Añade una elipse a la ruta que está centrada en la posición (x, y) con los radios radiusX y radiusY, comenzando en startAngle y terminando en endAngle, yendo en la dirección indicada por anticlockwise (por defecto en sentido horario). |
| [lineTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | Conecta el último punto de la subruta a las coordenadas x, y mediante una línea recta. |
| [moveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | Mueve el punto de inicio de una nueva subruta a las coordenadas (x, y). |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | Añade una curva cuadrática Bézier a la ruta actual. |
| [rect](../../com.aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | Crea una ruta para un rectángulo en la posición (x, y) con un tamaño determinado por width y height. |

### Ver también

* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
