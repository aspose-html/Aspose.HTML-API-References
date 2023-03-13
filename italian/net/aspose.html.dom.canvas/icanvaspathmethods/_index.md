---
title: Interface ICanvasPathMethods
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Canvas.ICanvasPathMethods interfaccia. Linterfaccia ICanvasPathMethods viene utilizzata per manipolare i percorsi degli oggetti.
type: docs
weight: 240
url: /it/net/aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

L'interfaccia ICanvasPathMethods viene utilizzata per manipolare i percorsi degli oggetti.

```csharp
public interface ICanvasPathMethods
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | Aggiunge un arco al percorso centrato nella posizione (x, y) con raggio r che inizia a startAngle e termina a endAngle andando nella direzione data in senso antiorario (predefinito in senso orario). |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | Aggiunge un arco al percorso centrato nella posizione (x, y) con raggio r che inizia a startAngle e termina a endAngle andando nella direzione data in senso antiorario (predefinito in senso orario). |
| [ArcTo](../../aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | Aggiunge un arco al percorso con i punti di controllo e il raggio dati, collegato al punto precedente da una linea retta. |
| [BezierCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | Aggiunge una curva di Bézier cubica al tracciato. Richiede tre punti. I primi due punti sono punti di controllo e il terzo è il punto finale. Il punto di partenza è l'ultimo punto nel percorso corrente, che può essere modificato utilizzando moveTo() prima di creare la curva di Bézier. |
| [ClosePath](../../aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | Fa tornare la punta della penna all'inizio del sottotracciato corrente. Cerca di tracciare una linea retta dal punto corrente all'inizio. Se la forma è già stata chiusa o ha un solo punto, questa funzione non fa nulla. |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | Aggiunge un'ellisse al percorso centrato nella posizione (x, y) con i raggi radiusX e radiusY che iniziano a startAngle e terminano a endAngle andando nella direzione data in senso antiorario (predefinito in senso orario). |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Aggiunge un'ellisse al percorso centrato nella posizione (x, y) con i raggi radiusX e radiusY che iniziano a startAngle e terminano a endAngle andando nella direzione data in senso antiorario (predefinito in senso orario). |
| [LineTo](../../aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | Collega l'ultimo punto nel sottotracciato alle coordinate x, y con una linea retta. |
| [MoveTo](../../aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | Sposta il punto iniziale di un nuovo sottotracciato alle coordinate (x, y). |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | Aggiunge una curva Bézier quadratica al percorso corrente. |
| [Rect](../../aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | Crea un percorso per un rettangolo nella posizione (x, y) con una dimensione determinata da larghezza e altezza. |

### Guarda anche

* spazio dei nomi [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* assemblea [Aspose.HTML](../../)


