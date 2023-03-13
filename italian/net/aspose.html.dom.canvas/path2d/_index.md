---
title: Class Path2D
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Canvas.Path2D classe. Linterfaccia Path2D dellAPI Canvas 2D viene utilizzata per dichiarare i percorsi che vengono successivamente utilizzati sugli oggetti CanvasRenderingContext2D. I metodi di percorso dellinterfaccia CanvasRenderingContext2D sono presenti anche su questa interfaccia e ti consentono di creare percorsi che puoi conservare e riprodurre come richiesto su una tela.
type: docs
weight: 290
url: /it/net/aspose.html.dom.canvas/path2d/
---
## Path2D class

L'interfaccia Path2D dell'API Canvas 2D viene utilizzata per dichiarare i percorsi che vengono successivamente utilizzati sugli oggetti CanvasRenderingContext2D. I metodi di percorso dell'interfaccia CanvasRenderingContext2D sono presenti anche su questa interfaccia e ti consentono di creare percorsi che puoi conservare e riprodurre come richiesto su una tela.

```csharp
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Path2D](path2d/#constructor)() | restituisce un oggetto Path2D appena istanziato |
| [Path2D](path2d/#constructor_1)(Path2D) | restituisce un oggetto Path2D appena istanziato con un altro percorso come argomento (crea una copia) |
| [Path2D](path2d/#constructor_2)(string) | restituisce un oggetto Path2D appena istanziato con una stringa composta da dati di percorso SVG. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | Aggiunge al percorso il percorso dato dall'argomento. |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | Aggiunge al percorso il percorso dato dall'argomento. |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | Aggiunge un arco al percorso centrato nella posizione (x, y) con raggio r che inizia a startAngle e termina a endAngle andando nella direzione data in senso antiorario (predefinito in senso orario). |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | Aggiunge un arco al percorso centrato nella posizione (x, y) con raggio r che inizia a startAngle e termina a endAngle andando nella direzione data in senso antiorario (predefinito in senso orario). |
| [ArcTo](../../aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | Aggiunge un arco al percorso con i punti di controllo e il raggio dati, collegato al punto precedente da una linea retta. |
| [BezierCurveTo](../../aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | Aggiunge una curva di Bézier cubica al tracciato. Richiede tre punti. I primi due punti sono punti di controllo e il terzo è il punto finale. Il punto di partenza è l'ultimo punto nel percorso corrente, che può essere modificato utilizzando moveTo() prima di creare la curva di Bézier. |
| [ClosePath](../../aspose.html.dom.canvas/path2d/closepath/)() | Fa tornare la punta della penna all'inizio del sottotracciato corrente. Cerca di tracciare una linea retta dal punto corrente all'inizio. Se la forma è già stata chiusa o ha un solo punto, questa funzione non fa nulla. |
| [Dispose](../../aspose.html.dom.canvas/path2d/dispose/)() | Elimina l'oggetto. |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | Aggiunge un'ellisse al percorso centrato nella posizione (x, y) con i raggi radiusX e radiusY che iniziano a startAngle e terminano a endAngle andando nella direzione data in senso antiorario (predefinito in senso orario). |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Aggiunge un'ellisse al percorso centrato nella posizione (x, y) con i raggi radiusX e radiusY che iniziano a startAngle e terminano a endAngle andando nella direzione data in senso antiorario (predefinito in senso orario). |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Questo metodo viene utilizzato per recuperare l'oggetto ECMAScriptType . |
| [LineTo](../../aspose.html.dom.canvas/path2d/lineto/)(double, double) | Collega l'ultimo punto nel sottotracciato alle coordinate x, y con una linea retta. |
| [MoveTo](../../aspose.html.dom.canvas/path2d/moveto/)(double, double) | Sposta il punto iniziale di un nuovo sottotracciato alle coordinate (x, y). |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | Aggiunge una curva Bézier quadratica al percorso corrente. |
| [Rect](../../aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | Crea un percorso per un rettangolo nella posizione (x, y) con una dimensione determinata da larghezza e altezza. |

### Guarda anche

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* spazio dei nomi [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* assemblea [Aspose.HTML](../../)


